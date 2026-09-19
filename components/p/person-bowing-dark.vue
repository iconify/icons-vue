<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iv89uPd)" class="lwps2obys"/><path fill="url(#iWiAcSx)" class="lwps2obys"/><path fill="url(#iiHXf7b)" class="lwps2obys"/><g filter="url(#iZuqTYm)"><path fill="url(#i30XoYh)" class="txd0f1icf"/><path fill="url(#i2fVYxd)" class="txd0f1icf"/></g><path fill="url(#iS1QEAd)" class="pkmnhobup"/><path fill="url(#iTdsYBe)" class="pkmnhobup"/><path fill="url(#iCx1BUd)" class="pkmnhobup"/><path fill="url(#iZhI9Td)" class="pkmnhobup"/><path fill="url(#iY8aclc)" class="pkmnhobup"/><g filter="url(#iifh18d)"><path fill="url(#ivTqIPb)" class="a76pxr2zz"/></g><g filter="url(#iRAKXSd)"><path fill="url(#inZmpUb)" class="xbmasxbtf"/></g><g filter="url(#i1sVnee)"><path fill="url(#imBreIb)" class="ryvejj5je"/></g><path fill="url(#iNEAHsc)" class="eembywbiw"/><path fill="url(#iaQUBdd)" class="o-97ijbge"/><path fill="url(#i9RpBld)" class="o-97ijbge"/><g filter="url(#iCkRLNb)"><path class="ivu6jd0iq"/><path fill="url(#iWdsTke)" class="rq808nblb"/><path fill="url(#iyhnZPe)" class="rq808nblb"/><path fill="url(#iJswygd)" class="rq808nblb"/><path fill="url(#iHmqLrc)" class="rq808nblb"/><path fill="url(#ixZXHGe)" class="rq808nblb"/></g><g filter="url(#iUrvOCc)"><path class="hwl1wzb5h"/></g><g filter="url(#iXcS0bc)"><path class="nsdlvubzy"/></g><g filter="url(#i2QMxRb)"><path class="lfhwesbpt"/></g><g filter="url(#iEiVyYb)"><path class="uuaqpn7jb"/><path fill="url(#inaqsKb)" class="i8b3k7x5a"/></g><path fill="url(#ibfphcU)" class="i8b3k7x5a"/><g filter="url(#iY7Vqzc)"><path fill="url(#i2o4sob)" class="tqq30fi4f"/><path fill="url(#iX2OIYc)" class="tqq30fi4f"/><path fill="url(#iq5swkc)" class="tqq30fi4f"/></g><g filter="url(#ibM9E8Z)"><path fill="url(#iwxBX1H)" class="v7at5lbln"/></g><g filter="url(#iRvvyqc)"><path fill="url(#ikg0KSb)" class="toaba5-2f"/><path fill="url(#i4cNyDb)" class="toaba5-2f"/><path fill="url(#it4V3gc)" class="toaba5-2f"/></g><path class="krbucv5ge"/><path fill="url(#itEUNKb)" class="vcev7m60r"/><path class="o1ialsbyj"/><g filter="url(#icOsmgb)"><path fill="url(#in4rMlc)" class="malbd67au"/></g><g filter="url(#icICe8d)"><ellipse transform="rotate(-27.914 12.82 20.378)" class="hs9amccpo"/><ellipse fill="url(#iuNsYfn)" transform="rotate(-27.914 12.82 20.378)" class="gkwz71b2m"/></g><path class="dwlm-abvw"/><path fill="url(#iYtLDVc)" class="nqgeh70eu"/><path class="gb_qn6urd"/><g filter="url(#i0L7Sob)"><path fill="url(#i0KlVJb)" class="ypw2_2bvq"/></g><g filter="url(#iXf91Rb)"><ellipse transform="rotate(-27.914 18.477 20.378)" class="ra9_m8sho"/><ellipse fill="url(#iAKuyad)" transform="rotate(-27.914 18.477 20.378)" class="ladvbr8pz"/></g><g filter="url(#ibCngUc)"><path stroke="url(#i2Y4uex)" class="e7ibb9z3d"/></g><g filter="url(#it9eJoe)"><path stroke="url(#icRpJSc)" class="kjz636bae"/></g><g filter="url(#iOBWtxb)"><path class="g2__l29ji"/></g><g filter="url(#i5blMpd)"><path fill="url(#iaPmsHe)" class="cdhyx9bbc"/></g><defs><radialGradient id="iv89uPd" cx="0" cy="0" r="1" gradientTransform="rotate(123.959 7.435 15.856)scale(12.144 23.7823)" gradientUnits="userSpaceOnUse"><stop class="tn5cwfbmj"/><stop offset=".27" class="gur5_240r"/><stop offset="1" class="hke44nb4h"/></radialGradient><radialGradient id="iWiAcSx" cx="0" cy="0" r="1" gradientTransform="matrix(-3.01499 4.36558 -4.67954 -3.23182 14.325 23.5)" gradientUnits="userSpaceOnUse"><stop offset=".5" class="ml47xab2p"/><stop offset="1" class="ih_n8tb4s"/></radialGradient><radialGradient id="i30XoYh" cx="0" cy="0" r="1" gradientTransform="rotate(-164.898 7.342 12.764)scale(6.67145 7.19435)" gradientUnits="userSpaceOnUse"><stop class="ygnqhzbrp"/><stop offset="1" class="pmiei2beq"/></radialGradient><radialGradient id="iS1QEAd" cx="0" cy="0" r="1" gradientTransform="matrix(-8.03127 4.7187 -4.36101 -7.42248 28.486 24.434)" gradientUnits="userSpaceOnUse"><stop class="mi21-2olq"/><stop offset=".724" class="wziyle_fm"/></radialGradient><radialGradient id="iCx1BUd" cx="0" cy="0" r="1" gradientTransform="matrix(6.28125 -1.78432 .36961 1.30113 22.267 27)" gradientUnits="userSpaceOnUse"><stop offset=".078" class="sludkgsww"/><stop offset="1" class="pjd1wtbcg"/></radialGradient><radialGradient id="iZhI9Td" cx="0" cy="0" r="1" gradientTransform="matrix(-6.04861 -4.1627 5.4796 -7.96214 25.049 31.292)" gradientUnits="userSpaceOnUse"><stop offset=".855" class="sd7jkkb7x"/><stop offset="1" class="lt28sz2zp"/></radialGradient><radialGradient id="iNEAHsc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.79873 0 0 -1.83056 9.75 17.93)" gradientUnits="userSpaceOnUse"><stop offset=".32" class="tyr2ocbkv"/><stop offset="1" class="mnuqjbbig"/></radialGradient><radialGradient id="i9RpBld" cx="0" cy="0" r="1" gradientTransform="rotate(100.008 3.865 18.365)scale(1.23447)" gradientUnits="userSpaceOnUse"><stop offset=".143" class="n8gt6nhas"/><stop offset="1" class="g02e8i-0p"/></radialGradient><radialGradient id="iWdsTke" cx="0" cy="0" r="1" gradientTransform="matrix(-2.6462 1.11638 -.94379 -2.2371 18.319 21.46)" gradientUnits="userSpaceOnUse"><stop class="tvsa7kbms"/><stop offset="1" class="ukqgmvbmd"/></radialGradient><radialGradient id="iyhnZPe" cx="0" cy="0" r="1" gradientTransform="matrix(11.4008 0 0 12.5877 11.503 20.271)" gradientUnits="userSpaceOnUse"><stop offset=".702" class="l3tdbf_yb"/><stop offset=".946" class="ge9zhbwdd"/></radialGradient><radialGradient id="iJswygd" cx="0" cy="0" r="1" gradientTransform="rotate(-39.188 37.719 -17.048)scale(1.63592 .99685)" gradientUnits="userSpaceOnUse"><stop offset=".617" class="z3-admb9g"/><stop offset="1" class="d-8dw9bma"/></radialGradient><radialGradient id="iHmqLrc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.48946 -1.27698 1.16366 -1.35728 12.862 20.173)" gradientUnits="userSpaceOnUse"><stop offset=".173" class="dv93degws"/><stop offset="1" class="fep4_2b7o"/></radialGradient><radialGradient id="ixZXHGe" cx="0" cy="0" r="1" gradientTransform="rotate(86.82 -3.03 12.823)scale(8.07057 1.48882)" gradientUnits="userSpaceOnUse"><stop offset=".363" class="k0vx8mbgy"/><stop offset="1" class="sfykj7bgx"/></radialGradient><radialGradient id="inaqsKb" cx="0" cy="0" r="1" gradientTransform="matrix(-.13784 -1.92952 1.14204 -.08158 16.913 22.7)" gradientUnits="userSpaceOnUse"><stop class="ucq7a8b-c"/><stop offset="1" class="uw9wndd8q"/></radialGradient><radialGradient id="iX2OIYc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.10938 .25 0 9.622 30.201)" gradientUnits="userSpaceOnUse"><stop offset=".23" class="cr72a2i9r"/><stop offset="1" class="e01_crb7q"/></radialGradient><radialGradient id="iq5swkc" cx="0" cy="0" r="1" gradientTransform="rotate(-155.863 10.266 12.812)scale(1.56665 .45501)" gradientUnits="userSpaceOnUse"><stop class="jqljwdbro"/><stop offset=".609" class="v9yutqrme"/></radialGradient><radialGradient id="iwxBX1H" cx="0" cy="0" r="1" gradientTransform="matrix(6 -3.25 2.38008 4.394 17.61 30.247)" gradientUnits="userSpaceOnUse"><stop offset=".3" class="dx2s30bnr"/><stop offset="1" class="kz5pwxb0z"/></radialGradient><radialGradient id="ikg0KSb" cx="0" cy="0" r="1" gradientTransform="rotate(141.127 9.738 8.766)scale(17.2506 15.7503)" gradientUnits="userSpaceOnUse"><stop offset=".166" class="wqu1hduus"/><stop offset=".559" class="bstw1xboe"/></radialGradient><radialGradient id="i4cNyDb" cx="0" cy="0" r="1" gradientTransform="rotate(164.808 10.604 7.122)scale(15.0251 12.7011)" gradientUnits="userSpaceOnUse"><stop offset=".643" class="zalfqh_is"/><stop offset="1" class="tww8s068l"/></radialGradient><radialGradient id="it4V3gc" cx="0" cy="0" r="1" gradientTransform="matrix(-4.44243 3.68753 -3.99367 -4.81125 24.252 9.983)" gradientUnits="userSpaceOnUse"><stop offset=".261" class="g5d3hjacf"/><stop offset="1" class="j2p90_-bc"/></radialGradient><radialGradient id="itEUNKb" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.05276 -1.67453 0 13.173 20.502)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="xbuk-xbxm"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="dggggwbdc"/></radialGradient><radialGradient id="iuNsYfn" cx="0" cy="0" r="1" gradientTransform="matrix(-.01004 -.64108 .77062 -.01207 12.8 20.786)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iYtLDVc" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.05276 -1.67453 0 18.83 20.502)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="xbuk-xbxm"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="dggggwbdc"/></radialGradient><radialGradient id="iAKuyad" cx="0" cy="0" r="1" gradientTransform="matrix(-.01004 -.64108 .77062 -.01207 18.457 20.786)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><filter id="iZuqTYm" width="11" height="6.1" x="2" y="24" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".1"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.890196 0 0 0 0 0.478431 0 0 0 0 0.27451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_4036"/></filter><filter id="iifh18d" width="3.2" height="3.2" x="14.4" y="1.9" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.188235 0 0 0 0 0.47451 0 0 0 0 0.698039 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_4036"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.286275 0 0 0 0 0.67451 0 0 0 0 0.929412 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_4036" result="effect2_innerShadow_4002_4036"/></filter><filter id="iRAKXSd" width="3.323" height="3.322" x="7.78" y="2.78" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.188235 0 0 0 0 0.47451 0 0 0 0 0.698039 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_4036"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.286275 0 0 0 0 0.67451 0 0 0 0 0.929412 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_4036" result="effect2_innerShadow_4002_4036"/></filter><filter id="i1sVnee" width="3.315" height="3.322" x="20.9" y="2.778" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.188235 0 0 0 0 0.47451 0 0 0 0 0.698039 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_4036"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.286275 0 0 0 0 0.67451 0 0 0 0 0.929412 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_4036" result="effect2_innerShadow_4002_4036"/></filter><filter id="iCkRLNb" width="12.65" height="11.707" x="9.685" y="14.543" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.145098 0 0 0 0 0.0705882 0 0 0 0 0.0941176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_4036"/></filter><filter id="iUrvOCc" width="2.836" height="1.386" x="11.256" y="17.304" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.15"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0666667 0 0 0 0 0.0313726 0 0 0 0 0.0862745 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_4036"/></filter><filter id="iXcS0bc" width="2.836" height="1.386" x="17.908" y="17.304" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.15"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0666667 0 0 0 0 0.0313726 0 0 0 0 0.0862745 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_4036"/></filter><filter id="i2QMxRb" width="3.344" height="4.294" x="14.145" y="20.363" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4036" stdDeviation=".25"/></filter><filter id="iEiVyYb" width="2.445" height="3.473" x="14.828" y="20.468" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.196078 0 0 0 0 0.0941176 0 0 0 0 0.117647 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_4036"/></filter><filter id="iY7Vqzc" width="7" height="3.5" x="9" y="26.5" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.313726 0 0 0 0 0.223529 0 0 0 0 0.215686 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_4036"/></filter><filter id="ibM9E8Z" width="7" height="3.6" x="16.5" y="26.4" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy="-.1"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.168627 0 0 0 0 0.0823529 0 0 0 0 0.0901961 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_4036"/></filter><filter id="iRvvyqc" width="17" height="12.5" x="7.752" y="6" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0823529 0 0 0 0 0.027451 0 0 0 0 0.0666667 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_4036"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-1"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.188235 0 0 0 0 0.160784 0 0 0 0 0.176471 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_4036" result="effect2_innerShadow_4002_4036"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.121569 0 0 0 0 0.0509804 0 0 0 0 0.141176 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_4002_4036" result="effect3_innerShadow_4002_4036"/></filter><filter id="icOsmgb" width="1.161" height="1.231" x="13.267" y="20.006" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4036" stdDeviation=".1"/></filter><filter id="icICe8d" width="1.125" height=".855" x="12.258" y="19.95" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4036" stdDeviation=".05"/></filter><filter id="i0L7Sob" width="1.161" height="1.231" x="18.924" y="20.006" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4036" stdDeviation=".1"/></filter><filter id="iXf91Rb" width="1.125" height=".855" x="17.914" y="19.95" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4036" stdDeviation=".05"/></filter><filter id="ibCngUc" width="2.906" height="1.276" x="17.907" y="17.409" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4036" stdDeviation=".125"/></filter><filter id="it9eJoe" width="2.906" height="1.276" x="11.221" y="17.409" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4036" stdDeviation=".125"/></filter><filter id="iOBWtxb" width="5.315" height="2.887" x="17.782" y="26.642" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4036" stdDeviation=".25"/></filter><filter id="i5blMpd" width="6.235" height="2.78" x="16.919" y="12.514" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4036" stdDeviation=".375"/></filter><linearGradient id="iiHXf7b" x1="2.95" x2="7.199" y1="23.5" y2="24.816" gradientUnits="userSpaceOnUse"><stop class="zsvzg4bjp"/><stop offset="1" class="t727h725g"/></linearGradient><linearGradient id="i2fVYxd" x1="7.19" x2="7.19" y1="30.219" y2="27.274" gradientUnits="userSpaceOnUse"><stop class="y8gz67bnb"/><stop offset="1" class="jiyavqyhw"/></linearGradient><linearGradient id="iTdsYBe" x1="24.5" x2="24.5" y1="30.044" y2="29.122" gradientUnits="userSpaceOnUse"><stop class="dcio5xd0n"/><stop offset="1" class="mw21cz39d"/></linearGradient><linearGradient id="iY8aclc" x1="23.044" x2="23.184" y1="24.826" y2="25.248" gradientUnits="userSpaceOnUse"><stop class="wfpeklbwv"/><stop offset="1" class="v6e6fkb_o"/></linearGradient><linearGradient id="ivTqIPb" x1="17.5" x2="14.905" y1="2.498" y2="5" gradientUnits="userSpaceOnUse"><stop offset=".32" class="ua70ijcgb"/><stop offset="1" class="cy-darb1h"/></linearGradient><linearGradient id="inZmpUb" x1="11.003" x2="8.302" y1="3.399" y2="6.003" gradientUnits="userSpaceOnUse"><stop offset=".32" class="ua70ijcgb"/><stop offset="1" class="cy-darb1h"/></linearGradient><linearGradient id="imBreIb" x1="24.115" x2="21.414" y1="3.397" y2="5.995" gradientUnits="userSpaceOnUse"><stop offset=".32" class="ua70ijcgb"/><stop offset="1" class="cy-darb1h"/></linearGradient><linearGradient id="iaQUBdd" x1="21.767" x2="23.954" y1="19.497" y2="16.497" gradientUnits="userSpaceOnUse"><stop class="am9kyybjv"/><stop offset="1" class="zs0txrbkc"/></linearGradient><linearGradient id="ibfphcU" x1="16" x2="16" y1="20.841" y2="23.94" gradientUnits="userSpaceOnUse"><stop class="v70h6u7jl"/><stop offset=".363" class="mmt32_2jk"/></linearGradient><linearGradient id="i2o4sob" x1="13.404" x2="11.869" y1="27.345" y2="31.044" gradientUnits="userSpaceOnUse"><stop offset=".053" class="urzqxtb3b"/><stop offset=".476" class="c4xwj5b4p"/></linearGradient><linearGradient id="in4rMlc" x1="14.138" x2="13.731" y1="20.572" y2="20.822" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="i0KlVJb" x1="19.794" x2="19.387" y1="20.572" y2="20.822" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="i2Y4uex" x1="20.338" x2="18.282" y1="18.125" y2="17.784" gradientUnits="userSpaceOnUse"><stop offset=".515" class="a6x862b5i"/><stop offset="1" class="rkma5lbuf"/></linearGradient><linearGradient id="icRpJSc" x1="13.552" x2="11.427" y1="17.725" y2="18.412" gradientUnits="userSpaceOnUse"><stop offset=".333" class="a6x862b5i"/><stop offset="1" class="rkma5lbuf"/></linearGradient><linearGradient id="iaPmsHe" x1="17.947" x2="23.154" y1="14.608" y2="12.876" gradientUnits="userSpaceOnUse"><stop class="hdoticcnk"/><stop offset="1" class="v-pdexbhk"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:person-bowing-dark" /></template>
<style>
.a6x862b5i {
  stop-color: var(--svg-color--333, #333);
}

.a76pxr2zz {
  d: path("m15.66 4.79l-1.122-2.248a.377.377 0 0 1 .34-.542h2.244c.28 0 .46.291.34.542L16.34 4.789a.38.38 0 0 1-.68 0");
}

.am9kyybjv {
  stop-color: var(--svg-color--442832, #442832);
}

.bstw1xboe {
  stop-color: var(--svg-color--251d20, #251D20);
}

.c4xwj5b4p {
  stop-color: var(--svg-color--3f252e, #3F252E);
}

.cdhyx9bbc {
  d: path("m22.185 13.264l-4.516.727c1.422.945 3.89.46 4.734.148z");
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cr72a2i9r {
  stop-color: var(--svg-color--543e3c, #543E3C);
}

.cy-darb1h {
  stop-color: var(--svg-color--3a91ce, #3A91CE);
}

.d-8dw9bma {
  stop-color: var(--svg-color--381b1f, #381B1F);
  stop-opacity: 0;
}

.dcio5xd0n {
  stop-color: var(--svg-color--eb5b6d, #EB5B6D);
}

.dggggwbdc {
  stop-color: var(--svg-color--6a4c45, #6A4C45);
}

.dv93degws {
  stop-color: var(--svg-color--3f1c1e, #3F1C1E);
}

.dwlm-abvw {
  fill: var(--svg-color--fff, #fff);
  d: path("M19.027 19.53a1.81 1.81 0 0 0-1.758 1.374a.356.356 0 0 0 .347.442h2.895a.3.3 0 0 0 .295-.353a1.82 1.82 0 0 0-1.78-1.463");
}

.dx2s30bnr {
  stop-color: var(--svg-color--462a2d, #462A2D);
}

.e01_crb7q {
  stop-color: var(--svg-color--543e3c, #543E3C);
  stop-opacity: 0;
}

.e7ibb9z3d {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M18.283 17.794c.348-.037 1.484 0 2.156.515");
}

.eembywbiw {
  d: path("M9.75 19.75a2 2 0 1 0 0-4a2 2 0 0 0 0 4");
}

.fep4_2b7o {
  stop-color: var(--svg-color--3f1c1e, #3F1C1E);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.g02e8i-0p {
  stop-color: var(--svg-color--3b232a, #3B232A);
  stop-opacity: 0;
}

.g2__l29ji {
  fill: var(--svg-color--6c5958, #6C5958);
  d: path("M20.35 27.53c-1.085.562-1.83.828-2.068.89c.188.104.723.094 1.525-.11c.604-.152 1.257-.444 1.787-.398c.423.038.84.784.989 1.117c.022-.276.036-.928-.083-1.328c-.149-.5-.794-.875-2.15-.172");
}

.g5d3hjacf {
  stop-color: var(--svg-color--4c4749, #4C4749);
}

.gb_qn6urd {
  fill: var(--svg-color--000, #000);
  d: path("M19.49 21.04a.66.66 0 0 0-.664-.663a.66.66 0 0 0-.59.969h1.175a.66.66 0 0 0 .079-.305");
}

.ge9zhbwdd {
  stop-color: var(--svg-color--58403d, #58403D);
}

.gkwz71b2m {
  cx: 12.821px;
  cy: 20.378px;
  rx: 0.506px;
  ry: 0.256px;
}

.gur5_240r {
  stop-color: var(--svg-color--ff802a, #FF802A);
}

.hdoticcnk {
  stop-color: var(--svg-color--62585b, #62585B);
}

.hke44nb4h {
  stop-color: var(--svg-color--fb5b1b, #FB5B1B);
}

.hs9amccpo {
  cx: 12.821px;
  cy: 20.378px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.506px;
  ry: 0.256px;
}

.hwl1wzb5h {
  fill: var(--svg-color--130b1a, #130B1A);
  d: path("M11.61 18.69a.35.35 0 0 1-.28-.14a.35.35 0 0 1 .06-.49c.04-.03.99-.75 2.39-.58c.19.02.33.2.31.39s-.19.33-.39.31c-1.11-.13-1.87.43-1.88.44c-.06.05-.14.07-.21.07");
}

.i8b3k7x5a {
  d: path("m15.52 20.92l-.66 2.14c-.14.44.19.88.65.88h.98c.46 0 .79-.45.65-.88l-.66-2.14c-.15-.47-.82-.47-.96 0");
}

.ih_n8tb4s {
  stop-color: var(--svg-color--e4380a, #E4380A);
  stop-opacity: 0;
}

.ivu6jd0iq {
  fill: var(--svg-color--3f2330, #3F2330);
  d: path("M9.693 17.79c-.15-2.287 1.778-3.247 4.098-3.247h1.713c.32.03.59.231.711.533a3.1 3.1 0 0 0 2.835 1.833h1.563q.208.008.412.01c.754.008 1.4.015 1.3.8l-.062.774h.002L22 21.7s-.44 4.3-5.97 4.3S10 21.7 10 21.7l-.286-3.652l-.01-.125l-.003-.031z");
}

.j2p90_-bc {
  stop-color: var(--svg-color--4c4749, #4C4749);
  stop-opacity: 0;
}

.jiyavqyhw {
  stop-color: var(--svg-color--fc6028, #FC6028);
  stop-opacity: 0;
}

.jqljwdbro {
  stop-color: var(--svg-color--665251, #665251);
}

.k0vx8mbgy {
  stop-color: var(--svg-color--523f3c, #523F3C);
}

.kjz636bae {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M13.752 17.794c-.349-.037-1.484 0-2.156.515");
}

.krbucv5ge {
  fill: var(--svg-color--fff, #fff);
  d: path("M12.902 19.53a1.81 1.81 0 0 0-1.758 1.374a.356.356 0 0 0 .347.442h2.895a.3.3 0 0 0 .295-.353a1.82 1.82 0 0 0-1.78-1.463");
}

.kz5pwxb0z {
  stop-color: var(--svg-color--4e2f2e, #4E2F2E);
}

.l3tdbf_yb {
  stop-color: var(--svg-color--58403d, #58403D);
  stop-opacity: 0;
}

.ladvbr8pz {
  cx: 18.477px;
  cy: 20.378px;
  rx: 0.506px;
  ry: 0.256px;
}

.lfhwesbpt {
  fill: var(--svg-color--2d161e, #2D161E);
  d: path("m15.44 21.184l-.753 2.045c-.16.42.15.862.61.883l.98.044c.459.021.808-.4.688-.824l-.565-2.105c-.13-.462-.799-.493-.96-.044");
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lt28sz2zp {
  stop-color: var(--svg-color--b64101, #B64101);
}

.lwps2obys {
  d: path("M26.916 19.188A3.58 3.58 0 0 0 23.61 17H8.31c-1.442 0-2.744.86-3.305 2.188L2.25 25.83H7V30h18v-4.15l4.75-.017z");
}

.malbd67au {
  d: path("M14.228 20.905c0-.375-.304-.624-.387-.7l-.374.363l.23.468z");
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mi21-2olq {
  stop-color: var(--svg-color--ffa741, #FFA741);
}

.ml47xab2p {
  stop-color: var(--svg-color--e4380a, #E4380A);
}

.mmt32_2jk {
  stop-color: var(--svg-color--3f2330, #3F2330);
  stop-opacity: 0;
}

.mnuqjbbig {
  stop-color: var(--svg-color--4f3b38, #4F3B38);
}

.mw21cz39d {
  stop-color: var(--svg-color--ff6836, #FF6836);
  stop-opacity: 0;
}

.n8gt6nhas {
  stop-color: var(--svg-color--3b232a, #3B232A);
}

.nqgeh70eu {
  d: path("M18.827 19.883a1.158 1.158 0 0 0-1.116 1.463h2.237q.04-.149.042-.305a1.166 1.166 0 0 0-1.163-1.158");
}

.nsdlvubzy {
  fill: var(--svg-color--130b1a, #130B1A);
  d: path("M20.39 18.69c-.07 0-.15-.02-.21-.07c-.01-.01-.77-.57-1.88-.44c-.2.01-.37-.12-.39-.31a.35.35 0 0 1 .31-.39c1.4-.17 2.35.55 2.39.58c.15.12.18.34.06.49c-.07.1-.18.14-.28.14");
}

.o-97ijbge {
  d: path("M22.25 19.75a2 2 0 1 0 0-4a2 2 0 0 0 0 4");
}

.o1ialsbyj {
  fill: var(--svg-color--000, #000);
  d: path("M13.833 21.04a.66.66 0 0 0-.663-.663a.66.66 0 0 0-.59.969h1.174a.66.66 0 0 0 .08-.305");
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.pjd1wtbcg {
  stop-color: var(--svg-color--ff9d3d, #FF9D3D);
  stop-opacity: 0;
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pkmnhobup {
  d: path("M21.026 25.59a3 3 0 0 0-.333.098c-.987.36-1.693 1.268-1.693 2.332c0 .81.405 1.521 1.039 1.98h6.782C28.578 30 30 28.644 30 26.995S28.577 24 26.811 24c-.27 0-.54.039-.79.098c-.114.029-.228.058-.332.097z");
}

.pmiei2beq {
  stop-color: var(--svg-color--f46a2e, #F46A2E);
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.ra9_m8sho {
  cx: 18.477px;
  cy: 20.378px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.506px;
  ry: 0.256px;
}

.rkma5lbuf {
  stop-color: var(--svg-color--333, #333);
  stop-opacity: 0;
}

.rq808nblb {
  d: path("M9.693 17.79c-.15-2.287 1.778-3.247 4.098-3.247h1.713c.32.03.59.231.711.533a3.1 3.1 0 0 0 2.835 1.833h1.563q.208.008.412.01c.754.008 1.4.015 1.3.8l-.062.774h.002L22 21.7s-.44 4.3-5.97 4.3S10 21.7 10 21.7l-.286-3.652l-.01-.125l-.003-.031z");
}

.ryvejj5je {
  d: path("m21.49 5.98l2.37-.79a.38.38 0 0 0 .15-.62l-1.58-1.58c-.2-.2-.53-.12-.62.15l-.79 2.38c-.1.28.18.56.47.46");
}

.sd7jkkb7x {
  stop-color: var(--svg-color--b64101, #B64101);
  stop-opacity: 0;
}

.sfykj7bgx {
  stop-color: var(--svg-color--523f3c, #523F3C);
  stop-opacity: 0;
}

.sludkgsww {
  stop-color: var(--svg-color--ff9d3d, #FF9D3D);
}

.t727h725g {
  stop-color: var(--svg-color--e57544, #E57544);
  stop-opacity: 0;
}

.tn5cwfbmj {
  stop-color: var(--svg-color--ff9c2c, #FF9C2C);
}

.toaba5-2f {
  d: path("M23.849 11.149a2.97 2.97 0 0 0-1.623-1.34a3.17 3.17 0 0 1-1.733-1.369A2.98 2.98 0 0 0 17.938 7c-.41 0-.811.08-1.172.242a1.93 1.93 0 0 1-1.533 0A2.8 2.8 0 0 0 14.071 7a2.98 2.98 0 0 0-2.524 1.4a3.37 3.37 0 0 1-1.773 1.41A3.02 3.02 0 0 0 8.1 11.24a3.04 3.04 0 0 0 .18 3.121c.22.332.35.715.35 1.118v1.984c0 .574.545 1.037 1.116 1.037l-.043-.577c-.234-2.384 1.723-3.38 4.087-3.38h1.713c.32.03.59.231.711.533a3.1 3.1 0 0 0 2.835 1.833h1.563c.911.04 1.83-.115 1.712.81l-.062.774c.55 0 1.095-.446 1.095-1v-2.025c0-.392.12-.784.35-1.107a2.98 2.98 0 0 0 .14-3.212");
}

.tqq30fi4f {
  d: path("M10.645 26.5c.243 0 .476.051.69.153l3.708 1.765a.82.82 0 0 1 .457.735c0 .449-.34.847-.769.847H9.01L9 28.235c-.01-.95.73-1.725 1.645-1.735");
}

.tvsa7kbms {
  stop-color: var(--svg-color--4d302d, #4D302D);
}

.tww8s068l {
  stop-color: var(--svg-color--403837, #403837);
}

.txd0f1icf {
  d: path("M10.975 25.59c.114.03.228.059.332.098c.987.36 1.693 1.268 1.693 2.332c0 .81-.405 1.521-1.039 1.98H5.178C3.423 30 2 28.644 2 26.995S3.423 24 5.189 24c.27 0 .54.039.79.098c.114.029.228.058.332.097z");
}

.tyr2ocbkv {
  stop-color: var(--svg-color--2a1722, #2A1722);
}

.ua70ijcgb {
  stop-color: var(--svg-color--399be2, #399BE2);
}

.ucq7a8b-c {
  stop-color: var(--svg-color--533431, #533431);
}

.ukqgmvbmd {
  stop-color: var(--svg-color--4d302d, #4D302D);
  stop-opacity: 0;
}

.urzqxtb3b {
  stop-color: var(--svg-color--472c28, #472C28);
}

.uuaqpn7jb {
  fill: var(--svg-color--3f272c, #3F272C);
  d: path("m15.52 20.92l-.66 2.14c-.14.44.19.88.65.88h.98c.46 0 .79-.45.65-.88l-.66-2.14c-.15-.47-.82-.47-.96 0");
}

.uw9wndd8q {
  stop-color: var(--svg-color--533431, #533431);
  stop-opacity: 0;
}

.v-pdexbhk {
  stop-color: var(--svg-color--62585b, #62585B);
  stop-opacity: 0;
}

.v6e6fkb_o {
  stop-color: var(--svg-color--c95506, #C95506);
  stop-opacity: 0;
}

.v70h6u7jl {
  stop-color: var(--svg-color--3f2330, #3F2330);
}

.v7at5lbln {
  d: path("M21.356 26.5c-.244 0-.477.051-.691.153l-3.708 1.765a.82.82 0 0 0-.457.735c0 .449.34.847.769.847h5.721l.01-1.765c.01-.95-.73-1.725-1.645-1.735");
}

.v9yutqrme {
  stop-color: var(--svg-color--665251, #665251);
  stop-opacity: 0;
}

.vcev7m60r {
  d: path("M13.17 19.883a1.158 1.158 0 0 0-1.116 1.463h2.237q.041-.149.042-.305a1.166 1.166 0 0 0-1.163-1.158");
}

.wfpeklbwv {
  stop-color: var(--svg-color--c95506, #C95506);
}

.wqu1hduus {
  stop-color: var(--svg-color--453e41, #453E41);
}

.wziyle_fm {
  stop-color: var(--svg-color--ff7530, #FF7530);
}

.xbmasxbtf {
  d: path("m10.512 5.982l-2.38-.79a.373.373 0 0 1-.14-.62l1.58-1.58c.2-.2.53-.12.62.15l.79 2.38c.1.28-.18.56-.47.46");
}

.xbuk-xbxm {
  stop-color: var(--svg-color--7f584b, #7F584B);
}

.y8gz67bnb {
  stop-color: var(--svg-color--e95252, #E95252);
}

.ygnqhzbrp {
  stop-color: var(--svg-color--ff7919, #FF7919);
}

.ypw2_2bvq {
  d: path("M19.884 20.905c0-.375-.304-.624-.386-.7l-.374.363l.23.468z");
}

.z3-admb9g {
  stop-color: var(--svg-color--381b1f, #381B1F);
}

.zalfqh_is {
  stop-color: var(--svg-color--403837, #403837);
  stop-opacity: 0;
}

.zs0txrbkc {
  stop-color: var(--svg-color--695655, #695655);
}

.zsvzg4bjp {
  stop-color: var(--svg-color--e57544, #E57544);
}

</style>
