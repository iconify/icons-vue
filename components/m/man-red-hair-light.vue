<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iEUGxMl)"><circle fill="url(#ioyLHBb)" class="v-30-7x4s"/></g><g filter="url(#iCA8Zab)"><circle fill="url(#icvss3d)" class="v-30-7x4s"/></g><g filter="url(#iDuzalc)"><circle fill="url(#iAghpsb)" class="s1mz5y7pt"/></g><g filter="url(#i2zRAad)"><circle fill="url(#ijKHY3c)" class="s72pw74ms"/><circle fill="url(#iex045b)" class="s72pw74ms"/></g><g filter="url(#iR5IQ3b)"><circle class="gcj4afbgh"/><circle fill="url(#iBPwyme)" class="pbw_1oblv"/><circle fill="url(#iAYWuKe)" class="pbw_1oblv"/></g><g filter="url(#ibeKoJc)"><path fill="url(#iwEr8cd)" class="xghyhmb_n"/><path fill="url(#iH2Rx3a)" class="xghyhmb_n"/><path fill="url(#i1wN7jw)" class="xghyhmb_n"/><path fill="url(#iL24Orc)" class="xghyhmb_n"/><path fill="url(#ibuRROb)" class="xghyhmb_n"/><path fill="url(#iE7Omoe)" class="xghyhmb_n"/><path fill="url(#idZwg8C)" class="xghyhmb_n"/></g><g filter="url(#iPxZwwe)"><path fill="url(#iKAsBod)" class="ll5bq8b7t"/></g><g filter="url(#iavNReb)"><path fill="url(#iCbLeig)" class="kdp2zyzxx"/><path fill="url(#iTzc2Me)" class="kdp2zyzxx"/><path fill="url(#iGI9RZk)" class="kdp2zyzxx"/><path fill="url(#iwbcRxe)" class="kdp2zyzxx"/><path fill="url(#iES7Qed)" class="kdp2zyzxx"/><path fill="url(#iGz5fdu)" class="kdp2zyzxx"/></g><path fill="url(#iq0eQKB)" class="kdp2zyzxx"/><path fill="url(#iW4bgAe)" class="kdp2zyzxx"/><path fill="url(#ilyeTsd)" class="kdp2zyzxx"/><g filter="url(#i7tl9be)"><path class="dky7fib-j"/></g><g filter="url(#iAiSVGe)"><path class="ndzxn1lxc"/><path fill="url(#iAc1Jxd)" class="cbq1t5_me"/><path fill="url(#ihv5kbc)" class="cbq1t5_me"/><path fill="url(#ikmfUlc)" class="cbq1t5_me"/><path fill="url(#iaMcaod)" class="cbq1t5_me"/></g><path fill="url(#iAcujHo)" class="cbq1t5_me"/><path stroke="url(#iGsbGPd)" class="vld6k812o"/><g filter="url(#iRnimCb)"><path class="z5ld33bgu"/><path fill="url(#ilCFxZb)" class="ro9l-sbza"/></g><g filter="url(#ipoz7Cc)"><path class="pvp6am2qg"/><path fill="url(#iydC1mb)" class="s_gvjrbyd"/></g><path class="f6czxtz5j"/><path fill="url(#imVZpOb)" class="syqh2sbqs"/><path class="xp9lbpb1d"/><g filter="url(#iujoPER)"><path class="pu69_yu4m"/><path fill="url(#iVJu1Dc)" class="hh__2aceo"/></g><g filter="url(#i7qWeHJ)"><path fill="url(#iBI2wxd)" class="z5h7u4bip"/></g><path class="v3rmoybey"/><path fill="url(#iov9blb)" class="jwnwh9mpl"/><path class="w5wsyh14x"/><g filter="url(#iW2Smpe)"><path fill="url(#ih7Js6z)" class="labizxbgi"/></g><g filter="url(#iCkgLwb)"><ellipse transform="rotate(-27.914 11.367 16.599)" class="e9gbg1d-u"/><ellipse fill="url(#ius6L4b)" transform="rotate(-27.914 11.367 16.599)" class="oufadibrx"/></g><g filter="url(#iupd32d)"><path stroke="url(#iHT3ebd)" class="ca06pugdq"/></g><g filter="url(#i9qYIqo)"><path stroke="url(#ij0Y6hA)" class="n-zw6k8dv"/></g><defs><radialGradient id="ioyLHBb" cx="0" cy="0" r="1" gradientTransform="matrix(3.27255 0 0 5.72699 3.979 18.05)" gradientUnits="userSpaceOnUse"><stop offset=".351" class="n91c-gs8j"/><stop offset="1" class="qo7u-3bcf"/></radialGradient><radialGradient id="icvss3d" cx="0" cy="0" r="1" gradientTransform="matrix(3.27255 0 0 5.72699 3.979 18.05)" gradientUnits="userSpaceOnUse"><stop offset=".351" class="crp6d4bqv"/><stop offset="1" class="lu78seb9e"/></radialGradient><radialGradient id="iex045b" cx="0" cy="0" r="1" gradientTransform="matrix(1.54168 -1.12256 1.28126 1.75963 25.527 17.555)" gradientUnits="userSpaceOnUse"><stop offset=".543" class="wdqn7tq-u"/><stop offset="1" class="r3t82tbzk"/></radialGradient><radialGradient id="iBPwyme" cx="0" cy="0" r="1" gradientTransform="matrix(1.53153 -2.8169 1.64874 .8964 24.756 19.58)" gradientUnits="userSpaceOnUse"><stop offset=".755" class="n7c5lw_4k"/><stop offset=".916" class="bw8j_5egh"/></radialGradient><radialGradient id="iAYWuKe" cx="0" cy="0" r="1" gradientTransform="rotate(44.708 -9.529 39.219)scale(.68036 .87707)" gradientUnits="userSpaceOnUse"><stop class="fa9i5bbvu"/><stop offset="1" class="x8d9utbsu"/></radialGradient><radialGradient id="iwEr8cd" cx="0" cy="0" r="1" gradientTransform="matrix(-14.1844 0 0 -27.6939 24.188 20.366)" gradientUnits="userSpaceOnUse"><stop class="g4x2unb_n"/><stop offset="1" class="pxvs_abtj"/></radialGradient><radialGradient id="i1wN7jw" cx="0" cy="0" r="1" gradientTransform="matrix(0 16.3495 -27.7163 0 17.216 14.236)" gradientUnits="userSpaceOnUse"><stop offset=".652" class="ibem-2huv"/><stop offset="1" class="hil9j9kpd"/></radialGradient><radialGradient id="iL24Orc" cx="0" cy="0" r="1" gradientTransform="matrix(-2.9969 0 0 -3.02146 18.111 17.678)" gradientUnits="userSpaceOnUse"><stop class="dky8lccpu"/><stop offset="1" class="m9zfab8yd"/></radialGradient><radialGradient id="ibuRROb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.5 2.93253 0 20.321 15.74)" gradientUnits="userSpaceOnUse"><stop offset=".237" class="nve4o1bcy"/><stop offset="1" class="lekcnobli"/></radialGradient><radialGradient id="iE7Omoe" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.59375 3.22556 0 11.821 15.616)" gradientUnits="userSpaceOnUse"><stop class="pajtq1t7s"/><stop offset="1" class="k6zwfqo1x"/></radialGradient><radialGradient id="idZwg8C" cx="0" cy="0" r="1" gradientTransform="matrix(-8.16694 4.8677 -4.19823 -7.04371 26.313 10.24)" gradientUnits="userSpaceOnUse"><stop class="z8y6fgvmn"/><stop offset="1" class="ew7jqnj6t"/></radialGradient><radialGradient id="iTzc2Me" cx="0" cy="0" r="1" gradientTransform="rotate(-169.032 11.111 3.06)scale(8.21251 6.30254)" gradientUnits="userSpaceOnUse"><stop offset=".223" class="tzxi8pb6h"/><stop offset="1" class="hmx8eit6p"/></radialGradient><radialGradient id="iGI9RZk" cx="0" cy="0" r="1" gradientTransform="matrix(-.56248 -7.49998 14.07497 -1.05559 26.813 17.01)" gradientUnits="userSpaceOnUse"><stop class="gg3p-v-oi"/><stop offset="1" class="go8dnjb_b"/></radialGradient><radialGradient id="iwbcRxe" cx="0" cy="0" r="1" gradientTransform="matrix(3.8125 -.625 1.78488 10.88777 3.813 11.553)" gradientUnits="userSpaceOnUse"><stop class="zk1gozblh"/><stop offset="1" class="o7liw8bnz"/></radialGradient><radialGradient id="iES7Qed" cx="0" cy="0" r="1" gradientTransform="matrix(1.1875 1.40625 -6.20388 5.23883 7.813 4.803)" gradientUnits="userSpaceOnUse"><stop class="hchmvbcwb"/><stop offset="1" class="ei1bt-b0e"/></radialGradient><radialGradient id="iGz5fdu" cx="0" cy="0" r="1" gradientTransform="rotate(80.538 7.782 11.419)scale(1.61573 2.88964)" gradientUnits="userSpaceOnUse"><stop offset=".173" class="e_h6jabwf"/><stop offset="1" class="moyyndcqm"/></radialGradient><radialGradient id="iq0eQKB" cx="0" cy="0" r="1" gradientTransform="matrix(-.25 -4.59375 1.72724 -.094 8.219 11.803)" gradientUnits="userSpaceOnUse"><stop offset=".169" class="sn-n94bif"/><stop offset="1" class="vu7vn7bhc"/></radialGradient><radialGradient id="iW4bgAe" cx="0" cy="0" r="1" gradientTransform="matrix(-.69638 -4.375 1.72998 -.27536 4.196 11.115)" gradientUnits="userSpaceOnUse"><stop class="sdjph8tjs"/><stop offset="1" class="xhmtc9b9f"/></radialGradient><radialGradient id="ilyeTsd" cx="0" cy="0" r="1" gradientTransform="matrix(1.11615 -6 2.3152 .43068 27.696 14.366)" gradientUnits="userSpaceOnUse"><stop offset=".442" class="t7o6ccjes"/><stop offset="1" class="kd9fr-txf"/></radialGradient><radialGradient id="iaMcaod" cx="0" cy="0" r="1" gradientTransform="matrix(0 .36719 -1.17969 0 16.556 21.045)" gradientUnits="userSpaceOnUse"><stop class="a7vfdrbiy"/><stop offset="1" class="x6mjr8bji"/></radialGradient><radialGradient id="ilCFxZb" cx="0" cy="0" r="1" gradientTransform="rotate(-80.201 18.66 -5.092)scale(1.14166 3.3775)" gradientUnits="userSpaceOnUse"><stop class="ig6ibcrff"/><stop offset="1" class="u9p-sccfc"/></radialGradient><radialGradient id="iydC1mb" cx="0" cy="0" r="1" gradientTransform="rotate(-80.2 13.86 .608)scale(1.14166 3.37768)" gradientUnits="userSpaceOnUse"><stop class="ig6ibcrff"/><stop offset="1" class="u9p-sccfc"/></radialGradient><radialGradient id="imVZpOb" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.68424 -1.9929 0 20.01 17.4)" gradientUnits="userSpaceOnUse"><stop offset=".75" class="e0-rnofaa"/><stop offset="1" class="qh547r7uu"/></radialGradient><radialGradient id="iVJu1Dc" cx="0" cy="0" r="1" gradientTransform="rotate(-127.812 13.939 3.671)scale(.70528 .97101)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iov9blb" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.68433 -1.993 0 11.873 17.4)" gradientUnits="userSpaceOnUse"><stop offset=".75" class="e0-rnofaa"/><stop offset="1" class="qh547r7uu"/></radialGradient><radialGradient id="ius6L4b" cx="0" cy="0" r="1" gradientTransform="rotate(-90.897 14.13 3.012)scale(.92129 1.10743)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><filter id="iEUGxMl" width="6.427" height="6.227" x="3.979" y="14.936" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.619608 0 0 0 0 0.470588 0 0 0 0 0.407843 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_20010"/></filter><filter id="iCA8Zab" width="6.427" height="6.227" x="3.979" y="14.936" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.917647 0 0 0 0 0.694118 0 0 0 0 0.607843 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_20010"/></filter><filter id="iDuzalc" width="4.711" height="4.711" x="4.737" y="15.694" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_20010" stdDeviation=".25"/></filter><filter id="i2zRAad" width="6.477" height="6.477" x="21.72" y="14.686" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.843137 0 0 0 0 0.623529 0 0 0 0 0.580392 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_20010"/></filter><filter id="iR5IQ3b" width="4.711" height="4.711" x="22.478" y="15.694" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_20010" stdDeviation=".25"/></filter><filter id="ibeKoJc" width="19.345" height="22.73" x="6.327" y="7.561" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".3"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.854902 0 0 0 0 0.592157 0 0 0 0 0.509804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_20010"/></filter><filter id="iPxZwwe" width="11.918" height="9.719" x="15.009" y="5.561" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_20010" stdDeviation="1"/></filter><filter id="iavNReb" width="23.5" height="15.5" x="4.196" y="1.509" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.701961 0 0 0 0 0.262745 0 0 0 0 0.121569 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_20010"/></filter><filter id="i7tl9be" width="4.782" height="6.5" x="13.11" y="16.545" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_20010" stdDeviation=".375"/></filter><filter id="iAiSVGe" width="4" height="5.5" x="13.946" y="16.741" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_20010" stdDeviation=".125"/></filter><filter id="iRnimCb" width="5.34" height="3.147" x="18.151" y="11.591" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.627451 0 0 0 0 0.266667 0 0 0 0 0.219608 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_20010"/></filter><filter id="ipoz7Cc" width="5.341" height="3.147" x="8.551" y="11.591" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.627451 0 0 0 0 0.266667 0 0 0 0 0.219608 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_20010"/></filter><filter id="iujoPER" width="1.294" height="1.125" x="18.727" y="16.044" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_20010" stdDeviation=".05"/></filter><filter id="i7qWeHJ" width="1.316" height="1.357" x="20.38" y="16.27" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_20010" stdDeviation=".1"/></filter><filter id="iW2Smpe" width="1.493" height="1.594" x="12.097" y="16.152" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_20010" stdDeviation=".1"/></filter><filter id="iCkgLwb" width="1.529" height="1.141" x="10.603" y="16.029" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_20010" stdDeviation=".05"/></filter><filter id="iupd32d" width="4.949" height="2.304" x="18.293" y="11.895" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_20010" stdDeviation=".25"/></filter><filter id="i9qYIqo" width="5.094" height="2.41" x="8.56" y="12.014" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_20010" stdDeviation=".25"/></filter><linearGradient id="iAghpsb" x1="7.092" x2="5.898" y1="18.569" y2="18.569" gradientUnits="userSpaceOnUse"><stop class="wachewblq"/><stop offset="1" class="px4pa2bzd"/></linearGradient><linearGradient id="ijKHY3c" x1="26.859" x2="25.332" y1="16.014" y2="20.744" gradientUnits="userSpaceOnUse"><stop class="fuy988_rs"/><stop offset="1" class="h2u-65bda"/></linearGradient><linearGradient id="iH2Rx3a" x1="5.688" x2="9.469" y1="23.178" y2="22.991" gradientUnits="userSpaceOnUse"><stop offset=".323" class="hmo3unbrx"/><stop offset="1" class="yyvs3obha"/></linearGradient><linearGradient id="iKAsBod" x1="15.701" x2="30.889" y1="13.21" y2="7.772" gradientUnits="userSpaceOnUse"><stop class="md_nv2yaz"/><stop offset="1" class="affo-kbuc"/></linearGradient><linearGradient id="iCbLeig" x1="3.433" x2="25.91" y1="11.356" y2="11.356" gradientUnits="userSpaceOnUse"><stop class="z8b5eybgc"/><stop offset=".349" class="rkde3beof"/><stop offset="1" class="q1uq6hbwz"/></linearGradient><linearGradient id="iAc1Jxd" x1="14.335" x2="16.084" y1="20.005" y2="20.005" gradientUnits="userSpaceOnUse"><stop class="h7h6nwjtb"/><stop offset="1" class="btip4dbzo"/></linearGradient><linearGradient id="ihv5kbc" x1="17.696" x2="15.784" y1="20.606" y2="20.579" gradientUnits="userSpaceOnUse"><stop class="ag4c77bht"/><stop offset="1" class="qb120pbsb"/></linearGradient><linearGradient id="ikmfUlc" x1="16.309" x2="16.309" y1="21.991" y2="20.922" gradientUnits="userSpaceOnUse"><stop class="rlzetx3ey"/><stop offset="1" class="zf2atv-8x"/></linearGradient><linearGradient id="iAcujHo" x1="16.181" x2="16.181" y1="22.069" y2="21.756" gradientUnits="userSpaceOnUse"><stop class="l1er17byo"/><stop offset="1" class="abcg0lbyl"/></linearGradient><linearGradient id="iGsbGPd" x1="14.012" x2="14.824" y1="25.003" y2="23.72" gradientUnits="userSpaceOnUse"><stop class="wl-j51biu"/><stop offset=".663" class="i-vkeo5mo"/></linearGradient><linearGradient id="iBI2wxd" x1="21.46" x2="20.875" y1="16.878" y2="17.238" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="ih7Js6z" x1="13.26" x2="12.675" y1="16.878" y2="17.238" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iHT3ebd" x1="21.489" x2="20.706" y1="12.888" y2="11.287" gradientUnits="userSpaceOnUse"><stop class="xw_2ixv7m"/><stop offset="1" class="o2wzcab8c"/></linearGradient><linearGradient id="ij0Y6hA" x1="11.597" x2="9.379" y1="12.65" y2="11.72" gradientUnits="userSpaceOnUse"><stop class="xw_2ixv7m"/><stop offset="1" class="o2wzcab8c"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:man-red-hair-light" /></template>
<style>
.a7vfdrbiy {
  stop-color: var(--svg-color--ffd7c1, #FFD7C1);
}

.abcg0lbyl {
  stop-color: var(--svg-color--d6938e, #D6938E);
  stop-opacity: 0;
}

.affo-kbuc {
  stop-color: var(--svg-color--fcc8a7, #FCC8A7);
  stop-opacity: 0;
}

.ag4c77bht {
  stop-color: var(--svg-color--ffdfc4, #FFDFC4);
}

.btip4dbzo {
  stop-color: var(--svg-color--dfa790, #DFA790);
  stop-opacity: 0;
}

.bw8j_5egh {
  stop-color: var(--svg-color--d6a38d, #D6A38D);
}

.ca06pugdq {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("M19.043 12.707c.802-.14 2.366-.1 3.449.742");
}

.cbq1t5_me {
  d: path("m15.234 17.517l-.991 3.17a1.005 1.005 0 0 0 .97 1.304h1.466c.688 0 1.173-.662.971-1.304l-.99-3.17c-.213-.702-1.204-.702-1.427 0");
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.crp6d4bqv {
  stop-color: var(--svg-color--cf9888, #CF9888);
}

.dky7fib-j {
  fill: var(--svg-color--d89992, #D89992);
  d: path("m15.433 17.822l-1.53 3.169c-.19.652.266 1.304.91 1.304h1.375c.645 0 1.1-.662.91-1.304l-.929-3.17c-.199-.702-.527-.702-.736 0");
}

.dky8lccpu {
  stop-color: var(--svg-color--ffdfc3, #FFDFC3);
}

.e_h6jabwf {
  stop-color: var(--svg-color--bd765f, #BD765F);
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.e9gbg1d-u {
  cx: 11.367px;
  cy: 16.599px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.726px;
  ry: 0.368px;
}

.ei1bt-b0e {
  stop-color: var(--svg-color--af725f, #AF725F);
  stop-opacity: 0;
}

.ew7jqnj6t {
  stop-color: var(--svg-color--ffdabf, #FFDABF);
  stop-opacity: 0;
}

.f6czxtz5j {
  fill: var(--svg-color--fff, #fff);
  d: path("M20.4 15.381c1.217 0 2.245.84 2.525 1.974a.51.51 0 0 1-.499.636h-4.16a.43.43 0 0 1-.423-.507a2.606 2.606 0 0 1 2.556-2.103");
}

.fa9i5bbvu {
  stop-color: var(--svg-color--d5a58e, #D5A58E);
}

.ft5dv1b6b {
  fill: none;
}

.fuy988_rs {
  stop-color: var(--svg-color--fbd3bd, #FBD3BD);
}

.g4x2unb_n {
  stop-color: var(--svg-color--ffdbc1, #FFDBC1);
}

.gcj4afbgh {
  cx: 24.833px;
  cy: 18.049px;
  r: 1.855px;
  fill: var(--svg-color--e4af9a, #E4AF9A);
}

.gg3p-v-oi {
  stop-color: var(--svg-color--d56a42, #D56A42);
}

.go8dnjb_b {
  stop-color: var(--svg-color--d56a42, #D56A42);
  stop-opacity: 0;
}

.h2u-65bda {
  stop-color: var(--svg-color--f0b8a4, #F0B8A4);
}

.h7h6nwjtb {
  stop-color: var(--svg-color--dfa790, #DFA790);
}

.hchmvbcwb {
  stop-color: var(--svg-color--af725f, #AF725F);
}

.hh__2aceo {
  d: path("M19.891 16.24c.119.158-.13.352-.41.562c-.283.211-.492.36-.61.2c-.119-.158.014-.457.295-.668c.282-.21.607-.253.725-.094");
}

.hil9j9kpd {
  stop-color: var(--svg-color--b57895, #B57895);
}

.hmo3unbrx {
  stop-color: var(--svg-color--e8ad97, #E8AD97);
}

.hmx8eit6p {
  stop-color: var(--svg-color--f78d61, #F78D61);
  stop-opacity: 0;
}

.i-vkeo5mo {
  stop-color: var(--svg-color--d9a4a4, #D9A4A4);
  stop-opacity: 0;
}

.ibem-2huv {
  stop-color: var(--svg-color--d49a9f, #D49A9F);
  stop-opacity: 0;
}

.ig6ibcrff {
  stop-color: var(--svg-color--a83e3f, #A83E3F);
}

.jwnwh9mpl {
  d: path("M11.87 15.888a1.664 1.664 0 0 0-1.604 2.103h3.214c.038-.144.061-.288.061-.44a1.675 1.675 0 0 0-1.671-1.663");
}

.k6zwfqo1x {
  stop-color: var(--svg-color--d0948d, #D0948D);
  stop-opacity: 0;
}

.kd9fr-txf {
  stop-color: var(--svg-color--d57852, #D57852);
  stop-opacity: 0;
}

.kdp2zyzxx {
  d: path("m24.933 5.97l.8.397c1.4.696 2.2 2.288 1.9 3.978l-1.1 5.67c-.098.585-.485.98-1.066.994h-.034s.1-1.69.2-2.685c.081-.808-.06-1.054-.8-1.79c-.4-.398-.7-.995-.7-1.592V9.351c0-.497-.4-.895-.8-.995c-1.201-.298-3.702-.795-7.303-.795s-6.102.497-7.302.795c-.5.1-.8.498-.8.995v1.591c0 .597-.2 1.194-.7 1.592l-.3.298c-.4.298-.6.895-.6 1.392c.1 1.094.2 2.686.2 2.686q-.047 0-.092-.003a1.18 1.18 0 0 1-1.109-.992l-1.1-5.669c-.2-1.591.6-3.183 2-3.879l.8-.398c.5-.298 1-.696 1.501-1.094l1.8-1.89c1.1-.994 2.701-1.292 4.102-.596c1.03.512 2.1.298 3.1 0c1.501-.498 3.202-.1 4.402.994l1.5 1.492c.4.497.9.796 1.5 1.094");
}

.l1er17byo {
  stop-color: var(--svg-color--d6938e, #D6938E);
}

.labizxbgi {
  d: path("M13.39 17.357c0-.538-.438-.897-.556-1.005l-.537.52l.33.674z");
}

.lekcnobli {
  stop-color: var(--svg-color--f6b8a7, #F6B8A7);
  stop-opacity: 0;
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.ll5bq8b7t {
  d: path("m24.084 7.56l-5.739 1.914a1.953 1.953 0 0 0 .877 3.788l5.706-.764z");
}

.lu78seb9e {
  stop-color: var(--svg-color--be8c77, #BE8C77);
}

.m9zfab8yd {
  stop-color: var(--svg-color--ffdfc3, #FFDFC3);
  stop-opacity: 0;
}

.md_nv2yaz {
  stop-color: var(--svg-color--fcc8a7, #FCC8A7);
}

.moyyndcqm {
  stop-color: var(--svg-color--bd765f, #BD765F);
  stop-opacity: 0;
}

.n-zw6k8dv {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("M9.31 13.674c.61-.539 1.942-1.107 3.593-.843");
}

.n7c5lw_4k {
  stop-color: var(--svg-color--d6a38d, #D6A38D);
  stop-opacity: 0;
}

.n91c-gs8j {
  stop-color: var(--svg-color--865d5f, #865D5F);
}

.ndzxn1lxc {
  fill: var(--svg-color--fbc4b1, #FBC4B1);
  d: path("m15.234 17.517l-.991 3.17a1.005 1.005 0 0 0 .97 1.304h1.466c.688 0 1.173-.662.971-1.304l-.99-3.17c-.213-.702-1.204-.702-1.427 0");
}

.nve4o1bcy {
  stop-color: var(--svg-color--f6b8a7, #F6B8A7);
}

.o2wzcab8c {
  stop-color: var(--svg-color--cc725e, #CC725E);
  stop-opacity: 0;
}

.o7liw8bnz {
  stop-color: var(--svg-color--ba7260, #BA7260);
  stop-opacity: 0;
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.oufadibrx {
  cx: 11.367px;
  cy: 16.599px;
  rx: 0.726px;
  ry: 0.368px;
}

.pajtq1t7s {
  stop-color: var(--svg-color--d0948d, #D0948D);
}

.pbw_1oblv {
  cx: 24.833px;
  cy: 18.049px;
  r: 1.855px;
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pu69_yu4m {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M19.891 16.24c.119.158-.13.352-.41.562c-.283.211-.492.36-.61.2c-.119-.158.014-.457.295-.668c.282-.21.607-.253.725-.094");
}

.pvp6am2qg {
  fill: var(--svg-color--bd593b, #BD593B);
  d: path("M8.91 12.978v-.002h.002l.004-.004l.008-.007l.022-.017l.067-.051q.083-.062.222-.15c.186-.116.45-.261.783-.393a5.3 5.3 0 0 1 2.784-.295a.995.995 0 1 1-.31 1.966a3.3 3.3 0 0 0-1.742.18a3 3 0 0 0-.56.298l-.015.01a.995.995 0 0 1-1.266-1.535");
}

.px4pa2bzd {
  stop-color: var(--svg-color--be8474, #BE8474);
}

.pxvs_abtj {
  stop-color: var(--svg-color--d9a496, #D9A496);
}

.q1uq6hbwz {
  stop-color: var(--svg-color--ea8455, #EA8455);
}

.qb120pbsb {
  stop-color: var(--svg-color--ffdfc4, #FFDFC4);
  stop-opacity: 0;
}

.qh547r7uu {
  stop-color: var(--svg-color--5e433e, #5E433E);
}

.qo7u-3bcf {
  stop-color: var(--svg-color--76594a, #76594A);
}

.r3t82tbzk {
  stop-color: var(--svg-color--d9aa94, #D9AA94);
  stop-opacity: 0;
}

.rkde3beof {
  stop-color: var(--svg-color--c26333, #C26333);
}

.rlzetx3ey {
  stop-color: var(--svg-color--dc9c96, #DC9C96);
}

.ro9l-sbza {
  d: path("m22.883 12.977l-.002-.002l-.004-.003l-.008-.007l-.023-.017l-.067-.051a4 4 0 0 0-.221-.15a5 5 0 0 0-.783-.393a5.3 5.3 0 0 0-2.784-.295a.995.995 0 1 0 .31 1.966a3.3 3.3 0 0 1 1.742.18a2.8 2.8 0 0 1 .56.298q.011.009.015.01a.995.995 0 0 0 1.265-1.536");
}

.s_gvjrbyd {
  d: path("M8.91 12.978v-.002h.002l.004-.004l.008-.007l.022-.017l.067-.051q.083-.062.222-.15c.186-.116.45-.261.783-.393a5.3 5.3 0 0 1 2.784-.295a.995.995 0 1 1-.31 1.966a3.3 3.3 0 0 0-1.742.18a3 3 0 0 0-.56.298l-.015.01a.995.995 0 0 1-1.266-1.535");
}

.s1mz5y7pt {
  cx: 7.092px;
  cy: 18.049px;
  r: 1.855px;
}

.s72pw74ms {
  cx: 24.833px;
  cy: 18.049px;
  r: 3.113px;
}

.sdjph8tjs {
  stop-color: var(--svg-color--b97362, #B97362);
}

.sn-n94bif {
  stop-color: var(--svg-color--de6f4f, #DE6F4F);
}

.syqh2sbqs {
  d: path("M20.013 15.888a1.664 1.664 0 0 1 1.604 2.103h-3.215a1.7 1.7 0 0 1-.06-.439a1.67 1.67 0 0 1 1.671-1.664");
}

.t7o6ccjes {
  stop-color: var(--svg-color--d57852, #D57852);
}

.tzxi8pb6h {
  stop-color: var(--svg-color--f78d61, #F78D61);
}

.u9p-sccfc {
  stop-color: var(--svg-color--a83e3f, #A83E3F);
  stop-opacity: 0;
}

.v-30-7x4s {
  cx: 7.092px;
  cy: 18.049px;
  r: 3.113px;
}

.v3rmoybey {
  fill: var(--svg-color--fff, #fff);
  d: path("M11.484 15.381c-1.218 0-2.247.84-2.526 1.974a.51.51 0 0 0 .499.636h4.16a.43.43 0 0 0 .423-.507a2.61 2.61 0 0 0-2.556-2.103");
}

.vld6k812o {
  fill: var(--svg-color--88024e, #88024E);
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M13.386 23.23a.335.335 0 0 0-.4.069a.305.305 0 0 0-.033.393a3.58 3.58 0 0 0 2.993 1.599a3.58 3.58 0 0 0 2.994-1.6a.31.31 0 0 0-.034-.396a.34.34 0 0 0-.4-.066a5.5 5.5 0 0 1-2.56.607c-.938 0-1.82-.22-2.56-.606Z");
}

.vu7vn7bhc {
  stop-color: var(--svg-color--de6f4f, #DE6F4F);
  stop-opacity: 0;
}

.w5wsyh14x {
  fill: var(--svg-color--000, #000);
  d: path("M12.823 17.552a.95.95 0 0 0-.953-.953a.95.95 0 0 0-.953.953c0 .159.037.31.105.439h1.687a.95.95 0 0 0 .114-.439");
}

.wachewblq {
  stop-color: var(--svg-color--ba7c6b, #BA7C6B);
}

.wdqn7tq-u {
  stop-color: var(--svg-color--d9aa94, #D9AA94);
}

.wl-j51biu {
  stop-color: var(--svg-color--d9a4a4, #D9A4A4);
}

.x6mjr8bji {
  stop-color: var(--svg-color--ffd7c1, #FFD7C1);
  stop-opacity: 0;
}

.x8d9utbsu {
  stop-color: var(--svg-color--d5a58e, #D5A58E);
  stop-opacity: 0;
}

.xghyhmb_n {
  d: path("M6.327 14.224c0-.497.2-1.094.6-1.392l.3-.299c.5-.397.7-.994.7-1.59V9.35c0-.497.301-.895.801-.995c1.2-.298 3.701-.795 7.302-.795s6.102.497 7.302.795c.4.1.8.498.8.995v1.591c0 .597.3 1.194.7 1.592c.937.656.879 1.016.801 1.79c-.1.994-.2 2.685-.2 2.685h.034l-.496 7.382c-.3 3.3-2.894 5.6-5.987 5.6h-5.987c-3.193 0-5.687-2.3-5.987-5.6c-.26-3.388-.373-6.785-.683-10.167");
}

.xhmtc9b9f {
  stop-color: var(--svg-color--b97362, #B97362);
  stop-opacity: 0;
}

.xp9lbpb1d {
  fill: var(--svg-color--000, #000);
  d: path("M19.06 17.552c0-.53.424-.953.953-.953c.53 0 .953.424.953.953a.94.94 0 0 1-.106.439h-1.686a.86.86 0 0 1-.113-.439");
}

.xw_2ixv7m {
  stop-color: var(--svg-color--cc725e, #CC725E);
}

.yyvs3obha {
  stop-color: var(--svg-color--e8ad97, #E8AD97);
  stop-opacity: 0;
}

.z5h7u4bip {
  d: path("M21.496 17.333a1.57 1.57 0 0 0-.432-.863l-.484.532l.218.425z");
}

.z5ld33bgu {
  fill: var(--svg-color--bd593b, #BD593B);
  d: path("m22.883 12.977l-.002-.002l-.004-.003l-.008-.007l-.023-.017l-.067-.051a4 4 0 0 0-.221-.15a5 5 0 0 0-.783-.393a5.3 5.3 0 0 0-2.784-.295a.995.995 0 1 0 .31 1.966a3.3 3.3 0 0 1 1.742.18a2.8 2.8 0 0 1 .56.298q.011.009.015.01a.995.995 0 0 0 1.265-1.536");
}

.z8b5eybgc {
  stop-color: var(--svg-color--bc613d, #BC613D);
}

.z8y6fgvmn {
  stop-color: var(--svg-color--ffdabf, #FFDABF);
}

.zf2atv-8x {
  stop-color: var(--svg-color--dc9c96, #DC9C96);
  stop-opacity: 0;
}

.zk1gozblh {
  stop-color: var(--svg-color--ba7260, #BA7260);
}

</style>
