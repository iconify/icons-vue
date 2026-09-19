<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<defs><path id="iOd1Vsb" class="vwwlod5tb"/></defs><g class="ft5dv1b6b"><g filter="url(#imdgcSd)"><path fill="url(#iJGvNWb)" class="jqrsdeafm"/></g><g filter="url(#iMBZFKd)"><path fill="url(#i5Xhs8T)" class="vjgrxi2qw"/><path fill="url(#iMltmod)" class="vjgrxi2qw"/></g><g filter="url(#iO71lSd)"><path class="yeh-4kb4a"/><path fill="url(#iemouqx)" class="oazx0zdky"/></g><g filter="url(#ieHgwid)"><path class="o0haeebrm"/><path fill="url(#i1VXOGd)" class="ap6-qctaz"/></g><path fill="url(#iAiNHae)" class="nsn47rbed"/><path fill="url(#iBcFe2d)" class="nsn47rbed"/><path fill="url(#iZXhLkE)" class="nsn47rbed"/><g filter="url(#ijjJgHn)"><path fill="url(#iynkrQd)" class="r_e9t9m_k"/><path fill="url(#icfzW0c)" class="r_e9t9m_k"/><path fill="url(#i0b32qs)" class="r_e9t9m_k"/><path fill="url(#i2L4sHe)" class="r_e9t9m_k"/><path fill="url(#iuTXfQc)" class="r_e9t9m_k"/><path fill="url(#ifVwhMx)" class="r_e9t9m_k"/><path fill="url(#iq7m4QM)" class="r_e9t9m_k"/><path fill="url(#ivXm1fe)" class="r_e9t9m_k"/><path fill="url(#iVPXvjd)" class="r_e9t9m_k"/></g><path fill="url(#iiwMBCf)" class="r_e9t9m_k"/><path fill="url(#ieYMYNc)" class="r_e9t9m_k"/><path fill="url(#ii2zjwd)" class="r_e9t9m_k"/><g filter="url(#i90yAZc)"><path fill="url(#i5EYg7b)" class="opjf3kbfq"/><path fill="url(#ixY9nMe)" class="opjf3kbfq"/></g><g filter="url(#iGJYX7b)"><path fill="url(#iLPDbid)" class="m9efqem2s"/></g><path fill="url(#iZrVsec)" class="m9efqem2s"/><path fill="url(#iDxKDTb)" class="m9efqem2s"/><path fill="url(#iOK7KGi)" class="m9efqem2s"/><g filter="url(#ib3xgBd)"><path fill="url(#if2XEiA)" class="ajkq73jxq"/></g><path fill="url(#iUlKGqd)" class="ajkq73jxq"/><path fill="url(#i8KfJqF)" class="ajkq73jxq"/><path fill="url(#iAMx8mb)" class="ajkq73jxq"/><path fill="url(#iRXTsMd)" class="ajkq73jxq"/><path fill="url(#ittfgOd)" class="ajkq73jxq"/><g filter="url(#ieBnXTb)"><path fill="url(#iRtnCtc)" class="empsclb_z"/><path fill="url(#iFLgi9b)" class="empsclb_z"/><path fill="url(#iHoI0yb)" class="empsclb_z"/><path fill="url(#iaumesd)" class="empsclb_z"/><path fill="url(#i3pO2hc)" class="empsclb_z"/></g><g filter="url(#icbfqre)"><path fill="url(#i2cEdqd)" class="r3imb_bxi"/></g><path fill="url(#iXxQ0Oe)" class="r3imb_bxi"/><path fill="url(#iBQf8Bd)" class="r3imb_bxi"/><g filter="url(#iifTlFJ)"><path class="o8dy3hheh"/></g><g filter="url(#iSglW2W)"><path class="i2jjtyqhr"/><path fill="url(#i5hX5ib)" class="obw0imwoz"/><path fill="url(#iv8itYo)" class="obw0imwoz"/><path fill="url(#i36nGJe)" class="obw0imwoz"/><path fill="url(#iwo2YvH)" class="obw0imwoz"/></g><g filter="url(#iKsKhUc)"><path fill="url(#iqP1j4c)" class="vxblmsj4h"/></g><g filter="url(#i3QL6yb)"><use href="#iOd1Vsb"/><path stroke="url(#ip19IPd)" class="lv_ze4bos"/></g><use href="#iOd1Vsb"/><g filter="url(#i2gUBze)"><path class="j-wsjf_jj"/></g><g filter="url(#iFdkEIc)"><path class="vex46bbmn"/></g><g filter="url(#izpiS7o)"><path class="kk5kzjxzh"/></g><g filter="url(#ig4ynHk)"><path clip-rule="evenodd" class="pqj6bioog"/></g><path class="a_um2hbdh"/><path fill="url(#ivZzDvB)" class="vtmaael7d"/><path class="ly_7e_lbd"/><g filter="url(#igzF2se)"><path class="rc8hkzs9u"/><path fill="url(#iGps0WW)" class="xk4rg9b0l"/></g><g filter="url(#icU2IEb)"><path fill="url(#i0vzjGb)" class="yo7rwbb1x"/></g><path class="ggsky7blk"/><path fill="url(#iwKNjfb)" class="uw_0kccnw"/><path class="afej9acvw"/><g filter="url(#i4Josbb)"><path fill="url(#iz5U8fb)" class="bu0h-eudr"/></g><g filter="url(#iOc1JEd)"><ellipse transform="rotate(-27.914 11.2 17.29)" class="bbtlhwboq"/><ellipse fill="url(#iyDXqRA)" transform="rotate(-27.914 11.2 17.29)" class="c_enu_b8j"/></g><g filter="url(#iYOBxic)"><path class="zk6usj6rs"/></g><g filter="url(#iclMzqc)"><path class="migzlo1qy"/></g><defs><radialGradient id="i5Xhs8T" cx="0" cy="0" r="1" gradientTransform="matrix(4.73366 -2.15167 2.62709 5.77958 23.548 19.443)" gradientUnits="userSpaceOnUse"><stop offset=".64" class="olqyf7fmb"/><stop offset=".944" class="hpeo8yzih"/></radialGradient><radialGradient id="iMltmod" cx="0" cy="0" r="1" gradientTransform="matrix(2.5023 1.40257 -.39653 .70744 25.508 15.41)" gradientUnits="userSpaceOnUse"><stop class="mt9k2qzvi"/><stop offset="1" class="fx1tjiblm"/></radialGradient><radialGradient id="iemouqx" cx="0" cy="0" r="1" gradientTransform="matrix(2.8715 -.2136 .16697 2.2447 24.217 18.82)" gradientUnits="userSpaceOnUse"><stop offset=".719" class="l__dw9bpv"/><stop offset="1" class="wrh2b4bbx"/></radialGradient><radialGradient id="i1VXOGd" cx="0" cy="0" r="1" gradientTransform="rotate(180 3.558 9.304)scale(2.00822)" gradientUnits="userSpaceOnUse"><stop offset=".722" class="o3wo53bzp"/><stop offset="1" class="eo_7g0bzd"/></radialGradient><radialGradient id="iAiNHae" cx="0" cy="0" r="1" gradientTransform="matrix(-.84218 3.75478 -8.78476 -1.97039 25.881 5.042)" gradientUnits="userSpaceOnUse"><stop class="s6vdf8bty"/><stop offset=".789" class="lxkykv_ud"/></radialGradient><radialGradient id="iBcFe2d" cx="0" cy="0" r="1" gradientTransform="matrix(2.09375 .53125 -1.15317 4.54483 20.347 6.676)" gradientUnits="userSpaceOnUse"><stop offset=".152" class="q2rl-9b2o"/><stop offset="1" class="fi285-b6u"/></radialGradient><radialGradient id="iZXhLkE" cx="0" cy="0" r="1" gradientTransform="matrix(1.5 -2.625 6.33197 3.61827 22.284 10.52)" gradientUnits="userSpaceOnUse"><stop class="p6ygghbxv"/><stop offset="1" class="ih_njzbst"/></radialGradient><radialGradient id="iynkrQd" cx="0" cy="0" r="1" gradientTransform="matrix(-12.3684 5.70348 -7.63403 -16.55492 21.303 17.585)" gradientUnits="userSpaceOnUse"><stop class="crj44uotj"/><stop offset="1" class="yamoh3dov"/></radialGradient><radialGradient id="icfzW0c" cx="0" cy="0" r="1" gradientTransform="rotate(156.249 7.787 11.667)scale(4.53012 3.1547)" gradientUnits="userSpaceOnUse"><stop class="up8l18w-p"/><stop offset="1" class="ai95fabuh"/></radialGradient><radialGradient id="i0b32qs" cx="0" cy="0" r="1" gradientTransform="rotate(-71.832 26.56 6.867)scale(7.86291 9.97658)" gradientUnits="userSpaceOnUse"><stop class="osxg47drp"/><stop offset="1" class="da7h3oe0u"/></radialGradient><radialGradient id="i2L4sHe" cx="0" cy="0" r="1" gradientTransform="matrix(0 13.0372 -14.085 0 15.86 16.947)" gradientUnits="userSpaceOnUse"><stop offset=".7" class="utuphuu_g"/><stop offset="1" class="bsxz4fbna"/></radialGradient><radialGradient id="iuTXfQc" cx="0" cy="0" r="1" gradientTransform="matrix(-13.03755 .06258 -.10774 -22.44674 19.328 22.635)" gradientUnits="userSpaceOnUse"><stop offset=".753" class="opgioqbtx"/><stop offset=".95" class="wg3eepbwp"/></radialGradient><radialGradient id="ifVwhMx" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.18852 2.68591 0 20.242 16.79)" gradientUnits="userSpaceOnUse"><stop class="t9k87pm2r"/><stop offset="1" class="ax9af2vtk"/></radialGradient><radialGradient id="iq7m4QM" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.49612 2.86073 0 11.916 16.355)" gradientUnits="userSpaceOnUse"><stop class="x_ik4kbfh"/><stop offset="1" class="gcfqr7bfg"/></radialGradient><radialGradient id="ivXm1fe" cx="0" cy="0" r="1" gradientTransform="rotate(105.092 4.504 13.277)scale(6.35581 5.08569)" gradientUnits="userSpaceOnUse"><stop class="uj7hgsb3u"/><stop offset="1" class="p88c31myn"/></radialGradient><radialGradient id="iVPXvjd" cx="0" cy="0" r="1" gradientTransform="rotate(126.365 7.525 10.127)scale(7.21822 3.61963)" gradientUnits="userSpaceOnUse"><stop class="lun1rzujg"/><stop offset="1" class="n7j-lccxy"/></radialGradient><radialGradient id="iiwMBCf" cx="0" cy="0" r="1" gradientTransform="matrix(-2.414 0 0 -11.3076 25.431 20.444)" gradientUnits="userSpaceOnUse"><stop class="zoq8fuaif"/><stop offset="1" class="ycrcotb4u"/></radialGradient><radialGradient id="ieYMYNc" cx="0" cy="0" r="1" gradientTransform="rotate(-123.339 19.067 8.207)scale(2.72329 2.97871)" gradientUnits="userSpaceOnUse"><stop class="ni-4se4rm"/><stop offset="1" class="wsh5tsbcf"/></radialGradient><radialGradient id="ii2zjwd" cx="0" cy="0" r="1" gradientTransform="rotate(-39.827 43.64 2.881)scale(4.27984 5.03126)" gradientUnits="userSpaceOnUse"><stop class="z26rrllgi"/><stop offset="1" class="fs9pa7bci"/></radialGradient><radialGradient id="i5EYg7b" cx="0" cy="0" r="1" gradientTransform="matrix(.17188 2.91016 -14.53547 .85847 21.253 2.016)" gradientUnits="userSpaceOnUse"><stop class="nsg0945ca"/><stop offset="1" class="mcdrc7blw"/></radialGradient><radialGradient id="ixY9nMe" cx="0" cy="0" r="1" gradientTransform="matrix(1.45313 0 0 5.1925 20.8 3.332)" gradientUnits="userSpaceOnUse"><stop offset=".253" class="w7pk8_-qm"/><stop offset="1" class="wfm74pxcd"/></radialGradient><radialGradient id="iZrVsec" cx="0" cy="0" r="1" gradientTransform="matrix(2.46875 1.71875 -3.03125 4.35398 17.69 9.051)" gradientUnits="userSpaceOnUse"><stop offset=".391" class="hc5vad6zv"/><stop offset="1" class="m71s56bwv"/></radialGradient><radialGradient id="iDxKDTb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.93844 1.49148 0 24.653 14.5)" gradientUnits="userSpaceOnUse"><stop offset=".306" class="b5m4mk31i"/><stop offset="1" class="o02xvvb7n"/></radialGradient><radialGradient id="iOK7KGi" cx="0" cy="0" r="1" gradientTransform="matrix(3.71875 0 0 .30337 18.753 8.676)" gradientUnits="userSpaceOnUse"><stop class="w98e9_6zv"/><stop offset="1" class="phr-zrige"/></radialGradient><radialGradient id="if2XEiA" cx="0" cy="0" r="1" gradientTransform="matrix(-4.28125 -.09372 .19553 -8.93238 21.565 5.582)" gradientUnits="userSpaceOnUse"><stop class="qnoj66lkr"/><stop offset="1" class="s_fkwccyi"/></radialGradient><radialGradient id="iUlKGqd" cx="0" cy="0" r="1" gradientTransform="matrix(11.55068 3.52232 -4.80864 15.76891 9.13 5.736)" gradientUnits="userSpaceOnUse"><stop offset=".633" class="rjs9uccph"/><stop offset=".952" class="x7ia8vuzd"/></radialGradient><radialGradient id="i8KfJqF" cx="0" cy="0" r="1" gradientTransform="matrix(1.11064 -4.72815 1.61144 .37853 16.84 4.594)" gradientUnits="userSpaceOnUse"><stop offset=".348" class="zz39r5b3o"/><stop offset="1" class="wvn8vtban"/></radialGradient><radialGradient id="iAMx8mb" cx="0" cy="0" r="1" gradientTransform="matrix(-.06346 1.33277 -6.75892 -.32185 9.193 7.386)" gradientUnits="userSpaceOnUse"><stop class="biviy7bfr"/><stop offset="1" class="ednzh9b6g"/></radialGradient><radialGradient id="iRXTsMd" cx="0" cy="0" r="1" gradientTransform="matrix(-13.48639 2.82409 -3.69438 -17.64244 17.539 7.513)" gradientUnits="userSpaceOnUse"><stop offset=".681" class="rq033_icj"/><stop offset="1" class="dbmxbxbzy"/></radialGradient><radialGradient id="ittfgOd" cx="0" cy="0" r="1" gradientTransform="matrix(.88851 -3.93483 2.3195 .52376 6.94 14.494)" gradientUnits="userSpaceOnUse"><stop offset=".201" class="nmcqtrbfm"/><stop offset="1" class="w9crknafl"/></radialGradient><radialGradient id="iRtnCtc" cx="0" cy="0" r="1" gradientTransform="rotate(137.988 8.553 4.64)scale(9.89862 9.45071)" gradientUnits="userSpaceOnUse"><stop class="rnyxtsb4p"/><stop offset="1" class="isvyw7ooh"/></radialGradient><radialGradient id="iFLgi9b" cx="0" cy="0" r="1" gradientTransform="matrix(-1.78125 0 0 -4.75 18.44 3.488)" gradientUnits="userSpaceOnUse"><stop class="dqjzd9_8e"/><stop offset="1" class="jcrjf-b8x"/></radialGradient><radialGradient id="iaumesd" cx="0" cy="0" r="1" gradientTransform="matrix(5.90625 .125 -.02777 1.31192 10.128 4.113)" gradientUnits="userSpaceOnUse"><stop class="qw_ssccar"/><stop offset="1" class="mvpyyqb8k"/></radialGradient><radialGradient id="i3pO2hc" cx="0" cy="0" r="1" gradientTransform="matrix(1.28125 -.09375 .17757 2.4268 14.128 2.457)" gradientUnits="userSpaceOnUse"><stop offset=".256" class="jdd1i0reo"/><stop offset="1" class="ixxpbv8hf"/></radialGradient><radialGradient id="i2cEdqd" cx="0" cy="0" r="1" gradientTransform="matrix(-8.06249 1.65631 -3.03846 -14.79042 14.534 2.582)" gradientUnits="userSpaceOnUse"><stop class="nsmntj3ul"/><stop offset="1" class="q9wqsddqp"/></radialGradient><radialGradient id="iXxQ0Oe" cx="0" cy="0" r="1" gradientTransform="matrix(8.03125 .96875 -1.11478 9.24187 7.253 3.238)" gradientUnits="userSpaceOnUse"><stop offset=".869" class="atp4gmb-q"/><stop offset="1" class="qfleuzzqm"/></radialGradient><radialGradient id="iBQf8Bd" cx="0" cy="0" r="1" gradientTransform="matrix(2.71875 -2.3259 1.71042 1.99932 4.597 7.752)" gradientUnits="userSpaceOnUse"><stop class="lo97d1z0q"/><stop offset="1" class="qt9c-0dps"/></radialGradient><radialGradient id="i5hX5ib" cx="0" cy="0" r="1" gradientTransform="matrix(-.86635 -3.88728 1.19803 -.267 17.357 21)" gradientUnits="userSpaceOnUse"><stop offset=".017" class="bof3uzbpf"/><stop offset="1" class="jaf6nfbfs"/></radialGradient><radialGradient id="iwo2YvH" cx="0" cy="0" r="1" gradientTransform="matrix(-1.48226 0 0 -.4144 16.901 21.403)" gradientUnits="userSpaceOnUse"><stop class="bof3uzbpf"/><stop offset="1" class="jaf6nfbfs"/></radialGradient><radialGradient id="ivZzDvB" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.54295 -2.45424 0 20.015 17.472)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="iGps0WW" cx="0" cy="0" r="1" gradientTransform="rotate(-127.812 14.108 4.02)scale(.71942 .99047)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iwKNjfb" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.54296 -2.45425 0 11.715 17.472)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="iyDXqRA" cx="0" cy="0" r="1" gradientTransform="matrix(-.01471 -.9396 1.12943 -.01768 11.17 17.888)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><filter id="imdgcSd" width="6.27" height="6.12" x="3.894" y="15.547" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.509804 0 0 0 0 0.376471 0 0 0 0 0.34902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3100"/></filter><filter id="iMBZFKd" width="6.12" height="6.37" x="21.986" y="15.297" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.431373 0 0 0 0 0.243137 0 0 0 0 0.282353 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3100"/></filter><filter id="iO71lSd" width="5.085" height="5.085" x="22.503" y="16.064" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3100" stdDeviation=".25"/></filter><filter id="ieHgwid" width="4.585" height="4.585" x="4.698" y="16.314" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3100" stdDeviation=".125"/></filter><filter id="ijjJgHn" width="19.14" height="19.331" x="6.291" y="10.903" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".25"/><feGaussianBlur stdDeviation=".175"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.407843 0 0 0 0 0.223529 0 0 0 0 0.25098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3100"/></filter><filter id="i90yAZc" width="7.307" height="5.168" x="20.417" y="1.916" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.843137 0 0 0 0 0.8 0 0 0 0 0.890196 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3100"/></filter><filter id="iGJYX7b" width="12.925" height="6.714" x="14.465" y="8.129" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.05" dy=".1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.992157 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3100"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4" dy="-.25"/><feGaussianBlur stdDeviation=".325"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.670588 0 0 0 0 0.560784 0 0 0 0 0.756863 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_3100" result="effect2_innerShadow_4002_3100"/></filter><filter id="ib3xgBd" width="17.006" height="13.059" x="4.107" y="1.766" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25" dy="-.25"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.603922 0 0 0 0 0.45098 0 0 0 0 0.721569 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3100"/></filter><filter id="ieBnXTb" width="13.757" height="8.679" x="4.257" y="1.916" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy="-.1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.611765 0 0 0 0 0.588235 0 0 0 0 0.635294 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3100"/></filter><filter id="icbfqre" width="10.523" height="5.986" x="4.357" y="1.816" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.686275 0 0 0 0 0.619608 0 0 0 0 0.752941 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3100"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".05"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.705882 0 0 0 0 0.701961 0 0 0 0 0.705882 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_3100" result="effect2_innerShadow_4002_3100"/></filter><filter id="iifTlFJ" width="4.57" height="6.1" x="13.271" y="17.146" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3100" stdDeviation=".25"/></filter><filter id="iSglW2W" width="4.07" height="5.6" x="13.83" y="17.133" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3100" stdDeviation=".125"/></filter><filter id="iKsKhUc" width="4.07" height="5.6" x="13.801" y="16.909" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3100" stdDeviation=".125"/></filter><filter id="i3QL6yb" width="6.68" height="2.541" x="12.525" y="23.253" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3100" stdDeviation=".05"/></filter><filter id="i2gUBze" width="5.528" height="2.445" x="17.837" y="15.936" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0941176 0 0 0 0 0.0666667 0 0 0 0 0.117647 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3100"/></filter><filter id="iFdkEIc" width="5.528" height="2.445" x="8.366" y="15.936" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0862745 0 0 0 0 0.054902 0 0 0 0 0.113725 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3100"/></filter><filter id="izpiS7o" width="4.484" height="1.895" x="8.623" y="13.409" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.164706 0 0 0 0 0.0901961 0 0 0 0 0.109804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3100"/></filter><filter id="ig4ynHk" width="4.484" height="1.895" x="18.925" y="13.409" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.164706 0 0 0 0 0.0901961 0 0 0 0 0.109804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3100"/></filter><filter id="igzF2se" width="1.316" height="1.144" x="18.709" y="16.725" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3100" stdDeviation=".05"/></filter><filter id="icU2IEb" width="1.334" height="1.376" x="20.396" y="16.959" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3100" stdDeviation=".1"/></filter><filter id="i4Josbb" width="1.515" height="1.618" x="11.947" y="16.838" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3100" stdDeviation=".1"/></filter><filter id="iOc1JEd" width="1.556" height="1.159" x="10.421" y="16.71" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3100" stdDeviation=".05"/></filter><filter id="iYOBxic" width="3.758" height="1.318" x="19.254" y="13.732" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3100" stdDeviation=".1"/></filter><filter id="iclMzqc" width="3.758" height="1.318" x="8.886" y="13.732" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3100" stdDeviation=".1"/></filter><linearGradient id="iJGvNWb" x1="3.991" x2="6.35" y1="18.773" y2="18.773" gradientUnits="userSpaceOnUse"><stop class="b9k-3ybvb"/><stop offset="1" class="vbw-bobru"/></linearGradient><linearGradient id="iLPDbid" x1="26.159" x2="15.409" y1="13.582" y2="13.582" gradientUnits="userSpaceOnUse"><stop class="qxbo6kk2p"/><stop offset="1" class="kkvh--b-a"/></linearGradient><linearGradient id="iHoI0yb" x1="4.357" x2="8.534" y1="9.551" y2="8.582" gradientUnits="userSpaceOnUse"><stop class="d2rffhbfx"/><stop offset="1" class="m1v3gnbun"/></linearGradient><linearGradient id="iv8itYo" x1="14.08" x2="15.865" y1="21.139" y2="21.139" gradientUnits="userSpaceOnUse"><stop class="rby1z7ber"/><stop offset="1" class="dl0nwov2w"/></linearGradient><linearGradient id="i36nGJe" x1="15.865" x2="15.865" y1="22.659" y2="21.498" gradientUnits="userSpaceOnUse"><stop class="cyl8wapbv"/><stop offset="1" class="jplc2lvem"/></linearGradient><linearGradient id="iqP1j4c" x1="15.836" x2="15.836" y1="17.159" y2="19.422" gradientUnits="userSpaceOnUse"><stop class="x-hxb0kwa"/><stop offset="1" class="hdz2uubro"/></linearGradient><linearGradient id="ip19IPd" x1="13.841" x2="14.718" y1="25.34" y2="23.985" gradientUnits="userSpaceOnUse"><stop class="lwz87437z"/><stop offset=".663" class="c7jfumw-i"/></linearGradient><linearGradient id="i0vzjGb" x1="21.494" x2="20.898" y1="17.575" y2="17.942" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iz5U8fb" x1="13.13" x2="12.533" y1="17.575" y2="17.942" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:woman-wearing-turban-medium-dark" /></template>
<style>
.a_um2hbdh {
  fill: var(--svg-color--fff, #fff);
  d: path("M20.412 16.048c1.242 0 2.292.856 2.577 2.013a.52.52 0 0 1-.51.648h-4.242a.438.438 0 0 1-.432-.516a2.66 2.66 0 0 1 2.607-2.145");
}

.afej9acvw {
  fill: var(--svg-color--000, #000);
  d: path("M12.684 18.262a.97.97 0 0 0-.972-.972a.97.97 0 0 0-.972.972c0 .162.038.316.108.448h1.72a.96.96 0 0 0 .116-.448");
}

.ai95fabuh {
  stop-color: var(--svg-color--986b5a, #986B5A);
  stop-opacity: 0;
}

.ajkq73jxq {
  d: path("M20.946 2.016c.357 1.961.193 4.54-1.02 6.425c-.921 1.434-2.18 2.462-3.472 2.462H9.39c-.89 0-1.8.09-2.6 1.285c-.499.743-.485 1.88-.478 2.47l.001.166c-.364-.29-1.568-1.374-1.761-4.18c-.183-.857-.195-2.226-.195-2.985c0-.642.08-1.73.673-2.844c.743-1.393 1.71-2.8 5.42-2.8z");
}

.ap6-qctaz {
  d: path("M6.99 20.65a2.043 2.043 0 1 0 0-4.085a2.043 2.043 0 0 0 0 4.085");
}

.atp4gmb-q {
  stop-color: var(--svg-color--a5a0a9, #A5A0A9);
  stop-opacity: 0;
}

.ax9af2vtk {
  stop-color: var(--svg-color--875555, #875555);
  stop-opacity: 0;
}

.b5m4mk31i {
  stop-color: var(--svg-color--b384b3, #B384B3);
}

.b9k-3ybvb {
  stop-color: var(--svg-color--6a4745, #6A4745);
}

.bbtlhwboq {
  cx: 11.2px;
  cy: 17.29px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.741px;
  ry: 0.375px;
}

.biviy7bfr {
  stop-color: var(--svg-color--bdbbbe, #BDBBBE);
}

.bof3uzbpf {
  stop-color: var(--svg-color--a07a6f, #A07A6F);
}

.bsxz4fbna {
  stop-color: var(--svg-color--7d4370, #7D4370);
}

.bu0h-eudr {
  d: path("M13.262 18.063c0-.549-.446-.914-.567-1.025l-.548.53l.338.688z");
}

.c_enu_b8j {
  cx: 11.2px;
  cy: 17.29px;
  rx: 0.741px;
  ry: 0.375px;
}

.c7jfumw-i {
  stop-color: var(--svg-color--865e63, #865E63);
  stop-opacity: 0;
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.crj44uotj {
  stop-color: var(--svg-color--996b5e, #996B5E);
}

.cyl8wapbv {
  stop-color: var(--svg-color--7c455c, #7C455C);
}

.d2rffhbfx {
  stop-color: var(--svg-color--b6b0bb, #B6B0BB);
}

.da7h3oe0u {
  stop-color: var(--svg-color--743f5a, #743F5A);
  stop-opacity: 0;
}

.dbmxbxbzy {
  stop-color: var(--svg-color--bfb7c6, #BFB7C6);
}

.dl0nwov2w {
  stop-color: var(--svg-color--744c45, #744C45);
  stop-opacity: 0;
}

.dqjzd9_8e {
  stop-color: var(--svg-color--ebeaec, #EBEAEC);
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.ednzh9b6g {
  stop-color: var(--svg-color--bdbbbe, #BDBBBE);
  stop-opacity: 0;
}

.empsclb_z {
  d: path("M4.542 10.595c.457-.912 1.614-2.206 5.677-2.626c.406-.042 1.003-.06 1.672-.08c1.666-.05 3.775-.113 4.482-.594c.933-.445 1.973-3.245 1.54-5.28h-5.97l-6.989 2.95c-.524 1.062-.598 2.081-.597 2.695c0 .745.012 2.077.185 2.936");
}

.eo_7g0bzd {
  stop-color: var(--svg-color--5a3638, #5A3638);
}

.fi285-b6u {
  stop-color: var(--svg-color--ece8f1, #ECE8F1);
  stop-opacity: 0;
}

.fs9pa7bci {
  stop-color: var(--svg-color--6e494b, #6E494B);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.fx1tjiblm {
  stop-color: var(--svg-color--755041, #755041);
  stop-opacity: 0;
}

.gcfqr7bfg {
  stop-color: var(--svg-color--714350, #714350);
  stop-opacity: 0;
}

.ggsky7blk {
  fill: var(--svg-color--fff, #fff);
  d: path("M11.318 16.048a2.656 2.656 0 0 0-2.577 2.013a.52.52 0 0 0 .51.648h4.243c.27 0 .486-.246.432-.516a2.664 2.664 0 0 0-2.608-2.145");
}

.hc5vad6zv {
  stop-color: var(--svg-color--bfb1c9, #BFB1C9);
}

.hdz2uubro {
  stop-color: var(--svg-color--8b6059, #8B6059);
  stop-opacity: 0;
}

.hpeo8yzih {
  stop-color: var(--svg-color--9d7e72, #9D7E72);
}

.i2jjtyqhr {
  fill: var(--svg-color--8a6058, #8A6058);
  d: path("m15.138 17.92l-1.01 3.233c-.207.666.288 1.33.99 1.33h1.495c.701 0 1.196-.675.99-1.33l-1.01-3.233c-.217-.716-1.228-.716-1.455 0");
}

.ih_njzbst {
  stop-color: var(--svg-color--d3cfd9, #D3CFD9);
  stop-opacity: 0;
}

.isvyw7ooh {
  stop-color: var(--svg-color--c0bbc4, #C0BBC4);
}

.ixxpbv8hf {
  stop-color: var(--svg-color--bbb9bd, #BBB9BD);
  stop-opacity: 0;
}

.j-wsjf_jj {
  fill: var(--svg-color--2d2b2e, #2D2B2E);
  d: path("M18.037 17.525c.505-.888 1.272-1.589 2.924-1.589c.723 0 1.42.2 2.04.701c.511.413.443.942.047 1.14l-1.057.604c-1.24-.401-2.61-.455-3.954-.856");
}

.jaf6nfbfs {
  stop-color: var(--svg-color--a07a6f, #A07A6F);
  stop-opacity: 0;
}

.jcrjf-b8x {
  stop-color: var(--svg-color--ebeaec, #EBEAEC);
  stop-opacity: 0;
}

.jdd1i0reo {
  stop-color: var(--svg-color--bbb9bd, #BBB9BD);
}

.jplc2lvem {
  stop-color: var(--svg-color--7c455c, #7C455C);
  stop-opacity: 0;
}

.jqrsdeafm {
  d: path("M6.954 21.668a3.06 3.06 0 1 0 0-6.12a3.06 3.06 0 0 0 0 6.12");
}

.kk5kzjxzh {
  fill: var(--svg-color--352827, #352827);
  d: path("m9.404 15.226l-.009.005a.51.51 0 0 1-.524-.875l.003-.001l.005-.004l.018-.01l.062-.034q.08-.044.22-.112c.188-.09.455-.204.78-.308c.647-.206 1.55-.38 2.527-.207a.51.51 0 1 1-.178 1.004c-.758-.134-1.486-.001-2.038.175a5 5 0 0 0-.825.345z");
}

.kkvh--b-a {
  stop-color: var(--svg-color--ddd6e4, #DDD6E4);
}

.l__dw9bpv {
  stop-color: var(--svg-color--7d4d48, #7D4D48);
  stop-opacity: 0;
}

.l7c47o-wr {
  stop-color: var(--svg-color--664944, #664944);
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lo97d1z0q {
  stop-color: var(--svg-color--bcb7c1, #BCB7C1);
}

.lun1rzujg {
  stop-color: var(--svg-color--997570, #997570);
}

.lv_ze4bos {
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M15.865 24.145a5.76 5.76 0 0 1-2.703-.656c-.268-.139-.555.169-.386.417a3.67 3.67 0 0 0 3.09 1.689a3.67 3.67 0 0 0 3.09-1.689c.168-.258-.12-.556-.387-.417a5.7 5.7 0 0 1-2.704.656Z");
}

.lwz87437z {
  stop-color: var(--svg-color--865e63, #865E63);
}

.lxkykv_ud {
  stop-color: var(--svg-color--ebe6f2, #EBE6F2);
}

.ly_7e_lbd {
  fill: var(--svg-color--000, #000);
  d: path("M19.047 18.262c0-.54.432-.972.972-.972s.972.432.972.972a.96.96 0 0 1-.108.448h-1.72a.9.9 0 0 1-.116-.448");
}

.m1v3gnbun {
  stop-color: var(--svg-color--b6b0bb, #B6B0BB);
  stop-opacity: 0;
}

.m71s56bwv {
  stop-color: var(--svg-color--e0dae8, #E0DAE8);
  stop-opacity: 0;
}

.m9efqem2s {
  d: path("M26.99 12.484c.005-1.483-1.085-2.607-1.93-3.106c-1.34-.79-3.268-1.004-4.104-.999H19.47l-4.955.806l.256 1.718h7.579c2.465 0 3.102 1.792 3.043 2.694l-.055 1.146c.217 0 .866-.236 1.115-.728c.203-.4.383-.936.537-1.531");
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mcdrc7blw {
  stop-color: var(--svg-color--fafafa, #FAFAFA);
}

.migzlo1qy {
  stroke: var(--svg-color--473c3c, #473C3C);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M12.344 14.095c-.613-.149-2.139-.074-3.158.655");
}

.mt9k2qzvi {
  stop-color: var(--svg-color--755041, #755041);
}

.mvpyyqb8k {
  stop-color: var(--svg-color--b8b2be, #B8B2BE);
  stop-opacity: 0;
}

.n7j-lccxy {
  stop-color: var(--svg-color--997570, #997570);
  stop-opacity: 0;
}

.ni-4se4rm {
  stop-color: var(--svg-color--836462, #836462);
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

.o02xvvb7n {
  stop-color: var(--svg-color--b384b3, #B384B3);
  stop-opacity: 0;
}

.o0haeebrm {
  fill: var(--svg-color--5f3c45, #5F3C45);
  d: path("M6.99 20.65a2.043 2.043 0 1 0 0-4.085a2.043 2.043 0 0 0 0 4.085");
}

.o3wo53bzp {
  stop-color: var(--svg-color--5a3638, #5A3638);
  stop-opacity: 0;
}

.o8dy3hheh {
  fill: var(--svg-color--70404a, #70404A);
  d: path("m15.119 18.184l-1.3 3.233c-.207.665.288 1.33.99 1.33h1.495c.702 0 1.197-.675.99-1.33l-1.01-3.233c-.217-.717-.939-.717-1.165 0");
}

.oazx0zdky {
  d: path("M25.046 20.65a2.043 2.043 0 1 0 0-4.086a2.043 2.043 0 0 0 0 4.086");
}

.obw0imwoz {
  d: path("m15.138 17.92l-1.01 3.233c-.207.666.288 1.33.99 1.33h1.495c.701 0 1.196-.675.99-1.33l-1.01-3.233c-.217-.716-1.228-.716-1.455 0");
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.olqyf7fmb {
  stop-color: var(--svg-color--875e5e, #875E5E);
}

.opgioqbtx {
  stop-color: var(--svg-color--805c54, #805C54);
  stop-opacity: 0;
}

.opjf3kbfq {
  d: path("m20.417 2.016l.055 2.427c1.224-.031 3.562.082 5.578 1.227c.85.482 1.29.992 1.574 1.413c-.073-.969-.366-1.894-1.202-3.047c-.979-1.35-2.795-2.02-4.42-2.02z");
}

.osxg47drp {
  stop-color: var(--svg-color--743f5a, #743F5A);
}

.p6ygghbxv {
  stop-color: var(--svg-color--d3cfd9, #D3CFD9);
}

.p88c31myn {
  stop-color: var(--svg-color--815a5b, #815A5B);
  stop-opacity: 0;
}

.phr-zrige {
  stop-color: var(--svg-color--d0ccd3, #D0CCD3);
  stop-opacity: 0;
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pqj6bioog {
  fill: var(--svg-color--352827, #352827);
  fill-rule: evenodd;
  d: path("m22.962 14.356l-.262.438za.51.51 0 0 1-.524.876l-.01-.006l-.04-.023a5 5 0 0 0-.825-.344c-.552-.176-1.28-.309-2.039-.175a.51.51 0 1 1-.177-1.004c.976-.173 1.88 0 2.526.207a6 6 0 0 1 1 .42l.062.034l.018.01l.006.004h.002z");
}

.q2rl-9b2o {
  stop-color: var(--svg-color--cfcad4, #CFCAD4);
}

.q9wqsddqp {
  stop-color: var(--svg-color--b5b4b6, #B5B4B6);
}

.qfleuzzqm {
  stop-color: var(--svg-color--a5a0a9, #A5A0A9);
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

.r_e9t9m_k {
  d: path("m6.29 14.806l.023.018l-.001-.166c-.007-.59-.02-1.727.477-2.47c.801-1.196 1.711-1.285 2.601-1.285h12.96c2.465 0 3.081 1.796 3.081 2.694l-.093 1.146l.04-.002l-.033 6.335c-.234 5.33-4.396 8.908-9.477 8.908c-5.08 0-9.242-3.579-9.477-8.908z");
}

.r3imb_bxi {
  d: path("M4.357 7.752c.557-.67 1.563-1.613 2.897-1.974c1.879-.509 4.836-.733 6.069-.82c.45.025 1.556-.442 1.556-1.61c0-.434-.016-.89-.053-1.332H10.45c-3.712 0-4.678 1.406-5.42 2.8c-.594 1.114-.675 2.2-.674 2.843z");
}

.rby1z7ber {
  stop-color: var(--svg-color--744c45, #744C45);
}

.rc8hkzs9u {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M19.894 16.923c.121.162-.132.36-.419.574c-.287.215-.5.366-.622.204c-.12-.161.015-.466.302-.681s.618-.258.74-.097");
}

.rjs9uccph {
  stop-color: var(--svg-color--d1cad9, #D1CAD9);
  stop-opacity: 0;
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

.s6vdf8bty {
  stop-color: var(--svg-color--f8f6fb, #F8F6FB);
}

.t9k87pm2r {
  stop-color: var(--svg-color--875555, #875555);
}

.uj7hgsb3u {
  stop-color: var(--svg-color--815a5b, #815A5B);
}

.up8l18w-p {
  stop-color: var(--svg-color--986b5a, #986B5A);
}

.utuphuu_g {
  stop-color: var(--svg-color--78415c, #78415C);
  stop-opacity: 0;
}

.uw_0kccnw {
  d: path("M11.712 16.565a1.697 1.697 0 0 0-1.636 2.144h3.279q.059-.217.061-.447a1.71 1.71 0 0 0-1.705-1.698");
}

.vbw-bobru {
  stop-color: var(--svg-color--533335, #533335);
}

.vex46bbmn {
  fill: var(--svg-color--272528, #272528);
  d: path("M13.694 17.525c-.505-.888-1.272-1.589-2.924-1.589c-.723 0-1.42.2-2.04.701c-.512.413-.443.942-.047 1.14l1.057.604c1.24-.401 2.61-.455 3.954-.856");
}

.vjgrxi2qw {
  d: path("M25.046 21.668a3.06 3.06 0 1 0 0-6.12a3.06 3.06 0 0 0 0 6.12");
}

.vtmaael7d {
  d: path("M20.019 16.565a1.697 1.697 0 0 1 1.636 2.145h-3.28a1.7 1.7 0 0 1-.061-.448c0-.933.764-1.697 1.705-1.697");
}

.vwwlod5tb {
  fill: var(--svg-color--88014f, #88014F);
  d: path("M15.865 24.145a5.76 5.76 0 0 1-2.703-.656c-.268-.139-.555.169-.386.417a3.67 3.67 0 0 0 3.09 1.689a3.67 3.67 0 0 0 3.09-1.689c.168-.258-.12-.556-.387-.417a5.7 5.7 0 0 1-2.704.656");
}

.vxblmsj4h {
  d: path("m15.109 17.696l-1.01 3.233c-.207.665.288 1.33.99 1.33h1.495c.701 0 1.196-.675.99-1.33l-1.01-3.233c-.217-.716-1.228-.716-1.455 0");
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

.wfm74pxcd {
  stop-color: var(--svg-color--e2dce8, #E2DCE8);
  stop-opacity: 0;
}

.wg3eepbwp {
  stop-color: var(--svg-color--805c54, #805C54);
}

.wrh2b4bbx {
  stop-color: var(--svg-color--7d4d48, #7D4D48);
}

.wsh5tsbcf {
  stop-color: var(--svg-color--836462, #836462);
  stop-opacity: 0;
}

.wvn8vtban {
  stop-color: var(--svg-color--c5c2c8, #C5C2C8);
  stop-opacity: 0;
}

.x_ik4kbfh {
  stop-color: var(--svg-color--714350, #714350);
}

.x-hxb0kwa {
  stop-color: var(--svg-color--8b6059, #8B6059);
}

.x7ia8vuzd {
  stop-color: var(--svg-color--f1edf4, #F1EDF4);
}

.xk4rg9b0l {
  d: path("M19.894 16.923c.121.162-.132.36-.419.574c-.287.215-.5.366-.622.204c-.12-.161.015-.466.302-.681s.618-.258.74-.097");
}

.yamoh3dov {
  stop-color: var(--svg-color--764e4c, #764E4C);
}

.ycrcotb4u {
  stop-color: var(--svg-color--986f60, #986F60);
  stop-opacity: 0;
}

.yeh-4kb4a {
  fill: var(--svg-color--845f59, #845F59);
  d: path("M25.046 20.65a2.043 2.043 0 1 0 0-4.086a2.043 2.043 0 0 0 0 4.086");
}

.yo7rwbb1x {
  d: path("M21.53 18.039a1.6 1.6 0 0 0-.44-.88l-.494.542l.224.434z");
}

.z26rrllgi {
  stop-color: var(--svg-color--6e494b, #6E494B);
}

.zk6usj6rs {
  stroke: var(--svg-color--473c3c, #473C3C);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M19.554 14.095c.613-.149 2.139-.074 3.158.655");
}

.zoq8fuaif {
  stop-color: var(--svg-color--986f60, #986F60);
}

.zz39r5b3o {
  stop-color: var(--svg-color--c5c2c8, #C5C2C8);
}

</style>
