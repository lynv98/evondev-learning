<!-- variable in css -->
 - khai báo biến: 
    :root{...}
 - sử dụng: var(--name);
<!-- Css selector & Combinator-->
 -Css combinator 
 div p: chọn tất cả thẻ p là con của div(tính cả cháu)
 div > p: chọn tất cả thẻ p là con trực tiếp của div ( không tính cháu)
 div + p: chọn thẻ p liền kề cùng cấp với div
 div ~v p: chọn thẻ p cùng cấp với div

 - emmet trong html
 >: con bên trong
 +: cùng cấp
 *: nhân số lần
 #: id
 .: class
 .class1.class2
 $: thứ tự
 [title=value$]: custom attributes
 {item $}: text
 (): grouping   

 // systax fast
 /* 1 số ký hiệu */
     /* t, l, r, b: top left right bottom :a auto*/
     /* z: z-index */
     /* fl: float*/
     /* d: display */
     /* v: visibility */
     /* o: overflow (ovx, ovy)*/
     /* cur: cursor */
     /* m, p: margin padding */
     /* bxz: box-sizing */
     /* w, h, maw, mah: max-width... */
     /* f, fw, fs, ff... */
     /* va: vertical-align */
     /* ta: text-align, td: text-decoration */
     /* c: color, bg; background, c:r rgb(), c:ra(rgba), opa: opacity */
     /* cnt: content */
     /* ol: outline */
     /* bdrs : border radius */

    <!-- pesudo class -->
    thao tác trực tiếp với thẻ: vị trí của thẻ, hover,...
    selector: pesudo-class{...}
    <!-- pesudo element -->
    thao tác gián tiếp với thẻ: chỉnh sử màu sắc của thé, style trước sau ::apter, before
    selector::pesudo-element{...}

    <!-- atomic desgin -->
    - kiến trúc css, class được chia nhỏ, đảm nhiệm một chức năng khác nhau
    - thư viện tailwind css
    - style cố định được chia nhỏ
    - khai báo 1 lần sử dụng nhiêu lần

    <!-- dots circle -->
    

