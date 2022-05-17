# Chia số cột 

 /*grid-teamplate-columns: column-size column-size .... */
 
 /*Chia số columns theo size cho sẵn px*/
+ grid-template-columns: 200px 200px 100px;

 /*Chia số rows theo size cho sẵn px*/
+ grid-template-rows: 350px 100px 350px;

/*Chia số cột theo fr %*/
+ grid-template-columns: 1fr 1fr 1fr;

# khoảng trống giữa cột và hàng
/* gap: grid-row-gap grid-column-gap */
/* gap: chia khoảng cách theo column */
+ grid-column-gap: 20px;

/* gap: chia khoảng cách theo rows */
+ grid-row-gap: 20px;

/* gap: gộp */
+ grid-gap: 20px 40px;

# chia rows và column theo track-line
/* gird-column: track-line-start / tracck-line-end */

+ grid-column: 1/3;
+ grid-row: 1/2;

![image](https://user-images.githubusercontent.com/70182883/168754474-cc68ba4f-2c66-4f21-b2bd-1fc749ad266b.png)

# chia theo rows và colums: grid-teamplate-areas
/* grid-teamplate-areas: dùng cho phần tử cha
grid-areas: dùng cho phần tử con */

+  grid-template-areas:
        "h1 h1 h2 h3"
        "h4 h5 h2 h3"
        "h4 h5 h6 h6"
    ;
    
+ grid-area: h1;
+ grid-area: h2;
+ grid-area: h3;
+ grid-area: h4;
+ grid-area: h5;
+ grid-area: h6;
