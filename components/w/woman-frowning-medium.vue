<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iLgEZ3b)"><path fill="url(#imUtfZb)" clip-rule="evenodd" class="astei_btd"/><path fill="url(#iiAZTAd)" clip-rule="evenodd" class="astei_btd"/><path fill="url(#ibC9fjd)" clip-rule="evenodd" class="astei_btd"/><path fill="url(#iOhNqiK)" clip-rule="evenodd" class="astei_btd"/><path fill="url(#iGCjhcd)" clip-rule="evenodd" class="astei_btd"/><path fill="url(#iwP9Aud)" clip-rule="evenodd" class="astei_btd"/><path fill="url(#ixwJZgd)" clip-rule="evenodd" class="astei_btd"/><path fill="url(#iTm9GMy)" clip-rule="evenodd" class="astei_btd"/><path fill="url(#ikrt6fe)" clip-rule="evenodd" class="astei_btd"/><path fill="url(#i5GIn5j)" clip-rule="evenodd" class="astei_btd"/><path fill="url(#in843Fb)" clip-rule="evenodd" class="astei_btd"/><path fill="url(#igTqmhc)" clip-rule="evenodd" class="astei_btd"/></g><path fill="url(#inLHO7c)" class="pjisx3b4a"/><path fill="url(#iSjk2Oe)" class="pjisx3b4a"/><path fill="url(#imQ2QWs)" class="pjisx3b4a"/><path fill="url(#iFoQlJC)" class="pjisx3b4a"/><path fill="url(#idbemfd)" class="rvthnubxr"/><g filter="url(#iDYn51b)"><path fill="url(#iSZgXVN)" class="wbk6ucn9c"/></g><path fill="url(#iXZvzpj)" class="wbk6ucn9c"/><g filter="url(#igQ83le)"><path fill="url(#i3PzhKR)" class="vui8zzb2e"/><path fill="url(#i6fjS2d)" class="vui8zzb2e"/></g><g filter="url(#iVto7ud)"><path class="w0p203bkm"/><path fill="url(#i08qRAc)" class="r93zt1bun"/></g><g filter="url(#iQ2r7jd)"><path class="gczm2g3vb"/><path fill="url(#i3sfRLd)" class="simefcbpz"/></g><g filter="url(#i7JLoTd)"><path fill="url(#iuTpQDc)" class="v-3c40bfm"/><path fill="url(#iiQptyc)" class="v-3c40bfm"/><path fill="url(#iv1AwMd)" class="v-3c40bfm"/><path fill="url(#i5cL5xe)" class="v-3c40bfm"/><path fill="url(#ichoPlb)" class="v-3c40bfm"/><path fill="url(#i4fxCYa)" class="v-3c40bfm"/><path fill="url(#imDG32d)" class="v-3c40bfm"/><path fill="url(#iCGBzWE)" class="v-3c40bfm"/><path fill="url(#io1gR5b)" class="v-3c40bfm"/></g><path fill="url(#iZL6pze)" class="v-3c40bfm"/><g filter="url(#iRASHOb)"><path class="q9c3mjbjj"/></g><g filter="url(#iNsoB2d)"><path class="ye9jsebph"/><path fill="url(#im0ynVd)" class="lzpq_lk8e"/><path fill="url(#iG5m53b)" class="lzpq_lk8e"/><path fill="url(#iVcaq4d)" class="lzpq_lk8e"/><path fill="url(#ia7tDHd)" class="lzpq_lk8e"/></g><path fill="url(#iP3Ks5d)" class="lzpq_lk8e"/><path fill="url(#iN5JYGc)" class="lzpq_lk8e"/><g filter="url(#iHIgTQb)"><path class="y81s-xb2w"/></g><g filter="url(#iH0aonc)"><path class="o_0o1qb1m"/></g><path class="c2lb4b6vk"/><path fill="url(#iPGdi0y)" class="yuyqets-n"/><path class="p1a_w1bbg"/><g filter="url(#iwvSMae)"><path class="e6m4weblg"/><path fill="url(#iiw4Mfb)" class="qkldzbfgk"/></g><g filter="url(#ijGKsbb)"><path fill="url(#iWrsJyd)" class="ynan09_5d"/></g><path class="rwx39rb0s"/><path fill="url(#ic01WXb)" class="twhu2ibhb"/><path class="iscvwabvz"/><g filter="url(#iKS40Jb)"><path fill="url(#iVtjcJd)" class="q5yds9sop"/></g><g filter="url(#i43evUd)"><ellipse transform="rotate(-27.914 12.416 12.725)" class="z4kepib_k"/><ellipse fill="url(#iDUycue)" transform="rotate(-27.914 12.416 12.725)" class="nknvx1bjj"/></g><g filter="url(#igKrQte)"><path class="toqdhybri"/><path fill="url(#i8GN4uc)" class="rmb-p-bnb"/><path fill="url(#i7P3DdV)" class="rmb-p-bnb"/></g><g filter="url(#iMzZckb)"><path class="tt7i09v5e"/><path fill="url(#iGHa8Je)" class="j_9i3ybgw"/><path fill="url(#i2TuGVc)" class="j_9i3ybgw"/></g><g filter="url(#iGRtEYb)"><path stroke="url(#iN2VpQc)" class="tloh_6bhk"/></g><g filter="url(#iaFWcJe)"><path clip-rule="evenodd" class="crv4p3byc"/></g><g filter="url(#iSyElJe)"><path class="c1r04407f"/></g><g filter="url(#ihVwawb)"><path clip-rule="evenodd" class="blh39oylr"/></g><g filter="url(#ilSv0lB)"><path class="bbj_-6ble"/></g><g filter="url(#i9wygse)"><path stroke="url(#iJxwJec)" clip-rule="evenodd" class="wmtrstb6j"/><path stroke="url(#irPchGb)" clip-rule="evenodd" class="wmtrstb6j"/></g><path clip-rule="evenodd" class="iwx_cchng"/><g filter="url(#iDDxKQd)"><path class="wdg9peb-j"/></g><defs><radialGradient id="iiAZTAd" cx="0" cy="0" r="1" gradientTransform="matrix(-.81504 6.15812 -7.69275 -1.01815 15.323 17.039)" gradientUnits="userSpaceOnUse"><stop offset=".591" class="w9gpkna4y"/><stop offset="1" class="xvq3mubqy"/></radialGradient><radialGradient id="ibC9fjd" cx="0" cy="0" r="1" gradientTransform="rotate(146.004 3.1 10.461)scale(4.69703 6.17153)" gradientUnits="userSpaceOnUse"><stop offset=".258" class="u3fmvdnwh"/><stop offset="1" class="ysga7wb0w"/></radialGradient><radialGradient id="iOhNqiK" cx="0" cy="0" r="1" gradientTransform="matrix(-1.76592 2.3093 -1.77323 -1.35598 9.187 13.96)" gradientUnits="userSpaceOnUse"><stop offset=".334" class="jo-m975mj"/><stop offset="1" class="ecm2ecc2d"/></radialGradient><radialGradient id="iGCjhcd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.74331 2.85264 -2.00944 -1.228 9.798 11.22)" gradientUnits="userSpaceOnUse"><stop offset=".321" class="ksj-40n4x"/><stop offset="1" class="qkj18_koj"/></radialGradient><radialGradient id="iwP9Aud" cx="0" cy="0" r="1" gradientTransform="matrix(1.8565 3.53186 -4.90276 2.5771 10.976 2.775)" gradientUnits="userSpaceOnUse"><stop class="bk_mrebvc"/><stop offset="1" class="o57gz703y"/></radialGradient><radialGradient id="ixwJZgd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.94693 1.94707 -2.721 -2.7208 23.609 5.583)" gradientUnits="userSpaceOnUse"><stop class="g2m4aac5s"/><stop offset="1" class="tulkzacvs"/></radialGradient><radialGradient id="iTm9GMy" cx="0" cy="0" r="1" gradientTransform="rotate(163.779 12.045 8.099)scale(2.59355 5.40865)" gradientUnits="userSpaceOnUse"><stop class="ii82yjbfl"/><stop offset="1" class="tobrp8lrd"/></radialGradient><radialGradient id="ikrt6fe" cx="0" cy="0" r="1" gradientTransform="rotate(165.963 11.475 10.107)scale(3.9205 4.99413)" gradientUnits="userSpaceOnUse"><stop class="gto3tpbjl"/><stop offset="1" class="k8ni71bqd"/></radialGradient><radialGradient id="i5GIn5j" cx="0" cy="0" r="1" gradientTransform="matrix(-1.22167 -3.57981 2.83142 -.96627 22.123 9.223)" gradientUnits="userSpaceOnUse"><stop class="j6tbtfb5n"/><stop offset="1" class="u7ezkxzae"/></radialGradient><radialGradient id="in843Fb" cx="0" cy="0" r="1" gradientTransform="matrix(2.0314 .21308 -.34526 3.29145 7.434 12.462)" gradientUnits="userSpaceOnUse"><stop class="r4e237cot"/><stop offset="1" class="ktpt3tb_i"/></radialGradient><radialGradient id="igTqmhc" cx="0" cy="0" r="1" gradientTransform="rotate(-102.748 15.945 -3.252)scale(5.12993 1.85149)" gradientUnits="userSpaceOnUse"><stop class="fyy3crxae"/><stop offset="1" class="x7431zb1g"/></radialGradient><radialGradient id="inLHO7c" cx="0" cy="0" r="1" gradientTransform="rotate(167.548 9.337 14.198)scale(15.0733 14.5482)" gradientUnits="userSpaceOnUse"><stop class="o569z9a1w"/><stop offset=".514" class="tir3d5q-g"/><stop offset=".928" class="bqsidlj4b"/></radialGradient><radialGradient id="imQ2QWs" cx="0" cy="0" r="1" gradientTransform="matrix(-14.0601 0 0 -10.457 19.437 29.349)" gradientUnits="userSpaceOnUse"><stop offset=".829" class="sw5cssher"/><stop offset="1" class="v_je8db5f"/></radialGradient><radialGradient id="iFoQlJC" cx="0" cy="0" r="1" gradientTransform="rotate(170.242 5.668 10.697)scale(6.21871 3.13729)" gradientUnits="userSpaceOnUse"><stop offset=".194" class="fff_vbcwe"/><stop offset="1" class="vp-la-38w"/></radialGradient><radialGradient id="idbemfd" cx="0" cy="0" r="1" gradientTransform="matrix(3.43666 3.13974 -4.13338 4.52426 14.22 20.985)" gradientUnits="userSpaceOnUse"><stop offset=".17" class="jjshjdl1g"/><stop offset=".866" class="k-rrjrbul"/></radialGradient><radialGradient id="iXZvzpj" cx="0" cy="0" r="1" gradientTransform="matrix(-.88297 -1.62556 1.84198 -1.00053 8.87 15.834)" gradientUnits="userSpaceOnUse"><stop class="wlzou1bho"/><stop offset="1" class="muarw1mje"/></radialGradient><radialGradient id="i3PzhKR" cx="0" cy="0" r="1" gradientTransform="matrix(3.36206 -1.52821 1.86588 4.10492 21.187 14.254)" gradientUnits="userSpaceOnUse"><stop offset=".64" class="xqzyuky4n"/><stop offset="1" class="yiz6fvgdb"/></radialGradient><radialGradient id="i6fjS2d" cx="0" cy="0" r="1" gradientTransform="matrix(1.63009 0 0 .70184 22.41 11.356)" gradientUnits="userSpaceOnUse"><stop class="v4cuahbfk"/><stop offset="1" class="ame5l9u0o"/></radialGradient><radialGradient id="i08qRAc" cx="0" cy="0" r="1" gradientTransform="matrix(2.03947 -.1517 .1186 1.5943 21.662 13.813)" gradientUnits="userSpaceOnUse"><stop offset=".719" class="j_jb06m8v"/><stop offset="1" class="t9v208shd"/></radialGradient><radialGradient id="i3sfRLd" cx="0" cy="0" r="1" gradientTransform="rotate(-180 4.758 6.83)scale(1.42633)" gradientUnits="userSpaceOnUse"><stop offset=".722" class="w5re42dqy"/><stop offset="1" class="w4wkyodwa"/></radialGradient><radialGradient id="iuTpQDc" cx="0" cy="0" r="1" gradientTransform="matrix(-8.78464 4.05089 -5.42204 -11.75807 19.592 12.935)" gradientUnits="userSpaceOnUse"><stop class="ox3481l0h"/><stop offset="1" class="l65mx1yct"/></radialGradient><radialGradient id="iiQptyc" cx="0" cy="0" r="1" gradientTransform="matrix(-2.945 1.29589 -.90243 -2.05084 18.392 14.088)" gradientUnits="userSpaceOnUse"><stop class="vw42v6b3v"/><stop offset="1" class="v5m4qhb2r"/></radialGradient><radialGradient id="iv1AwMd" cx="0" cy="0" r="1" gradientTransform="matrix(1.7413 -5.30619 6.73257 2.20939 12.81 21.725)" gradientUnits="userSpaceOnUse"><stop class="hl813wbpa"/><stop offset="1" class="a21bmlbcx"/></radialGradient><radialGradient id="i5cL5xe" cx="0" cy="0" r="1" gradientTransform="matrix(-1.73527 9.95926 -12.44895 -2.16906 17.112 12.373)" gradientUnits="userSpaceOnUse"><stop offset=".637" class="ndb61xwjr"/><stop offset="1" class="l57p2o49o"/></radialGradient><radialGradient id="ichoPlb" cx="0" cy="0" r="1" gradientTransform="matrix(0 8.46739 -8.51274 0 15.377 13.462)" gradientUnits="userSpaceOnUse"><stop offset=".911" class="i-c7amj6z"/><stop offset="1" class="nmcs74byh"/></radialGradient><radialGradient id="i4fxCYa" cx="0" cy="0" r="1" gradientTransform="rotate(168.897 8.345 8.52)scale(9.50567 16.3658)" gradientUnits="userSpaceOnUse"><stop offset=".795" class="qh0bdqbav"/><stop offset="1" class="dt7ct4boy"/></radialGradient><radialGradient id="imDG32d" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.55439 1.90766 0 18.839 12.37)" gradientUnits="userSpaceOnUse"><stop class="azt-9rbtm"/><stop offset="1" class="ci16jsbol"/></radialGradient><radialGradient id="iCGBzWE" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.77286 2.03182 0 12.925 12.06)" gradientUnits="userSpaceOnUse"><stop class="zemyxxbjg"/><stop offset="1" class="k1zv-ubmt"/></radialGradient><radialGradient id="io1gR5b" cx="0" cy="0" r="1" gradientTransform="rotate(105.092 5.26 11.361)scale(4.51419 3.61209)" gradientUnits="userSpaceOnUse"><stop class="aotu-xwil"/><stop offset="1" class="izc7dk1pl"/></radialGradient><radialGradient id="iZL6pze" cx="0" cy="0" r="1" gradientTransform="matrix(-1.73608 0 0 -8.70628 22.613 14.379)" gradientUnits="userSpaceOnUse"><stop class="fyxppic9g"/><stop offset="1" class="kq5b787yl"/></radialGradient><radialGradient id="im0ynVd" cx="0" cy="0" r="1" gradientTransform="matrix(-.61532 -2.76092 .8509 -.18964 16.79 15.36)" gradientUnits="userSpaceOnUse"><stop offset=".017" class="ab1vgh_ru"/><stop offset="1" class="f80hfjhpj"/></radialGradient><radialGradient id="ia7tDHd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.05277 0 0 -.29432 16.466 15.646)" gradientUnits="userSpaceOnUse"><stop class="hjp773b9j"/><stop offset="1" class="wh0vrhbzi"/></radialGradient><radialGradient id="iN5JYGc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.85215 1.27157 -1.52823 -2.226 16.24 14.843)" gradientUnits="userSpaceOnUse"><stop offset=".778" class="xs9vt_bzp"/><stop offset="1" class="p13423bzd"/><stop offset="1" class="jjvamgr7p"/></radialGradient><radialGradient id="iPGdi0y" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.09588 -1.74311 0 18.678 12.854)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="xbuk-xbxm"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="cqpaw5wjj"/></radialGradient><radialGradient id="iiw4Mfb" cx="0" cy="0" r="1" gradientTransform="rotate(-127.812 12.36 1.986)scale(.51097 .70347)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="ic01WXb" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.09588 -1.74312 0 12.783 12.854)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="xbuk-xbxm"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="cqpaw5wjj"/></radialGradient><radialGradient id="iDUycue" cx="0" cy="0" r="1" gradientTransform="rotate(-90.897 12.671 .474)scale(.66743 .80227)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="i8GN4uc" cx="0" cy="0" r="1" gradientTransform="rotate(-64.926 11.915 -1.354)scale(4.10923 2.13135)" gradientUnits="userSpaceOnUse"><stop class="gaydocc3b"/><stop offset="1" class="o5ryhdc_j"/></radialGradient><radialGradient id="i7P3DdV" cx="0" cy="0" r="1" gradientTransform="matrix(1.58617 -2.66813 1.44732 .86041 10.449 8.687)" gradientUnits="userSpaceOnUse"><stop class="bkfqk3fbn"/><stop offset="1" class="hrqlkdbpd"/></radialGradient><radialGradient id="iGHa8Je" cx="0" cy="0" r="1" gradientTransform="rotate(116.702 8.142 7.164)scale(6.50047 10.9231)" gradientUnits="userSpaceOnUse"><stop offset=".639" class="ukea7pdhy"/><stop offset="1" class="wuqjd3b5z"/></radialGradient><radialGradient id="i2TuGVc" cx="0" cy="0" r="1" gradientTransform="matrix(-.29092 1.80796 -4.0595 -.6532 15.848 3.598)" gradientUnits="userSpaceOnUse"><stop class="y3gk9pbvh"/><stop offset="1" class="j2p90_-bc"/><stop offset="1" class="ru9fl6bjc"/></radialGradient><radialGradient id="iJxwJec" cx="0" cy="0" r="1" gradientTransform="rotate(-74.859 20.008 -1.537)scale(.68794 1.67216)" gradientUnits="userSpaceOnUse"><stop offset=".269" class="lk7khdb2p"/><stop offset=".581" class="awrx3dbzo"/></radialGradient><radialGradient id="irPchGb" cx="0" cy="0" r="1" gradientTransform="matrix(.53516 -.58203 .42042 .38656 14.176 18.405)" gradientUnits="userSpaceOnUse"><stop offset=".065" class="lk7khdb2p"/><stop offset=".571" class="awrx3dbzo"/></radialGradient><filter id="iLgEZ3b" width="20.535" height="21.036" x="5.587" y="1.391" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.75"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.262745 0 0 0 0 0.133333 0 0 0 0 0.184314 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_21897"/></filter><filter id="iDYn51b" width="4.497" height="4.347" x="7.228" y="11.487" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.607843 0 0 0 0 0.458824 0 0 0 0 0.403922 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_21897"/></filter><filter id="igQ83le" width="4.347" height="4.597" x="20.077" y="11.237" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.556863 0 0 0 0 0.34902 0 0 0 0 0.384314 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_21897"/></filter><filter id="iVto7ud" width="3.902" height="3.902" x="20.3" y="11.71" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_21897" stdDeviation=".25"/></filter><filter id="iQ2r7jd" width="3.602" height="3.602" x="7.626" y="11.86" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_21897" stdDeviation=".175"/></filter><filter id="i7JLoTd" width="13.765" height="15.092" x="8.848" y="7.033" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.407843 0 0 0 0 0.223529 0 0 0 0 0.25098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_21897"/></filter><filter id="iRASHOb" width="3.536" height="4.622" x="13.743" y="12.479" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_21897" stdDeviation=".25"/></filter><filter id="iNsoB2d" width="3.036" height="4.122" x="14.212" y="12.541" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_21897" stdDeviation=".125"/></filter><filter id="iHIgTQb" width="3.984" height="1.736" x="17.073" y="11.764" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.141176 0 0 0 0 0.0862745 0 0 0 0 0.176471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_21897"/></filter><filter id="iH0aonc" width="3.984" height="1.736" x="10.404" y="11.764" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.133333 0 0 0 0 0.0784314 0 0 0 0 0.168627 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_21897"/></filter><filter id="iwvSMae" width=".993" height=".87" x="17.721" y="12.295" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_21897" stdDeviation=".05"/></filter><filter id="ijGKsbb" width="1.064" height="1.093" x="18.891" y="12.432" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_21897" stdDeviation=".1"/></filter><filter id="iKS40Jb" width="1.192" height="1.265" x="12.889" y="12.346" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_21897" stdDeviation=".1"/></filter><filter id="i43evUd" width="1.163" height=".881" x="11.835" y="12.284" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_21897" stdDeviation=".05"/></filter><filter id="igKrQte" width="6.208" height="6.516" x="6.933" y="4.096" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy=".5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.345098 0 0 0 0 0.286275 0 0 0 0 0.27451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_21897"/><feGaussianBlur result="effect2_foregroundBlur_3987_21897" stdDeviation=".375"/></filter><filter id="iMzZckb" width="12.865" height="8.485" x="10.837" y="2.489" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.3" dy=".2"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.415686 0 0 0 0 0.317647 0 0 0 0 0.305882 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_21897"/><feGaussianBlur result="effect2_foregroundBlur_3987_21897" stdDeviation=".375"/></filter><filter id="iGRtEYb" width="1.336" height="2.909" x="11.525" y="4.524" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_21897" stdDeviation=".1"/></filter><filter id="iaFWcJe" width="3.08" height="1.757" x="10.74" y="9.666" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.211765 0 0 0 0 0.121569 0 0 0 0 0.12549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_21897"/></filter><filter id="iSyElJe" width="2.83" height="1.507" x="10.815" y="9.841" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_21897" stdDeviation=".1"/></filter><filter id="ihVwawb" width="3.08" height="1.757" x="17.74" y="9.666" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.211765 0 0 0 0 0.121569 0 0 0 0 0.12549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_21897"/></filter><filter id="ilSv0lB" width="2.83" height="1.507" x="17.815" y="9.841" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_21897" stdDeviation=".1"/></filter><filter id="i9wygse" width="3.791" height="1.496" x="13.835" y="17.143" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_21897" stdDeviation=".1"/></filter><filter id="iDDxKQd" width="8.107" height="4.32" x="15.037" y="5.732" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_21897" stdDeviation=".5"/></filter><linearGradient id="imUtfZb" x1="22.07" x2="13.783" y1="4.27" y2="18.805" gradientUnits="userSpaceOnUse"><stop class="ap760fb9g"/><stop offset="1" class="w1etxcbdz"/></linearGradient><linearGradient id="iSjk2Oe" x1="15.73" x2="15.73" y1="30.329" y2="29.485" gradientUnits="userSpaceOnUse"><stop class="h094d73xa"/><stop offset="1" class="pt83qis4i"/></linearGradient><linearGradient id="iSZgXVN" x1="7.228" x2="9.737" y1="13.779" y2="13.779" gradientUnits="userSpaceOnUse"><stop class="cg1k0hirj"/><stop offset="1" class="u6m78ac0i"/></linearGradient><linearGradient id="iG5m53b" x1="14.462" x2="15.73" y1="15.459" y2="15.459" gradientUnits="userSpaceOnUse"><stop class="hm31m3bmo"/><stop offset="1" class="vh12xwf7a"/></linearGradient><linearGradient id="iVcaq4d" x1="15.73" x2="15.73" y1="16.414" y2="15.567" gradientUnits="userSpaceOnUse"><stop class="us3ue9b4r"/><stop offset="1" class="hxr-reb3g"/></linearGradient><linearGradient id="iP3Ks5d" x1="15.836" x2="15.836" y1="16.503" y2="16.314" gradientUnits="userSpaceOnUse"><stop class="b576ppbxh"/><stop offset="1" class="a_xwx-nqh"/></linearGradient><linearGradient id="iWrsJyd" x1="19.728" x2="19.305" y1="12.927" y2="13.188" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iVtjcJd" x1="13.788" x2="13.364" y1="12.927" y2="13.188" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iN2VpQc" x1="11.531" x2="12.193" y1="4.27" y2="5.979" gradientUnits="userSpaceOnUse"><stop class="olrv_cchi"/><stop offset="1" class="lwhsndh-i"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:woman-frowning-medium" /></template>
<style>
.a_xwx-nqh {
  stop-color: var(--svg-color--8f5269, #8F5269);
  stop-opacity: 0;
}

.a21bmlbcx {
  stop-color: var(--svg-color--945a73, #945A73);
  stop-opacity: 0;
}

.ab1vgh_ru {
  stop-color: var(--svg-color--cda38b, #CDA38B);
}

.ame5l9u0o {
  stop-color: var(--svg-color--906d53, #906D53);
  stop-opacity: 0;
}

.aotu-xwil {
  stop-color: var(--svg-color--ab8179, #AB8179);
}

.ap760fb9g {
  stop-color: var(--svg-color--6d524e, #6D524E);
}

.astei_btd {
  fill-rule: evenodd;
  d: path("M25.436 15.565a4.4 4.4 0 0 0 .437-1.928c0-.63-.13-1.223-.363-1.763h.007a4.3 4.3 0 0 0-.38-.693l-.002-.004a4.4 4.4 0 0 1-.711-2.392V8.77a4.457 4.457 0 0 0-4.456-4.456a.73.73 0 0 1-.615-.314a4.47 4.47 0 0 0-3.623-1.86c-1.49 0-2.816.739-3.622 1.86a.76.76 0 0 1-.616.314l-.114.001A4.457 4.457 0 0 0 7.036 8.77v.014c0 .847-.246 1.681-.71 2.392l-.004.005a4.46 4.46 0 0 0-.735 2.455c0 .698.164 1.34.438 1.928a.7.7 0 0 1 0 .615a4.4 4.4 0 0 0-.438 1.9a4.34 4.34 0 0 0 4.347 4.347h11.592a4.34 4.34 0 0 0 4.347-4.347c0-.683-.164-1.326-.437-1.9a.7.7 0 0 1 0-.615m-16.56-3.61h-.017l1.619 3.182c.166 3.785 1.644 0 5.252 0s5.182 4.213 5.348.428l1.535-4.318c-.073-1.682-1.291-1.8-1.535-1.8H16.73a5.22 5.22 0 0 1-4.308-2.26a.356.356 0 0 0-.623.069l-.11.262a3.1 3.1 0 0 1-1.608 1.667q-.031.011-.069.028l-.07.027c-.318.166-1.066.662-1.093 1.944l.013.413z");
}

.awrx3dbzo {
  stop-color: var(--svg-color--b68a85, #B68A85);
  stop-opacity: 0;
}

.azt-9rbtm {
  stop-color: var(--svg-color--ae7b75, #AE7B75);
}

.b576ppbxh {
  stop-color: var(--svg-color--8f5269, #8F5269);
}

.bbj_-6ble {
  stroke: var(--svg-color--5b4545, #5B4545);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M20.346 11.048c-.521.01-1.606-.188-2.231-.906");
}

.bk_mrebvc {
  stop-color: var(--svg-color--554543, #554543);
}

.bkfqk3fbn {
  stop-color: var(--svg-color--4b2839, #4B2839);
}

.blh39oylr {
  fill: var(--svg-color--432a28, #432A28);
  fill-rule: evenodd;
  d: path("M17.869 9.859a.375.375 0 0 0-.037.529c.37.426.864.684 1.319.836s.898.205 1.202.199a.375.375 0 0 0-.015-.75a3 3 0 0 1-.95-.16c-.375-.126-.736-.325-.99-.618a.375.375 0 0 0-.53-.036");
}

.bqsidlj4b {
  stop-color: var(--svg-color--5e4d84, #5E4D84);
}

.c1r04407f {
  stroke: var(--svg-color--473c3c, #473C3C);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M11.115 11.048c.52.01 1.605-.188 2.23-.906");
}

.c2lb4b6vk {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.96 11.843c.882 0 1.627.608 1.83 1.43a.37.37 0 0 1-.362.46h-3.013a.31.31 0 0 1-.307-.367a1.89 1.89 0 0 1 1.852-1.523");
}

.cg1k0hirj {
  stop-color: var(--svg-color--8d645f, #8D645F);
}

.ci16jsbol {
  stop-color: var(--svg-color--ae7b75, #AE7B75);
  stop-opacity: 0;
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cqpaw5wjj {
  stop-color: var(--svg-color--664b41, #664B41);
}

.crv4p3byc {
  fill: var(--svg-color--432a28, #432A28);
  fill-rule: evenodd;
  d: path("M13.592 9.859a.375.375 0 0 1 .036.529c-.37.426-.864.684-1.318.836a3.8 3.8 0 0 1-1.203.199a.375.375 0 0 1 .016-.75a3 3 0 0 0 .95-.16c.374-.126.735-.325.99-.618a.375.375 0 0 1 .528-.036");
}

.dt7ct4boy {
  stop-color: var(--svg-color--9a7267, #9A7267);
}

.e6m4weblg {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M18.592 12.465c.086.115-.094.255-.298.407c-.204.153-.356.26-.442.146c-.085-.115.01-.332.215-.485c.204-.152.439-.183.525-.068");
}

.ecm2ecc2d {
  stop-color: var(--svg-color--27141e, #27141E);
  stop-opacity: 0;
}

.f80hfjhpj {
  stop-color: var(--svg-color--cda38b, #CDA38B);
  stop-opacity: 0;
}

.fff_vbcwe {
  stop-color: var(--svg-color--402a66, #402A66);
}

.ft5dv1b6b {
  fill: none;
}

.fyxppic9g {
  stop-color: var(--svg-color--c0967a, #C0967A);
}

.fyy3crxae {
  stop-color: var(--svg-color--3e2125, #3E2125);
}

.g2m4aac5s {
  stop-color: var(--svg-color--6e5350, #6E5350);
}

.gaydocc3b {
  stop-color: var(--svg-color--5c4643, #5C4643);
}

.gczm2g3vb {
  fill: var(--svg-color--7e555a, #7E555A);
  d: path("M9.427 15.112a1.45 1.45 0 1 0 0-2.902a1.45 1.45 0 0 0 0 2.902");
}

.gto3tpbjl {
  stop-color: var(--svg-color--564544, #564544);
}

.h094d73xa {
  stop-color: var(--svg-color--5f4e9d, #5F4E9D);
}

.hjp773b9j {
  stop-color: var(--svg-color--ca9f8c, #CA9F8C);
}

.hl813wbpa {
  stop-color: var(--svg-color--945a73, #945A73);
}

.hm31m3bmo {
  stop-color: var(--svg-color--875f54, #875F54);
}

.hrqlkdbpd {
  stop-color: var(--svg-color--4b2839, #4B2839);
  stop-opacity: 0;
}

.hxr-reb3g {
  stop-color: var(--svg-color--995c76, #995C76);
  stop-opacity: 0;
}

.i-c7amj6z {
  stop-color: var(--svg-color--9f6394, #9F6394);
  stop-opacity: 0;
}

.ii82yjbfl {
  stop-color: var(--svg-color--604947, #604947);
}

.iscvwabvz {
  fill: var(--svg-color--000, #000);
  d: path("M13.47 13.415a.69.69 0 0 0-.69-.69a.688.688 0 0 0-.614 1.008h1.222a.7.7 0 0 0 .082-.318");
}

.iwx_cchng {
  fill: var(--svg-color--87004d, #87004D);
  fill-rule: evenodd;
  d: path("M16.912 18.301c-.958-.557-1.98-.232-2.36-.002a.275.275 0 1 1-.284-.471c.484-.291 1.729-.695 2.92-.002a.275.275 0 0 1-.276.475");
}

.izc7dk1pl {
  stop-color: var(--svg-color--ab8179, #AB8179);
  stop-opacity: 0;
}

.j_9i3ybgw {
  d: path("M15.344 3.264c-1.97-.234-3.297 1.25-3.757 1.73c2.083 4.89 5.281 4.424 8.83 4.03c2.124-.236 2.354.732 2.535 1.2c-.588-5.479-4.063-6.538-7.608-6.96");
}

.j_jb06m8v {
  stop-color: var(--svg-color--a26d62, #A26D62);
  stop-opacity: 0;
}

.j2p90_-bc {
  stop-color: var(--svg-color--4c4749, #4C4749);
  stop-opacity: 0;
}

.j6tbtfb5n {
  stop-color: var(--svg-color--5f4846, #5F4846);
}

.jjshjdl1g {
  stop-color: var(--svg-color--84535b, #84535B);
}

.jjvamgr7p {
  stop-color: var(--svg-color--815553, #815553);
}

.jo-m975mj {
  stop-color: var(--svg-color--27141e, #27141E);
}

.k-rrjrbul {
  stop-color: var(--svg-color--c19581, #C19581);
}

.k1zv-ubmt {
  stop-color: var(--svg-color--8f5c65, #8F5C65);
  stop-opacity: 0;
}

.k8ni71bqd {
  stop-color: var(--svg-color--564544, #564544);
  stop-opacity: 0;
}

.kq5b787yl {
  stop-color: var(--svg-color--c0967a, #C0967A);
  stop-opacity: 0;
}

.ksj-40n4x {
  stop-color: var(--svg-color--230c14, #230C14);
}

.ktpt3tb_i {
  stop-color: var(--svg-color--56413d, #56413D);
  stop-opacity: 0;
}

.l57p2o49o {
  stop-color: var(--svg-color--97577d, #97577D);
}

.l65mx1yct {
  stop-color: var(--svg-color--946568, #946568);
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lk7khdb2p {
  stop-color: var(--svg-color--b68a85, #B68A85);
}

.lwhsndh-i {
  stop-color: var(--svg-color--452531, #452531);
}

.lzpq_lk8e {
  d: path("m15.214 13.173l-.718 2.296a.728.728 0 0 0 .703.945h1.062a.73.73 0 0 0 .704-.945l-.718-2.296c-.154-.509-.872-.509-1.033 0");
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.muarw1mje {
  stop-color: var(--svg-color--814e62, #814E62);
  stop-opacity: 0;
}

.ndb61xwjr {
  stop-color: var(--svg-color--97577d, #97577D);
  stop-opacity: 0;
}

.nknvx1bjj {
  cx: 12.416px;
  cy: 12.725px;
  rx: 0.526px;
  ry: 0.266px;
}

.nmcs74byh {
  stop-color: var(--svg-color--9f6394, #9F6394);
}

.o_0o1qb1m {
  fill: var(--svg-color--35292e, #35292E);
  d: path("M14.188 12.892c-.359-.63-.904-1.128-2.077-1.128c-.513 0-1.009.142-1.449.498c-.363.293-.314.668-.033.809l.751.429c.88-.285 1.854-.323 2.808-.608");
}

.o569z9a1w {
  stop-color: var(--svg-color--917ccd, #917CCD);
}

.o57gz703y {
  stop-color: var(--svg-color--554543, #554543);
  stop-opacity: 0;
}

.o5ryhdc_j {
  stop-color: var(--svg-color--5c4643, #5C4643);
  stop-opacity: 0;
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.olrv_cchi {
  stop-color: var(--svg-color--361f1f, #361F1F);
}

.ox3481l0h {
  stop-color: var(--svg-color--c79980, #C79980);
}

.p13423bzd {
  stop-color: var(--svg-color--693b40, #693B40);
}

.p1a_w1bbg {
  fill: var(--svg-color--000, #000);
  d: path("M17.99 13.415c0-.383.307-.69.69-.69a.688.688 0 0 1 .614 1.008h-1.222a.6.6 0 0 1-.082-.318");
}

.pjisx3b4a {
  d: path("M25.645 30v-.386c0-5.347-4.436-9.691-9.915-9.691s-9.915 4.335-9.915 9.691v.387z");
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pt83qis4i {
  stop-color: var(--svg-color--5f4e9d, #5F4E9D);
  stop-opacity: 0;
}

.q5yds9sop {
  d: path("M13.881 13.274c0-.39-.316-.65-.402-.728l-.39.377l.24.488z");
}

.q9c3mjbjj {
  fill: var(--svg-color--88555f, #88555F);
  d: path("m15.2 13.36l-.923 2.296a.728.728 0 0 0 .703.945h1.062a.73.73 0 0 0 .703-.945l-.718-2.296c-.153-.509-.666-.509-.827 0");
}

.qh0bdqbav {
  stop-color: var(--svg-color--9a7267, #9A7267);
  stop-opacity: 0;
}

.qkj18_koj {
  stop-color: var(--svg-color--230c14, #230C14);
  stop-opacity: 0;
}

.qkldzbfgk {
  d: path("M18.592 12.465c.086.115-.094.255-.298.407c-.204.153-.356.26-.442.146c-.085-.115.01-.332.215-.485c.204-.152.439-.183.525-.068");
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.r4e237cot {
  stop-color: var(--svg-color--56413d, #56413D);
}

.r93zt1bun {
  d: path("M22.25 15.112a1.45 1.45 0 1 0 0-2.902a1.45 1.45 0 0 0 0 2.902");
}

.rmb-p-bnb {
  d: path("M9.12 5.538c.838-.748 2.048-.755 2.728-.634l.543 1.743c-.347-.053-.657.068-.917.317c-.616 1.702-2.732 2.641-3.713 2.898c-.204-2.015-.09-3.034 1.358-4.324");
}

.ru9fl6bjc {
  stop-color: var(--svg-color--634945, #634945);
  stop-opacity: 0;
}

.rvthnubxr {
  d: path("M15.73 23.594c-1.43 0-2.587-1.067-2.587-2.387v-2.82c0-1.32 1.157-2.387 2.587-2.387s2.587 1.067 2.587 2.387v2.82c0 1.32-1.156 2.387-2.587 2.387");
}

.rwx39rb0s {
  fill: var(--svg-color--fff, #fff);
  d: path("M12.5 11.843c-.881 0-1.627.608-1.83 1.43a.37.37 0 0 0 .362.46h3.014a.31.31 0 0 0 .307-.367a1.89 1.89 0 0 0-1.852-1.523");
}

.simefcbpz {
  d: path("M9.427 15.112a1.45 1.45 0 1 0 0-2.902a1.45 1.45 0 0 0 0 2.902");
}

.sw5cssher {
  stop-color: var(--svg-color--6d5b88, #6D5B88);
  stop-opacity: 0;
}

.t9v208shd {
  stop-color: var(--svg-color--a26d62, #A26D62);
}

.tir3d5q-g {
  stop-color: var(--svg-color--715cac, #715CAC);
}

.tloh_6bhk {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M11.825 4.824c.031.329.317 1.563.736 2.31");
}

.tobrp8lrd {
  stop-color: var(--svg-color--604947, #604947);
  stop-opacity: 0;
}

.toqdhybri {
  fill: var(--svg-color--49302e, #49302E);
  d: path("M9.12 5.538c.838-.748 2.048-.755 2.728-.634l.543 1.743c-.347-.053-.657.068-.917.317c-.616 1.702-2.732 2.641-3.713 2.898c-.204-2.015-.09-3.034 1.358-4.324");
}

.tt7i09v5e {
  fill: var(--svg-color--553836, #553836);
  d: path("M15.344 3.264c-1.97-.234-3.297 1.25-3.757 1.73c2.083 4.89 5.281 4.424 8.83 4.03c2.124-.236 2.354.732 2.535 1.2c-.588-5.479-4.063-6.538-7.608-6.96");
}

.tulkzacvs {
  stop-color: var(--svg-color--6e5350, #6E5350);
  stop-opacity: 0;
}

.twhu2ibhb {
  d: path("M12.78 12.21a1.205 1.205 0 0 0-1.162 1.523h2.33q.042-.154.043-.318a1.214 1.214 0 0 0-1.21-1.205");
}

.u3fmvdnwh {
  stop-color: var(--svg-color--25131c, #25131C);
}

.u6m78ac0i {
  stop-color: var(--svg-color--604138, #604138);
}

.u7ezkxzae {
  stop-color: var(--svg-color--5f4846, #5F4846);
  stop-opacity: 0;
}

.ukea7pdhy {
  stop-color: var(--svg-color--442534, #442534);
  stop-opacity: 0;
}

.us3ue9b4r {
  stop-color: var(--svg-color--995c76, #995C76);
}

.v_je8db5f {
  stop-color: var(--svg-color--6d5b88, #6D5B88);
}

.v-3c40bfm {
  d: path("M8.859 11.955h.016l-.013-.358l-.014-.413c.027-1.282.775-1.778 1.094-1.944l.07-.027l.068-.028a3.1 3.1 0 0 0 1.607-1.667l.111-.262a.356.356 0 0 1 .623-.07a5.22 5.22 0 0 0 4.308 2.261h4.35c.243 0 1.461.118 1.534 1.8l-.16 4.15c-.167 3.786-3.123 6.328-6.732 6.328s-6.564-2.542-6.73-6.328z");
}

.v4cuahbfk {
  stop-color: var(--svg-color--906d53, #906D53);
}

.v5m4qhb2r {
  stop-color: var(--svg-color--c4967a, #C4967A);
  stop-opacity: 0;
}

.vh12xwf7a {
  stop-color: var(--svg-color--875f54, #875F54);
  stop-opacity: 0;
}

.vp-la-38w {
  stop-color: var(--svg-color--402a66, #402A66);
  stop-opacity: 0;
}

.vui8zzb2e {
  d: path("M22.25 15.834a2.173 2.173 0 1 0 0-4.347a2.173 2.173 0 0 0 0 4.347");
}

.vw42v6b3v {
  stop-color: var(--svg-color--c4967a, #C4967A);
}

.w0p203bkm {
  fill: var(--svg-color--b38574, #B38574);
  d: path("M22.25 15.112a1.45 1.45 0 1 0 0-2.902a1.45 1.45 0 0 0 0 2.902");
}

.w1etxcbdz {
  stop-color: var(--svg-color--2c1c24, #2C1C24);
}

.w4wkyodwa {
  stop-color: var(--svg-color--6c4640, #6C4640);
}

.w5re42dqy {
  stop-color: var(--svg-color--6c4640, #6C4640);
  stop-opacity: 0;
}

.w9gpkna4y {
  stop-color: var(--svg-color--261326, #261326);
}

.wbk6ucn9c {
  d: path("M9.401 15.834a2.173 2.173 0 1 0 0-4.347a2.173 2.173 0 0 0 0 4.347");
}

.wdg9peb-j {
  fill: var(--svg-color--664a4a, #664A4A);
  d: path("m18.811 8.099l-1.767.325a.853.853 0 1 1-.155-1.692h2.902c1.716 0 2.284 1.73 2.353 2.32a3.9 3.9 0 0 0-3.333-.953");
}

.wh0vrhbzi {
  stop-color: var(--svg-color--ca9f8c, #CA9F8C);
  stop-opacity: 0;
}

.wlzou1bho {
  stop-color: var(--svg-color--814e62, #814E62);
}

.wmtrstb6j {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M16.912 18.301c-.958-.557-1.98-.232-2.36-.002a.275.275 0 1 1-.284-.471c.484-.291 1.729-.695 2.92-.002a.275.275 0 0 1-.276.475Z");
}

.wuqjd3b5z {
  stop-color: var(--svg-color--442534, #442534);
}

.x7431zb1g {
  stop-color: var(--svg-color--3e2125, #3E2125);
  stop-opacity: 0;
}

.xbuk-xbxm {
  stop-color: var(--svg-color--7f584b, #7F584B);
}

.xqzyuky4n {
  stop-color: var(--svg-color--b28279, #B28279);
}

.xs9vt_bzp {
  stop-color: var(--svg-color--815553, #815553);
  stop-opacity: 0;
}

.xvq3mubqy {
  stop-color: var(--svg-color--261326, #261326);
  stop-opacity: 0;
}

.y3gk9pbvh {
  stop-color: var(--svg-color--634945, #634945);
}

.y81s-xb2w {
  fill: var(--svg-color--383034, #383034);
  d: path("M17.273 12.892c.358-.63.903-1.128 2.076-1.128c.514 0 1.01.142 1.45.498c.363.293.314.668.033.809l-.751.429c-.88-.285-1.854-.323-2.808-.608");
}

.ye9jsebph {
  fill: var(--svg-color--b38578, #B38578);
  d: path("m15.214 13.173l-.718 2.296a.728.728 0 0 0 .703.945h1.062a.73.73 0 0 0 .704-.945l-.718-2.296c-.154-.509-.872-.509-1.033 0");
}

.yiz6fvgdb {
  stop-color: var(--svg-color--cca58b, #CCA58B);
}

.ynan09_5d {
  d: path("M19.754 13.257a1.14 1.14 0 0 0-.312-.625l-.351.385l.158.308z");
}

.ysga7wb0w {
  stop-color: var(--svg-color--25131c, #25131C);
  stop-opacity: 0;
}

.yuyqets-n {
  d: path("M18.68 12.21a1.205 1.205 0 0 1 1.162 1.523h-2.329a1.2 1.2 0 0 1-.044-.318a1.21 1.21 0 0 1 1.211-1.205");
}

.z4kepib_k {
  cx: 12.416px;
  cy: 12.725px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.526px;
  ry: 0.266px;
}

.zemyxxbjg {
  stop-color: var(--svg-color--8f5c65, #8F5C65);
}

</style>
