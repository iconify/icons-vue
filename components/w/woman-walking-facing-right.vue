<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#igVlLGd)" transform="scale(-1 1)rotate(-4.337 79.944 238.654)" class="z8jy9-b3h"/><path fill="url(#iPT4N8b)" class="b7xhvm0eq"/><g filter="url(#ikxffYd)"><path fill="url(#iPpFxDc)" class="s60kk4b1z"/><path fill="url(#ikcV02b)" class="s60kk4b1z"/></g><g filter="url(#ifHE2Go)"><path class="vsrmvq78p"/></g><path fill="url(#it1M9nc)" class="aj6_uub8g"/><path fill="url(#iLMsHBb)" class="mgi2ykbre"/><g filter="url(#iJhtmNd)"><path fill="url(#iMAvXjD)" class="de1ubobvt"/><path fill="url(#iFchPJb)" class="de1ubobvt"/><path fill="url(#iwDihLN)" class="de1ubobvt"/></g><g filter="url(#iq69nGd)"><path class="cib2xzpbp"/><path fill="url(#iomIeSc)" class="evwj63bjo"/><path fill="url(#iFXjklb)" class="evwj63bjo"/><path fill="url(#ihjFaKb)" class="evwj63bjo"/><path fill="url(#idHi0Ob)" class="evwj63bjo"/><path fill="url(#i0srsUd)" class="evwj63bjo"/></g><path fill="url(#iybaexq)" class="bh0m-hhvd"/><path fill="url(#i71uMce)" class="bh0m-hhvd"/><path fill="url(#idwEQ2X)" class="bh0m-hhvd"/><path fill="url(#iackThc)" class="bh0m-hhvd"/><path fill="url(#iuorxnc)" class="bh0m-hhvd"/><path class="fzxnh5bei"/><path fill="url(#iB2Gpcd)" class="cn9j7sbna"/><path fill="url(#iqwAjyd)" class="cn9j7sbna"/><path fill="url(#idu5Rbc)" class="cn9j7sbna"/><g filter="url(#iVBYk1d)"><path clip-rule="evenodd" class="b1ti77bmx"/></g><path fill="url(#iW4XZUc)" class="hhshosbgw"/><path class="kb2zfib-q"/><path fill="url(#inBSsNe)" class="q08162bxq"/><path fill="url(#icsNHIe)" class="q08162bxq"/><path fill="url(#i5cvxXK)" class="q08162bxq"/><path fill="url(#iehjird)" class="q08162bxq"/><path fill="url(#iX1DJqe)" class="q08162bxq"/><circle fill="url(#iBatVRV)" transform="matrix(-1 0 0 1 11.62 17.491)" class="am9uocbqt"/><g filter="url(#iDKAwBe)"><path class="lw1w950ty"/></g><g filter="url(#iGdz3kb)"><path clip-rule="evenodd" class="dtmiyib6l"/></g><g filter="url(#ivRQbMc)"><path fill="url(#iKIFRdr)" class="zxd9r4bii"/><path fill="url(#itgKhHd)" class="zxd9r4bii"/><path fill="url(#i7vfRRc)" class="zxd9r4bii"/></g><path fill="url(#i1u9bsd)" class="de8xr2gph"/><path clip-rule="evenodd" class="k846x6yho"/><g filter="url(#ixzSIVd)"><path clip-rule="evenodd" class="mwub4tbja"/></g><path class="ottrzhb3p"/><path class="o835mkbbk"/><path fill="url(#ierh8Zb)" class="h2pkht5ud"/><path fill="url(#ioayomb)" class="aupzjnb6g"/><ellipse fill="url(#ipECBte)" transform="scale(-1 1)rotate(24.61 -21.741 -42.44)" class="m1l7k9jve"/><g filter="url(#iJi6BBd)"><path fill="url(#ikbB7ud)" class="o0u08fb4f"/></g><g filter="url(#i5BSsOb)"><path fill="url(#iNdxovc)" class="t79vivb6l"/></g><defs><radialGradient id="igVlLGd" cx="0" cy="0" r="1" gradientTransform="matrix(-.76278 .55328 -.95792 -1.32064 1.33 1.556)" gradientUnits="userSpaceOnUse"><stop class="j04p-ebdr"/><stop offset="1" class="kyqggpm3k"/></radialGradient><radialGradient id="iPT4N8b" cx="0" cy="0" r="1" gradientTransform="matrix(-.3125 .60583 -.77155 -.39799 20.699 5.976)" gradientUnits="userSpaceOnUse"><stop offset=".332" class="fvok_qxen"/><stop offset="1" class="suyap8bzv"/></radialGradient><radialGradient id="ikcV02b" cx="0" cy="0" r="1" gradientTransform="matrix(.84375 -.04687 .05715 1.0287 17.16 5.561)" gradientUnits="userSpaceOnUse"><stop offset=".156" class="d7kch3t0q"/><stop offset="1" class="admd7db0k"/></radialGradient><radialGradient id="it1M9nc" cx="0" cy="0" r="1" gradientTransform="matrix(-.84375 5.57813 -4.53655 -.6862 16.468 3.384)" gradientUnits="userSpaceOnUse"><stop offset=".718" class="rmg76y8bk"/><stop offset="1" class="dgcxumb4u"/></radialGradient><radialGradient id="iLMsHBb" cx="0" cy="0" r="1" gradientTransform="matrix(.45312 .9414 -1.52974 .7363 16.953 5.382)" gradientUnits="userSpaceOnUse"><stop offset=".04" class="bervkqbmz"/><stop offset="1" class="c479w-bpn"/></radialGradient><radialGradient id="iFchPJb" cx="0" cy="0" r="1" gradientTransform="matrix(-2.45369 2.93958 -5.96661 -4.98038 15.047 18.039)" gradientUnits="userSpaceOnUse"><stop offset=".434" class="oiy_54b9a"/><stop offset="1" class="rm4aiz5dn"/></radialGradient><radialGradient id="iwDihLN" cx="0" cy="0" r="1" gradientTransform="rotate(143.616 4.55 12.051)scale(1.10629 6.64432)" gradientUnits="userSpaceOnUse"><stop offset=".043" class="v5lz4sb9o"/><stop offset="1" class="m_uy2vb_d"/></radialGradient><radialGradient id="iomIeSc" cx="0" cy="0" r="1" gradientTransform="rotate(-122.302 13.828 6.002)scale(6.08182 1.60193)" gradientUnits="userSpaceOnUse"><stop offset=".07" class="mngz2ebss"/><stop offset="1" class="ttsumpbek"/></radialGradient><radialGradient id="iFXjklb" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.42188 -1.38588 0 15.332 16.194)" gradientUnits="userSpaceOnUse"><stop class="f3j6dkfip"/><stop offset="1" class="fxoxl0blj"/></radialGradient><radialGradient id="idHi0Ob" cx="0" cy="0" r="1" gradientTransform="matrix(-.14062 -.17969 .6458 -.50541 20.027 28.108)" gradientUnits="userSpaceOnUse"><stop class="ryq0o3qru"/><stop offset="1" class="yfqxgqb1h"/></radialGradient><radialGradient id="i0srsUd" cx="0" cy="0" r="1" gradientTransform="matrix(-6.375 -1.81248 4.6745 -16.4415 19.707 19.241)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="ex23x-brg"/><stop offset="1" class="ux4w7lb6c"/></radialGradient><radialGradient id="iybaexq" cx="0" cy="0" r="1" gradientTransform="matrix(.09374 -1.53125 2.45635 .15037 21.161 29.46)" gradientUnits="userSpaceOnUse"><stop class="cl2mlwbhs"/><stop offset="1" class="yvuyjoqpy"/></radialGradient><radialGradient id="i71uMce" cx="0" cy="0" r="1" gradientTransform="matrix(-1.0625 -.21876 .15137 -.73521 24.27 28.523)" gradientUnits="userSpaceOnUse"><stop class="m3n9jy0fh"/><stop offset="1" class="hdzwkybza"/></radialGradient><radialGradient id="idwEQ2X" cx="0" cy="0" r="1" gradientTransform="matrix(-.59376 -1.71875 .84778 -.29287 20.254 29.757)" gradientUnits="userSpaceOnUse"><stop offset=".08" class="a541b3bqx"/><stop offset="1" class="zc8ie-1dg"/></radialGradient><radialGradient id="idu5Rbc" cx="0" cy="0" r="1" gradientTransform="rotate(-47.125 35.171 4.246)scale(1.99789 1.10527)" gradientUnits="userSpaceOnUse"><stop class="xh_da2q2q"/><stop offset="1" class="stwbr2bhy"/></radialGradient><radialGradient id="inBSsNe" cx="0" cy="0" r="1" gradientTransform="rotate(-88.915 15.97 .231)scale(4.95211 1.34022)" gradientUnits="userSpaceOnUse"><stop class="dkjt4cbcx"/><stop offset="1" class="w9ku-ifwq"/></radialGradient><radialGradient id="icsNHIe" cx="0" cy="0" r="1" gradientTransform="matrix(-3.65186 0 0 -15.6875 17.311 14.306)" gradientUnits="userSpaceOnUse"><stop offset=".436" class="p0p0ijbbx"/><stop offset=".967" class="dvcrl_y_s"/></radialGradient><radialGradient id="i5cvxXK" cx="0" cy="0" r="1" gradientTransform="matrix(4.78125 .78125 -1.79108 10.96143 13.936 15.118)" gradientUnits="userSpaceOnUse"><stop offset=".781" class="jx6m9tune"/><stop offset=".931" class="g41565bda"/></radialGradient><radialGradient id="iehjird" cx="0" cy="0" r="1" gradientTransform="matrix(-.51563 1.34375 -3.67742 -1.41111 17.374 8.274)" gradientUnits="userSpaceOnUse"><stop offset=".297" class="p663aq61v"/><stop offset="1" class="kqh0ncb_u"/></radialGradient><radialGradient id="iX1DJqe" cx="0" cy="0" r="1" gradientTransform="rotate(54.539 -.573 19.4)scale(1.15812 2.04942)" gradientUnits="userSpaceOnUse"><stop class="jq_uanbes"/><stop offset="1" class="oq2q2abrd"/></radialGradient><radialGradient id="iBatVRV" cx="0" cy="0" r="1" gradientTransform="rotate(90 .008 .406)scale(.90625)" gradientUnits="userSpaceOnUse"><stop offset=".256" class="d69nsybly"/><stop offset="1" class="eluf2xb_e"/></radialGradient><radialGradient id="itgKhHd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.0907 .20313 -.4206 -2.25834 17.12 10.352)" gradientUnits="userSpaceOnUse"><stop offset=".12" class="xot8u71lw"/><stop offset="1" class="jjp3z2beb"/></radialGradient><radialGradient id="i7vfRRc" cx="0" cy="0" r="1" gradientTransform="rotate(135.955 4.99 7.887)scale(2.65202 1.5046)" gradientUnits="userSpaceOnUse"><stop offset=".204" class="lz70c3nqo"/><stop offset="1" class="pt5v4qb1w"/></radialGradient><radialGradient id="i1u9bsd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.09375 .1806 -.14313 -.86685 23.675 16.413)" gradientUnits="userSpaceOnUse"><stop class="j4xesqbgr"/><stop offset=".839" class="fa3xzswyd"/></radialGradient><radialGradient id="ierh8Zb" cx="0" cy="0" r="1" gradientTransform="matrix(-.27344 0 0 -.53125 19.523 5.636)" gradientUnits="userSpaceOnUse"><stop offset=".895" class="l0aricxam"/><stop offset="1" class="n9r91ylyy"/></radialGradient><radialGradient id="ioayomb" cx="0" cy="0" r="1" gradientTransform="matrix(-.25 0 0 -.54102 19.691 5.657)" gradientUnits="userSpaceOnUse"><stop class="gv3iwdbvq"/><stop offset=".813" class="ubyl24bdb"/></radialGradient><linearGradient id="iPpFxDc" x1="17.472" x2="20.335" y1="6.304" y2="6.476" gradientUnits="userSpaceOnUse"><stop class="egm-dub4f"/><stop offset="1" class="zhwoohbuw"/></linearGradient><linearGradient id="iMAvXjD" x1="14.027" x2="11.798" y1="22.898" y2="20.954" gradientUnits="userSpaceOnUse"><stop offset=".211" class="pat1zf4-w"/><stop offset="1" class="wtea7v6lu"/></linearGradient><linearGradient id="ihjFaKb" x1="16.254" x2="16.254" y1="16.085" y2="16.429" gradientUnits="userSpaceOnUse"><stop offset=".136" class="x5p6yzbmf"/><stop offset="1" class="cnh3p8b3x"/></linearGradient><linearGradient id="iackThc" x1="21.722" x2="21.637" y1="29.632" y2="29.319" gradientUnits="userSpaceOnUse"><stop class="l138bfbcs"/><stop offset="1" class="oxce79bcz"/></linearGradient><linearGradient id="iuorxnc" x1="19.754" x2="20.332" y1="30.007" y2="29.788" gradientUnits="userSpaceOnUse"><stop offset=".064" class="lhdz7oxfj"/><stop offset="1" class="csaq2_bel"/></linearGradient><linearGradient id="iB2Gpcd" x1="11.144" x2="10.55" y1="27.991" y2="28.163" gradientUnits="userSpaceOnUse"><stop class="oxg1n1wjw"/><stop offset="1" class="y0g_czb9f"/></linearGradient><linearGradient id="iqwAjyd" x1="9.019" x2="9.199" y1="28.065" y2="27.917" gradientUnits="userSpaceOnUse"><stop class="p6qc3nb-j"/><stop offset="0" class="ezcqmvbni"/><stop offset="1" class="stwbr2bhy"/></linearGradient><linearGradient id="iW4XZUc" x1="19.3" x2="18.425" y1="12.851" y2="10.46" gradientUnits="userSpaceOnUse"><stop class="t55apucyo"/><stop offset=".787" class="biw5o_cgj"/></linearGradient><linearGradient id="iKIFRdr" x1="15.269" x2="14.16" y1="9.132" y2="12.585" gradientUnits="userSpaceOnUse"><stop offset=".118" class="u1dukib7n"/><stop offset="1" class="mk0srdu2z"/></linearGradient><linearGradient id="ipECBte" x1="-.007" x2=".179" y1=".05" y2=".11" gradientUnits="userSpaceOnUse"><stop class="vc--wpv5i"/><stop offset="1" class="stui2mbih"/></linearGradient><linearGradient id="ikbB7ud" x1="19.925" x2="15.3" y1="27.429" y2="17.288" gradientUnits="userSpaceOnUse"><stop class="v9kimlbms"/><stop offset="1" class="g24ahctiy"/></linearGradient><linearGradient id="iNdxovc" x1="9.781" x2="14.092" y1="25.338" y2="19.966" gradientUnits="userSpaceOnUse"><stop class="ckhjb_bgt"/><stop offset="1" class="rnrhdzckq"/></linearGradient><filter id="ikxffYd" width="4.493" height="5.449" x="15.842" y="3.163" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25" dy="-.4"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.85098 0 0 0 0 0.54902 0 0 0 0 0.227451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_476"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.15" dy="-.05"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.737255 0 0 0 0 0.4 0 0 0 0 0.0470588 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_2_476" result="effect2_innerShadow_2_476"/></filter><filter id="ifHE2Go" width="6.813" height="7.403" x="13.683" y="1.701" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.4" dy=".4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.843137 0 0 0 0 0.207843 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_476"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.607843 0 0 0 0 0.117647 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_2_476" result="effect2_innerShadow_2_476"/></filter><filter id="iJhtmNd" width="8.674" height="14.771" x="7.888" y="15.476" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".75" dy="-.75"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.439216 0 0 0 0 0.388235 0 0 0 0 0.486275 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_476"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.537255 0 0 0 0 0.423529 0 0 0 0 0.635294 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_2_476" result="effect2_innerShadow_2_476"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy=".25"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.529412 0 0 0 0 0.490196 0 0 0 0 0.537255 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_2_476" result="effect3_innerShadow_2_476"/></filter><filter id="iq69nGd" width="10.972" height="14.104" x="13.646" y="15.994" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy="-.2"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.619608 0 0 0 0 0.592157 0 0 0 0 0.611765 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_476"/></filter><filter id="iVBYk1d" width="8.438" height="7.859" x="15.777" y="10.624" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-1"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.894118 0 0 0 0 0.505882 0 0 0 0 0.137255 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_476"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.752941 0 0 0 0 0.466667 0 0 0 0 0.254902 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_2_476" result="effect2_innerShadow_2_476"/></filter><filter id="iDKAwBe" width="5.442" height="5.875" x="12.278" y="8.468" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_2_476" stdDeviation=".375"/></filter><filter id="iGdz3kb" width="7.59" height="10.511" x="8.519" y="9.157" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.901961 0 0 0 0 0.623529 0 0 0 0 0.188235 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_476"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.4" dy=".4"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.835294 0 0 0 0 0.25098 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_2_476" result="effect2_innerShadow_2_476"/></filter><filter id="ivRQbMc" width="4.758" height="4.525" x="12.613" y="8.654" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.15"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.392157 0 0 0 0 0.254902 0 0 0 0 0.639216 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_476"/></filter><filter id="ixzSIVd" width="1.013" height=".568" x="18.66" y="4.307" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.682353 0 0 0 0 0.219608 0 0 0 0 0.133333 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_476"/></filter><filter id="iJi6BBd" width="6.844" height="12.891" x="14.3" y="16.116" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_2_476" stdDeviation=".5"/></filter><filter id="i5BSsOb" width="6.45" height="8.475" x="8.746" y="18.044" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_2_476" stdDeviation=".375"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:woman-walking-facing-right" /></template>
<style>
.a541b3bqx {
  stop-color: var(--svg-color--515279, #515279);
}

.admd7db0k {
  stop-color: var(--svg-color--ffab1d, #FFAB1D);
  stop-opacity: 0;
}

.aj6_uub8g {
  d: path("M20.427 3.517c.171-.41-.017-.844-.113-.993c-.368-.672-1.129-.716-1.567-.523c-.516.226-.67.347-1.504.11c-.837-.239-1.867-.13-2.406.84c-.54.968.046 2.058-.086 2.651c-.133.594-.513.653-.653 1.34c-.117.953.473 1.575.996 1.715c.524.14 1.602 0 1.954-.875c.575-1.431.184-2.11.309-2.828c.125-.719.554-.922 1.335-.766c.92.184 1.506-.126 1.735-.671");
}

.am9uocbqt {
  cx: 0.551px;
  cy: 0.551px;
  r: 0.551px;
}

.aupzjnb6g {
  d: path("m19.39 5.657l-.003-.072c0-.186.078-.336.175-.336s.176.15.176.336l-.004.072z");
}

.b1ti77bmx {
  fill: var(--svg-color--f5b02e, #F5B02E);
  fill-rule: evenodd;
  d: path("M22.831 18.406a.85.85 0 0 0 1.13-.433l.19-.427a.755.755 0 0 0-.383-.992c-1.533-.704-4.023-2.149-4.983-5.93l-2.008.524c1.185 4.668 4.29 6.44 6.054 7.258");
}

.b7xhvm0eq {
  d: path("M20.53 5.827a1 1 0 0 1-.257-.457h-.18v1.125c.215.137.522.115.613-.09c.079-.176.02-.394-.175-.578");
}

.bervkqbmz {
  stop-color: var(--svg-color--ffd040, #FFD040);
}

.bh0m-hhvd {
  d: path("m19.406 28.636l.391 1.285a.25.25 0 0 0 .315.166l3.737-1.183c.195-.061.326-.265.244-.452c-.107-.245-.333-.5-.886-.656c-.59-.167-1.672-.262-2.306-.317l-.21-.019v-.002z");
}

.biw5o_cgj {
  stop-color: var(--svg-color--816fa6, #816FA6);
}

.c479w-bpn {
  stop-color: var(--svg-color--fead30, #FEAD30);
}

.cib2xzpbp {
  fill: var(--svg-color--8c8393, #8C8393);
  d: path("M19.183 18.577c-.383-1.05-.716-2.029-.773-2.383h-4.742c-.1 1.375.144 1.712.773 2.422c.693.782 2.172 2.43 2.54 2.895c.35.35.5.789.554.98l2.262 7.43a.25.25 0 0 0 .315.166l3.737-1.183c.195-.061.326-.265.244-.452c-.107-.245-.333-.5-.886-.656c-.663-.188-1.943-.284-2.516-.336c-.213-1.766-.66-5.431-.734-5.969c-.094-.672-.227-1.414-.774-2.914");
}

.ckhjb_bgt {
  stop-color: var(--svg-color--a39fa7, #A39FA7);
}

.cl2mlwbhs {
  stop-color: var(--svg-color--4a4b75, #4A4B75);
}

.cn9j7sbna {
  d: path("m8.965 25.668l1.638.678l-.022.02l.107.355c.217.713.536 1.764.62 2.27c.077.462-.145.768-.35.953c-.094.083-.235.064-.319-.03L7.952 26.92a.25.25 0 0 1 .018-.353l.986-.887z");
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

.de1ubobvt {
  d: path("m12.831 19.96l.89-3.734h1.782c.052.614.152 2.215.29 3.515s-.493 2.032-.766 2.313l-4.446 4.312c.198.662.627 2.025.727 2.625c.077.462-.145.768-.35.953c-.094.083-.236.064-.319-.03L7.951 26.92a.25.25 0 0 1 .02-.353l.985-.887c1.042-1.365 3.19-4.194 3.453-4.594c.182-.276.391-.917.422-1.125");
}

.de8xr2gph {
  d: path("m23.343 16.026l-.496.052a.435.435 0 0 0-.388.403a.38.38 0 0 0 .076.266c.264.33.525.366.722.408c.219.047.676-.191.59-.691a.53.53 0 0 0-.504-.438");
}

.dgcxumb4u {
  stop-color: var(--svg-color--a76445, #A76445);
}

.dkjt4cbcx {
  stop-color: var(--svg-color--7966a4, #7966A4);
}

.dtmiyib6l {
  fill: var(--svg-color--ffbf35, #FFBF35);
  fill-rule: evenodd;
  d: path("M10.163 19.238a.614.614 0 0 0 .776-.407c1.215-3.921 3.166-6.29 4.542-7.545c.438-.4.515-1.082.128-1.53c-.346-.401-.944-.472-1.348-.13c-1.626 1.381-3.91 3.976-5.317 8.605a.59.59 0 0 0 .383.73z");
}

.dvcrl_y_s {
  stop-color: var(--svg-color--6c5d89, #6C5D89);
}

.egm-dub4f {
  stop-color: var(--svg-color--ffc33e, #FFC33E);
}

.eluf2xb_e {
  stop-color: var(--svg-color--ce853f, #CE853F);
}

.evwj63bjo {
  d: path("M19.183 18.577c-.383-1.05-.716-2.029-.773-2.383h-4.742c-.1 1.375.144 1.712.773 2.422c.693.782 2.172 2.43 2.54 2.895c.35.35.5.789.554.98l2.262 7.43a.25.25 0 0 0 .315.166l3.737-1.183c.195-.061.326-.265.244-.452c-.107-.245-.333-.5-.886-.656c-.663-.188-1.943-.284-2.516-.336c-.213-1.766-.66-5.431-.734-5.969c-.094-.672-.227-1.414-.774-2.914");
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

.fa3xzswyd {
  stop-color: var(--svg-color--eb9f1c, #EB9F1C);
}

.ft5dv1b6b {
  fill: none;
}

.fvok_qxen {
  stop-color: var(--svg-color--ffbf42, #FFBF42);
}

.fxoxl0blj {
  stop-color: var(--svg-color--8c8393, #8C8393);
  stop-opacity: 0;
}

.fzxnh5bei {
  fill: var(--svg-color--45437a, #45437A);
  d: path("m8.965 25.668l1.638.678l-.022.02l.107.355c.217.713.536 1.764.62 2.27c.077.462-.145.768-.35.953c-.094.083-.235.064-.319-.03L7.952 26.92a.25.25 0 0 1 .018-.353l.986-.887z");
}

.g24ahctiy {
  stop-color: var(--svg-color--94899e, #94899E);
  stop-opacity: 0;
}

.g41565bda {
  stop-color: var(--svg-color--8272a4, #8272A4);
}

.gv3iwdbvq {
  stop-color: var(--svg-color--666361, #666361);
}

.h2pkht5ud {
  d: path("M19.195 5.657v-.004c0-.32.137-.58.307-.58s.306.26.306.58v.004z");
}

.hdzwkybza {
  stop-color: var(--svg-color--63617e, #63617E);
  stop-opacity: 0;
}

.hhshosbgw {
  d: path("M18.785 10.515c-.281-.713-.773-1.224-.985-1.391l.04 4.469l1.785-.836c-.278-.524-.488-1.352-.84-2.242");
}

.j04p-ebdr {
  stop-color: var(--svg-color--cc7716, #CC7716);
}

.j4xesqbgr {
  stop-color: var(--svg-color--ffbf3f, #FFBF3F);
}

.jjp3z2beb {
  stop-color: var(--svg-color--8974b4, #8974B4);
  stop-opacity: 0;
}

.jq_uanbes {
  stop-color: var(--svg-color--48234a, #48234A);
}

.jx6m9tune {
  stop-color: var(--svg-color--8272a4, #8272A4);
  stop-opacity: 0;
}

.k846x6yho {
  fill: var(--svg-color--87014d, #87014D);
  fill-rule: evenodd;
  d: path("M19.055 6.77a.125.125 0 0 0 .002.178c.238.233.582.293.692.304a.125.125 0 1 0 .025-.248c-.093-.01-.366-.062-.542-.235a.125.125 0 0 0-.177.002");
}

.kb2zfib-q {
  fill: var(--svg-color--725ca6, #725CA6);
  d: path("M16.476 8.612c-.89 0-1.136.215-1.433.407l-1.024 2.597c-.3 1.4-.364 3.636-.36 4.578h4.766c.258-.656.678-2.675.516-4.578c-.164-1.93-1.207-2.902-2.465-3.004");
}

.kqh0ncb_u {
  stop-color: var(--svg-color--885876, #885876);
  stop-opacity: 0;
}

.kyqggpm3k {
  stop-color: var(--svg-color--e29f36, #E29F36);
}

.l0aricxam {
  stop-color: var(--svg-color--916a62, #916A62);
}

.l138bfbcs {
  stop-color: var(--svg-color--282955, #282955);
}

.lhdz7oxfj {
  stop-color: var(--svg-color--444571, #444571);
}

.lw1w950ty {
  fill: var(--svg-color--442e79, #442E79);
  d: path("M16.764 10.985c.31-.248.178-.39.178-.818c0-.749-.013-.95-.761-.95a1.35 1.35 0 0 0-.883.327c-.95.692-1.79 1.592-2.27 2.135l2.04 1.914a58 58 0 0 0 1.696-2.608");
}

.lz70c3nqo {
  stop-color: var(--svg-color--9075ca, #9075CA);
}

.m_uy2vb_d {
  stop-color: var(--svg-color--695c75, #695C75);
  stop-opacity: 0;
}

.m1l7k9jve {
  cx: 0.064px;
  cy: 0.088px;
  rx: 0.064px;
  ry: 0.088px;
}

.m3n9jy0fh {
  stop-color: var(--svg-color--63617e, #63617E);
}

.mgi2ykbre {
  d: path("M17.543 6.323c.05 0 .085-.046.078-.096l-.173-1.249c-.008-.055-.06-.094-.113-.078a.727.727 0 0 0 .207 1.423");
}

.mk0srdu2z {
  stop-color: var(--svg-color--7759b2, #7759B2);
}

.mngz2ebss {
  stop-color: var(--svg-color--897998, #897998);
}

.mwub4tbja {
  fill: var(--svg-color--af5247, #AF5247);
  fill-rule: evenodd;
  d: path("M19.288 4.624a.8.8 0 0 1 .216-.015a.15.15 0 0 0 .038-.298a1 1 0 0 0-.313.02a1 1 0 0 0-.408.172a.15.15 0 1 0 .178.242c.085-.063.19-.1.289-.12");
}

.n9r91ylyy {
  stop-color: var(--svg-color--824d44, #824D44);
}

.o0u08fb4f {
  d: path("m18.8 21.194l1.344 6.5l-.36.313l-1.468-6.531l-3.015-3.875l.703-.485z");
}

.o835mkbbk {
  fill: var(--svg-color--fff, #fff);
  d: path("M19.8 5.657h-.988c0-.391.221-.709.494-.709s.494.318.494.71");
}

.oiy_54b9a {
  stop-color: var(--svg-color--887e8b, #887E8B);
}

.oq2q2abrd {
  stop-color: var(--svg-color--48234a, #48234A);
  stop-opacity: 0;
}

.ottrzhb3p {
  fill: var(--svg-color--2f2c2d, #2F2C2D);
  d: path("M18.775 5.146c.131-.131.349-.161.442-.16l-.303.467c-.147-.008-.303-.143-.139-.307");
}

.oxce79bcz {
  stop-color: var(--svg-color--282955, #282955);
  stop-opacity: 0;
}

.oxg1n1wjw {
  stop-color: var(--svg-color--5a577e, #5A577E);
}

.p0p0ijbbx {
  stop-color: var(--svg-color--6c5d89, #6C5D89);
  stop-opacity: 0;
}

.p663aq61v {
  stop-color: var(--svg-color--885876, #885876);
}

.p6qc3nb-j {
  stop-color: var(--svg-color--492d85, #492D85);
}

.pat1zf4-w {
  stop-color: var(--svg-color--8b8290, #8B8290);
}

.pt5v4qb1w {
  stop-color: var(--svg-color--9075ca, #9075CA);
  stop-opacity: 0;
}

.q08162bxq {
  d: path("M16.476 8.612c-.89 0-1.136.215-1.433.407l-1.024 2.597c-.3 1.4-.364 3.636-.36 4.578h4.766c.258-.656.678-2.675.516-4.578c-.164-1.93-1.207-2.902-2.465-3.004");
}

.rm4aiz5dn {
  stop-color: var(--svg-color--887e8b, #887E8B);
  stop-opacity: 0;
}

.rmg76y8bk {
  stop-color: var(--svg-color--fba522, #FBA522);
  stop-opacity: 0;
}

.rnrhdzckq {
  stop-color: var(--svg-color--a39fa7, #A39FA7);
  stop-opacity: 0;
}

.ryq0o3qru {
  stop-color: var(--svg-color--a19da6, #A19DA6);
}

.s60kk4b1z {
  d: path("M20.307 4.863c-.039-.8-.298-1.187-.42-1.3h-3.733l-.062 3.164c.866 2.121 3.511 2.212 3.906 1.445s.354-2.381.309-3.309");
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

.t55apucyo {
  stop-color: var(--svg-color--725d9d, #725D9D);
}

.t79vivb6l {
  d: path("M12.972 21.142L9.496 25.57l.514.199l3.484-3.708a3 3 0 0 0 .761-1.493l.19-1l-.751-.774l-.544 1.993a1 1 0 0 1-.178.355");
}

.ttsumpbek {
  stop-color: var(--svg-color--897998, #897998);
  stop-opacity: 0;
}

.u1dukib7n {
  stop-color: var(--svg-color--8265b5, #8265B5);
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

.vsrmvq78p {
  fill: var(--svg-color--ffb629, #FFB629);
  d: path("M20.427 3.517c.171-.41-.017-.844-.113-.993c-.368-.672-1.129-.716-1.567-.523c-.516.226-.67.347-1.504.11c-.837-.239-1.867-.13-2.406.84c-.54.968.046 2.058-.086 2.651c-.133.594-.513.653-.653 1.34c-.117.953.473 1.575.996 1.715c.524.14 1.602 0 1.954-.875c.575-1.431.184-2.11.309-2.828c.125-.719.554-.922 1.335-.766c.92.184 1.506-.126 1.735-.671");
}

.w9ku-ifwq {
  stop-color: var(--svg-color--7966a4, #7966A4);
  stop-opacity: 0;
}

.wtea7v6lu {
  stop-color: var(--svg-color--9f9c9f, #9F9C9F);
}

.x5p6yzbmf {
  stop-color: var(--svg-color--817076, #817076);
}

.xh_da2q2q {
  stop-color: var(--svg-color--60618d, #60618D);
}

.xot8u71lw {
  stop-color: var(--svg-color--8974b4, #8974B4);
}

.y0g_czb9f {
  stop-color: var(--svg-color--5a577e, #5A577E);
  stop-opacity: 0;
}

.yfqxgqb1h {
  stop-color: var(--svg-color--a19da6, #A19DA6);
  stop-opacity: 0;
}

.yvuyjoqpy {
  stop-color: var(--svg-color--47456f, #47456F);
}

.z8jy9-b3h {
  d: path("M0 0h1.946v3.44H0z");
}

.zc8ie-1dg {
  stop-color: var(--svg-color--515279, #515279);
  stop-opacity: 0;
}

.zhwoohbuw {
  stop-color: var(--svg-color--ffc247, #FFC247);
}

.zxd9r4bii {
  d: path("M16.612 11.218a1.355 1.355 0 1 0-1.729-2.088c-.95.692-1.79 1.592-2.27 2.135l2.04 1.914a154 154 0 0 1 1.959-1.961");
}

</style>
