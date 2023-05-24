## CSS Chapter 16
It is my coding practice with the TUTORIAL of Dave Gray. 

## Source
### Dave Gray 的 CSS 課程
https://youtube.com/playlist?list=PL0Zuz27SZ-6Mx9fd9elt80G1bPcySmWit

### Dave Gray 的 YouTube 頻道
https://www.youtube.com/@DaveGrayTeachesCode

## CSS Chapter 16
   Quick Concept outline
   中文摘要說明與重點提問

###  1. Intro
        教學影片固定的開頭

###  2. Welcome
        歡迎觀眾，說明工具與資料位置

###  3. Starter Code
        初始設定說明

###  4. Prevent content layout shift
        新增 section 元素，class 為 example。
        在 section 元素中新增 p 元素，文字為 Yeah, this is a paragraph.
        在文字上方新增圖片 img ，
        路徑 src 為 img/pat1.png，alt 為 Pattern 1，寬度和高度為200px

###  5. Style responsive images
        (1).example 中，設定 margin-top 為 1rem，padding-left 為 20px，border 為 1px solid red

        (2).example img 中，設定 width 為 25%，height 為 auto
        開啟 Google Chrome 的開發工具縮放視窗觀察變化

###  6. Remove the default space under images
        (1)在 img 中，設定 display 為 block，移動文字到圖片下方

        (2)刪除 Yeah, this is a paragraph. 文字和 p 標籤，移除圖片下方的空白空間

        (3)說明如果沒有設定 display 為 block，圖片下方的空白空間會出現

###  7. Profile picture example
        (1)新增 section 元素，class 為 hero。在 section 元素中，新增 figure 元素，class 為 profile-pic-figure。在 figure 元素中，新增圖片 img ，路徑 src 為 img/profile-800x800.png，alt 為 Profile Picture，title 為 My Profile Picture，寬度和高度為 800px。新增 figcaption 元素，圖片的下標文字為 Jane Doe

        (2)在 profile-pic-figure 中，設定 width 為 35%

        (3)在 profile-pic-figure img 中，設定 width 為 100%，height 為 auto，min-width 為 100px，border 為 5px double gray

        (4)在 profile-pic-figure img 中，設定 border-radius 為 50%，將圖片變成圓形

###  8. Hero section
        (1)在 figure 下新增 h1，設定 class 為 h1，加入兩個 span，class 為 nowrap，文字為 Hello👋 和 I am Jane.

        (2)在 .hero 中，設定 border-bottom 為 2px solid #000，padding 為 20px，display 為 flex，justify-content 為 flex-start，align-items 為 center，gap 為 30px

        (3)在 .h1 中，設定 font-size 為 500%，並開啟 Google Chrome 開發工具縮放觀察變化

        (4)新增備註: Begin Reset, End Reset, Utility Classes, End Utility Classes。
        
        (5)新增 .nowrap，設定 white-space 為 nowrap，讓特定文字不要換行。

        (6)新增 .offscreen，position 為absolute，left為-10000px，並設定 figcaption 的 class 為 offscreen。隱藏特定的文字

###  9. Fallback background-color
        設定 background-color 為 rgb(251, 210, 156) 修改背景顏色。
        

### 10. Setting a background-image
        (1)設定 background-image 為 url("../img/pat1.png") 修改背景圖片。
        (2)設定 h1 文字顏色為白色

### 11. background-repeat
        (1)設定 background-repeat 為預設值 no-repeat
        (2)設定 background-repeat 為 repeat
        (3)設定 background-repeat 為 repeat-y
        (4)設定 background-repeat 為 repeat-x

### 12. background image patterns
        (1)修改 background-image 為 url("../img/pat2.png")，background-repeat 為 repeat。
        (2)修改 background-image 為 url("../img/pat2.png")，background-repeat 為 no-repeat。
        (3)修改 background-image 為 url("../img/pat2-transparency.png")，background-repeat 為 repeat。

