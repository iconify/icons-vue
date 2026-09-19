<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iea667b)"><path fill="url(#ix2avQe)" class="fvypn-l2t"/></g><g filter="url(#iXEROdc)"><path class="bzuv3-bsa"/></g><path fill="url(#iyiZfXb)" class="nyy65wbma"/><path fill="url(#iaCIyke)" class="nyy65wbma"/><path fill="url(#ij4pNKc)" class="nyy65wbma"/><path fill="url(#i7s5dnb)" class="yd9d31b9u"/><path fill="url(#i1cmBpb)" class="k-09pt2nk"/><circle fill="url(#iQfmHMc)" class="qxp_99x3x"/><g filter="url(#i9tUD0d)"><circle fill="url(#iZ8hWSc)" class="y-df1ibxk"/></g><circle class="xl3l0pymg"/><g filter="url(#iCJj9Rc)"><circle class="f-1-c4bqu"/></g><path class="o8eu7tk1w"/><path fill="url(#iDdveVd)" class="x5nk9ib3y"/><g filter="url(#iZXncTd)"><path fill="url(#i9NRrUr)" class="hja5svbqn"/><path fill="url(#iTUkPVc)" class="hja5svbqn"/><path fill="url(#ihjF4ac)" class="hja5svbqn"/><path fill="url(#iGv8nwE)" class="hja5svbqn"/></g><g filter="url(#i6DWUCb)"><path fill="url(#iPze4Xc)" class="l_8rcxnim"/></g><g filter="url(#iuXeJ1c)"><circle stroke="url(#iEWqe5Y)" class="slh5hxrid"/></g><circle class="fe2sy7ihc"/><g filter="url(#id8W86d)"><path class="m60c0yvpa"/></g><g filter="url(#ij4P35d)"><path class="eta6w_bxh"/><path fill="url(#i6fR27E)" class="pwqh2_b9m"/></g><path fill="url(#i7QRwLb)" transform="rotate(45.489 14.576 13.47)" class="omsy-ibgn"/><path fill="url(#iMD5S7T)" transform="rotate(45.489 14.576 13.47)" class="omsy-ibgn"/><path fill="url(#ifa0Mde)" class="amcwihbnq"/><path fill="url(#i7leCly)" class="amcwihbnq"/><path fill="url(#iO0QQvX)" class="amcwihbnq"/><path class="u0dwkdmsq"/><path fill="url(#ilOOBmK)" class="valjk-fzx"/><path fill="url(#ihaWgrC)" class="valjk-fzx"/><path fill="url(#igz078c)" class="valjk-fzx"/><path fill="url(#iwqq1xe)" stroke="url(#isY0Rcc)" class="pvk15cbmg"/><path clip-rule="evenodd" class="y430tsild"/><g filter="url(#i31nyjb)"><path clip-rule="evenodd" class="yuey26agv"/></g><path fill="url(#ickI7LF)" stroke="url(#i2rYO6e)" class="ortmeybih"/><path clip-rule="evenodd" class="hy7pkqg_n"/><g filter="url(#ilks0Bb)"><path stroke="url(#ijQSDZo)" clip-rule="evenodd" class="mpopdcfzi"/></g><path fill="url(#iMG1koe)" class="i1_z57b6s"/><path fill="url(#iXg3c1c)" class="i1_z57b6s"/><path fill="url(#iUgxqfb)" class="i1_z57b6s"/><path fill="url(#i4954hc)" class="i1_z57b6s"/><path fill="url(#iN1LREb)" clip-rule="evenodd" class="co79auk3d"/><path clip-rule="evenodd" class="w8tznsbmn"/><path fill="url(#iV2gcje)" clip-rule="evenodd" class="o0fpb1hse"/><path clip-rule="evenodd" class="pve1j5pgx"/><path fill="url(#i7F7ZsE)" clip-rule="evenodd" class="iejpfubas"/><path clip-rule="evenodd" class="b_ap9_bec"/><path fill="url(#iRv2txe)" clip-rule="evenodd" class="g7dfx2pjn"/><g filter="url(#iQgnons)"><path clip-rule="evenodd" class="u2r42m7qy"/></g><path fill="url(#icsDe8c)" class="vd43esj3f"/><g filter="url(#iUzFVpe)"><path class="prllevbrd"/></g><defs><radialGradient id="iyiZfXb" cx="0" cy="0" r="1" gradientTransform="matrix(-2.55405 -7.26436 11.24805 -3.95466 24.764 22.229)" gradientUnits="userSpaceOnUse"><stop class="d182yby2y"/><stop offset="1" class="uj2c1hb5l"/></radialGradient><radialGradient id="iaCIyke" cx="0" cy="0" r="1" gradientTransform="matrix(5.40625 1.9375 -3.91835 10.93347 16.64 17.668)" gradientUnits="userSpaceOnUse"><stop class="tl15jfz0v"/><stop offset="1" class="hgg_sehjj"/></radialGradient><radialGradient id="ij4pNKc" cx="0" cy="0" r="1" gradientTransform="matrix(-.20312 .59375 -4.82693 -1.65131 22.031 14.886)" gradientUnits="userSpaceOnUse"><stop offset=".186" class="vya9e67pv"/><stop offset="1" class="u_jfvlucx"/></radialGradient><radialGradient id="i7s5dnb" cx="0" cy="0" r="1" gradientTransform="matrix(-.53125 .61718 -2.20347 -1.8967 13.602 18.808)" gradientUnits="userSpaceOnUse"><stop offset=".324" class="gpjywxbbc"/><stop offset="1" class="rhjfe48sn"/></radialGradient><radialGradient id="i1cmBpb" cx="0" cy="0" r="1" gradientTransform="matrix(.46118 -.42969 .6423 .68937 19.115 13.24)" gradientUnits="userSpaceOnUse"><stop offset=".311" class="hm5g_l6bp"/><stop offset="1" class="l_vvloedc"/></radialGradient><radialGradient id="iQfmHMc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.01562 .92188 -.5107 -.56264 18.654 11.248)" gradientUnits="userSpaceOnUse"><stop offset=".011" class="bozcytboc"/><stop offset="1" class="sl3bkxb0j"/></radialGradient><radialGradient id="iZ8hWSc" cx="0" cy="0" r="1" gradientTransform="matrix(.32031 -.30469 .39566 .41595 17.912 11.837)" gradientUnits="userSpaceOnUse"><stop class="aqrvmac3i"/><stop offset="1" class="qifaklbkc"/></radialGradient><radialGradient id="iTUkPVc" cx="0" cy="0" r="1" gradientTransform="matrix(1.84375 5.88499 -6.78343 2.12523 15.36 14.043)" gradientUnits="userSpaceOnUse"><stop offset=".545" class="zhkyw63vh"/><stop offset="1" class="vwetdeble"/></radialGradient><radialGradient id="ihjF4ac" cx="0" cy="0" r="1" gradientTransform="matrix(1.43751 1.34374 -1.37698 1.47307 15.888 13.232)" gradientUnits="userSpaceOnUse"><stop offset=".277" class="nnbo53bfv"/><stop offset="1" class="oye5tcbbb"/></radialGradient><radialGradient id="iGv8nwE" cx="0" cy="0" r="1" gradientTransform="matrix(1.27128 1.07818 -.89068 1.0502 13.433 15.386)" gradientUnits="userSpaceOnUse"><stop offset=".422" class="wstn6lblo"/><stop offset="1" class="pffxlnw2p"/></radialGradient><radialGradient id="i6fR27E" cx="0" cy="0" r="1" gradientTransform="rotate(135.14 5.036 10.967)scale(.85969 .22297)" gradientUnits="userSpaceOnUse"><stop offset=".254" class="dg0-lwyyf"/><stop offset="1" class="d94uojbbb"/></radialGradient><radialGradient id="iMD5S7T" cx="0" cy="0" r="1" gradientTransform="rotate(90.613 .826 14.098)scale(.28732 .60402)" gradientUnits="userSpaceOnUse"><stop offset=".649" class="wjyjhxryd"/><stop offset="1" class="y01zyrbyt"/></radialGradient><radialGradient id="ilOOBmK" cx="0" cy="0" r="1" gradientTransform="matrix(-.46094 .29687 -.34413 -.53431 11.951 16.225)" gradientUnits="userSpaceOnUse"><stop offset=".214" class="y84i3jbqp"/><stop offset="1" class="mn36x_bue"/></radialGradient><radialGradient id="isY0Rcc" cx="0" cy="0" r="1" gradientTransform="rotate(133.409 5.777 9.594)scale(1.9895 1.30599)" gradientUnits="userSpaceOnUse"><stop class="y_4rzacqk"/><stop offset=".96" class="td_1nybnc"/></radialGradient><radialGradient id="i2rYO6e" cx="0" cy="0" r="1" gradientTransform="matrix(-1.0078 1.59375 -1.27162 -.8041 13.74 14.85)" gradientUnits="userSpaceOnUse"><stop class="y_4rzacqk"/><stop offset="1" class="psw8g7_uy"/></radialGradient><radialGradient id="iMG1koe" cx="0" cy="0" r="1" gradientTransform="matrix(-2.75 -2.62501 3.8318 -4.01424 14.203 11.761)" gradientUnits="userSpaceOnUse"><stop class="taiuw254n"/><stop offset="1" class="wk7-7rb8w"/></radialGradient><radialGradient id="iXg3c1c" cx="0" cy="0" r="1" gradientTransform="rotate(-157.729 8.545 4.784)scale(6.59658 10.6884)" gradientUnits="userSpaceOnUse"><stop offset=".546" class="g4b5macvs"/><stop offset="1" class="s4_cj8byh"/></radialGradient><radialGradient id="iUgxqfb" cx="0" cy="0" r="1" gradientTransform="matrix(.20313 -1.98437 .81115 .08303 8.766 13.605)" gradientUnits="userSpaceOnUse"><stop class="mo87chbhx"/><stop offset="1" class="bbj4eu2oj"/></radialGradient><radialGradient id="iV2gcje" cx="0" cy="0" r="1" gradientTransform="rotate(146.787 3.543 4.261)scale(3.43755 1.60167)" gradientUnits="userSpaceOnUse"><stop offset=".402" class="bhsim2zfs"/><stop offset="1" class="k03nt5bji"/></radialGradient><radialGradient id="i7F7ZsE" cx="0" cy="0" r="1" gradientTransform="matrix(-3.21274 2.13195 -.99864 -1.5049 8.962 7.009)" gradientUnits="userSpaceOnUse"><stop offset=".402" class="bhsim2zfs"/><stop offset="1" class="k03nt5bji"/></radialGradient><radialGradient id="iRv2txe" cx="0" cy="0" r="1" gradientTransform="rotate(144.615 3.362 5.202)scale(3.29193 1.58011)" gradientUnits="userSpaceOnUse"><stop offset=".402" class="bhsim2zfs"/><stop offset="1" class="k03nt5bji"/></radialGradient><radialGradient id="icsDe8c" cx="0" cy="0" r="1" gradientTransform="matrix(5.125 .375 -.21772 2.97553 10.642 4.082)" gradientUnits="userSpaceOnUse"><stop offset=".344" class="q4wdhb0gi"/><stop offset="1" class="hl9fr5bol"/></radialGradient><linearGradient id="ix2avQe" x1="26.833" x2="2.047" y1="16.537" y2="16.537" gradientUnits="userSpaceOnUse"><stop class="q8sgc5k5k"/><stop offset="1" class="o5v952b3t"/></linearGradient><linearGradient id="iDdveVd" x1="16.656" x2="16.93" y1="10.277" y2="10.808" gradientUnits="userSpaceOnUse"><stop offset=".18" class="o5x7ihb3q"/><stop offset=".592" class="kgrbxd6rk"/></linearGradient><linearGradient id="i9NRrUr" x1="19.016" x2="14.391" y1="13.793" y2="19.293" gradientUnits="userSpaceOnUse"><stop class="qt5azf8qn"/><stop offset=".886" class="hy9zkkbug"/></linearGradient><linearGradient id="iPze4Xc" x1="26.833" x2="2.047" y1="23.599" y2="23.599" gradientUnits="userSpaceOnUse"><stop class="t8k4gwbbc"/><stop offset="1" class="kpw0uhrkg"/></linearGradient><linearGradient id="iEWqe5Y" x1="17.219" x2="17.188" y1="17.605" y2="15.699" gradientUnits="userSpaceOnUse"><stop class="awrv2obtn"/><stop offset="1" class="cf85y0bfp"/></linearGradient><linearGradient id="i7QRwLb" x1="14.945" x2="14.954" y1="13.643" y2="14.593" gradientUnits="userSpaceOnUse"><stop class="uhfoyqb3x"/><stop offset="1" class="eb0haibji"/></linearGradient><linearGradient id="ifa0Mde" x1="16.334" x2="17.49" y1="11.365" y2="11.154" gradientUnits="userSpaceOnUse"><stop class="nd7thpbgb"/><stop offset="1" class="fs5c4ebko"/></linearGradient><linearGradient id="i7leCly" x1="16.734" x2="16.848" y1="10.668" y2="10.746" gradientUnits="userSpaceOnUse"><stop offset=".354" class="r7rn_bcmx"/><stop offset="1" class="ht-1xqb8g"/></linearGradient><linearGradient id="iO0QQvX" x1="17.383" x2="17.301" y1="11.085" y2="11.03" gradientUnits="userSpaceOnUse"><stop class="hb9tx9b6i"/><stop offset="1" class="ppgh7wbyg"/></linearGradient><linearGradient id="ihaWgrC" x1="11.422" x2="11.305" y1="17.011" y2="16.828" gradientUnits="userSpaceOnUse"><stop offset=".145" class="u8ol5ho1k"/><stop offset="1" class="bbcrpz64i"/></linearGradient><linearGradient id="igz078c" x1="10.984" x2="11.027" y1="16.382" y2="16.453" gradientUnits="userSpaceOnUse"><stop class="bwf4x3cld"/><stop offset="1" class="a5orf1efs"/></linearGradient><linearGradient id="iwqq1xe" x1="16.467" x2="15.279" y1="12.092" y2="13.326" gradientUnits="userSpaceOnUse"><stop class="z1dq245it"/><stop offset="1" class="jzcp_rb0i"/></linearGradient><linearGradient id="ickI7LF" x1="13.678" x2="12.49" y1="14.85" y2="16.084" gradientUnits="userSpaceOnUse"><stop class="z1dq245it"/><stop offset="1" class="jzcp_rb0i"/></linearGradient><linearGradient id="ijQSDZo" x1="14.269" x2="12.127" y1="14.597" y2="16.643" gradientUnits="userSpaceOnUse"><stop offset=".096" class="qi1y9bzby"/><stop offset=".322" class="f-nlkoezi"/><stop offset=".768" class="qi1y9bzby"/></linearGradient><linearGradient id="i4954hc" x1="13.703" x2="13.641" y1="12.39" y2="12.332" gradientUnits="userSpaceOnUse"><stop class="d1-v2bc1s"/><stop offset="1" class="lt8u35u8x"/></linearGradient><linearGradient id="iN1LREb" x1="8.172" x2="10.923" y1="3.814" y2="3.556" gradientUnits="userSpaceOnUse"><stop class="bpe3vtb4h"/><stop offset="1" class="q4wdhb0gi"/></linearGradient><filter id="iea667b" width="28.306" height="9.762" x="1.847" y="12.121" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.32549 0 0 0 0 0.729412 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23153"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.247059 0 0 0 0 0.584314 0 0 0 0 0.854902 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_23153" result="effect2_innerShadow_3987_23153"/></filter><filter id="iXEROdc" width="19.969" height="19.969" x="10.642" y="1.769" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1.25" dy="-1.25"/><feGaussianBlur stdDeviation="1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.411765 0 0 0 0 0.25098 0 0 0 0 0.262745 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23153"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.396078 0 0 0 0 0.235294 0 0 0 0 0.235294 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_23153" result="effect2_innerShadow_3987_23153"/></filter><filter id="i9tUD0d" width="2.053" height="2.053" x="16.759" y="10.88" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23153" stdDeviation=".075"/></filter><filter id="iCJj9Rc" width="2.044" height="2.044" x="11.179" y="16.474" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23153" stdDeviation=".1"/></filter><filter id="iZXncTd" width="11.327" height="11.381" x="8.984" y="8.547" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.15"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.376471 0 0 0 0 0.266667 0 0 0 0 0.47451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23153"/></filter><filter id="i6DWUCb" width="28.306" height="9.762" x="1.847" y="19.183" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.301961 0 0 0 0 0.580392 0 0 0 0 0.87451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23153"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.207843 0 0 0 0 0.482353 0 0 0 0 0.772549 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_23153" result="effect2_innerShadow_3987_23153"/></filter><filter id="iuXeJ1c" width="2.217" height="2.217" x="15.887" y="15.567" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23153" stdDeviation=".1"/></filter><filter id="id8W86d" width="3.106" height="3.164" x="13.726" y="13.832" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23153" stdDeviation=".25"/></filter><filter id="ij4P35d" width="2.203" height="2.458" x="14.338" y="13.86" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.3"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.439216 0 0 0 0 0.262745 0 0 0 0 0.309804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23153"/><feGaussianBlur result="effect2_foregroundBlur_3987_23153" stdDeviation=".05"/></filter><filter id="i31nyjb" width="2.872" height="2.874" x="14.46" y="11.291" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23153" stdDeviation=".075"/></filter><filter id="ilks0Bb" width="2.872" height="2.874" x="11.68" y="14.086" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23153" stdDeviation=".075"/></filter><filter id="iQgnons" width="4.333" height="3.319" x="7.677" y="5.32" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.4"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.458824 0 0 0 0 0.270588 0 0 0 0 0.258824 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23153"/></filter><filter id="iUzFVpe" width="10.371" height="13.323" x="17.499" y="4.703" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23153" stdDeviation=".35"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:person-swimming-medium-dark" /></template>
<style>
.a5orf1efs {
  stop-color: var(--svg-color--504b5b, #504B5B);
  stop-opacity: 0;
}

.amcwihbnq {
  d: path("M17.065 10.228a.1.1 0 0 1 .139-.027l.439.298a.1.1 0 0 1 .027.139l-.84 1.239l-.605-.41z");
}

.aqrvmac3i {
  stop-color: var(--svg-color--806258, #806258);
}

.awrv2obtn {
  stop-color: var(--svg-color--8b686a, #8B686A);
}

.b_ap9_bec {
  fill: var(--svg-color--775248, #775248);
  fill-rule: evenodd;
  d: path("M11.379 5.532a.663.663 0 0 1-.635.69c-1.183.05-2.097.94-2.665 1.87a.662.662 0 1 1-1.131-.69c.651-1.067 1.893-2.427 3.74-2.504a.663.663 0 0 1 .69.634");
}

.bbcrpz64i {
  stop-color: var(--svg-color--443873, #443873);
  stop-opacity: 0;
}

.bbj4eu2oj {
  stop-color: var(--svg-color--dd617e, #DD617E);
  stop-opacity: 0;
}

.bhsim2zfs {
  stop-color: var(--svg-color--683859, #683859);
}

.bozcytboc {
  stop-color: var(--svg-color--94776d, #94776D);
}

.bpe3vtb4h {
  stop-color: var(--svg-color--6e4e42, #6E4E42);
}

.bwf4x3cld {
  stop-color: var(--svg-color--504b5b, #504B5B);
}

.bzuv3-bsa {
  fill: var(--svg-color--876253, #876253);
  d: path("M10.642 7.02h4.828a4 4 0 0 1 3.602 2.26l6.164 12.458l4.125-.594L22.674 7.54a8 8 0 0 0-7.204-4.52h-4.43z");
}

.cf85y0bfp {
  stop-color: var(--svg-color--8c5961, #8C5961);
}

.co79auk3d {
  fill-rule: evenodd;
  d: path("M9.936 4.43c-.557.043-1.037.102-1.262.16a.66.66 0 0 1-.804-.49a.673.673 0 0 1 .48-.816c.836-.213 1.78-.266 2.642-.266c.366 0 .647.287.647.659c0 .371.106.686-.26.686c-.345 0-.9.024-1.443.066");
}

.d1-v2bc1s {
  stop-color: var(--svg-color--f64a6a, #F64A6A);
}

.d182yby2y {
  stop-color: var(--svg-color--946f6a, #946F6A);
}

.d94uojbbb {
  stop-color: var(--svg-color--98766e, #98766E);
  stop-opacity: 0;
}

.dg0-lwyyf {
  stop-color: var(--svg-color--98766e, #98766E);
}

.eb0haibji {
  stop-color: var(--svg-color--413251, #413251);
}

.eta6w_bxh {
  fill: var(--svg-color--7d5650, #7D5650);
  d: path("m15.22 15.997l-.782-1.556l.29-.281l1.51.852a.4.4 0 0 1 .084.633l-.465.457a.4.4 0 0 1-.638-.105");
}

.f-1-c4bqu {
  cx: 12.201px;
  cy: 17.496px;
  r: 0.822px;
  fill: var(--svg-color--552b3a, #552B3A);
}

.f-nlkoezi {
  stop-color: var(--svg-color--5f5669, #5F5669);
  stop-opacity: 0;
}

.fe2sy7ihc {
  cx: 16.996px;
  cy: 16.675px;
  r: 0.809px;
  fill: var(--svg-color--87014e, #87014E);
}

.fs5c4ebko {
  stop-color: var(--svg-color--4c4055, #4C4055);
}

.ft5dv1b6b {
  fill: none;
}

.fvypn-l2t {
  d: path("M3.922 12.12c-.975 0-1.656.49-1.875.735v9.027h27.906v-8.87l-.003-.004c-.623-.545-1.015-.887-2.2-.887c-.906 0-1.67.67-2.05 1.003c-.261.224-.94.637-1.864.637s-1.469-.406-2.07-.906c-.27-.224-.952-.734-1.914-.734c-.963 0-1.857.666-2.165 1c-.244.224-.718.64-1.87.64c-.794 0-1.396-.35-1.614-.562c-.37-.36-1.133-1.078-2.312-1.078c-.975 0-1.54.468-1.907.78c-.367.313-1.006.892-2.093.892c-.985 0-1.585-.5-1.915-.775l-.007-.007c-.276-.297-1.072-.89-2.047-.89");
}

.g4b5macvs {
  stop-color: var(--svg-color--ad525e, #AD525E);
  stop-opacity: 0;
}

.g7dfx2pjn {
  fill-rule: evenodd;
  d: path("M11.379 5.532a.663.663 0 0 1-.635.69c-1.183.05-2.097.94-2.665 1.87a.662.662 0 1 1-1.131-.69c.651-1.067 1.893-2.427 3.74-2.504a.663.663 0 0 1 .69.634");
}

.gpjywxbbc {
  stop-color: var(--svg-color--140a1e, #140A1E);
}

.hb9tx9b6i {
  stop-color: var(--svg-color--574e60, #574E60);
}

.hgg_sehjj {
  stop-color: var(--svg-color--7a5249, #7A5249);
  stop-opacity: 0;
}

.hja5svbqn {
  d: path("m8.984 14.798l6.11-6.101l4.26 4.74a3.15 3.15 0 0 1-.079 4.296l-1.195 1.235a3.15 3.15 0 0 1-4.39.134z");
}

.hl9fr5bol {
  stop-color: var(--svg-color--765148, #765148);
  stop-opacity: 0;
}

.hm5g_l6bp {
  stop-color: var(--svg-color--373334, #373334);
}

.ht-1xqb8g {
  stop-color: var(--svg-color--403044, #403044);
  stop-opacity: 0;
}

.hy7pkqg_n {
  fill: var(--svg-color--412e4c, #412E4C);
  fill-rule: evenodd;
  d: path("m14.144 16.13l-.488.477a1.181 1.181 0 1 1-1.65-1.69l.487-.477a1.181 1.181 0 1 1 1.65 1.69m-.238-1.418a.82.82 0 0 0-1.162-.014l-.487.476a.821.821 0 1 0 1.148 1.175l.487-.476a.82.82 0 0 0 .014-1.162");
}

.hy9zkkbug {
  stop-color: var(--svg-color--6b3c54, #6B3C54);
}

.i1_z57b6s {
  d: path("M9.475 15.705c-1.367-1.367-1.202-3.537.236-5.17l1.21-1.203c1.556-1.414 3.79-1.595 5.156-.229l.317.318a.2.2 0 0 1 0 .282l-6.319 6.32a.2.2 0 0 1-.282 0z");
}

.iejpfubas {
  fill-rule: evenodd;
  d: path("M11.67 4.709a.663.663 0 0 1-.607.713c-.639.05-1.95.359-2.427.803c-.482.448-.861 1.004-1.156 1.487a.663.663 0 0 1-1.131-.69c.314-.516.769-1.195 1.385-1.768c.62-.576 1.5-1.153 3.223-1.153c.366 0 .684.243.713.608");
}

.jzcp_rb0i {
  stop-color: var(--svg-color--4893e1, #4893E1);
}

.k-09pt2nk {
  d: path("m19.598 12.707l-.614-.668l-.785.73l1.664 1.91c.375-.844.047-1.633-.265-1.972");
}

.k03nt5bji {
  stop-color: var(--svg-color--6d4c45, #6D4C45);
  stop-opacity: 0;
}

.kgrbxd6rk {
  stop-color: var(--svg-color--0a010d, #0A010D);
}

.kpw0uhrkg {
  stop-color: var(--svg-color--4184e7, #4184E7);
}

.l_8rcxnim {
  d: path("M3.922 19.183c-.975 0-1.656.49-1.875.735v9.027h27.906v-8.871l-.003-.003c-.623-.545-1.015-.888-2.2-.888c-.906 0-1.67.67-2.05 1.003v.001c-.261.224-.94.637-1.864.637s-1.469-.407-2.07-.907c-.27-.223-.952-.734-1.914-.734c-.963 0-1.857.667-2.165 1c-.244.224-.718.64-1.87.64c-.794 0-1.396-.35-1.614-.562c-.37-.36-1.133-1.078-2.312-1.078c-.975 0-1.54.469-1.907.781s-1.006.891-2.093.891c-.985 0-1.585-.5-1.915-.775l-.007-.006c-.276-.297-1.072-.89-2.047-.89");
}

.l_vvloedc {
  stop-color: var(--svg-color--110c12, #110C12);
}

.lt8u35u8x {
  stop-color: var(--svg-color--f64a6a, #F64A6A);
  stop-opacity: 0;
}

.m60c0yvpa {
  fill: var(--svg-color--724056, #724056);
  d: path("m15.047 16.264l-.821-1.636l.304-.296l1.588.896a.42.42 0 0 1 .088.666l-.488.481a.42.42 0 0 1-.67-.111");
}

.mn36x_bue {
  stop-color: var(--svg-color--483e5b, #483E5B);
  stop-opacity: 0;
}

.mo87chbhx {
  stop-color: var(--svg-color--dd617e, #DD617E);
}

.mpopdcfzi {
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M14.077 14.586c-.364-.373-1-.41-1.373-.046l-.56.547c-.372.363-.34.99.024 1.362s.977.43 1.35.067l.559-.546c.372-.364.363-1.012 0-1.384Z");
}

.nd7thpbgb {
  stop-color: var(--svg-color--574c62, #574C62);
}

.nnbo53bfv {
  stop-color: var(--svg-color--623838, #623838);
}

.nyy65wbma {
  d: path("M17.313 16.543c-1.688 1.15-3.224 3.25-3.782 4.156c3.25 2.162 7.927 2.172 9.86 1.906l6.53-2.266c-.765-1.304-2.036-2.52-2.53-3l-5.407-2.375c-.937 0-2.562.141-4.672 1.579");
}

.o0fpb1hse {
  fill-rule: evenodd;
  d: path("M11.266 3.927a.663.663 0 0 1-.608.713c-1.395.112-2.487 1.077-3.036 1.864a.663.663 0 0 1-1.087-.759c.678-.97 2.085-2.271 4.018-2.425a.663.663 0 0 1 .713.607");
}

.o5v952b3t {
  stop-color: var(--svg-color--3ea5fe, #3EA5FE);
}

.o5x7ihb3q {
  stop-color: var(--svg-color--312b2d, #312B2D);
}

.o8eu7tk1w {
  fill: var(--svg-color--241a3a, #241A3A);
  d: path("M10.762 16.714L9.922 16l.293-.555l1.137.887z");
}

.omsy-ibgn {
  d: path("M14.576 13.47h.758v1.123h-.758z");
}

.ortmeybih {
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("m13.805 15.784l-.488.476a.696.696 0 0 1-.973-.997l.488-.476a.696.696 0 1 1 .973.997Z");
}

.oye5tcbbb {
  stop-color: var(--svg-color--7a564e, #7A564E);
  stop-opacity: 0;
}

.pffxlnw2p {
  stop-color: var(--svg-color--5c3440, #5C3440);
  stop-opacity: 0;
}

.ppgh7wbyg {
  stop-color: var(--svg-color--574e60, #574E60);
  stop-opacity: 0;
}

.prllevbrd {
  fill: var(--svg-color--9c766f, #9C766F);
  d: path("M20.637 7.451c-.675-1.475-1.907-1.969-2.438-2.031c1.469-.156 2.672.789 3.156 1.656l5.815 10.25l-2.533-1.281c-1.052-2.25-3.325-7.119-4-8.594");
}

.psw8g7_uy {
  stop-color: var(--svg-color--2c6fb5, #2C6FB5);
}

.pve1j5pgx {
  fill: var(--svg-color--775248, #775248);
  fill-rule: evenodd;
  d: path("M11.67 4.709a.663.663 0 0 1-.607.713c-.639.05-1.95.359-2.427.803c-.482.448-.861 1.004-1.156 1.487a.663.663 0 0 1-1.131-.69c.314-.516.769-1.195 1.385-1.768c.62-.576 1.5-1.153 3.223-1.153c.366 0 .684.243.713.608");
}

.pvk15cbmg {
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("m16.594 13.026l-.488.476a.696.696 0 1 1-.973-.997l.488-.476a.696.696 0 1 1 .973.997Z");
}

.pwqh2_b9m {
  d: path("m15.22 15.997l-.782-1.556l.29-.281l1.51.852a.4.4 0 0 1 .084.633l-.465.457a.4.4 0 0 1-.638-.105");
}

.q4wdhb0gi {
  stop-color: var(--svg-color--765148, #765148);
}

.q8sgc5k5k {
  stop-color: var(--svg-color--40aafe, #40AAFE);
}

.qi1y9bzby {
  stop-color: var(--svg-color--5f5669, #5F5669);
}

.qifaklbkc {
  stop-color: var(--svg-color--754c40, #754C40);
}

.qt5azf8qn {
  stop-color: var(--svg-color--a27c72, #A27C72);
}

.qxp_99x3x {
  cx: 17.785px;
  cy: 11.907px;
  r: 1.296px;
}

.r7rn_bcmx {
  stop-color: var(--svg-color--403044, #403044);
}

.rhjfe48sn {
  stop-color: var(--svg-color--262442, #262442);
}

.s4_cj8byh {
  stop-color: var(--svg-color--ad525e, #AD525E);
}

.sl3bkxb0j {
  stop-color: var(--svg-color--76554d, #76554D);
}

.slh5hxrid {
  cx: 16.996px;
  cy: 16.675px;
  r: 0.809px;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
}

.t8k4gwbbc {
  stop-color: var(--svg-color--3f90f0, #3F90F0);
}

.taiuw254n {
  stop-color: var(--svg-color--fb5684, #FB5684);
}

.td_1nybnc {
  stop-color: var(--svg-color--1f64c4, #1F64C4);
}

.tl15jfz0v {
  stop-color: var(--svg-color--553438, #553438);
}

.u_jfvlucx {
  stop-color: var(--svg-color--5d4239, #5D4239);
  stop-opacity: 0;
}

.u0dwkdmsq {
  fill: var(--svg-color--4e496a, #4E496A);
  d: path("M10.925 17.3a.1.1 0 0 1-.138-.029l-.29-.444a.1.1 0 0 1 .03-.139l1.253-.817l.4.612z");
}

.u2r42m7qy {
  fill: var(--svg-color--724d47, #724D47);
  fill-rule: evenodd;
  d: path("M11.348 7.019c-.585 0-1.22.253-1.659.552c-.31.21-.668.602-.82.805a.662.662 0 1 1-1.058-.8c.202-.266.661-.78 1.133-1.1c.63-.429 1.52-.756 2.404-.756c.366 0 .662.297.662.662s-.296.637-.662.637");
}

.u8ol5ho1k {
  stop-color: var(--svg-color--443873, #443873);
}

.uhfoyqb3x {
  stop-color: var(--svg-color--52475d, #52475D);
}

.uj2c1hb5l {
  stop-color: var(--svg-color--764e4a, #764E4A);
}

.valjk-fzx {
  d: path("M10.925 17.3a.1.1 0 0 1-.138-.029l-.29-.444a.1.1 0 0 1 .03-.139l1.253-.817l.4.612z");
}

.vd43esj3f {
  d: path("M10.642 7.02h4.828a4 4 0 0 1 3.602 2.26l6.164 12.458l4.125-.594L22.674 7.54a8 8 0 0 0-7.204-4.52h-4.457z");
}

.vwetdeble {
  stop-color: var(--svg-color--5b2c42, #5B2C42);
}

.vya9e67pv {
  stop-color: var(--svg-color--5d4239, #5D4239);
}

.w8tznsbmn {
  fill: var(--svg-color--775248, #775248);
  fill-rule: evenodd;
  d: path("M11.266 3.927a.663.663 0 0 1-.608.713c-1.395.112-2.487 1.077-3.036 1.864a.663.663 0 0 1-1.087-.759c.678-.97 2.085-2.271 4.018-2.425a.663.663 0 0 1 .713.607");
}

.wjyjhxryd {
  stop-color: var(--svg-color--453b50, #453B50);
}

.wk7-7rb8w {
  stop-color: var(--svg-color--e12e6e, #E12E6E);
}

.wstn6lblo {
  stop-color: var(--svg-color--5c3440, #5C3440);
}

.x5nk9ib3y {
  d: path("m17.133 10.382l-.758-.742l-.844.301c.401.427 1.206 1.276 1.215 1.258z");
}

.xl3l0pymg {
  cx: 12.201px;
  cy: 17.496px;
  r: 1.296px;
  fill: var(--svg-color--5d2f4e, #5D2F4E);
}

.y_4rzacqk {
  stop-color: var(--svg-color--54abec, #54ABEC);
}

.y-df1ibxk {
  cx: 17.785px;
  cy: 11.907px;
  r: 0.877px;
}

.y01zyrbyt {
  stop-color: var(--svg-color--453b50, #453B50);
  stop-opacity: 0;
}

.y430tsild {
  fill: var(--svg-color--412e4c, #412E4C);
  fill-rule: evenodd;
  d: path("m16.933 13.373l-.488.476a1.181 1.181 0 0 1-1.65-1.69l.487-.477a1.181 1.181 0 0 1 1.65 1.69m-.238-1.42a.82.82 0 0 0-1.162-.013l-.487.476a.821.821 0 0 0 1.148 1.175l.487-.476a.82.82 0 0 0 .014-1.161");
}

.y84i3jbqp {
  stop-color: var(--svg-color--483e5b, #483E5B);
}

.yd9d31b9u {
  d: path("m12.973 19.261l-.614-.57l.235-.937l2.14 1.87c-.937.266-1.493-.13-1.761-.363");
}

.yuey26agv {
  stroke: var(--svg-color--5c4c6d, #5C4C6D);
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M16.857 11.79c-.364-.371-1-.408-1.373-.044l-.559.546c-.373.364-.34.99.024 1.362c.363.373.976.431 1.348.068l.56-.547c.372-.363.364-1.012 0-1.384Z");
}

.z1dq245it {
  stop-color: var(--svg-color--479ded, #479DED);
}

.zhkyw63vh {
  stop-color: var(--svg-color--825458, #825458);
  stop-opacity: 0;
}

</style>
