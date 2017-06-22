# ZSCustomCircleView
圆环进度条 使用方便

在需要使用的地方导入#import "ZSCirclePercentView.h"


ZSCirclePercentView *circleView = [[ZSCirclePercentView alloc]initWithFrame:CGRectMake(50, 100, 200, 200)];
circleView.lineWidth = 5;
circleView.lineColor = [UIColor greenColor];
circleView.lineCap = kCALineJoinMiter;
[circleView buildView];
[self.view addSubview:circleView];
circleView.percent = 0.33;
[circleView show];

线宽,颜色等属性必须在 buildView 之前设置