### 13. background-size
        (1)修改 background-image 為 url("../img/scenic-2200x1331.png")
        (2)設定 background-size 為 cover，使圖片能完整呈現，並開始 Google Chrome 開發工具縮放視窗。
        (3)修改 background-size 為 contain。
        (4)修改 background-repeat 為 no-repeat
        (5)復原 background-size 為 cover。

### 14. Image size considerations
        修改 background-image 為 url("../img/map-2176x1451.png")
        

### 15. Make text standout over a background
        (1)設定 h1 文字顏色為 aliceblue
        (2)設定 h1 文字陰影為 2px 2px 5px #000
        (3)設定 h1 的背景為黑色
        (4)設定 h1 的背景為黑色，透明度為 40%
        (5)設定 h1 的 padding 為 0.25rem，border-radius 為 10px
        (6)移除 h1 的 background-color, padding, border-radius

### 16. Create a background mask layer
        (1)在 section 外層新增 div，class 為 container，並將 background-color, background-image, background-repeat, background-size 移動至 .container
        (2)設定 hero 背景為黑色，透明度為 40%
        (3)修改亮度為 100%
        (4)修改透明度為 35%
        (5)修改亮度為 0%
        (6)修改亮度為 100%，透明度為 35%

### 17. background-position
        (1)在 .container 設定 background-position 為 center center
        (2)在 .container 設定 background-position 為 top right
        (3)在 .container 設定 background-position 為 top left
        (4)在 .container 設定 background-position 為 bottom right
        (5)在 .container 設定 background-position 為 top
        (6)在 .container 設定 background-position 為 center
        (7)在 .container 設定 background-position 為 bottom

### 18. linear-gradient backgrounds
        (1)設定 body 背景為 aliceblue
        (2)設定 background-image 為 linear-gradient(steelblue, #fff)
        (3)設定 background-image 為 linear-gradient(steelblue, purple, #fff)
        (4)設定 background-image 為 linear-gradient(to left, steelblue, #fff)，顏色呈現由右到左
        (5)設定 background-image 為 linear-gradient(to right, steelblue, #fff)，顏色呈現由左到右
        (6)設定 background-image 為 linear-gradient(to bottom, steelblue, #fff)，顏色呈現由上往下
        (7)設定 background-image 為 linear-gradient(to top, steelblue, #fff)，顏色呈現由下往上

### 19. Multiple background image layers
        (1)設定 background-image 為 url(../img/bubbles.png), linear-gradient(to left, steelblue, #fff)
        (2)設定 background-repeat 為 repeat-y, no-repeat
        (3)設定 background-position 為 right center

### 20. background-size
        設定 background-size 為 20% auto

### 21. Filling text with a background image
        (1)新增 section 元素。
        在 section 元素中新增 p 元素，class 為 clip，文字為 Jane。移除 body 的 background-image, background-repeat, background-position, background-size
        (2)在 .clip 中，設定 font-weight 為 800，調整文字粗細
        (3)設定 font-size 為 18rem，調整文字大小
        (4)設定 text-align 為 center，使文字置中
        (5)設定 background-image 為 url("../img/scenic-2200x1331.png")
        (6)設定 background-size 為 100%
        (7)設定 text-transform 為 uppercase

        開啟 https://caniuse.com/?search=background-clip 確認瀏覽器是否能使用 background-clip
        
        (8)設定 -webkit-background-clip 為 text
        (9)設定文字顏色為黑色，透明度為 20%
        (10)設定文字顏色為透明
        (11)設定 background-clip 為 text，作為瀏覽器不支援時的備用選項

### 22. background property shorthand
        (1)在 body 中復原
        background-image 為 url(../img/bubbles.png), linear-gradient(to left, steelblue, #fff)，
        background-repeat 為 repeat-y, no-repeat，
        background-position 為 right center，
        background-size 為 20% auto;
        (2)使用 background 簡寫取代 background-repeat, background-position, background-image