# LHTagsViewDemo
CollectionView 实现标签视图
![]()

        _tagsView.dataSource = [@[@"tag",@"tag",@"tag",@"tag",@"tag"] mutableCopy]; // 设置数据源并更新显示
        _tagsView.isShowHeader = NO;// 是否显示头部视图
       [_tagsView insertCellAtLast:@"less is more"]; // 尾部最后插入数据
       [_tagsView deleteLastCell]; // 删除尾部的最后一个数据