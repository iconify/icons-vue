<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iHjHGqX)"><path fill="url(#iCR1XOe)" class="tvh3rxb7z"/></g><g filter="url(#iBxVSOk)"><path fill="url(#i4dEBzc)" class="ycobh_6lz"/><path fill="url(#iuXwjlb)" class="ycobh_6lz"/></g><g filter="url(#i4pe5Ed)"><path class="zl7ej5b_j"/><path fill="url(#ieJsY3c)" class="n9tnz5ikc"/></g><g filter="url(#i97UI7b)"><path class="spe-wrvgh"/><path fill="url(#ik2yWeb)" class="cnl1fccua"/></g><g filter="url(#i3F9qDd)"><path fill="url(#iB6FkTD)" class="cmzi6t3zf"/><path fill="url(#iq1v03p)" class="cmzi6t3zf"/><path fill="url(#iHeZv9k)" class="cmzi6t3zf"/><path fill="url(#i4JCzrd)" class="cmzi6t3zf"/><path fill="url(#iAGcEec)" class="cmzi6t3zf"/><path fill="url(#iK6q5ib)" class="cmzi6t3zf"/><path fill="url(#iJkCejc)" class="cmzi6t3zf"/></g><path fill="url(#iVhZMNb)" class="cmzi6t3zf"/><path fill="url(#iEKnKoc)" class="cmzi6t3zf"/><g filter="url(#itgTG7V)"><path class="zflxaub1u"/></g><g filter="url(#ihzcxne)"><path class="r6yvhvbxp"/><path fill="url(#iyxqQPb)" class="i16q27b0z"/><path fill="url(#i86TRhc)" class="i16q27b0z"/><path fill="url(#iZxQGHd)" class="i16q27b0z"/></g><g filter="url(#iwmEagd)"><path fill="url(#iJQZBPb)" class="w6o2k5blk"/></g><g filter="url(#iIoyJde)"><path stroke="url(#i87xePd)" class="q61vir6ce"/></g><path class="wa-728m0i"/><g filter="url(#ioGfKXX)"><path class="c_uyp7b4u"/></g><g filter="url(#ikncU8R)"><path class="ez0-28s9u"/></g><g filter="url(#isHOcPY)"><path class="rn9c96bjh"/></g><g filter="url(#ib1V7cd)"><path clip-rule="evenodd" class="n79ty2bbc"/></g><path class="ef0qz83po"/><path fill="url(#i7nIB2D)" class="s9p5w3b7j"/><path class="nzgowqbpe"/><g filter="url(#iQUlvqe)"><path class="rdwuebbdx"/><path fill="url(#iyFcH0c)" class="gelt6sv6v"/></g><g filter="url(#ipyrM9R)"><path fill="url(#ieDNCad)" class="d95d_ibmu"/></g><path class="hgdod9bjp"/><path fill="url(#iQyBSdb)" class="n644_45yf"/><path class="p__cvka-s"/><g filter="url(#iX0C1zd)"><path fill="url(#i1nHNpc)" class="jxp6cl9zo"/></g><g filter="url(#ikh5rTd)"><ellipse transform="rotate(-27.914 11.2 17.313)" class="s6qc0ccmr"/><ellipse fill="url(#icARiZc)" transform="rotate(-27.914 11.2 17.313)" class="j1honvvth"/></g><g filter="url(#ihsOz0c)"><path class="w-6axbcrg"/></g><g filter="url(#iPOvYde)"><path class="s2ksypb6u"/></g><path fill="url(#iAiNHae)" class="nsn47rbed"/><path fill="url(#iBcFe2d)" class="nsn47rbed"/><path fill="url(#iZXhLkE)" class="nsn47rbed"/><g filter="url(#iFC13be)"><path fill="url(#i5EYg7b)" class="opjf3kbfq"/><path fill="url(#ixY9nMe)" class="opjf3kbfq"/></g><g filter="url(#i2ksFgb)"><path fill="url(#iLPDbid)" class="etyder0ew"/></g><path fill="url(#i4dwOqd)" class="etyder0ew"/><path fill="url(#iDxKDTb)" class="etyder0ew"/><path fill="url(#iqQdf3d)" class="etyder0ew"/><g filter="url(#ipGFR2b)"><path fill="url(#if2XEiA)" class="ajkq73jxq"/></g><path fill="url(#iUlKGqd)" class="ajkq73jxq"/><path fill="url(#i8KfJqF)" class="ajkq73jxq"/><path fill="url(#iAMx8mb)" class="ajkq73jxq"/><path fill="url(#iRXTsMd)" class="ajkq73jxq"/><path fill="url(#ittfgOd)" class="ajkq73jxq"/><g filter="url(#iBnjabc)"><path fill="url(#iRtnCtc)" class="empsclb_z"/><path fill="url(#iFLgi9b)" class="empsclb_z"/><path fill="url(#iHoI0yb)" class="empsclb_z"/><path fill="url(#iaumesd)" class="empsclb_z"/><path fill="url(#i3pO2hc)" class="empsclb_z"/></g><g filter="url(#i6fFZkd)"><path fill="url(#i2cEdqd)" class="r3imb_bxi"/></g><path fill="url(#iXxQ0Oe)" class="r3imb_bxi"/><path fill="url(#iBQf8Bd)" class="r3imb_bxi"/><defs><radialGradient id="i4dEBzc" cx="0" cy="0" r="1" gradientTransform="rotate(-24.444 56.708 -44.622)scale(5.1997 6.34859)" gradientUnits="userSpaceOnUse"><stop offset=".572" class="qmmvvysmp"/><stop offset=".905" class="epx_cgb2c"/></radialGradient><radialGradient id="iuXwjlb" cx="0" cy="0" r="1" gradientTransform="matrix(1.89663 .5419 -.2849 .99714 25.492 15.242)" gradientUnits="userSpaceOnUse"><stop class="aso-vybjw"/><stop offset="1" class="krvd34mtu"/></radialGradient><radialGradient id="ieJsY3c" cx="0" cy="0" r="1" gradientTransform="rotate(-20.298 65.603 -59.17)scale(2.48103)" gradientUnits="userSpaceOnUse"><stop offset=".71" class="la61skb4q"/><stop offset="1" class="urs_pbb4x"/></radialGradient><radialGradient id="ik2yWeb" cx="0" cy="0" r="1" gradientTransform="matrix(-2.3142 0 0 -2.21368 6.99 18.63)" gradientUnits="userSpaceOnUse"><stop offset=".573" class="prydr8bcy"/><stop offset="1" class="ybx_6zbxd"/></radialGradient><radialGradient id="iB6FkTD" cx="0" cy="0" r="1" gradientTransform="matrix(-12.36831 5.70344 -7.63398 -16.55483 21.303 17.608)" gradientUnits="userSpaceOnUse"><stop class="uy3z2gbbp"/><stop offset="1" class="gvh2bspmv"/></radialGradient><radialGradient id="iq1v03p" cx="0" cy="0" r="1" gradientTransform="matrix(-4.01225 2.12222 -1.80055 -3.4041 19.48 18.935)" gradientUnits="userSpaceOnUse"><stop class="j8hkuac-d"/><stop offset="1" class="cre_5tbhq"/></radialGradient><radialGradient id="iHeZv9k" cx="0" cy="0" r="1" gradientTransform="matrix(1.5916 -7.69295 9.76093 2.01944 11.72 30.508)" gradientUnits="userSpaceOnUse"><stop class="t6jzi2-1t"/><stop offset="1" class="i3g5qu-9r"/></radialGradient><radialGradient id="i4JCzrd" cx="0" cy="0" r="1" gradientTransform="matrix(-.80672 13.70548 -16.4139 -.96614 16.672 16.857)" gradientUnits="userSpaceOnUse"><stop offset=".62" class="cmn1n6bms"/><stop offset="1" class="q31ht9hnt"/></radialGradient><radialGradient id="iAGcEec" cx="0" cy="0" r="1" gradientTransform="rotate(172.34 7.8 11.596)scale(10.9999 18.9384)" gradientUnits="userSpaceOnUse"><stop offset=".813" class="zzstxpr9j"/><stop offset="1" class="irzp_cb7o"/></radialGradient><radialGradient id="iK6q5ib" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.18851 3.14623 0 20.242 16.813)" gradientUnits="userSpaceOnUse"><stop offset=".259" class="mt3h7fbpd"/><stop offset="1" class="wcr1klbjh"/></radialGradient><radialGradient id="iJkCejc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.58642 2.96421 0 12.217 16.979)" gradientUnits="userSpaceOnUse"><stop class="r-jog4w_t"/><stop offset="1" class="xjkdvxqyn"/></radialGradient><radialGradient id="iVhZMNb" cx="0" cy="0" r="1" gradientTransform="matrix(-2.52846 0 0 -7.77903 25.431 20.444)" gradientUnits="userSpaceOnUse"><stop class="yhs2bn2id"/><stop offset="1" class="g1fw3-bff"/></radialGradient><radialGradient id="iEKnKoc" cx="0" cy="0" r="1" gradientTransform="matrix(2.17047 7.40105 -16.2008 4.75114 11.173 8.909)" gradientUnits="userSpaceOnUse"><stop class="mih5kfbap"/><stop offset="1" class="kqfxh5bnm"/></radialGradient><radialGradient id="iyxqQPb" cx="0" cy="0" r="1" gradientTransform="rotate(-105.892 16.616 3.96)scale(4.844 2.7718)" gradientUnits="userSpaceOnUse"><stop offset=".017" class="xjug-415a"/><stop offset="1" class="bd8jqdorr"/></radialGradient><radialGradient id="i7nIB2D" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.54294 -2.45422 0 20.015 17.495)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="iyFcH0c" cx="0" cy="0" r="1" gradientTransform="matrix(-.44105 -.56836 .7825 -.60723 19.581 17.655)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iQyBSdb" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.54295 -2.45424 0 11.716 17.495)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="icARiZc" cx="0" cy="0" r="1" gradientTransform="matrix(-.01471 -.9396 1.12943 -.01768 11.17 17.911)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iAiNHae" cx="0" cy="0" r="1" gradientTransform="matrix(-.84218 3.75478 -8.78476 -1.97039 25.881 5.042)" gradientUnits="userSpaceOnUse"><stop class="s6vdf8bty"/><stop offset=".789" class="lxkykv_ud"/></radialGradient><radialGradient id="iBcFe2d" cx="0" cy="0" r="1" gradientTransform="matrix(2.09375 .53125 -1.15317 4.54483 20.347 6.676)" gradientUnits="userSpaceOnUse"><stop offset=".152" class="q2rl-9b2o"/><stop offset="1" class="fi285-b6u"/></radialGradient><radialGradient id="iZXhLkE" cx="0" cy="0" r="1" gradientTransform="matrix(1.5 -2.625 6.33197 3.61827 22.284 10.52)" gradientUnits="userSpaceOnUse"><stop class="p6ygghbxv"/><stop offset="1" class="ih_njzbst"/></radialGradient><radialGradient id="i5EYg7b" cx="0" cy="0" r="1" gradientTransform="matrix(.17188 2.91016 -14.53547 .85847 21.253 2.016)" gradientUnits="userSpaceOnUse"><stop class="nsg0945ca"/><stop offset="1" class="mcdrc7blw"/></radialGradient><radialGradient id="ixY9nMe" cx="0" cy="0" r="1" gradientTransform="matrix(1.45313 0 0 5.1925 20.8 3.332)" gradientUnits="userSpaceOnUse"><stop offset=".253" class="w7pk8_-qm"/><stop offset="1" class="wfm74pxcd"/></radialGradient><radialGradient id="i4dwOqd" cx="0" cy="0" r="1" gradientTransform="matrix(2.46875 1.71875 -3.03125 4.35398 17.69 9.05)" gradientUnits="userSpaceOnUse"><stop offset=".391" class="hc5vad6zv"/><stop offset="1" class="m71s56bwv"/></radialGradient><radialGradient id="iDxKDTb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.93844 1.49148 0 24.653 14.5)" gradientUnits="userSpaceOnUse"><stop offset=".306" class="b5m4mk31i"/><stop offset="1" class="o02xvvb7n"/></radialGradient><radialGradient id="iqQdf3d" cx="0" cy="0" r="1" gradientTransform="matrix(3.71875 0 0 .30337 18.753 8.675)" gradientUnits="userSpaceOnUse"><stop class="w98e9_6zv"/><stop offset="1" class="phr-zrige"/></radialGradient><radialGradient id="if2XEiA" cx="0" cy="0" r="1" gradientTransform="matrix(-4.28125 -.09372 .19553 -8.93238 21.565 5.582)" gradientUnits="userSpaceOnUse"><stop class="qnoj66lkr"/><stop offset="1" class="s_fkwccyi"/></radialGradient><radialGradient id="iUlKGqd" cx="0" cy="0" r="1" gradientTransform="matrix(11.55068 3.52232 -4.80864 15.76891 9.13 5.736)" gradientUnits="userSpaceOnUse"><stop offset=".633" class="rjs9uccph"/><stop offset=".952" class="x7ia8vuzd"/></radialGradient><radialGradient id="i8KfJqF" cx="0" cy="0" r="1" gradientTransform="matrix(1.11064 -4.72815 1.61144 .37853 16.84 4.594)" gradientUnits="userSpaceOnUse"><stop offset=".348" class="zz39r5b3o"/><stop offset="1" class="wvn8vtban"/></radialGradient><radialGradient id="iAMx8mb" cx="0" cy="0" r="1" gradientTransform="matrix(-.06346 1.33277 -6.75892 -.32185 9.193 7.386)" gradientUnits="userSpaceOnUse"><stop class="biviy7bfr"/><stop offset="1" class="ednzh9b6g"/></radialGradient><radialGradient id="iRXTsMd" cx="0" cy="0" r="1" gradientTransform="matrix(-13.48639 2.82409 -3.69438 -17.64244 17.539 7.513)" gradientUnits="userSpaceOnUse"><stop offset=".681" class="rq033_icj"/><stop offset="1" class="dbmxbxbzy"/></radialGradient><radialGradient id="ittfgOd" cx="0" cy="0" r="1" gradientTransform="matrix(.88851 -3.93483 2.3195 .52376 6.94 14.494)" gradientUnits="userSpaceOnUse"><stop offset=".201" class="nmcqtrbfm"/><stop offset="1" class="w9crknafl"/></radialGradient><radialGradient id="iRtnCtc" cx="0" cy="0" r="1" gradientTransform="rotate(137.988 8.553 4.64)scale(9.89862 9.45071)" gradientUnits="userSpaceOnUse"><stop class="rnyxtsb4p"/><stop offset="1" class="isvyw7ooh"/></radialGradient><radialGradient id="iFLgi9b" cx="0" cy="0" r="1" gradientTransform="matrix(-1.78125 0 0 -4.75 18.44 3.488)" gradientUnits="userSpaceOnUse"><stop class="dqjzd9_8e"/><stop offset="1" class="jcrjf-b8x"/></radialGradient><radialGradient id="iaumesd" cx="0" cy="0" r="1" gradientTransform="matrix(5.90625 .125 -.02777 1.31192 10.128 4.113)" gradientUnits="userSpaceOnUse"><stop class="qw_ssccar"/><stop offset="1" class="mvpyyqb8k"/></radialGradient><radialGradient id="i3pO2hc" cx="0" cy="0" r="1" gradientTransform="matrix(1.28125 -.09375 .17757 2.4268 14.128 2.457)" gradientUnits="userSpaceOnUse"><stop offset=".256" class="jdd1i0reo"/><stop offset="1" class="ixxpbv8hf"/></radialGradient><radialGradient id="i2cEdqd" cx="0" cy="0" r="1" gradientTransform="matrix(-8.06249 1.65631 -3.03846 -14.79042 14.534 2.582)" gradientUnits="userSpaceOnUse"><stop class="nsmntj3ul"/><stop offset="1" class="q9wqsddqp"/></radialGradient><radialGradient id="iXxQ0Oe" cx="0" cy="0" r="1" gradientTransform="matrix(8.03125 .96875 -1.11478 9.24187 7.253 3.238)" gradientUnits="userSpaceOnUse"><stop offset=".869" class="atp4gmb-q"/><stop offset="1" class="qfleuzzqm"/></radialGradient><radialGradient id="iBQf8Bd" cx="0" cy="0" r="1" gradientTransform="matrix(2.71875 -2.3259 1.71042 1.99932 4.597 7.752)" gradientUnits="userSpaceOnUse"><stop class="lo97d1z0q"/><stop offset="1" class="qt9c-0dps"/></radialGradient><filter id="iHjHGqX" width="6.27" height="6.37" x="3.894" y="15.571" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy=".25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.858824 0 0 0 0 0.635294 0 0 0 0 0.533333 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3106"/></filter><filter id="iBxVSOk" width="6.12" height="6.37" x="21.986" y="15.321" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.827451 0 0 0 0 0.568627 0 0 0 0 0.505882 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3106"/></filter><filter id="i4pe5Ed" width="5.085" height="5.085" x="22.503" y="16.088" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3106" stdDeviation=".25"/></filter><filter id="i97UI7b" width="4.885" height="4.885" x="4.548" y="16.188" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3106" stdDeviation=".2"/></filter><filter id="i3F9qDd" width="19.13" height="19.331" x="6.301" y="10.903" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".25"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.745098 0 0 0 0 0.486275 0 0 0 0 0.384314 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3106"/></filter><filter id="itgTG7V" width="4.57" height="6.1" x="13.272" y="17.17" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3106" stdDeviation=".25"/></filter><filter id="ihzcxne" width="4.07" height="5.6" x="13.83" y="17.157" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3106" stdDeviation=".125"/></filter><filter id="iwmEagd" width="4.07" height="5.6" x="13.83" y="16.811" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3106" stdDeviation=".125"/></filter><filter id="iIoyJde" width="6.68" height="2.541" x="12.525" y="23.277" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3106" stdDeviation=".05"/></filter><filter id="ioGfKXX" width="5.528" height="2.445" x="17.837" y="15.96" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.141176 0 0 0 0 0.0862745 0 0 0 0 0.176471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3106"/></filter><filter id="ikncU8R" width="5.528" height="2.445" x="8.366" y="15.96" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.133333 0 0 0 0 0.0784314 0 0 0 0 0.168627 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3106"/></filter><filter id="isHOcPY" width="4.484" height="1.995" x="8.623" y="13.332" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.3"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.47451 0 0 0 0 0.262745 0 0 0 0 0.172549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3106"/></filter><filter id="ib1V7cd" width="4.484" height="1.995" x="18.925" y="13.332" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.3"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.47451 0 0 0 0 0.262745 0 0 0 0 0.172549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3106"/></filter><filter id="iQUlvqe" width="1.316" height="1.144" x="18.709" y="16.749" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3106" stdDeviation=".05"/></filter><filter id="ipyrM9R" width="1.334" height="1.376" x="20.396" y="16.982" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3106" stdDeviation=".1"/></filter><filter id="iX0C1zd" width="1.515" height="1.618" x="11.947" y="16.861" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3106" stdDeviation=".1"/></filter><filter id="ikh5rTd" width="1.556" height="1.159" x="10.421" y="16.733" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3106" stdDeviation=".05"/></filter><filter id="ihsOz0c" width="3.758" height="1.318" x="19.363" y="13.724" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3106" stdDeviation=".1"/></filter><filter id="iPOvYde" width="3.758" height="1.318" x="8.734" y="13.724" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3106" stdDeviation=".1"/></filter><filter id="iFC13be" width="7.307" height="5.168" x="20.417" y="1.916" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.843137 0 0 0 0 0.8 0 0 0 0 0.890196 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3106"/></filter><filter id="i2ksFgb" width="12.925" height="6.714" x="14.465" y="8.129" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.05" dy=".1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.992157 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3106"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4" dy="-.25"/><feGaussianBlur stdDeviation=".325"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.670588 0 0 0 0 0.560784 0 0 0 0 0.756863 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_3106" result="effect2_innerShadow_4002_3106"/></filter><filter id="ipGFR2b" width="17.006" height="13.059" x="4.107" y="1.766" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25" dy="-.25"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.603922 0 0 0 0 0.45098 0 0 0 0 0.721569 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3106"/></filter><filter id="iBnjabc" width="13.757" height="8.679" x="4.257" y="1.916" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy="-.1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.611765 0 0 0 0 0.588235 0 0 0 0 0.635294 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3106"/></filter><filter id="i6fFZkd" width="10.523" height="5.986" x="4.357" y="1.816" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.686275 0 0 0 0 0.619608 0 0 0 0 0.752941 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3106"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".05"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.705882 0 0 0 0 0.701961 0 0 0 0 0.705882 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_3106" result="effect2_innerShadow_4002_3106"/></filter><linearGradient id="iCR1XOe" x1="3.894" x2="9.522" y1="18.797" y2="18.797" gradientUnits="userSpaceOnUse"><stop class="nka4--b6e"/><stop offset="1" class="aps1jhbfc"/></linearGradient><linearGradient id="i86TRhc" x1="13.876" x2="15.5" y1="21.057" y2="21.256" gradientUnits="userSpaceOnUse"><stop class="urkjpbftr"/><stop offset="1" class="lwjatlajn"/></linearGradient><linearGradient id="iZxQGHd" x1="15.866" x2="15.866" y1="22.682" y2="21.521" gradientUnits="userSpaceOnUse"><stop class="dvyniwihb"/><stop offset="1" class="e5pm1bciq"/></linearGradient><linearGradient id="iJQZBPb" x1="15.866" x2="15.866" y1="17.061" y2="19.875" gradientUnits="userSpaceOnUse"><stop class="hji3x4euu"/><stop offset="1" class="nemspp6bt"/></linearGradient><linearGradient id="i87xePd" x1="14.479" x2="15.34" y1="25.491" y2="23.833" gradientUnits="userSpaceOnUse"><stop class="hvrv4iryz"/><stop offset="1" class="u1r8ksb5m"/></linearGradient><linearGradient id="ieDNCad" x1="21.494" x2="20.898" y1="17.598" y2="17.965" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="i1nHNpc" x1="13.13" x2="12.534" y1="17.598" y2="17.965" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iLPDbid" x1="26.159" x2="15.409" y1="13.582" y2="13.582" gradientUnits="userSpaceOnUse"><stop class="qxbo6kk2p"/><stop offset="1" class="kkvh--b-a"/></linearGradient><linearGradient id="iHoI0yb" x1="4.357" x2="8.534" y1="9.551" y2="8.582" gradientUnits="userSpaceOnUse"><stop class="d2rffhbfx"/><stop offset="1" class="m1v3gnbun"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:woman-wearing-turban-medium-light" /></template>
<style>
.ajkq73jxq {
  d: path("M20.946 2.016c.357 1.961.193 4.54-1.02 6.425c-.921 1.434-2.18 2.462-3.472 2.462H9.39c-.89 0-1.8.09-2.6 1.285c-.499.743-.485 1.88-.478 2.47l.001.166c-.364-.29-1.568-1.374-1.761-4.18c-.183-.857-.195-2.226-.195-2.985c0-.642.08-1.73.673-2.844c.743-1.393 1.71-2.8 5.42-2.8z");
}

.aps1jhbfc {
  stop-color: var(--svg-color--b47860, #B47860);
}

.aso-vybjw {
  stop-color: var(--svg-color--d59566, #D59566);
}

.atp4gmb-q {
  stop-color: var(--svg-color--a5a0a9, #A5A0A9);
  stop-opacity: 0;
}

.b5m4mk31i {
  stop-color: var(--svg-color--b384b3, #B384B3);
}

.bd8jqdorr {
  stop-color: var(--svg-color--fdc9a8, #FDC9A8);
  stop-opacity: 0;
}

.biviy7bfr {
  stop-color: var(--svg-color--bdbbbe, #BDBBBE);
}

.c_uyp7b4u {
  fill: var(--svg-color--635d5f, #635D5F);
  d: path("M18.037 17.548c.505-.887 1.273-1.588 2.924-1.588c.723 0 1.42.2 2.04.7c.512.414.443.942.047 1.14l-1.057.604c-1.24-.4-2.61-.455-3.954-.856");
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cmn1n6bms {
  stop-color: var(--svg-color--c3828a, #C3828A);
  stop-opacity: 0;
}

.cmzi6t3zf {
  d: path("m6.301 14.814l.012.01l-.001-.166c-.007-.59-.02-1.727.477-2.47c.801-1.196 1.711-1.285 2.601-1.285h12.96c2.465 0 3.081 1.796 3.081 2.694l-.085 1.054l-.016.037v6.388c-.234 5.33-4.397 8.908-9.477 8.908s-9.243-3.579-9.477-8.908l-.07-6.129z");
}

.cnl1fccua {
  d: path("M6.99 20.673a2.043 2.043 0 1 0 0-4.085a2.043 2.043 0 0 0 0 4.085");
}

.cre_5tbhq {
  stop-color: var(--svg-color--ffc89e, #FFC89E);
  stop-opacity: 0;
}

.d2rffhbfx {
  stop-color: var(--svg-color--b6b0bb, #B6B0BB);
}

.d95d_ibmu {
  d: path("M21.53 18.062a1.6 1.6 0 0 0-.44-.88l-.494.542l.223.434z");
}

.dbmxbxbzy {
  stop-color: var(--svg-color--bfb7c6, #BFB7C6);
}

.dqjzd9_8e {
  stop-color: var(--svg-color--ebeaec, #EBEAEC);
}

.dvyniwihb {
  stop-color: var(--svg-color--c57f82, #C57F82);
}

.e5pm1bciq {
  stop-color: var(--svg-color--c57f82, #C57F82);
  stop-opacity: 0;
}

.ednzh9b6g {
  stop-color: var(--svg-color--bdbbbe, #BDBBBE);
  stop-opacity: 0;
}

.ef0qz83po {
  fill: var(--svg-color--fff, #fff);
  d: path("M20.412 16.071c1.242 0 2.292.857 2.577 2.014a.52.52 0 0 1-.51.648h-4.242a.438.438 0 0 1-.432-.517a2.66 2.66 0 0 1 2.607-2.145");
}

.empsclb_z {
  d: path("M4.542 10.595c.457-.912 1.614-2.206 5.677-2.626c.406-.042 1.003-.06 1.672-.08c1.666-.05 3.775-.113 4.482-.594c.933-.445 1.973-3.245 1.54-5.28h-5.97l-6.989 2.95c-.524 1.062-.598 2.081-.597 2.695c0 .745.012 2.077.185 2.936");
}

.epx_cgb2c {
  stop-color: var(--svg-color--f6c3a3, #F6C3A3);
}

.etyder0ew {
  d: path("M26.99 12.483c.005-1.482-1.085-2.607-1.93-3.105c-1.34-.79-3.268-1.004-4.104-.999H19.47l-4.955.805l.256 1.719h7.579c2.465 0 3.102 1.792 3.043 2.694l-.055 1.146c.217 0 .866-.237 1.115-.728c.203-.4.383-.937.537-1.532");
}

.ez0-28s9u {
  fill: var(--svg-color--635d5f, #635D5F);
  d: path("M13.694 17.548c-.505-.887-1.272-1.588-2.924-1.588c-.723 0-1.42.2-2.04.7c-.512.414-.443.942-.047 1.14l1.057.604c1.24-.4 2.61-.455 3.954-.856");
}

.fi285-b6u {
  stop-color: var(--svg-color--ece8f1, #ECE8F1);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.g1fw3-bff {
  stop-color: var(--svg-color--f4c099, #F4C099);
  stop-opacity: 0;
}

.gelt6sv6v {
  d: path("M19.894 16.947c.121.162-.132.359-.42.574c-.287.214-.5.366-.62.204c-.121-.162.013-.467.3-.682c.288-.215.62-.258.74-.096");
}

.gh784hb2c {
  stop-color: var(--svg-color--85534d, #85534D);
}

.gvh2bspmv {
  stop-color: var(--svg-color--d39b88, #D39B88);
}

.hc5vad6zv {
  stop-color: var(--svg-color--bfb1c9, #BFB1C9);
}

.hgdod9bjp {
  fill: var(--svg-color--fff, #fff);
  d: path("M11.318 16.071a2.656 2.656 0 0 0-2.576 2.014a.52.52 0 0 0 .509.648h4.243c.27 0 .486-.247.432-.517a2.665 2.665 0 0 0-2.608-2.145");
}

.hji3x4euu {
  stop-color: var(--svg-color--efb696, #EFB696);
}

.hvrv4iryz {
  stop-color: var(--svg-color--d8a29e, #D8A29E);
}

.i16q27b0z {
  d: path("m15.138 17.944l-1.01 3.233c-.207.665.288 1.33.99 1.33h1.495c.701 0 1.197-.675.99-1.33l-1.01-3.233c-.217-.716-1.228-.716-1.455 0");
}

.i3g5qu-9r {
  stop-color: var(--svg-color--b97783, #B97783);
  stop-opacity: 0;
}

.ih_njzbst {
  stop-color: var(--svg-color--d3cfd9, #D3CFD9);
  stop-opacity: 0;
}

.irzp_cb7o {
  stop-color: var(--svg-color--e3ab91, #E3AB91);
}

.isvyw7ooh {
  stop-color: var(--svg-color--c0bbc4, #C0BBC4);
}

.ixxpbv8hf {
  stop-color: var(--svg-color--bbb9bd, #BBB9BD);
  stop-opacity: 0;
}

.j1honvvth {
  cx: 11.2px;
  cy: 17.313px;
  rx: 0.741px;
  ry: 0.375px;
}

.j8hkuac-d {
  stop-color: var(--svg-color--ffc89e, #FFC89E);
}

.jcrjf-b8x {
  stop-color: var(--svg-color--ebeaec, #EBEAEC);
  stop-opacity: 0;
}

.jdd1i0reo {
  stop-color: var(--svg-color--bbb9bd, #BBB9BD);
}

.jxp6cl9zo {
  d: path("M13.262 18.086c0-.549-.446-.914-.566-1.025l-.549.53l.338.688z");
}

.kkvh--b-a {
  stop-color: var(--svg-color--ddd6e4, #DDD6E4);
}

.kqfxh5bnm {
  stop-color: var(--svg-color--be7c5a, #BE7C5A);
  stop-opacity: 0;
}

.krvd34mtu {
  stop-color: var(--svg-color--d59566, #D59566);
  stop-opacity: 0;
}

.la61skb4q {
  stop-color: var(--svg-color--e3a280, #E3A280);
  stop-opacity: 0;
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lo97d1z0q {
  stop-color: var(--svg-color--bcb7c1, #BCB7C1);
}

.lwjatlajn {
  stop-color: var(--svg-color--d1987a, #D1987A);
  stop-opacity: 0;
}

.lxkykv_ud {
  stop-color: var(--svg-color--ebe6f2, #EBE6F2);
}

.m1v3gnbun {
  stop-color: var(--svg-color--b6b0bb, #B6B0BB);
  stop-opacity: 0;
}

.m71s56bwv {
  stop-color: var(--svg-color--e0dae8, #E0DAE8);
  stop-opacity: 0;
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mcdrc7blw {
  stop-color: var(--svg-color--fafafa, #FAFAFA);
}

.mih5kfbap {
  stop-color: var(--svg-color--be7c5a, #BE7C5A);
}

.mt3h7fbpd {
  stop-color: var(--svg-color--e3a48e, #E3A48E);
}

.mvpyyqb8k {
  stop-color: var(--svg-color--b8b2be, #B8B2BE);
  stop-opacity: 0;
}

.n644_45yf {
  d: path("M11.712 16.588a1.697 1.697 0 0 0-1.636 2.145h3.279c.038-.147.062-.294.062-.448a1.71 1.71 0 0 0-1.705-1.697");
}

.n79ty2bbc {
  fill: var(--svg-color--956032, #956032);
  fill-rule: evenodd;
  d: path("m22.962 14.38l-.262.437za.51.51 0 0 1-.525.875l-.008-.005l-.041-.023a5 5 0 0 0-.825-.344c-.552-.176-1.28-.309-2.039-.175a.51.51 0 0 1-.177-1.005c.976-.172 1.88.002 2.526.208a6 6 0 0 1 1 .42l.062.034l.018.01l.006.003z");
}

.n9tnz5ikc {
  d: path("M25.046 20.673a2.043 2.043 0 1 0 0-4.085a2.043 2.043 0 0 0 0 4.085");
}

.nemspp6bt {
  stop-color: var(--svg-color--efb696, #EFB696);
  stop-opacity: 0;
}

.nka4--b6e {
  stop-color: var(--svg-color--c48b78, #C48B78);
}

.nmcqtrbfm {
  stop-color: var(--svg-color--a87b9c, #A87B9C);
}

.nsg0945ca {
  stop-color: var(--svg-color--dbdbdc, #DBDBDC);
}

.nsmntj3ul {
  stop-color: var(--svg-color--d2d1d3, #D2D1D3);
}

.nsn47rbed {
  d: path("M4.552 10.644c.193 2.806 1.397 3.89 1.761 4.18c0-.515-.074-1.815.476-2.636c.801-1.196 1.711-1.285 2.601-1.285h12.96c2.465 0 3.081 1.796 3.081 2.694l-.093 1.146c.217 0 .866-.237 1.115-.728c.65-1.285 1.068-3.963 1.161-5.527s.031-2.764-1.192-4.452c-.979-1.35-2.795-2.02-4.42-2.02H10.45c-3.712 0-4.678 1.406-5.42 2.8c-.594 1.114-.675 2.2-.674 2.843c0 .759.012 2.128.195 2.985");
}

.nzgowqbpe {
  fill: var(--svg-color--000, #000);
  d: path("M19.047 18.285c0-.54.432-.972.972-.972s.972.432.972.972a.96.96 0 0 1-.108.448h-1.72a.9.9 0 0 1-.116-.448");
}

.o02xvvb7n {
  stop-color: var(--svg-color--b384b3, #B384B3);
  stop-opacity: 0;
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.opjf3kbfq {
  d: path("m20.417 2.016l.055 2.427c1.224-.031 3.562.082 5.578 1.227c.85.482 1.29.992 1.574 1.413c-.073-.969-.366-1.894-1.202-3.047c-.979-1.35-2.795-2.02-4.42-2.02z");
}

.p__cvka-s {
  fill: var(--svg-color--000, #000);
  d: path("M12.684 18.285a.97.97 0 0 0-.972-.972a.97.97 0 0 0-.972.972c0 .162.038.316.108.448h1.72a.96.96 0 0 0 .116-.448");
}

.p6ygghbxv {
  stop-color: var(--svg-color--d3cfd9, #D3CFD9);
}

.phr-zrige {
  stop-color: var(--svg-color--d0ccd3, #D0CCD3);
  stop-opacity: 0;
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.prydr8bcy {
  stop-color: var(--svg-color--b0725a, #B0725A);
  stop-opacity: 0;
}

.q2rl-9b2o {
  stop-color: var(--svg-color--cfcad4, #CFCAD4);
}

.q31ht9hnt {
  stop-color: var(--svg-color--b36f92, #B36F92);
}

.q61vir6ce {
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M15.865 24.168a5.76 5.76 0 0 1-2.703-.655c-.268-.14-.555.168-.386.417a3.67 3.67 0 0 0 3.09 1.688a3.67 3.67 0 0 0 3.09-1.688c.168-.259-.12-.557-.387-.418a5.7 5.7 0 0 1-2.704.656Z");
}

.q9wqsddqp {
  stop-color: var(--svg-color--b5b4b6, #B5B4B6);
}

.qfleuzzqm {
  stop-color: var(--svg-color--a5a0a9, #A5A0A9);
}

.qmmvvysmp {
  stop-color: var(--svg-color--e1a792, #E1A792);
}

.qnoj66lkr {
  stop-color: var(--svg-color--f5f4f6, #F5F4F6);
}

.qt9c-0dps {
  stop-color: var(--svg-color--bcb7c1, #BCB7C1);
  stop-opacity: 0;
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.qw_ssccar {
  stop-color: var(--svg-color--b8b2be, #B8B2BE);
}

.qxbo6kk2p {
  stop-color: var(--svg-color--eee8f4, #EEE8F4);
}

.r-jog4w_t {
  stop-color: var(--svg-color--c2847a, #C2847A);
}

.r3imb_bxi {
  d: path("M4.357 7.752c.557-.67 1.563-1.613 2.897-1.974c1.879-.509 4.836-.733 6.069-.82c.45.025 1.556-.442 1.556-1.61c0-.434-.016-.89-.053-1.332H10.45c-3.712 0-4.678 1.406-5.42 2.8c-.594 1.114-.675 2.2-.674 2.843z");
}

.r6yvhvbxp {
  fill: var(--svg-color--efb696, #EFB696);
  d: path("m15.138 17.944l-1.01 3.233c-.207.665.288 1.33.99 1.33h1.495c.701 0 1.197-.675.99-1.33l-1.01-3.233c-.217-.716-1.228-.716-1.455 0");
}

.rdwuebbdx {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M19.894 16.947c.121.162-.132.359-.42.574c-.287.214-.5.366-.62.204c-.121-.162.013-.467.3-.682c.288-.215.62-.258.74-.096");
}

.rjs9uccph {
  stop-color: var(--svg-color--d1cad9, #D1CAD9);
  stop-opacity: 0;
}

.rn9c96bjh {
  fill: var(--svg-color--956032, #956032);
  d: path("m9.404 15.25l-.009.004a.51.51 0 0 1-.524-.875h.001l.002-.002l.006-.003l.017-.01l.062-.034q.08-.045.22-.112c.188-.09.455-.204.78-.308c.647-.206 1.551-.38 2.527-.207a.51.51 0 0 1-.178 1.004c-.758-.134-1.486-.001-2.038.175a5 5 0 0 0-.866.367");
}

.rnyxtsb4p {
  stop-color: var(--svg-color--ddddde, #DDDDDE);
}

.rq033_icj {
  stop-color: var(--svg-color--bfb7c6, #BFB7C6);
  stop-opacity: 0;
}

.s_fkwccyi {
  stop-color: var(--svg-color--cfc8d7, #CFC8D7);
}

.s2ksypb6u {
  stroke: var(--svg-color--a57045, #A57045);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M12.192 14.088c-.614-.15-2.139-.075-3.158.655");
}

.s6qc0ccmr {
  cx: 11.2px;
  cy: 17.313px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.741px;
  ry: 0.375px;
}

.s6vdf8bty {
  stop-color: var(--svg-color--f8f6fb, #F8F6FB);
}

.s9p5w3b7j {
  d: path("M20.019 16.588a1.697 1.697 0 0 1 1.635 2.145h-3.278a1.7 1.7 0 0 1-.062-.448c0-.933.764-1.697 1.705-1.697");
}

.spe-wrvgh {
  fill: var(--svg-color--b47a6c, #B47A6C);
  d: path("M6.99 20.673a2.043 2.043 0 1 0 0-4.085a2.043 2.043 0 0 0 0 4.085");
}

.t6jzi2-1t {
  stop-color: var(--svg-color--b97783, #B97783);
}

.tvh3rxb7z {
  d: path("M6.954 21.691a3.06 3.06 0 1 0 0-6.12a3.06 3.06 0 0 0 0 6.12");
}

.u1r8ksb5m {
  stop-color: var(--svg-color--d8a29e, #D8A29E);
  stop-opacity: 0;
}

.urkjpbftr {
  stop-color: var(--svg-color--d1987a, #D1987A);
}

.urs_pbb4x {
  stop-color: var(--svg-color--e3a280, #E3A280);
}

.uy3z2gbbp {
  stop-color: var(--svg-color--ffc59d, #FFC59D);
}

.v60bq3cin {
  stop-color: var(--svg-color--925c51, #925C51);
}

.w-6axbcrg {
  stroke: var(--svg-color--a57045, #A57045);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M19.663 14.088c.614-.15 2.139-.075 3.159.655");
}

.w6o2k5blk {
  d: path("m15.138 17.598l-1.01 3.233c-.207.665.288 1.33.99 1.33h1.495c.701 0 1.197-.675.99-1.33l-1.01-3.233c-.217-.716-1.228-.716-1.455 0");
}

.w7pk8_-qm {
  stop-color: var(--svg-color--e2dce8, #E2DCE8);
}

.w98e9_6zv {
  stop-color: var(--svg-color--d0ccd3, #D0CCD3);
}

.w9crknafl {
  stop-color: var(--svg-color--a87b9c, #A87B9C);
  stop-opacity: 0;
}

.wa-728m0i {
  fill: var(--svg-color--88014e, #88014E);
  d: path("M15.865 24.168a5.76 5.76 0 0 1-2.703-.655c-.268-.14-.555.168-.386.417a3.67 3.67 0 0 0 3.09 1.688a3.67 3.67 0 0 0 3.09-1.688c.168-.259-.12-.557-.387-.418a5.7 5.7 0 0 1-2.704.656");
}

.wcr1klbjh {
  stop-color: var(--svg-color--e3a48e, #E3A48E);
  stop-opacity: 0;
}

.wfm74pxcd {
  stop-color: var(--svg-color--e2dce8, #E2DCE8);
  stop-opacity: 0;
}

.wvn8vtban {
  stop-color: var(--svg-color--c5c2c8, #C5C2C8);
  stop-opacity: 0;
}

.x7ia8vuzd {
  stop-color: var(--svg-color--f1edf4, #F1EDF4);
}

.xjkdvxqyn {
  stop-color: var(--svg-color--c2847a, #C2847A);
  stop-opacity: 0;
}

.xjug-415a {
  stop-color: var(--svg-color--fdc9a8, #FDC9A8);
}

.ybx_6zbxd {
  stop-color: var(--svg-color--b0725a, #B0725A);
}

.ycobh_6lz {
  d: path("M25.046 21.691a3.06 3.06 0 1 0 0-6.12a3.06 3.06 0 0 0 0 6.12");
}

.yhs2bn2id {
  stop-color: var(--svg-color--f4c099, #F4C099);
}

.zflxaub1u {
  fill: var(--svg-color--c28178, #C28178);
  d: path("m15.119 18.207l-1.3 3.233c-.206.665.289 1.33.99 1.33h1.496c.7 0 1.196-.675.99-1.33l-1.011-3.233c-.217-.716-.938-.716-1.165 0");
}

.zl7ej5b_j {
  fill: var(--svg-color--e5aa8b, #E5AA8B);
  d: path("M25.046 20.673a2.043 2.043 0 1 0 0-4.085a2.043 2.043 0 0 0 0 4.085");
}

.zz39r5b3o {
  stop-color: var(--svg-color--c5c2c8, #C5C2C8);
}

.zzstxpr9j {
  stop-color: var(--svg-color--e3ab91, #E3AB91);
  stop-opacity: 0;
}

</style>
