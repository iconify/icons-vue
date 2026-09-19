<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iiRNxbe)" transform="rotate(-4.337 14.016 6.699)" class="vhngi0brz"/><path fill="url(#i6Ne7Rx)" transform="rotate(-4.337 14.016 6.699)" class="vhngi0brz"/><path fill="url(#iBhfJjc)" class="jfh6mhbkd"/><g filter="url(#iPl9jPe)"><path fill="url(#iNA3Hhc)" class="goy59mjnj"/><path fill="url(#iply4Zc)" class="goy59mjnj"/></g><g filter="url(#i7btXSb)"><path fill="url(#iJxWybe)" class="eq2rq9_ls"/></g><path fill="url(#iUZSOrK)" class="eq2rq9_ls"/><path fill="url(#i0cRqae)" class="x1m_k_w7d"/><g filter="url(#igFWled)"><path fill="url(#iKRbAgc)" class="oi9m3v5fw"/><path fill="url(#iuDAvue)" class="oi9m3v5fw"/><path fill="url(#ikzHGBe)" class="oi9m3v5fw"/></g><g filter="url(#iETVIcc)"><path class="nil-0yb-e"/><path fill="url(#i4yv9Dd)" class="atkqp4bni"/><path fill="url(#iro3cod)" class="atkqp4bni"/><path fill="url(#i5pAw4G)" class="atkqp4bni"/><path fill="url(#iliUz1b)" class="atkqp4bni"/><path fill="url(#ibSCEDe)" class="atkqp4bni"/></g><path fill="url(#iggyAWb)" class="nzsvucbed"/><path fill="url(#iGaghHb)" class="nzsvucbed"/><path fill="url(#itoNOVc)" class="nzsvucbed"/><path fill="url(#iKNDuud)" class="nzsvucbed"/><path fill="url(#is7AhQc)" class="nzsvucbed"/><path class="zm-13h6pm"/><path fill="url(#iAIddOb)" class="j4yagvc3d"/><path fill="url(#iDWpq5c)" class="j4yagvc3d"/><path fill="url(#ieRD2Md)" class="j4yagvc3d"/><g filter="url(#iiNeJpd)"><path clip-rule="evenodd" class="qoong9y8p"/></g><path fill="url(#iCUiGUF)" class="fwje7xbdz"/><path class="aec09jske"/><path fill="url(#iUe8gRd)" class="ruv3-m1-j"/><path fill="url(#iJNBrIe)" class="ruv3-m1-j"/><path fill="url(#itgdUYc)" class="ruv3-m1-j"/><path fill="url(#i1X1iqc)" class="ruv3-m1-j"/><path fill="url(#ieGsYoO)" class="ruv3-m1-j"/><path fill="url(#ijB1vyb)" class="ruv3-m1-j"/><circle fill="url(#i3u8zsb)" class="ku59qhbwu"/><g filter="url(#izyyHbd)"><path class="hpsek7bxs"/></g><g filter="url(#iVKoXCb)"><path clip-rule="evenodd" class="jtrifveya"/></g><g filter="url(#inbgmed)"><path fill="url(#ikJ7VKc)" class="rrx6lyb8f"/><path fill="url(#iBmXzeI)" class="rrx6lyb8f"/><path fill="url(#ieW21od)" class="rrx6lyb8f"/></g><path fill="url(#izOgPXb)" class="rrx6lyb8f"/><path fill="url(#ifx5ede)" class="ogbr74b_a"/><path clip-rule="evenodd" class="vx1nqnctp"/><path class="z-pxk1bva"/><path fill="url(#i1qBfne)" class="f40yid48g"/><path fill="url(#i2VsjVd)" class="w5ha6gb7b"/><ellipse fill="url(#is5MiLe)" transform="rotate(24.61 12.373 5.247)" class="oq10l_bzx"/><g filter="url(#icDlMmd)"><path fill="url(#i0HhFvd)" class="trooh4bhx"/></g><g filter="url(#i4P0vla)"><path fill="url(#izYCoRr)" class="ip6ypkbod"/></g><g filter="url(#icT118b)"><path class="x18acf5hu"/></g><defs><radialGradient id="iiRNxbe" cx="0" cy="0" r="1" gradientTransform="matrix(-.05152 -2.21336 1.59858 -.0372 15.724 8.708)" gradientUnits="userSpaceOnUse"><stop offset=".116" class="zfe5-2blx"/><stop offset="1" class="y9fv3rfwl"/></radialGradient><radialGradient id="i6Ne7Rx" cx="0" cy="0" r="1" gradientTransform="matrix(-.53617 .66448 -.89991 -.72614 16.078 7.138)" gradientUnits="userSpaceOnUse"><stop class="dtmda4epx"/><stop offset="1" class="m4p4mmbye"/></radialGradient><radialGradient id="iBhfJjc" cx="0" cy="0" r="1" gradientTransform="matrix(.3125 .60583 -.77155 .39799 11.3 5.917)" gradientUnits="userSpaceOnUse"><stop offset=".332" class="fvok_qxen"/><stop offset="1" class="suyap8bzv"/></radialGradient><radialGradient id="iply4Zc" cx="0" cy="0" r="1" gradientTransform="matrix(-.84375 -.04688 .05715 -1.0287 14.84 5.503)" gradientUnits="userSpaceOnUse"><stop offset=".156" class="d7kch3t0q"/><stop offset="1" class="admd7db0k"/></radialGradient><radialGradient id="iJxWybe" cx="0" cy="0" r="1" gradientTransform="matrix(-3.43749 3.12502 -3.54357 -3.89789 16.715 2.841)" gradientUnits="userSpaceOnUse"><stop offset=".363" class="jve2rcqoj"/><stop offset="1" class="kpbiulbbs"/></radialGradient><radialGradient id="iUZSOrK" cx="0" cy="0" r="1" gradientTransform="matrix(-.1172 -1.30469 2.76646 -.2485 16.082 7.036)" gradientUnits="userSpaceOnUse"><stop offset=".064" class="jfv70ccah"/><stop offset="1" class="b30rr0b3q"/></radialGradient><radialGradient id="i0cRqae" cx="0" cy="0" r="1" gradientTransform="rotate(115.703 5.9 7.42)scale(1.04478 1.69772)" gradientUnits="userSpaceOnUse"><stop offset=".04" class="bervkqbmz"/><stop offset="1" class="c479w-bpn"/></radialGradient><radialGradient id="iuDAvue" cx="0" cy="0" r="1" gradientTransform="matrix(2.45369 2.93958 -5.96661 4.98038 16.953 17.98)" gradientUnits="userSpaceOnUse"><stop offset=".434" class="oiy_54b9a"/><stop offset="1" class="rm4aiz5dn"/></radialGradient><radialGradient id="ikzHGBe" cx="0" cy="0" r="1" gradientTransform="matrix(.89062 .65625 -3.9414 5.34905 16.637 18.995)" gradientUnits="userSpaceOnUse"><stop offset=".043" class="v5lz4sb9o"/><stop offset="1" class="m_uy2vb_d"/></radialGradient><radialGradient id="i4yv9Dd" cx="0" cy="0" r="1" gradientTransform="matrix(3.25 -5.14063 1.35402 .85604 15.856 20.839)" gradientUnits="userSpaceOnUse"><stop offset=".07" class="mngz2ebss"/><stop offset="1" class="ttsumpbek"/></radialGradient><radialGradient id="iro3cod" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.42188 -1.38588 0 16.668 16.136)" gradientUnits="userSpaceOnUse"><stop class="f3j6dkfip"/><stop offset="1" class="fxoxl0blj"/></radialGradient><radialGradient id="iliUz1b" cx="0" cy="0" r="1" gradientTransform="matrix(.14063 -.17968 .6458 .50543 11.973 28.05)" gradientUnits="userSpaceOnUse"><stop class="ryq0o3qru"/><stop offset="1" class="yfqxgqb1h"/></radialGradient><radialGradient id="ibSCEDe" cx="0" cy="0" r="1" gradientTransform="matrix(6.375 -1.8125 4.67455 16.4415 12.293 19.183)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="ex23x-brg"/><stop offset="1" class="ux4w7lb6c"/></radialGradient><radialGradient id="iggyAWb" cx="0" cy="0" r="1" gradientTransform="matrix(-.09375 -1.53125 2.45635 -.15039 10.84 29.401)" gradientUnits="userSpaceOnUse"><stop class="cl2mlwbhs"/><stop offset="1" class="yvuyjoqpy"/></radialGradient><radialGradient id="iGaghHb" cx="0" cy="0" r="1" gradientTransform="matrix(1.0625 -.21875 .15137 .73521 7.73 28.464)" gradientUnits="userSpaceOnUse"><stop class="m3n9jy0fh"/><stop offset="1" class="hdzwkybza"/></radialGradient><radialGradient id="itoNOVc" cx="0" cy="0" r="1" gradientTransform="rotate(-70.942 26.713 6.607)scale(1.81842 .89694)" gradientUnits="userSpaceOnUse"><stop offset=".08" class="a541b3bqx"/><stop offset="1" class="zc8ie-1dg"/></radialGradient><radialGradient id="ieRD2Md" cx="0" cy="0" r="1" gradientTransform="rotate(-132.875 17.84 8.331)scale(1.99789 1.10527)" gradientUnits="userSpaceOnUse"><stop class="xh_da2q2q"/><stop offset="1" class="stwbr2bhy"/></radialGradient><radialGradient id="iUe8gRd" cx="0" cy="0" r="1" gradientTransform="rotate(-160.71 8.757 3.486)scale(1.65544 2.30985)" gradientUnits="userSpaceOnUse"><stop offset=".266" class="anxjqssms"/><stop offset="1" class="p0binz11r"/></radialGradient><radialGradient id="iJNBrIe" cx="0" cy="0" r="1" gradientTransform="matrix(-.09377 -4.95122 1.33998 -.02538 16.564 16.135)" gradientUnits="userSpaceOnUse"><stop class="ba65pd9sy"/><stop offset="1" class="c0n24ybhp"/></radialGradient><radialGradient id="itgdUYc" cx="0" cy="0" r="1" gradientTransform="matrix(3.65186 0 0 15.6875 14.689 14.247)" gradientUnits="userSpaceOnUse"><stop offset=".436" class="l7vpqwwuy"/><stop offset="1" class="r5z1pjbbo"/></radialGradient><radialGradient id="i1X1iqc" cx="0" cy="0" r="1" gradientTransform="matrix(-4.78125 .78125 -1.79108 -10.96143 18.064 15.06)" gradientUnits="userSpaceOnUse"><stop offset=".781" class="gxh5rg5pu"/><stop offset=".931" class="x45bnccdq"/></radialGradient><radialGradient id="ieGsYoO" cx="0" cy="0" r="1" gradientTransform="matrix(-2 -7.58203 5.68464 -1.4995 16.652 16.136)" gradientUnits="userSpaceOnUse"><stop offset=".908" class="o1-ca2hwf"/><stop offset=".983" class="gt4gdfbnu"/></radialGradient><radialGradient id="i3u8zsb" cx="0" cy="0" r="1" gradientTransform="rotate(90 1.481 19.312)scale(.90625)" gradientUnits="userSpaceOnUse"><stop offset=".256" class="d69nsybly"/><stop offset="1" class="eluf2xb_e"/></radialGradient><radialGradient id="iBmXzeI" cx="0" cy="0" r="1" gradientTransform="matrix(1.0907 .20313 -.42058 2.25834 14.88 10.294)" gradientUnits="userSpaceOnUse"><stop offset=".12" class="c7e6m9b-c"/><stop offset="1" class="kqn0y5w2b"/></radialGradient><radialGradient id="ieW21od" cx="0" cy="0" r="1" gradientTransform="rotate(-132.997 12.013 1.696)scale(3.16181 1.21321)" gradientUnits="userSpaceOnUse"><stop class="mpu3do46a"/><stop offset="1" class="ftb4gxmwr"/></radialGradient><radialGradient id="izOgPXb" cx="0" cy="0" r="1" gradientTransform="matrix(.46875 1.14253 -2.54725 1.04507 15.543 8.745)" gradientUnits="userSpaceOnUse"><stop offset=".126" class="jogzo_66p"/><stop offset="1" class="hir3rg47y"/></radialGradient><radialGradient id="ifx5ede" cx="0" cy="0" r="1" gradientTransform="matrix(1.09375 .1806 -.14313 .86684 8.324 16.354)" gradientUnits="userSpaceOnUse"><stop class="j4xesqbgr"/><stop offset=".839" class="fa3xzswyd"/></radialGradient><radialGradient id="i1qBfne" cx="0" cy="0" r="1" gradientTransform="matrix(.27344 0 0 .53125 12.477 5.577)" gradientUnits="userSpaceOnUse"><stop offset=".895" class="l0aricxam"/><stop offset="1" class="n9r91ylyy"/></radialGradient><radialGradient id="i2VsjVd" cx="0" cy="0" r="1" gradientTransform="matrix(.25 0 0 .54102 12.309 5.599)" gradientUnits="userSpaceOnUse"><stop class="gv3iwdbvq"/><stop offset=".813" class="ubyl24bdb"/></radialGradient><linearGradient id="iNA3Hhc" x1="14.528" x2="11.665" y1="6.245" y2="6.417" gradientUnits="userSpaceOnUse"><stop class="egm-dub4f"/><stop offset="1" class="zhwoohbuw"/></linearGradient><linearGradient id="iKRbAgc" x1="17.973" x2="20.202" y1="22.839" y2="20.896" gradientUnits="userSpaceOnUse"><stop offset=".211" class="pat1zf4-w"/><stop offset="1" class="wtea7v6lu"/></linearGradient><linearGradient id="i5pAw4G" x1="15.746" x2="15.746" y1="16.026" y2="16.37" gradientUnits="userSpaceOnUse"><stop offset=".136" class="x5p6yzbmf"/><stop offset="1" class="cnh3p8b3x"/></linearGradient><linearGradient id="iKNDuud" x1="10.278" x2="10.364" y1="29.573" y2="29.261" gradientUnits="userSpaceOnUse"><stop class="l138bfbcs"/><stop offset="1" class="oxce79bcz"/></linearGradient><linearGradient id="is7AhQc" x1="12.246" x2="11.668" y1="29.948" y2="29.73" gradientUnits="userSpaceOnUse"><stop offset=".064" class="lhdz7oxfj"/><stop offset="1" class="csaq2_bel"/></linearGradient><linearGradient id="iAIddOb" x1="20.856" x2="21.45" y1="27.933" y2="28.105" gradientUnits="userSpaceOnUse"><stop class="oxg1n1wjw"/><stop offset="1" class="y0g_czb9f"/></linearGradient><linearGradient id="iDWpq5c" x1="22.981" x2="22.801" y1="28.007" y2="27.858" gradientUnits="userSpaceOnUse"><stop class="p6qc3nb-j"/><stop offset="0" class="ezcqmvbni"/><stop offset="1" class="stwbr2bhy"/></linearGradient><linearGradient id="iCUiGUF" x1="13.34" x2="12.754" y1="12.833" y2="12.122" gradientUnits="userSpaceOnUse"><stop class="f8fpq6bgz"/><stop offset="1" class="w48m3830t"/></linearGradient><linearGradient id="ijB1vyb" x1="16.059" x2="16.059" y1="16.169" y2="15.989" gradientUnits="userSpaceOnUse"><stop class="znpkhwbgq"/><stop offset="1" class="z629lk5yz"/></linearGradient><linearGradient id="ikJ7VKc" x1="16.731" x2="17.84" y1="9.073" y2="12.527" gradientUnits="userSpaceOnUse"><stop offset=".118" class="bds_ezblb"/><stop offset="1" class="y3zdm1aic"/></linearGradient><linearGradient id="is5MiLe" x1="12.302" x2="12.488" y1="5.209" y2="5.27" gradientUnits="userSpaceOnUse"><stop class="vc--wpv5i"/><stop offset="1" class="stui2mbih"/></linearGradient><linearGradient id="i0HhFvd" x1="12.075" x2="16.7" y1="27.37" y2="17.23" gradientUnits="userSpaceOnUse"><stop class="v9kimlbms"/><stop offset="1" class="g24ahctiy"/></linearGradient><linearGradient id="izYCoRr" x1="22.219" x2="17.908" y1="25.279" y2="19.907" gradientUnits="userSpaceOnUse"><stop class="ckhjb_bgt"/><stop offset="1" class="rnrhdzckq"/></linearGradient><filter id="iPl9jPe" width="4.443" height="5.249" x="11.465" y="3.305" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2" dy="-.2"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.780392 0 0 0 0 0.576471 0 0 0 0 0.2 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_96"/></filter><filter id="i7btXSb" width="6.391" height="5.479" x="11.032" y="1.66" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.3" dy=".3"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.835294 0 0 0 0 0.211765 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_96"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.3"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.976471 0 0 0 0 0.592157 0 0 0 0 0.109804 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_96" result="effect2_innerShadow_4002_96"/></filter><filter id="igFWled" width="8.674" height="14.771" x="16.188" y="15.417" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".75" dy="-.75"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.439216 0 0 0 0 0.388235 0 0 0 0 0.486275 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_96"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.537255 0 0 0 0 0.423529 0 0 0 0 0.635294 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_96" result="effect2_innerShadow_4002_96"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy=".25"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.529412 0 0 0 0 0.490196 0 0 0 0 0.537255 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_4002_96" result="effect3_innerShadow_4002_96"/></filter><filter id="iETVIcc" width="10.972" height="14.104" x="7.882" y="15.936" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy="-.2"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.619608 0 0 0 0 0.592157 0 0 0 0 0.611765 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_96"/></filter><filter id="iiNeJpd" width="8.438" height="7.859" x="6.785" y="10.566" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-1"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.894118 0 0 0 0 0.505882 0 0 0 0 0.137255 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_96"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.752941 0 0 0 0 0.466667 0 0 0 0 0.254902 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_96" result="effect2_innerShadow_4002_96"/></filter><filter id="izyyHbd" width="5.586" height="5.875" x="14.26" y="8.255" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_96" stdDeviation=".375"/></filter><filter id="iVKoXCb" width="7.59" height="10.511" x="15.741" y="9.099" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.901961 0 0 0 0 0.623529 0 0 0 0 0.188235 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_96"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.4" dy=".4"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.835294 0 0 0 0 0.25098 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_96" result="effect2_innerShadow_4002_96"/></filter><filter id="inbgmed" width="4.758" height="4.525" x="14.879" y="8.595" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.15"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.160784 0 0 0 0 0.47451 0 0 0 0 0.866667 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_96"/></filter><filter id="icDlMmd" width="6.844" height="12.891" x="10.856" y="16.058" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_96" stdDeviation=".5"/></filter><filter id="i4P0vla" width="6.45" height="8.475" x="16.804" y="17.986" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_96" stdDeviation=".375"/></filter><filter id="icT118b" width="1.117" height=".649" x="12.268" y="4.231" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy=".1"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.619608 0 0 0 0 0.2 0 0 0 0 0.0862745 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_96"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:man-walking" /></template>
<style>
.a541b3bqx {
  stop-color: var(--svg-color--515279, #515279);
}

.admd7db0k {
  stop-color: var(--svg-color--ffab1d, #FFAB1D);
  stop-opacity: 0;
}

.aec09jske {
  fill: var(--svg-color--397ec9, #397EC9);
  d: path("M15.524 8.554c.89 0 1.136.215 1.433.406l1.024 2.598c.3 1.4.364 3.635.36 4.578h-4.747c-.258-.656-.697-2.675-.535-4.578c.164-1.93 1.207-2.903 2.465-3.004");
}

.anxjqssms {
  stop-color: var(--svg-color--3d98c9, #3D98C9);
}

.atkqp4bni {
  d: path("M12.817 18.519c.383-1.051.716-2.029.773-2.383h4.742c.1 1.375-.144 1.712-.773 2.422c-.693.781-2.172 2.43-2.54 2.894c-.35.35-.5.79-.554.98l-2.262 7.43a.25.25 0 0 1-.315.166l-3.737-1.182c-.195-.062-.326-.266-.244-.453c.107-.244.333-.499.886-.656c.663-.187 1.943-.283 2.516-.335c.213-1.766.66-5.432.734-5.97c.094-.671.227-1.413.774-2.913");
}

.b30rr0b3q {
  stop-color: var(--svg-color--ef9926, #EF9926);
  stop-opacity: 0;
}

.ba65pd9sy {
  stop-color: var(--svg-color--407bbe, #407BBE);
}

.bds_ezblb {
  stop-color: var(--svg-color--2e83d0, #2E83D0);
}

.bervkqbmz {
  stop-color: var(--svg-color--ffd040, #FFD040);
}

.c0n24ybhp {
  stop-color: var(--svg-color--407bbe, #407BBE);
  stop-opacity: 0;
}

.c479w-bpn {
  stop-color: var(--svg-color--fead30, #FEAD30);
}

.c7e6m9b-c {
  stop-color: var(--svg-color--5696dc, #5696DC);
}

.ckhjb_bgt {
  stop-color: var(--svg-color--a39fa7, #A39FA7);
}

.cl2mlwbhs {
  stop-color: var(--svg-color--4a4b75, #4A4B75);
}

.cnh3p8b3x {
  stop-color: var(--svg-color--817076, #817076);
  stop-opacity: 0;
}

.csaq2_bel {
  stop-color: var(--svg-color--444571, #444571);
  stop-opacity: 0;
}

.d69nsybly {
  stop-color: var(--svg-color--e99f2e, #E99F2E);
}

.d7kch3t0q {
  stop-color: var(--svg-color--ffab1d, #FFAB1D);
}

.dtmda4epx {
  stop-color: var(--svg-color--bb851e, #BB851E);
}

.egm-dub4f {
  stop-color: var(--svg-color--ffc33e, #FFC33E);
}

.eluf2xb_e {
  stop-color: var(--svg-color--ce853f, #CE853F);
}

.eq2rq9_ls {
  d: path("M12.332 4.052c-.656 0-.969-.371-1-.836c0-.656.501-.796.695-.816c.22-.024.305-.047.61-.262a.9.9 0 0 1 .91-.098c.148.07.476.106.71.035c.391-.117.696-.113.997.118c.209.16.363.16.613.16c.344 0 .636.154.856.32c.657.497.582 2.207.258 3.168c-.31.92-.778 1.027-1.169.992c-.47-.042-.59-.398-.66-.695c-.056-.238-.2-.792-.265-1.04a1.07 1.07 0 0 1-.532-.671c-.1-.388-.492-.432-.757-.406c-.162.015-.61.03-1.266.03");
}

.ex23x-brg {
  stop-color: var(--svg-color--8c8388, #8C8388);
  stop-opacity: 0;
}

.ezcqmvbni {
  stop-color: var(--svg-color--443a80, #443A80);
}

.f3j6dkfip {
  stop-color: var(--svg-color--99919a, #99919A);
}

.f40yid48g {
  d: path("M12.805 5.599v-.004c0-.32-.137-.58-.307-.58s-.306.26-.306.58v.004z");
}

.f8fpq6bgz {
  stop-color: var(--svg-color--3981ca, #3981CA);
}

.fa3xzswyd {
  stop-color: var(--svg-color--eb9f1c, #EB9F1C);
}

.ft5dv1b6b {
  fill: none;
}

.ftb4gxmwr {
  stop-color: var(--svg-color--4d95e1, #4D95E1);
  stop-opacity: 0;
}

.fvok_qxen {
  stop-color: var(--svg-color--ffbf42, #FFBF42);
}

.fwje7xbdz {
  d: path("M13.215 10.456c.281-.712.774-1.224.985-1.39l-.04 4.468l-1.785-.836c.278-.523.489-1.351.84-2.242");
}

.fxoxl0blj {
  stop-color: var(--svg-color--8c8393, #8C8393);
  stop-opacity: 0;
}

.g24ahctiy {
  stop-color: var(--svg-color--94899e, #94899E);
  stop-opacity: 0;
}

.goy59mjnj {
  d: path("M11.693 4.805c.039-.801.298-1.188.42-1.3h3.733l.062 3.163c-.866 2.122-3.511 2.213-3.906 1.445c-.395-.767-.354-2.38-.309-3.308");
}

.gt4gdfbnu {
  stop-color: var(--svg-color--648ba6, #648BA6);
}

.gv3iwdbvq {
  stop-color: var(--svg-color--666361, #666361);
}

.gxh5rg5pu {
  stop-color: var(--svg-color--588fc4, #588FC4);
  stop-opacity: 0;
}

.hdzwkybza {
  stop-color: var(--svg-color--63617e, #63617E);
  stop-opacity: 0;
}

.hir3rg47y {
  stop-color: var(--svg-color--4080be, #4080BE);
  stop-opacity: 0;
}

.hpsek7bxs {
  fill: var(--svg-color--1049ac, #1049AC);
  d: path("M15.473 11.232c-.31-.249-.463-.639-.463-1.067c0-.749.185-1.16.934-1.16c.337 0 .645.123.882.327c.951.691 1.79 1.591 2.27 2.134l-2.039 1.914a357 357 0 0 1-1.584-2.149");
}

.ip6ypkbod {
  d: path("m19.028 21.084l3.476 4.428l-.514.198l-3.485-3.708a3 3 0 0 1-.76-1.493l-.19-1l.75-.773l.544 1.993q.054.195.179.355");
}

.j4xesqbgr {
  stop-color: var(--svg-color--ffbf3f, #FFBF3F);
}

.j4yagvc3d {
  d: path("m23.035 25.61l-1.638.677l.022.02l-.108.355c-.216.713-.535 1.764-.62 2.27c-.076.463.146.769.352.953c.093.083.234.064.318-.029l2.687-2.995a.25.25 0 0 0-.018-.353l-.986-.888z");
}

.jfh6mhbkd {
  d: path("M11.47 5.769c.155-.147.236-.366.257-.457h.18v1.125c-.215.136-.523.115-.614-.09c-.078-.176-.02-.395.176-.578");
}

.jfv70ccah {
  stop-color: var(--svg-color--b28146, #B28146);
}

.jogzo_66p {
  stop-color: var(--svg-color--5b789d, #5B789D);
}

.jtrifveya {
  fill: var(--svg-color--ffbf35, #FFBF35);
  fill-rule: evenodd;
  d: path("M21.836 19.18a.614.614 0 0 1-.775-.407c-1.215-3.922-3.166-6.29-4.542-7.545c-.438-.4-.516-1.082-.128-1.53c.346-.402.944-.473 1.348-.13c1.626 1.38 3.91 3.976 5.316 8.605a.59.59 0 0 1-.382.729z");
}

.jve2rcqoj {
  stop-color: var(--svg-color--ffbc2b, #FFBC2B);
}

.kpbiulbbs {
  stop-color: var(--svg-color--ffa629, #FFA629);
}

.kqn0y5w2b {
  stop-color: var(--svg-color--5696dc, #5696DC);
  stop-opacity: 0;
}

.ku59qhbwu {
  cx: 20.93px;
  cy: 17.983px;
  r: 0.551px;
}

.l0aricxam {
  stop-color: var(--svg-color--916a62, #916A62);
}

.l138bfbcs {
  stop-color: var(--svg-color--282955, #282955);
}

.l7vpqwwuy {
  stop-color: var(--svg-color--4475a6, #4475A6);
  stop-opacity: 0;
}

.lhdz7oxfj {
  stop-color: var(--svg-color--444571, #444571);
}

.m_uy2vb_d {
  stop-color: var(--svg-color--695c75, #695C75);
  stop-opacity: 0;
}

.m3n9jy0fh {
  stop-color: var(--svg-color--63617e, #63617E);
}

.m4p4mmbye {
  stop-color: var(--svg-color--e2b639, #E2B639);
  stop-opacity: 0;
}

.mngz2ebss {
  stop-color: var(--svg-color--897998, #897998);
}

.mpu3do46a {
  stop-color: var(--svg-color--4d95e1, #4D95E1);
}

.n9r91ylyy {
  stop-color: var(--svg-color--824d44, #824D44);
}

.nil-0yb-e {
  fill: var(--svg-color--8c8393, #8C8393);
  d: path("M12.817 18.519c.383-1.051.716-2.029.773-2.383h4.742c.1 1.375-.144 1.712-.773 2.422c-.693.781-2.172 2.43-2.54 2.894c-.35.35-.5.79-.554.98l-2.262 7.43a.25.25 0 0 1-.315.166l-3.737-1.182c-.195-.062-.326-.266-.244-.453c.107-.244.333-.499.886-.656c.663-.187 1.943-.283 2.516-.335c.213-1.766.66-5.432.734-5.97c.094-.671.227-1.413.774-2.913");
}

.nzsvucbed {
  d: path("m12.594 28.577l-.391 1.286a.25.25 0 0 1-.315.165l-3.737-1.182c-.195-.062-.326-.266-.244-.453c.107-.244.333-.499.886-.656c.59-.167 1.673-.261 2.306-.317l.21-.019V27.4z");
}

.o1-ca2hwf {
  stop-color: var(--svg-color--648ba6, #648BA6);
  stop-opacity: 0;
}

.ogbr74b_a {
  d: path("m8.657 15.968l.496.052c.21.022.374.192.388.402a.38.38 0 0 1-.076.267c-.264.33-.525.366-.722.408c-.219.047-.676-.192-.59-.692a.53.53 0 0 1 .504-.437");
}

.oi9m3v5fw {
  d: path("m19.169 19.902l-.89-3.735h-1.782c-.052.615-.152 2.216-.29 3.516s.493 2.031.766 2.312l4.446 4.313c-.198.661-.627 2.025-.727 2.625c-.077.462.145.768.35.952c.094.083.235.064.319-.029l2.688-2.995a.25.25 0 0 0-.02-.353l-.985-.888c-1.042-1.364-3.19-4.193-3.453-4.594c-.182-.276-.391-.916-.422-1.125");
}

.oiy_54b9a {
  stop-color: var(--svg-color--887e8b, #887E8B);
}

.oq10l_bzx {
  cx: 12.373px;
  cy: 5.247px;
  rx: 0.064px;
  ry: 0.088px;
}

.oxce79bcz {
  stop-color: var(--svg-color--282955, #282955);
  stop-opacity: 0;
}

.oxg1n1wjw {
  stop-color: var(--svg-color--5a577e, #5A577E);
}

.p0binz11r {
  stop-color: var(--svg-color--3d98c9, #3D98C9);
  stop-opacity: 0;
}

.p6qc3nb-j {
  stop-color: var(--svg-color--492d85, #492D85);
}

.pat1zf4-w {
  stop-color: var(--svg-color--8b8290, #8B8290);
}

.qoong9y8p {
  fill: var(--svg-color--f5b02e, #F5B02E);
  fill-rule: evenodd;
  d: path("M9.169 18.347a.85.85 0 0 1-1.13-.433l-.19-.426a.755.755 0 0 1 .383-.992c1.533-.704 4.023-2.15 4.983-5.93l2.008.523c-1.186 4.668-4.29 6.44-6.054 7.258");
}

.r5z1pjbbo {
  stop-color: var(--svg-color--4475a6, #4475A6);
}

.rm4aiz5dn {
  stop-color: var(--svg-color--887e8b, #887E8B);
  stop-opacity: 0;
}

.rnrhdzckq {
  stop-color: var(--svg-color--a39fa7, #A39FA7);
  stop-opacity: 0;
}

.rrx6lyb8f {
  d: path("M15.388 11.16a1.355 1.355 0 1 1 1.729-2.088c.95.691 1.79 1.591 2.27 2.134l-2.04 1.914c-.307-.32-1.381-1.392-1.959-1.96");
}

.ruv3-m1-j {
  d: path("M15.524 8.554c.89 0 1.136.215 1.433.406l1.024 2.598c.3 1.4.364 3.635.36 4.578h-4.747c-.258-.656-.697-2.675-.535-4.578c.164-1.93 1.207-2.903 2.465-3.004");
}

.ryq0o3qru {
  stop-color: var(--svg-color--a19da6, #A19DA6);
}

.stui2mbih {
  stop-color: var(--svg-color--fff, #fff);
  stop-opacity: 0;
}

.stwbr2bhy {
  stop-color: var(--svg-color--46437b, #46437B);
  stop-opacity: 0;
}

.suyap8bzv {
  stop-color: var(--svg-color--eba544, #EBA544);
}

.trooh4bhx {
  d: path("m13.2 21.136l-1.344 6.5l.36.312l1.468-6.53l3.016-3.876l-.704-.484z");
}

.ttsumpbek {
  stop-color: var(--svg-color--897998, #897998);
  stop-opacity: 0;
}

.ubyl24bdb {
  stop-color: var(--svg-color--565352, #565352);
}

.ux4w7lb6c {
  stop-color: var(--svg-color--8c8388, #8C8388);
}

.v5lz4sb9o {
  stop-color: var(--svg-color--695c75, #695C75);
}

.v9kimlbms {
  stop-color: var(--svg-color--94899e, #94899E);
}

.vc--wpv5i {
  stop-color: var(--svg-color--fff, #fff);
}

.vhngi0brz {
  d: path("M14.016 6.699h1.946v3.44h-1.946z");
}

.vx1nqnctp {
  fill: var(--svg-color--87014d, #87014D);
  fill-rule: evenodd;
  d: path("M12.945 6.712a.125.125 0 0 1-.002.177c-.238.234-.582.294-.692.305a.125.125 0 1 1-.025-.249c.093-.01.366-.062.542-.234a.125.125 0 0 1 .177.001");
}

.w48m3830t {
  stop-color: var(--svg-color--4e98d7, #4E98D7);
}

.w5ha6gb7b {
  d: path("m12.61 5.599l.004-.073c0-.185-.08-.335-.176-.335c-.097 0-.176.15-.176.335q0 .038.004.073z");
}

.wtea7v6lu {
  stop-color: var(--svg-color--9f9c9f, #9F9C9F);
}

.x18acf5hu {
  stroke: var(--svg-color--bc5f4e, #BC5F4E);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M12.469 4.43c.129 0 .41 0 .617.15");
}

.x1m_k_w7d {
  d: path("m14.464 6.26l.2-1.44a.727.727 0 0 1-.2 1.44");
}

.x45bnccdq {
  stop-color: var(--svg-color--588fc4, #588FC4);
}

.x5p6yzbmf {
  stop-color: var(--svg-color--817076, #817076);
}

.xh_da2q2q {
  stop-color: var(--svg-color--60618d, #60618D);
}

.y0g_czb9f {
  stop-color: var(--svg-color--5a577e, #5A577E);
  stop-opacity: 0;
}

.y3zdm1aic {
  stop-color: var(--svg-color--3384e0, #3384E0);
}

.y9fv3rfwl {
  stop-color: var(--svg-color--daa238, #DAA238);
}

.yfqxgqb1h {
  stop-color: var(--svg-color--a19da6, #A19DA6);
  stop-opacity: 0;
}

.yvuyjoqpy {
  stop-color: var(--svg-color--47456f, #47456F);
}

.z-pxk1bva {
  fill: var(--svg-color--fff, #fff);
  d: path("M12.2 5.599h.988c0-.392-.222-.71-.494-.71c-.273 0-.495.318-.495.71");
}

.z629lk5yz {
  stop-color: var(--svg-color--417ab5, #417AB5);
  stop-opacity: 0;
}

.zc8ie-1dg {
  stop-color: var(--svg-color--515279, #515279);
  stop-opacity: 0;
}

.zfe5-2blx {
  stop-color: var(--svg-color--fcce3f, #FCCE3F);
}

.zhwoohbuw {
  stop-color: var(--svg-color--ffc247, #FFC247);
}

.zm-13h6pm {
  fill: var(--svg-color--45437a, #45437A);
  d: path("m23.035 25.61l-1.638.677l.022.02l-.108.355c-.216.713-.535 1.764-.62 2.27c-.076.463.146.769.352.953c.093.083.234.064.318-.029l2.687-2.995a.25.25 0 0 0-.018-.353l-.986-.888z");
}

.znpkhwbgq {
  stop-color: var(--svg-color--445b8b, #445B8B);
}

</style>
