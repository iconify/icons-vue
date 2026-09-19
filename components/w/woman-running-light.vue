<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#ilQU4kd)" transform="rotate(-4.337 12.169 7.269)" class="vy_lbsbpe"/><path fill="url(#iCroosb)" transform="rotate(-4.337 12.169 7.269)" class="vy_lbsbpe"/><path fill="url(#iGxAFPd)" transform="rotate(-4.337 12.169 7.269)" class="vy_lbsbpe"/><path fill="url(#i4Mje5d)" class="cdq5z3r7y"/><path fill="url(#ipKIRid)" class="cdq5z3r7y"/><g filter="url(#itHXPNc)"><path fill="url(#i1mSlBb)" class="nrayz3bjb"/><path fill="url(#iDxNDTc)" class="nrayz3bjb"/><path fill="url(#ixk1JNc)" class="nrayz3bjb"/><path fill="url(#iVoLn3b)" class="nrayz3bjb"/></g><g filter="url(#iFOiIbc)"><path class="pd_td0b5t"/><path fill="url(#i9dPMKe)" class="f2lax3blq"/></g><g filter="url(#i4mChWb)"><path class="qyh4htb2f"/><path fill="url(#io21Cxb)" class="f2lax3blq"/></g><path fill="url(#iegb3Bc)" class="eqdxe6bem"/><path fill="url(#iPiPNvb)" class="eqdxe6bem"/><path fill="url(#ipOHxrb)" class="eqdxe6bem"/><path class="jgvxgkbcu"/><path clip-rule="evenodd" class="g-yl6wiwd"/><g filter="url(#iYAHdJd)"><path clip-rule="evenodd" class="jkpn8qsux"/></g><path class="d_6o_2bzn"/><path fill="url(#i3hR4xc)" class="qtf1aub2p"/><path fill="url(#iMPIQxd)" class="s7euo-b6q"/><ellipse fill="url(#ioiAdJd)" transform="rotate(22.414 10.376 5.564)" class="b4d1jsb-e"/><g filter="url(#iQacEym)"><path fill="url(#is6ll8d)" class="c6zorkb0b"/><path fill="url(#i6HNQ0d)" class="c6zorkb0b"/><path fill="url(#it2nwTc)" class="c6zorkb0b"/><path fill="url(#iAhVZgc)" class="c6zorkb0b"/></g><path class="m7ubqjboj"/><path fill="url(#imQ5qQe)" class="c3jo68bka"/><path fill="url(#iUA7BvF)" class="c3jo68bka"/><path fill="url(#ivcyOGe)" class="c3jo68bka"/><path fill="url(#iQ61Lln)" class="c3jo68bka"/><path fill="url(#iUFB9qc)" class="c3jo68bka"/><path fill="url(#iJkjBmc)" class="c3jo68bka"/><path fill="url(#iwHykhc)" class="c3jo68bka"/><g filter="url(#itmsvFc)"><path stroke="url(#iJIB6Oe)" class="hudyc0tda"/></g><circle fill="url(#i5CtkJc)" class="b5k8qzs7h"/><g filter="url(#iema6oe)"><path fill="url(#i0Vpz8b)" clip-rule="evenodd" class="hth0c2b4n"/></g><path class="a50utefqs"/><path fill="url(#izV2Odb)" class="rlbmuyd6x"/><path fill="url(#i6Sf9vd)" class="rlbmuyd6x"/><path fill="url(#iTHYdMe)" class="rlbmuyd6x"/><path fill="url(#iqIfV4d)" class="rlbmuyd6x"/><rect class="hq1fg214b"/><rect fill="url(#iKDnj7c)" class="qvmw_ibnt"/><rect fill="url(#i4zWcAb)" class="qvmw_ibnt"/><path fill="url(#iZBsoEe)" class="dvh-v1bvy"/><path fill="url(#i4JXeSc)" class="dvh-v1bvy"/><path fill="url(#ijSJ4Ud)" class="dvh-v1bvy"/><path fill="url(#iu9Spcd)" class="dvh-v1bvy"/><g filter="url(#itXY91c)"><path class="jqdm_110x"/><path fill="url(#in0N6Tw)" class="o0q8xtq8c"/><path fill="url(#i6cd8oe)" class="o0q8xtq8c"/></g><path fill="url(#i9MRTzb)" class="o0q8xtq8c"/><g filter="url(#iUWosHc)"><path class="iihzz71vk"/><path fill="url(#iGvdX3b)" class="yqtpn3uat"/><path fill="url(#iTuW7Cx)" class="yqtpn3uat"/></g><g filter="url(#iFEF2ce)"><path class="brt_lr-gs"/></g><path class="jlws7_s9m"/><path fill="url(#ijCrltd)" class="wjk-6vj4h"/><path fill="url(#iiDzQnb)" class="wjk-6vj4h"/><path fill="url(#iFEDqob)" class="wjk-6vj4h"/><g filter="url(#icjzAve)"><path class="x022swbez"/><path fill="url(#iAivSjc)" class="lsq6lsfjr"/></g><path class="nl4rtcblm"/><path fill="url(#iqdiL0c)" class="t3d-9d8dp"/><path fill="url(#iXc5U5b)" class="t3d-9d8dp"/><path fill="url(#iZWxvnb)" class="t3d-9d8dp"/><path fill="url(#iVDBIId)" class="t3d-9d8dp"/><path fill="url(#iA2kwtb)" class="t3d-9d8dp"/><g filter="url(#ianb06d)"><path class="w6scaoblb"/></g><defs><radialGradient id="ilQU4kd" cx="0" cy="0" r="1" gradientTransform="matrix(-.05152 -2.21336 1.59858 -.0372 13.877 9.279)" gradientUnits="userSpaceOnUse"><stop offset=".116" class="u598_4blb"/><stop offset="1" class="poxe0lb6u"/></radialGradient><radialGradient id="iCroosb" cx="0" cy="0" r="1" gradientTransform="matrix(-.53617 .66448 -.89991 -.72614 14.23 7.707)" gradientUnits="userSpaceOnUse"><stop class="w1ctt_hwm"/><stop offset="1" class="c6t644beu"/></radialGradient><radialGradient id="iGxAFPd" cx="0" cy="0" r="1" gradientTransform="matrix(.01105 -.86884 .23985 .00305 12.383 9.682)" gradientUnits="userSpaceOnUse"><stop class="mvum_2bof"/><stop offset="1" class="e7u9e_b9n"/></radialGradient><radialGradient id="i4Mje5d" cx="0" cy="0" r="1" gradientTransform="matrix(.51675 .25445 -.35917 .72942 9.146 6.632)" gradientUnits="userSpaceOnUse"><stop offset=".101" class="hymklqb8k"/><stop offset=".684" class="s2f2c_bct"/></radialGradient><radialGradient id="ipKIRid" cx="0" cy="0" r="1" gradientTransform="matrix(-.1394 -.30479 .45742 -.20922 9.589 6.953)" gradientUnits="userSpaceOnUse"><stop class="zkj259b3a"/><stop offset="1" class="iv0p50s_n"/></radialGradient><radialGradient id="iDxNDTc" cx="0" cy="0" r="1" gradientTransform="matrix(-.89822 -.01543 .0188 -1.0951 13.007 5.736)" gradientUnits="userSpaceOnUse"><stop offset=".156" class="l7mbhnbzh"/><stop offset="1" class="biuc-6bfh"/></radialGradient><radialGradient id="ixk1JNc" cx="0" cy="0" r="1" gradientTransform="matrix(-.21133 -5.51062 2.14118 -.08211 9.979 7.116)" gradientUnits="userSpaceOnUse"><stop offset=".219" class="wcectbccf"/><stop offset="1" class="b3jcjo1jv"/></radialGradient><radialGradient id="iVoLn3b" cx="0" cy="0" r="1" gradientTransform="rotate(87.804 2.356 8.552)scale(.41526 .64761)" gradientUnits="userSpaceOnUse"><stop offset=".155" class="ie_w39bfj"/><stop offset="1" class="dx40lk_kc"/></radialGradient><radialGradient id="i9dPMKe" cx="0" cy="0" r="1" gradientTransform="matrix(1.6129 -.5211 1.11672 3.45643 9.598 3.49)" gradientUnits="userSpaceOnUse"><stop class="k_urnmdao"/><stop offset="1" class="w7r1zi1yh"/></radialGradient><radialGradient id="io21Cxb" cx="0" cy="0" r="1" gradientTransform="matrix(1.6129 -.5211 1.11672 3.45643 9.598 3.49)" gradientUnits="userSpaceOnUse"><stop class="tzf255bgc"/><stop offset="1" class="ctuud_14h"/></radialGradient><radialGradient id="iegb3Bc" cx="0" cy="0" r="1" gradientTransform="matrix(.76323 -.25368 .12382 .37252 12.681 5.632)" gradientUnits="userSpaceOnUse"><stop offset=".17" class="i8aj4_5_r"/><stop offset="1" class="u2yjj3mld"/></radialGradient><radialGradient id="iPiPNvb" cx="0" cy="0" r="1" gradientTransform="matrix(.2881 1.24403 -1.29633 .3002 12.702 5.311)" gradientUnits="userSpaceOnUse"><stop offset=".556" class="chiqx4b_a"/><stop offset="1" class="vmk6x9_kg"/><stop offset="1" class="hq1ekobkc"/></radialGradient><radialGradient id="i3hR4xc" cx="0" cy="0" r="1" gradientTransform="matrix(.29047 -.01114 .02164 .56434 10.5 5.911)" gradientUnits="userSpaceOnUse"><stop offset=".895" class="l0aricxam"/><stop offset="1" class="n9r91ylyy"/></radialGradient><radialGradient id="iMPIQxd" cx="0" cy="0" r="1" gradientTransform="matrix(.265 -.01016 .022 .57348 10.322 5.94)" gradientUnits="userSpaceOnUse"><stop class="gv3iwdbvq"/><stop offset=".813" class="ubyl24bdb"/></radialGradient><radialGradient id="i6HNQ0d" cx="0" cy="0" r="1" gradientTransform="matrix(1.21002 -.125 .20081 1.94388 3.535 12.08)" gradientUnits="userSpaceOnUse"><stop class="xv1vs_4ih"/><stop offset="1" class="ni0zysbnp"/><stop offset="1" class="n3hnr4mdq"/></radialGradient><radialGradient id="it2nwTc" cx="0" cy="0" r="1" gradientTransform="matrix(-.32812 2.84912 -1.43111 -.16482 11.698 12.616)" gradientUnits="userSpaceOnUse"><stop class="d-5aclb3h"/><stop offset="1" class="p5bok0bog"/></radialGradient><radialGradient id="iAhVZgc" cx="0" cy="0" r="1" gradientTransform="matrix(-.74999 1.21876 -.42667 -.26256 5.167 11.074)" gradientUnits="userSpaceOnUse"><stop offset=".258" class="d7t4onbnf"/><stop offset="1" class="xnjlox7lf"/></radialGradient><radialGradient id="imQ5qQe" cx="0" cy="0" r="1" gradientTransform="rotate(141.806 6.078 10.14)scale(5.40769 7.07772)" gradientUnits="userSpaceOnUse"><stop offset=".611" class="z3ho42bzm"/><stop offset=".986" class="kl05mmksp"/></radialGradient><radialGradient id="iUA7BvF" cx="0" cy="0" r="1" gradientTransform="rotate(-159.126 10.341 5.45)scale(7.10407 10.7105)" gradientUnits="userSpaceOnUse"><stop offset=".765" class="g4frhmb7u"/><stop offset=".965" class="ls7ahvbmb"/></radialGradient><radialGradient id="ivcyOGe" cx="0" cy="0" r="1" gradientTransform="matrix(-3.36366 1.59373 -2.8979 -6.11618 17.364 14.038)" gradientUnits="userSpaceOnUse"><stop offset=".109" class="bhhn8hbxv"/><stop offset="1" class="lychkpbnw"/></radialGradient><radialGradient id="iQ61Lln" cx="0" cy="0" r="1" gradientTransform="rotate(121.109 5.1 10.054)scale(2.11694 2.06251)" gradientUnits="userSpaceOnUse"><stop class="o6m3gysuc"/><stop offset="1" class="oqmg4vaes"/></radialGradient><radialGradient id="iUFB9qc" cx="0" cy="0" r="1" gradientTransform="matrix(2.125 -1.09375 .92592 1.79894 15.047 10.772)" gradientUnits="userSpaceOnUse"><stop offset=".279" class="ciwfevm-x"/><stop offset="1" class="nim1shnhj"/></radialGradient><radialGradient id="iJkjBmc" cx="0" cy="0" r="1" gradientTransform="matrix(-.89062 .32813 -.43976 -1.19362 13.422 10.929)" gradientUnits="userSpaceOnUse"><stop offset=".274" class="kpglbvlsk"/><stop offset="1" class="j1ev22o7x"/></radialGradient><radialGradient id="iwHykhc" cx="0" cy="0" r="1" gradientTransform="matrix(-.26562 -.34375 2.58518 -1.99762 15.719 15.96)" gradientUnits="userSpaceOnUse"><stop offset=".403" class="kba1trwhz"/><stop offset="1" class="pb6-h6b6v"/></radialGradient><radialGradient id="i5CtkJc" cx="0" cy="0" r="1" gradientTransform="rotate(24.692 -17.855 55.553)scale(1.12213 1.1783)" gradientUnits="userSpaceOnUse"><stop class="slwiwcbms"/><stop offset=".906" class="a623v70-r"/></radialGradient><radialGradient id="iTHYdMe" cx="0" cy="0" r="1" gradientTransform="matrix(1.33216 .125 -.21108 2.2495 12.918 10.507)" gradientUnits="userSpaceOnUse"><stop class="mx7n4_bgp"/><stop offset="1" class="pism_984o"/></radialGradient><radialGradient id="iqIfV4d" cx="0" cy="0" r="1" gradientTransform="matrix(-.875 .45313 -.88734 -1.71347 17.485 8.976)" gradientUnits="userSpaceOnUse"><stop offset=".164" class="vunrlhvcc"/><stop offset="1" class="tm7ezfuma"/></radialGradient><radialGradient id="iKDnj7c" cx="0" cy="0" r="1" gradientTransform="matrix(.4375 -.74756 1.05666 .6184 5.276 11.733)" gradientUnits="userSpaceOnUse"><stop class="ynj07w4st"/><stop offset="1" class="i80r67bey"/></radialGradient><radialGradient id="i4zWcAb" cx="0" cy="0" r="1" gradientTransform="matrix(.5586 0 0 1.24803 4.717 11.071)" gradientUnits="userSpaceOnUse"><stop class="hvtacgb4z"/><stop offset="1" class="p8sjifbbs"/></radialGradient><radialGradient id="ijSJ4Ud" cx="0" cy="0" r="1" gradientTransform="matrix(-4.65317 9.34098 -2.71885 -1.35439 14.084 21.524)" gradientUnits="userSpaceOnUse"><stop offset=".183" class="z8qpeob8g"/><stop offset="1" class="wkc24ybrk"/></radialGradient><radialGradient id="iu9Spcd" cx="0" cy="0" r="1" gradientTransform="rotate(108.122 -1.026 15.747)scale(4.93961 1.23818)" gradientUnits="userSpaceOnUse"><stop offset=".173" class="pwq4emb2a"/><stop offset="1" class="grogb8blp"/></radialGradient><radialGradient id="i9MRTzb" cx="0" cy="0" r="1" gradientTransform="matrix(.89465 -.29687 .493 1.48575 3.933 28.35)" gradientUnits="userSpaceOnUse"><stop class="rmzq06bzd"/><stop offset="1" class="n1b4mhj1w"/></radialGradient><radialGradient id="iGvdX3b" cx="0" cy="0" r="1" gradientTransform="matrix(.53907 1.6172 -.97015 .32338 19.9 20.321)" gradientUnits="userSpaceOnUse"><stop class="psqzkesbw"/><stop offset="1" class="hw5zu2bcg"/></radialGradient><radialGradient id="iTuW7Cx" cx="0" cy="0" r="1" gradientTransform="matrix(.70312 1.125 -2.57259 1.60787 17.87 21.215)" gradientUnits="userSpaceOnUse"><stop class="y8e7yu08v"/><stop offset="1" class="jgi_q-wcb"/></radialGradient><radialGradient id="iAivSjc" cx="0" cy="0" r="1" gradientTransform="matrix(2.4375 4.75 -1.7011 .87293 17.015 19.163)" gradientUnits="userSpaceOnUse"><stop offset=".329" class="v1sha93vg"/><stop offset="1" class="kg-rnkb9f"/></radialGradient><radialGradient id="iqdiL0c" cx="0" cy="0" r="1" gradientTransform="matrix(2.87501 3.59374 -13.67711 10.94177 13.922 17.382)" gradientUnits="userSpaceOnUse"><stop offset=".554" class="j96xv6b5h"/><stop offset="1" class="osaguabiz"/></radialGradient><radialGradient id="iXc5U5b" cx="0" cy="0" r="1" gradientTransform="matrix(1.01138 -2.18079 7.25457 3.36445 14.536 22.862)" gradientUnits="userSpaceOnUse"><stop class="sq7_rccwx"/><stop offset="1" class="n8gqlhnrc"/></radialGradient><radialGradient id="iZWxvnb" cx="0" cy="0" r="1" gradientTransform="matrix(-2.05436 1.3596 -1.29326 -1.95412 18.044 17.204)" gradientUnits="userSpaceOnUse"><stop class="gewgt1jbg"/><stop offset="1" class="roa1y3bvy"/></radialGradient><radialGradient id="iA2kwtb" cx="0" cy="0" r="1" gradientTransform="matrix(1.90625 -.90625 .11383 .23944 13.515 17.491)" gradientUnits="userSpaceOnUse"><stop offset=".207" class="c6vpnsb1w"/><stop offset="1" class="j23k_cb2p"/></radialGradient><linearGradient id="i1mSlBb" x1="12.706" x2="9.672" y1="6.537" y2="6.837" gradientUnits="userSpaceOnUse"><stop class="dxjajos_o"/><stop offset="1" class="gu4uskbqq"/></linearGradient><linearGradient id="ipOHxrb" x1="12.626" x2="12.784" y1="5.707" y2="5.714" gradientUnits="userSpaceOnUse"><stop class="o01zddb6n"/><stop offset="1" class="h5b83fbqu"/></linearGradient><linearGradient id="ioiAdJd" x1="10.301" x2="10.498" y1="5.524" y2="5.588" gradientUnits="userSpaceOnUse"><stop class="vc--wpv5i"/><stop offset="1" class="stui2mbih"/></linearGradient><linearGradient id="is6ll8d" x1="4.37" x2="12.307" y1="11.787" y2="14.037" gradientUnits="userSpaceOnUse"><stop class="e7heivjxf"/><stop offset="1" class="htujpbbup"/></linearGradient><linearGradient id="iJIB6Oe" x1="5.604" x2="8.541" y1="11.846" y2="13.471" gradientUnits="userSpaceOnUse"><stop class="g99i-8b1k"/><stop offset="1" class="x1ob3cbbz"/><stop offset="1" class="j12scpkzx"/></linearGradient><linearGradient id="i0Vpz8b" x1="17.817" x2="25.325" y1="9.237" y2="13.238" gradientUnits="userSpaceOnUse"><stop class="cqolrprwc"/><stop offset="1" class="p0u56pe1z"/></linearGradient><linearGradient id="izV2Odb" x1="15.125" x2="15.781" y1="8.288" y2="9.413" gradientUnits="userSpaceOnUse"><stop class="tseva3beu"/><stop offset="1" class="jbtab4n_d"/></linearGradient><linearGradient id="i6Sf9vd" x1="16.515" x2="15.109" y1="11.382" y2="8.944" gradientUnits="userSpaceOnUse"><stop class="f-yzz_-ef"/><stop offset="1" class="qlv8umoui"/></linearGradient><linearGradient id="iZBsoEe" x1="12.453" x2="9.078" y1="20.444" y2="28.569" gradientUnits="userSpaceOnUse"><stop class="mrc1ztbfi"/><stop offset="1" class="qcut_9xzp"/></linearGradient><linearGradient id="i4JXeSc" x1="7.845" x2="9.12" y1="25.109" y2="25.591" gradientUnits="userSpaceOnUse"><stop class="x_q7-kble"/><stop offset="1" class="vvztplbrt"/></linearGradient><linearGradient id="in0N6Tw" x1="5.898" x2="6.054" y1="29.405" y2="29.093" gradientUnits="userSpaceOnUse"><stop class="vrnt79u8g"/><stop offset="1" class="z-p3-w_an"/></linearGradient><linearGradient id="i6cd8oe" x1="8.14" x2="7.484" y1="29.804" y2="29.366" gradientUnits="userSpaceOnUse"><stop class="sted03b1z"/><stop offset="1" class="ubkqlww9x"/></linearGradient><linearGradient id="ijCrltd" x1="26.14" x2="26.64" y1="19.999" y2="21.163" gradientUnits="userSpaceOnUse"><stop offset=".024" class="ruyfycb4r"/><stop offset="1" class="vuvc8_ujh"/></linearGradient><linearGradient id="iiDzQnb" x1="26.14" x2="26.904" y1="22.96" y2="22.155" gradientUnits="userSpaceOnUse"><stop class="clpaphbux"/><stop offset="1" class="gei07kbgq"/></linearGradient><linearGradient id="iFEDqob" x1="27.922" x2="27.515" y1="22.241" y2="22.382" gradientUnits="userSpaceOnUse"><stop offset=".213" class="e2g34f-cy"/><stop offset="1" class="vx88q5bse"/></linearGradient><linearGradient id="iVDBIId" x1="13.171" x2="13.859" y1="17.632" y2="18.564" gradientUnits="userSpaceOnUse"><stop class="hv04c4bjr"/><stop offset="1" class="j2u_3dtev"/></linearGradient><filter id="itHXPNc" width="4.755" height="5.677" x="9.434" y="3.372" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2" dy="-.2"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.815686 0 0 0 0 0.596078 0 0 0 0 0.580392 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_548"/></filter><filter id="iFOiIbc" width="7.379" height="7.681" x="8.964" y="1.727" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.4" dy=".4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.972549 0 0 0 0 0.737255 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_548"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.956863 0 0 0 0 0.788235 0 0 0 0 0.631373 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_548" result="effect2_innerShadow_4002_548"/></filter><filter id="i4mChWb" width="7.379" height="7.681" x="8.964" y="1.727" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.4" dy=".4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.290196 0 0 0 0 0.266667 0 0 0 0 0.27451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_548"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0901961 0 0 0 0 0.0392157 0 0 0 0 0.133333 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_548" result="effect2_innerShadow_4002_548"/></filter><filter id="iYAHdJd" width="1.077" height=".575" x="10.192" y="4.496" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0705882 0 0 0 0 0.0588235 0 0 0 0 0.054902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_548"/></filter><filter id="iQacEym" width="10.979" height="5.402" x="3.335" y="9.535" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2" dy=".2"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.870588 0 0 0 0 0.654902 0 0 0 0 0.545098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_548"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2" dy="-.6"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.788235 0 0 0 0 0.533333 0 0 0 0 0.564706 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_548" result="effect2_innerShadow_4002_548"/></filter><filter id="itmsvFc" width="3.929" height="2.283" x="5.507" y="11.359" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_548" stdDeviation=".1"/></filter><filter id="iema6oe" width="10.118" height="6.174" x="14.278" y="7.064" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.8"/><feGaussianBlur stdDeviation=".7"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.776471 0 0 0 0 0.517647 0 0 0 0 0.556863 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_548"/></filter><filter id="itXY91c" width="4.813" height="3.178" x="3.933" y="27.499" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy=".4"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.298039 0 0 0 0 0.286275 0 0 0 0 0.454902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_548"/></filter><filter id="iUWosHc" width="9.043" height="4.345" x="17.285" y="19.601" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.741176 0 0 0 0 0.505882 0 0 0 0 0.576471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_548"/></filter><filter id="iFEF2ce" width="7.952" height="2.809" x="18.555" y="19.936" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_548" stdDeviation=".3"/></filter><filter id="icjzAve" width="3.978" height="6.092" x="16.312" y="15.907" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.513726 0 0 0 0 0.458824 0 0 0 0 0.482353 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_548"/></filter><filter id="ianb06d" width="5.797" height="4.302" x="18.783" y="8.449" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_548" stdDeviation=".25"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:woman-running-light" /></template>
<style>
.a50utefqs {
  fill: var(--svg-color--6b47b8, #6B47B8);
  d: path("m17.85 10.442l-1.325-2.718l-2.764 1.322a1.483 1.483 0 0 0 1.255 2.687z");
}

.a623v70-r {
  stop-color: var(--svg-color--bb7d84, #BB7D84);
}

.b3jcjo1jv {
  stop-color: var(--svg-color--ffcdb7, #FFCDB7);
  stop-opacity: 0;
}

.b4d1jsb-e {
  cx: 10.376px;
  cy: 5.564px;
  rx: 0.068px;
  ry: 0.093px;
}

.b5k8qzs7h {
  cx: 22.204px;
  cy: 12.454px;
  r: 0.63px;
}

.bhhn8hbxv {
  stop-color: var(--svg-color--896fcc, #896FCC);
}

.biuc-6bfh {
  stop-color: var(--svg-color--eeb298, #EEB298);
  stop-opacity: 0;
}

.brt_lr-gs {
  stroke: var(--svg-color--fccbb9, #FCCBB9);
  stroke-width: var(--svg-stroke-width--0-3px, 0.3px);
  d: path("m19.297 20.585l.392 1.14a.4.4 0 0 0 .435.266l5.761-.833");
}

.c3jo68bka {
  d: path("m13.136 9.323l.74-.39a1 1 0 0 1 .585-.106l2.003 1.774c-.23 1.789.13 3.007.9 4.077l-4.254 3.23c-1.516-2.636-1.93-5.073-1.555-6.354c.317-1.229 1.05-1.899 1.581-2.23");
}

.c6t644beu {
  stop-color: var(--svg-color--e0a489, #E0A489);
  stop-opacity: 0;
}

.c6vpnsb1w {
  stop-color: var(--svg-color--9c959a, #9C959A);
}

.c6zorkb0b {
  d: path("M3.761 12.241c-.285-.363-.293-.871-.07-1.293s.547-.832 1.016-.812c.328.013.598.275.711.619q.105.027.206.076l3 1.447a1.6 1.6 0 0 0 1.639-.148l2.223-1.623a1.15 1.15 0 1 1 1.356 1.858l-2.224 1.623a3.9 3.9 0 0 1-3.993.362l-2.918-1.421c-.246-.122-.72-.4-.946-.688");
}

.cdq5z3r7y {
  d: path("M9.437 6.156c.16-.163.237-.399.255-.496l.191-.008l.046 1.196c-.223.153-.55.143-.655-.071c-.09-.184-.037-.418.163-.621");
}

.chiqx4b_a {
  stop-color: var(--svg-color--e7a792, #E7A792);
  stop-opacity: 0;
}

.ciwfevm-x {
  stop-color: var(--svg-color--5b39a7, #5B39A7);
}

.clpaphbux {
  stop-color: var(--svg-color--5a418f, #5A418F);
}

.cqolrprwc {
  stop-color: var(--svg-color--fbbea2, #FBBEA2);
}

.ctuud_14h {
  stop-color: var(--svg-color--534b49, #534B49);
  stop-opacity: 0;
}

.d_6o_2bzn {
  fill: var(--svg-color--fff, #fff);
  d: path("m10.206 5.945l1.05-.04c-.016-.416-.264-.744-.554-.733s-.512.358-.496.773");
}

.d-5aclb3h {
  stop-color: var(--svg-color--dd887e, #DD887E);
}

.d7t4onbnf {
  stop-color: var(--svg-color--e1a18e, #E1A18E);
}

.dvh-v1bvy {
  d: path("M9.015 22.35a858 858 0 0 1-1.546 5.22l1.074 1.39c.86-1.615 2.641-4.987 2.93-5.66c.242-.567.566-.711.808-.856l1.34-.804l-1.973-2.473c-.12.094-.594.444-1.32 1.074c-.734.637-1.169 1.618-1.313 2.11");
}

.dx40lk_kc {
  stop-color: var(--svg-color--fabfa4, #FABFA4);
  stop-opacity: 0;
}

.dxjajos_o {
  stop-color: var(--svg-color--f0b5a2, #F0B5A2);
}

.e2g34f-cy {
  stop-color: var(--svg-color--5e5d8f, #5E5D8F);
}

.e7heivjxf {
  stop-color: var(--svg-color--ebb1a3, #EBB1A3);
}

.e7u9e_b9n {
  stop-color: var(--svg-color--f0a48b, #F0A48B);
  stop-opacity: 0;
}

.eqdxe6bem {
  d: path("m12.556 6.566l.153-1.537a.773.773 0 0 1-.153 1.537");
}

.f-yzz_-ef {
  stop-color: var(--svg-color--5836a4, #5836A4);
}

.f2lax3blq {
  d: path("M9.454 3.697c-.2-.429-.017-.897.08-1.059c.362-.728 1.169-.806 1.642-.62c.557.22.726.342 1.602.055c.88-.287 1.979-.213 2.59.795c.613 1.007.035 2.188.2 2.814s.57.672.748 1.396c.163 1.008-.438 1.692-.989 1.863c-.55.17-1.7.065-2.11-.85c-.67-1.498-.282-2.234-.444-2.992s-.626-.957-1.45-.759c-.97.233-1.604-.072-1.87-.643");
}

.ft5dv1b6b {
  fill: none;
}

.g-yl6wiwd {
  fill: var(--svg-color--86004c, #86004C);
  fill-rule: evenodd;
  d: path("M11.043 7.098c.054.05.056.135.006.188c-.244.258-.607.335-.723.352a.133.133 0 0 1-.037-.263c.099-.014.387-.08.567-.271a.133.133 0 0 1 .187-.006");
}

.g4frhmb7u {
  stop-color: var(--svg-color--746399, #746399);
  stop-opacity: 0;
}

.g99i-8b1k {
  stop-color: var(--svg-color--f6bba5, #F6BBA5);
}

.gei07kbgq {
  stop-color: var(--svg-color--5a418f, #5A418F);
  stop-opacity: 0;
}

.gewgt1jbg {
  stop-color: var(--svg-color--afa8b2, #AFA8B2);
}

.grogb8blp {
  stop-color: var(--svg-color--be8394, #BE8394);
  stop-opacity: 0;
}

.gu4uskbqq {
  stop-color: var(--svg-color--fac1a8, #FAC1A8);
}

.gv3iwdbvq {
  stop-color: var(--svg-color--666361, #666361);
}

.h5b83fbqu {
  stop-color: var(--svg-color--f4bca5, #F4BCA5);
  stop-opacity: 0;
}

.hq1ekobkc {
  stop-color: var(--svg-color--e7a792, #E7A792);
}

.hq1fg214b {
  width: 1.484px;
  height: 1.324px;
  x: 4.738px;
  y: 10.409px;
  fill: var(--svg-color--f2bca0, #F2BCA0);
  rx: 0.662px;
}

.hth0c2b4n {
  fill-rule: evenodd;
  d: path("M19.704 10.586a1.85 1.85 0 0 0-1.873-.286l-2.687 1.092l-.866-2.13l2.687-1.093a4.15 4.15 0 0 1 4.2.64l2.997 2.508a.65.65 0 0 1 .085.912l-.636.772a.65.65 0 0 1-.919.085z");
}

.htujpbbup {
  stop-color: var(--svg-color--e5a48b, #E5A48B);
}

.hudyc0tda {
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("m5.792 11.74l3.062 1.422l-.156.122");
}

.hv04c4bjr {
  stop-color: var(--svg-color--908582, #908582);
}

.hvtacgb4z {
  stop-color: var(--svg-color--ffcfb6, #FFCFB6);
}

.hw5zu2bcg {
  stop-color: var(--svg-color--eeba9f, #EEBA9F);
  stop-opacity: 0;
}

.hymklqb8k {
  stop-color: var(--svg-color--ffd4b7, #FFD4B7);
}

.i80r67bey {
  stop-color: var(--svg-color--df9b93, #DF9B93);
  stop-opacity: 0;
}

.i8aj4_5_r {
  stop-color: var(--svg-color--fac7b1, #FAC7B1);
}

.ie_w39bfj {
  stop-color: var(--svg-color--fabfa4, #FABFA4);
}

.iihzz71vk {
  fill: var(--svg-color--eebb9f, #EEBB9F);
  d: path("m17.937 23.062l-.652-1.278l2.613-1.683l.344 1.015l5.836-.687l-.625 1.773c-1.422.445-4.465 1.408-5.504 1.68c-1.074.281-1.848-.434-2.012-.82");
}

.iv0p50s_n {
  stop-color: var(--svg-color--f0aa89, #F0AA89);
  stop-opacity: 0;
}

.j12scpkzx {
  stop-color: var(--svg-color--f6bba5, #F6BBA5);
  stop-opacity: 0;
}

.j1ev22o7x {
  stop-color: var(--svg-color--715fa7, #715FA7);
  stop-opacity: 0;
}

.j23k_cb2p {
  stop-color: var(--svg-color--9c959a, #9C959A);
  stop-opacity: 0;
}

.j2u_3dtev {
  stop-color: var(--svg-color--908582, #908582);
  stop-opacity: 0;
}

.j96xv6b5h {
  stop-color: var(--svg-color--917ea3, #917EA3);
  stop-opacity: 0;
}

.jbtab4n_d {
  stop-color: var(--svg-color--6b5396, #6B5396);
  stop-opacity: 0;
}

.jgi_q-wcb {
  stop-color: var(--svg-color--d6949b, #D6949B);
  stop-opacity: 0;
}

.jgvxgkbcu {
  fill: var(--svg-color--2f2c2d, #2F2C2D);
  d: path("M11.253 5.362c-.145-.134-.377-.157-.476-.152l.34.483c.157-.015.317-.164.136-.331");
}

.jkpn8qsux {
  fill: var(--svg-color--2c2828, #2C2828);
  fill-rule: evenodd;
  d: path("M10.709 4.827a.8.8 0 0 0-.231-.007a.16.16 0 0 1-.052-.315a1.1 1.1 0 0 1 .333.008c.136.021.298.07.44.167a.16.16 0 1 1-.179.263a.8.8 0 0 0-.311-.116");
}

.jlws7_s9m {
  fill: var(--svg-color--473f82, #473F82);
  d: path("m26.737 20.016l-1.234.472l-.16 1.75c.305.314 1.058 1.04 1.715 1.633c.428.387.844.467 1.146.432c.23-.026.312-.275.23-.491L27.06 20.16a.25.25 0 0 0-.323-.145");
}

.jqdm_110x {
  fill: var(--svg-color--534e8c, #534E8C);
  d: path("m5.039 27.499l2.46.07l1.048 1.39l-.624 1.184a.25.25 0 0 1-.335.106L4.178 28.5c-.197-.1-.317-.328-.197-.513c.247-.381.74-.488 1.058-.488");
}

.k_urnmdao {
  stop-color: var(--svg-color--ffecb8, #FFECB8);
}

.kba1trwhz {
  stop-color: var(--svg-color--7052bb, #7052BB);
}

.kg-rnkb9f {
  stop-color: var(--svg-color--827483, #827483);
  stop-opacity: 0;
}

.kl05mmksp {
  stop-color: var(--svg-color--836dbc, #836DBC);
}

.kpglbvlsk {
  stop-color: var(--svg-color--715fa7, #715FA7);
}

.l0aricxam {
  stop-color: var(--svg-color--916a62, #916A62);
}

.l7mbhnbzh {
  stop-color: var(--svg-color--eeb298, #EEB298);
}

.ls7ahvbmb {
  stop-color: var(--svg-color--746399, #746399);
}

.lsq6lsfjr {
  d: path("m17.226 21.999l-.914-2.148l1.793-3.844c1.258 1.754 1.738 2.664 1.98 3.054c.269.433.298.922-.062 1.282c-.637.569-2.13 1.34-2.797 1.656");
}

.lychkpbnw {
  stop-color: var(--svg-color--896fcc, #896FCC);
  stop-opacity: 0;
}

.m7ubqjboj {
  fill: var(--svg-color--7351bf, #7351BF);
  d: path("m13.136 9.323l.74-.39a1 1 0 0 1 .585-.106l2.003 1.774c-.23 1.789.13 3.007.9 4.077l-4.254 3.23c-1.516-2.636-1.93-5.073-1.555-6.354c.317-1.229 1.05-1.899 1.581-2.23");
}

.mrc1ztbfi {
  stop-color: var(--svg-color--f2beae, #F2BEAE);
}

.mvum_2bof {
  stop-color: var(--svg-color--ffbaa2, #FFBAA2);
}

.mx7n4_bgp {
  stop-color: var(--svg-color--806cb1, #806CB1);
}

.n1b4mhj1w {
  stop-color: var(--svg-color--64628c, #64628C);
  stop-opacity: 0;
}

.n3hnr4mdq {
  stop-color: var(--svg-color--ffd8be, #FFD8BE);
  stop-opacity: 0;
}

.n8gqlhnrc {
  stop-color: var(--svg-color--9583a6, #9583A6);
  stop-opacity: 0;
}

.n9r91ylyy {
  stop-color: var(--svg-color--824d44, #824D44);
}

.ni0zysbnp {
  stop-color: var(--svg-color--ffc5a1, #FFC5A1);
  stop-opacity: 0;
}

.nim1shnhj {
  stop-color: var(--svg-color--5b39a7, #5B39A7);
  stop-opacity: 0;
}

.nl4rtcblm {
  fill: var(--svg-color--918996, #918996);
  d: path("M17.351 14.67s-4.125 3.032-6.023 4.704a17.7 17.7 0 0 0 2.544 2.853a.92.92 0 0 0 1.23-.012c.92-.81 1.78-1.6 2.616-2.552c1.375-1.562 1.047-2.663.766-3.312c-.244-.563-.857-1.355-1.133-1.68");
}

.nrayz3bjb {
  d: path("M9.636 5.123c.008-.853.268-1.274.393-1.399l3.965-.152l.195 3.358c-.834 2.29-3.64 2.494-4.09 1.695c-.452-.8-.473-2.515-.463-3.502");
}

.o01zddb6n {
  stop-color: var(--svg-color--f4b9a2, #F4B9A2);
}

.o0q8xtq8c {
  d: path("m5.039 27.499l2.46.07l1.048 1.39l-.624 1.184a.25.25 0 0 1-.335.106L4.178 28.5c-.197-.1-.317-.328-.197-.513c.247-.381.74-.488 1.058-.488");
}

.o6m3gysuc {
  stop-color: var(--svg-color--68549d, #68549D);
}

.oqmg4vaes {
  stop-color: var(--svg-color--68549d, #68549D);
  stop-opacity: 0;
}

.osaguabiz {
  stop-color: var(--svg-color--917ea3, #917EA3);
}

.p0u56pe1z {
  stop-color: var(--svg-color--ffd5b7, #FFD5B7);
}

.p5bok0bog {
  stop-color: var(--svg-color--dd887e, #DD887E);
  stop-opacity: 0;
}

.p8sjifbbs {
  stop-color: var(--svg-color--ffcfb6, #FFCFB6);
  stop-opacity: 0;
}

.pb6-h6b6v {
  stop-color: var(--svg-color--7052bb, #7052BB);
  stop-opacity: 0;
}

.pd_td0b5t {
  fill: var(--svg-color--ffe0af, #FFE0AF);
  d: path("M9.454 3.697c-.2-.429-.017-.897.08-1.059c.362-.728 1.169-.806 1.642-.62c.557.22.726.342 1.602.055c.88-.287 1.979-.213 2.59.795c.613 1.007.035 2.188.2 2.814s.57.672.748 1.396c.163 1.008-.438 1.692-.989 1.863c-.55.17-1.7.065-2.11-.85c-.67-1.498-.282-2.234-.444-2.992s-.626-.957-1.45-.759c-.97.233-1.604-.072-1.87-.643");
}

.pism_984o {
  stop-color: var(--svg-color--6c57a8, #6C57A8);
  stop-opacity: 0;
}

.poxe0lb6u {
  stop-color: var(--svg-color--eda68d, #EDA68D);
}

.psqzkesbw {
  stop-color: var(--svg-color--eeba9f, #EEBA9F);
}

.pwq4emb2a {
  stop-color: var(--svg-color--be8394, #BE8394);
}

.qcut_9xzp {
  stop-color: var(--svg-color--f4bcb0, #F4BCB0);
}

.qlv8umoui {
  stop-color: var(--svg-color--5836a4, #5836A4);
  stop-opacity: 0;
}

.qtf1aub2p {
  d: path("m10.85 5.92l-.001-.003c-.013-.34-.17-.611-.35-.604s-.315.288-.302.629v.004z");
}

.qvmw_ibnt {
  width: 1.484px;
  height: 1.324px;
  x: 4.738px;
  y: 10.409px;
  rx: 0.662px;
}

.qyh4htb2f {
  fill: var(--svg-color--241823, #241823);
  d: path("M9.454 3.697c-.2-.429-.017-.897.08-1.059c.362-.728 1.169-.806 1.642-.62c.557.22.726.342 1.602.055c.88-.287 1.979-.213 2.59.795c.613 1.007.035 2.188.2 2.814s.57.672.748 1.396c.163 1.008-.438 1.692-.989 1.863c-.55.17-1.7.065-2.11-.85c-.67-1.498-.282-2.234-.444-2.992s-.626-.957-1.45-.759c-.97.233-1.604-.072-1.87-.643");
}

.rlbmuyd6x {
  d: path("m17.85 10.442l-1.325-2.718l-2.764 1.322a1.483 1.483 0 0 0 1.255 2.687z");
}

.rmzq06bzd {
  stop-color: var(--svg-color--64628c, #64628C);
}

.roa1y3bvy {
  stop-color: var(--svg-color--9b92a1, #9B92A1);
  stop-opacity: 0;
}

.ruyfycb4r {
  stop-color: var(--svg-color--444367, #444367);
}

.s2f2c_bct {
  stop-color: var(--svg-color--ffc4a7, #FFC4A7);
}

.s7euo-b6q {
  d: path("m10.64 5.928l.002-.077c-.007-.197-.097-.353-.2-.349s-.18.167-.172.363l.007.077z");
}

.slwiwcbms {
  stop-color: var(--svg-color--eca693, #ECA693);
}

.sq7_rccwx {
  stop-color: var(--svg-color--885fa7, #885FA7);
}

.sted03b1z {
  stop-color: var(--svg-color--4c438d, #4C438D);
}

.stui2mbih {
  stop-color: var(--svg-color--fff, #fff);
  stop-opacity: 0;
}

.t3d-9d8dp {
  d: path("M17.351 14.67s-4.125 3.032-6.023 4.704a17.7 17.7 0 0 0 2.544 2.853a.92.92 0 0 0 1.23-.012c.92-.81 1.78-1.6 2.616-2.552c1.375-1.562 1.047-2.663.766-3.312c-.244-.563-.857-1.355-1.133-1.68");
}

.tm7ezfuma {
  stop-color: var(--svg-color--7d68ba, #7D68BA);
  stop-opacity: 0;
}

.tseva3beu {
  stop-color: var(--svg-color--6b5396, #6B5396);
}

.tzf255bgc {
  stop-color: var(--svg-color--534b49, #534B49);
}

.u2yjj3mld {
  stop-color: var(--svg-color--ecb39e, #ECB39E);
}

.u598_4blb {
  stop-color: var(--svg-color--f5bda3, #F5BDA3);
}

.ubkqlww9x {
  stop-color: var(--svg-color--4c438d, #4C438D);
  stop-opacity: 0;
}

.ubyl24bdb {
  stop-color: var(--svg-color--565352, #565352);
}

.v1sha93vg {
  stop-color: var(--svg-color--746484, #746484);
}

.vc--wpv5i {
  stop-color: var(--svg-color--fff, #fff);
}

.vmk6x9_kg {
  stop-color: var(--svg-color--dd9a7e, #DD9A7E);
}

.vrnt79u8g {
  stop-color: var(--svg-color--443088, #443088);
}

.vunrlhvcc {
  stop-color: var(--svg-color--7d68ba, #7D68BA);
}

.vuvc8_ujh {
  stop-color: var(--svg-color--444367, #444367);
  stop-opacity: 0;
}

.vvztplbrt {
  stop-color: var(--svg-color--ffddbe, #FFDDBE);
  stop-opacity: 0;
}

.vx88q5bse {
  stop-color: var(--svg-color--484083, #484083);
  stop-opacity: 0;
}

.vy_lbsbpe {
  d: path("M12.169 7.269h1.946v3.44h-1.946z");
}

.w1ctt_hwm {
  stop-color: var(--svg-color--d09475, #D09475);
}

.w6scaoblb {
  fill: var(--svg-color--ffd1b9, #FFD1B9);
  d: path("M20.705 9.72c-.563-.487-1.182-.713-1.422-.765c.704-.06 1.422.41 1.766.667l2.468 2.036h.563l-.563.593c-.703-.64-2.25-2.043-2.812-2.53");
}

.w7r1zi1yh {
  stop-color: var(--svg-color--ffecb8, #FFECB8);
  stop-opacity: 0;
}

.wcectbccf {
  stop-color: var(--svg-color--ffcdb7, #FFCDB7);
}

.wjk-6vj4h {
  d: path("m26.737 20.016l-1.234.472l-.16 1.75c.305.314 1.058 1.04 1.715 1.633c.428.387.844.467 1.146.432c.23-.026.312-.275.23-.491L27.06 20.16a.25.25 0 0 0-.323-.145");
}

.wkc24ybrk {
  stop-color: var(--svg-color--dca5a4, #DCA5A4);
  stop-opacity: 0;
}

.x_q7-kble {
  stop-color: var(--svg-color--ffddbe, #FFDDBE);
}

.x022swbez {
  fill: var(--svg-color--97919e, #97919E);
  d: path("m17.226 21.999l-.914-2.148l1.793-3.844c1.258 1.754 1.738 2.664 1.98 3.054c.269.433.298.922-.062 1.282c-.637.569-2.13 1.34-2.797 1.656");
}

.x1ob3cbbz {
  stop-color: var(--svg-color--e2a789, #E2A789);
  stop-opacity: 0;
}

.xnjlox7lf {
  stop-color: var(--svg-color--e1a18e, #E1A18E);
  stop-opacity: 0;
}

.xv1vs_4ih {
  stop-color: var(--svg-color--ffd8be, #FFD8BE);
}

.y8e7yu08v {
  stop-color: var(--svg-color--d6949b, #D6949B);
}

.ynj07w4st {
  stop-color: var(--svg-color--df9b93, #DF9B93);
}

.yqtpn3uat {
  d: path("m17.937 23.062l-.652-1.278l2.613-1.683l.344 1.015l5.836-.687l-.625 1.773c-1.422.445-4.465 1.408-5.504 1.68c-1.074.281-1.848-.434-2.012-.82");
}

.z-p3-w_an {
  stop-color: var(--svg-color--534f8c, #534F8C);
  stop-opacity: 0;
}

.z3ho42bzm {
  stop-color: var(--svg-color--836dbc, #836DBC);
  stop-opacity: 0;
}

.z8qpeob8g {
  stop-color: var(--svg-color--dca5a4, #DCA5A4);
}

.zkj259b3a {
  stop-color: var(--svg-color--f0aa89, #F0AA89);
}

</style>
