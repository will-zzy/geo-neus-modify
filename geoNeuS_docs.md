首先运行```imgs2poses.py```生成```pose.npy```和```points.npy```与```view_id.npy```

然后运行```gen_cameras.py```生成```camera.npz```与```mask```



```pts_view_id```为一个```[N_images,n_pts]```的bool数组，```(i,j)```表示第i幅视图能否看到第j个三维点



然后运行```colmap2mvsnet_acm.py```得到```pair.txt```









