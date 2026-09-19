<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#i79u1tc)"><path clip-rule="evenodd" class="hm5ipfb1e"/><path fill="url(#iihWdCc)" clip-rule="evenodd" class="rjm7vebtj"/><path fill="url(#iSBrLmW)" clip-rule="evenodd" class="rjm7vebtj"/></g><path class="f00xt4bzn"/><g filter="url(#iYS2iUd)"><path stroke="url(#iBDizMu)" class="i9n-zdbqk"/></g><g filter="url(#ij3uQbc)"><path fill="url(#iKKXfYc)" clip-rule="evenodd" class="rdk9y-boj"/></g><path fill="url(#iQPo2Lb)" class="htt-kcc6h"/><path fill="url(#iPXPLDb)" class="htt-kcc6h"/><g filter="url(#iSuj5Zc)"><circle fill="url(#iUctc4d)" transform="matrix(-1 0 0 1 28.383 28.223)" class="ghq9gsa-q"/><circle fill="url(#iETpATd)" transform="matrix(-1 0 0 1 28.383 28.223)" class="ghq9gsa-q"/><circle fill="url(#iPmd0rd)" transform="matrix(-1 0 0 1 28.383 28.223)" class="ghq9gsa-q"/></g><g filter="url(#iYaE0Xc)"><path fill="url(#ij6Ri1f)" class="egj5webql"/><path fill="url(#ijWfPhb)" class="egj5webql"/></g><g filter="url(#i4fqhcc)"><rect transform="scale(-1 1)rotate(-7.657 106.609 156.24)" class="nauosacxo"/></g><path fill="url(#igVlLGd)" transform="scale(-1 1)rotate(-4.337 82.026 183.617)" class="z8jy9-b3h"/><path fill="url(#i0Jeete)" class="zette2dgx"/><g filter="url(#iBD2hwd)"><path fill="url(#iUOyqwe)" class="tqwucabqb"/><path fill="url(#iXfcV1b)" class="tqwucabqb"/></g><g filter="url(#idIcKQc)"><path class="r0bikq6kj"/></g><path fill="url(#ibI6tve)" class="q7l9pkmfb"/><path fill="url(#i91MRih)" class="tdu96mbso"/><g filter="url(#itcmwHe)"><path fill="url(#i8L1tPb)" class="rh704p7-v"/><path fill="url(#izmhOqd)" class="rh704p7-v"/><path fill="url(#iLuzMjb)" class="rh704p7-v"/></g><g filter="url(#i0yQkXa)"><path class="geodi6uui"/><path fill="url(#iX7Zbuc)" class="o9wm0bbzg"/><path fill="url(#iSwwsYc)" class="o9wm0bbzg"/><path fill="url(#i81bVxe)" class="o9wm0bbzg"/><path fill="url(#iPFAMDd)" class="o9wm0bbzg"/><path fill="url(#ipNv7rd)" class="o9wm0bbzg"/></g><path fill="url(#ipmfqPe)" class="d-yf4yoik"/><path fill="url(#iS92ZBc)" class="d-yf4yoik"/><path fill="url(#iLzzPlb)" class="d-yf4yoik"/><path fill="url(#iXl61qe)" class="d-yf4yoik"/><path fill="url(#iVPlhFb)" class="d-yf4yoik"/><path class="v1-jeibjs"/><path fill="url(#iJ627hb)" class="zwa6vrpwb"/><path fill="url(#iaAYIDc)" class="zwa6vrpwb"/><path fill="url(#i0mHHPb)" class="zwa6vrpwb"/><path fill="url(#igTLwTv)" class="ry392sb1p"/><path class="appbbetkk"/><path fill="url(#iocBSvu)" class="iuvw09bxv"/><path fill="url(#iPkhHVd)" class="iuvw09bxv"/><path fill="url(#i9jn0pd)" class="iuvw09bxv"/><path fill="url(#irulFzd)" class="iuvw09bxv"/><path fill="url(#iioWENb)" class="iuvw09bxv"/><circle fill="url(#iBatVRV)" transform="matrix(-1 0 0 1 7.453 17.491)" class="am9uocbqt"/><g filter="url(#iwY2EGd)"><path class="wyxgftiql"/></g><g filter="url(#i5SoE5b)"><path clip-rule="evenodd" class="sd64plbcm"/></g><g filter="url(#ib0qVcb)"><path fill="url(#ix1G3ae)" class="v7b318o3j"/><path fill="url(#igVmwzc)" class="v7b318o3j"/><path fill="url(#iwRHoNe)" class="v7b318o3j"/></g><path clip-rule="evenodd" class="ktz675vef"/><g filter="url(#idcQYjc)"><path clip-rule="evenodd" class="vtslwgb8s"/></g><path class="lt5g8e_rr"/><path class="xrg2by5ae"/><path fill="url(#ik7Yphb)" class="vrhoeqozk"/><path fill="url(#i6TRYIb)" class="nf6zt45gt"/><ellipse fill="url(#ipECBte)" transform="scale(-1 1)rotate(24.61 -19.658 -32.886)" class="m1l7k9jve"/><g filter="url(#if2nU5d)"><path fill="url(#iSEwu8S)" class="ymlbtkbyk"/></g><g filter="url(#ixct41t)"><path fill="url(#i5focee)" class="yr6_3jk-x"/></g><defs><radialGradient id="iihWdCc" cx="0" cy="0" r="1" gradientTransform="matrix(2.34375 2.75 -1.10746 .94385 15.457 12.496)" gradientUnits="userSpaceOnUse"><stop class="nzba4kbzo"/><stop offset="1" class="ye175uikr"/></radialGradient><radialGradient id="iSBrLmW" cx="0" cy="0" r="1" gradientTransform="rotate(176.424 9.287 8.437)scale(1.50293 1.62478)" gradientUnits="userSpaceOnUse"><stop class="a7cdq8ifc"/><stop offset="1" class="b4mjy6b9e"/></radialGradient><radialGradient id="iUctc4d" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.57031 -1.46069 0 .84 .234)" gradientUnits="userSpaceOnUse"><stop offset=".238" class="ygdc80fko"/><stop offset="1" class="a5_lx-bnb"/></radialGradient><radialGradient id="iETpATd" cx="0" cy="0" r="1" gradientTransform="rotate(-14.821 2.856 -4.348)scale(.48867)" gradientUnits="userSpaceOnUse"><stop class="tl0sw7mkk"/><stop offset="1" class="xu259ab4x"/></radialGradient><radialGradient id="iPmd0rd" cx="0" cy="0" r="1" gradientTransform="matrix(.50415 0 0 .66877 0 .727)" gradientUnits="userSpaceOnUse"><stop class="hyb__5ivb"/><stop offset="1" class="wfraawh3t"/></radialGradient><radialGradient id="igVlLGd" cx="0" cy="0" r="1" gradientTransform="matrix(-.76278 .55328 -.95792 -1.32064 1.33 1.556)" gradientUnits="userSpaceOnUse"><stop class="j04p-ebdr"/><stop offset="1" class="kyqggpm3k"/></radialGradient><radialGradient id="i0Jeete" cx="0" cy="0" r="1" gradientTransform="matrix(-.3125 .60583 -.77155 -.39799 16.531 5.976)" gradientUnits="userSpaceOnUse"><stop offset=".332" class="fvok_qxen"/><stop offset="1" class="suyap8bzv"/></radialGradient><radialGradient id="iXfcV1b" cx="0" cy="0" r="1" gradientTransform="matrix(.84375 -.04687 .05715 1.0287 12.992 5.561)" gradientUnits="userSpaceOnUse"><stop offset=".156" class="d7kch3t0q"/><stop offset="1" class="admd7db0k"/></radialGradient><radialGradient id="ibI6tve" cx="0" cy="0" r="1" gradientTransform="matrix(-.84375 5.57813 -4.53655 -.6862 12.3 3.384)" gradientUnits="userSpaceOnUse"><stop offset=".718" class="rmg76y8bk"/><stop offset="1" class="dgcxumb4u"/></radialGradient><radialGradient id="i91MRih" cx="0" cy="0" r="1" gradientTransform="matrix(.45312 .9414 -1.52974 .7363 12.785 5.382)" gradientUnits="userSpaceOnUse"><stop offset=".04" class="bervkqbmz"/><stop offset="1" class="c479w-bpn"/></radialGradient><radialGradient id="izmhOqd" cx="0" cy="0" r="1" gradientTransform="matrix(-2.45369 2.93958 -5.96661 -4.98038 10.88 18.039)" gradientUnits="userSpaceOnUse"><stop offset=".434" class="oiy_54b9a"/><stop offset="1" class="rm4aiz5dn"/></radialGradient><radialGradient id="iLuzMjb" cx="0" cy="0" r="1" gradientTransform="rotate(143.616 2.467 11.366)scale(1.10629 6.64432)" gradientUnits="userSpaceOnUse"><stop offset=".043" class="v5lz4sb9o"/><stop offset="1" class="m_uy2vb_d"/></radialGradient><radialGradient id="iX7Zbuc" cx="0" cy="0" r="1" gradientTransform="rotate(-122.302 11.744 7.15)scale(6.08182 1.60193)" gradientUnits="userSpaceOnUse"><stop offset=".07" class="mngz2ebss"/><stop offset="1" class="ttsumpbek"/></radialGradient><radialGradient id="iSwwsYc" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.42188 -1.38588 0 11.164 16.194)" gradientUnits="userSpaceOnUse"><stop class="f3j6dkfip"/><stop offset="1" class="fxoxl0blj"/></radialGradient><radialGradient id="iPFAMDd" cx="0" cy="0" r="1" gradientTransform="matrix(-.14062 -.17969 .6458 -.50541 15.86 28.108)" gradientUnits="userSpaceOnUse"><stop class="ryq0o3qru"/><stop offset="1" class="yfqxgqb1h"/></radialGradient><radialGradient id="ipNv7rd" cx="0" cy="0" r="1" gradientTransform="matrix(-6.375 -1.81248 4.6745 -16.4415 15.539 19.241)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="ex23x-brg"/><stop offset="1" class="ux4w7lb6c"/></radialGradient><radialGradient id="ipmfqPe" cx="0" cy="0" r="1" gradientTransform="matrix(.09374 -1.53125 2.45635 .15037 16.992 29.46)" gradientUnits="userSpaceOnUse"><stop class="cl2mlwbhs"/><stop offset="1" class="yvuyjoqpy"/></radialGradient><radialGradient id="iS92ZBc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.0625 -.21876 .15137 -.73521 20.101 28.522)" gradientUnits="userSpaceOnUse"><stop class="m3n9jy0fh"/><stop offset="1" class="hdzwkybza"/></radialGradient><radialGradient id="iLzzPlb" cx="0" cy="0" r="1" gradientTransform="matrix(-.59376 -1.71875 .84778 -.29287 16.086 29.757)" gradientUnits="userSpaceOnUse"><stop offset=".08" class="a541b3bqx"/><stop offset="1" class="zc8ie-1dg"/></radialGradient><radialGradient id="i0mHHPb" cx="0" cy="0" r="1" gradientTransform="rotate(-47.125 33.087 9.025)scale(1.99789 1.10527)" gradientUnits="userSpaceOnUse"><stop class="xh_da2q2q"/><stop offset="1" class="stwbr2bhy"/></radialGradient><radialGradient id="iocBSvu" cx="0" cy="0" r="1" gradientTransform="rotate(-88.915 13.886 2.355)scale(4.95211 1.34022)" gradientUnits="userSpaceOnUse"><stop class="dkjt4cbcx"/><stop offset="1" class="w9ku-ifwq"/></radialGradient><radialGradient id="iPkhHVd" cx="0" cy="0" r="1" gradientTransform="matrix(-3.65186 0 0 -15.6875 13.143 14.306)" gradientUnits="userSpaceOnUse"><stop offset=".436" class="p0p0ijbbx"/><stop offset=".967" class="dvcrl_y_s"/></radialGradient><radialGradient id="i9jn0pd" cx="0" cy="0" r="1" gradientTransform="matrix(4.78125 .78125 -1.79108 10.96143 9.768 15.118)" gradientUnits="userSpaceOnUse"><stop offset=".781" class="jx6m9tune"/><stop offset=".931" class="g41565bda"/></radialGradient><radialGradient id="irulFzd" cx="0" cy="0" r="1" gradientTransform="matrix(-.51563 1.34375 -3.67742 -1.41111 13.206 8.274)" gradientUnits="userSpaceOnUse"><stop offset=".297" class="p663aq61v"/><stop offset="1" class="kqh0ncb_u"/></radialGradient><radialGradient id="iioWENb" cx="0" cy="0" r="1" gradientTransform="rotate(54.539 -2.657 15.358)scale(1.15812 2.04942)" gradientUnits="userSpaceOnUse"><stop class="jq_uanbes"/><stop offset="1" class="oq2q2abrd"/></radialGradient><radialGradient id="iBatVRV" cx="0" cy="0" r="1" gradientTransform="rotate(90 .008 .406)scale(.90625)" gradientUnits="userSpaceOnUse"><stop offset=".256" class="d69nsybly"/><stop offset="1" class="eluf2xb_e"/></radialGradient><radialGradient id="igVmwzc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.0907 .20313 -.4206 -2.25834 12.953 10.352)" gradientUnits="userSpaceOnUse"><stop offset=".12" class="xot8u71lw"/><stop offset="1" class="jjp3z2beb"/></radialGradient><radialGradient id="iwRHoNe" cx="0" cy="0" r="1" gradientTransform="rotate(135.955 2.907 7.044)scale(2.65202 1.5046)" gradientUnits="userSpaceOnUse"><stop offset=".204" class="lz70c3nqo"/><stop offset="1" class="pt5v4qb1w"/></radialGradient><radialGradient id="ik7Yphb" cx="0" cy="0" r="1" gradientTransform="matrix(-.27344 0 0 -.53125 15.355 5.636)" gradientUnits="userSpaceOnUse"><stop offset=".895" class="l0aricxam"/><stop offset="1" class="n9r91ylyy"/></radialGradient><radialGradient id="i6TRYIb" cx="0" cy="0" r="1" gradientTransform="matrix(-.25 0 0 -.54102 15.523 5.657)" gradientUnits="userSpaceOnUse"><stop class="gv3iwdbvq"/><stop offset=".813" class="ubyl24bdb"/></radialGradient><linearGradient id="iBDizMu" x1="17.668" x2="19.551" y1="15.52" y2="17.559" gradientUnits="userSpaceOnUse"><stop class="o52vxyscb"/><stop offset="1" class="u-867gbtx"/></linearGradient><linearGradient id="iKKXfYc" x1="23.113" x2="21.863" y1="21.809" y2="22.747" gradientUnits="userSpaceOnUse"><stop class="n6l6ilaec"/><stop offset="1" class="vjqn9lx3p"/></linearGradient><linearGradient id="iQPo2Lb" x1="26.777" x2="25.043" y1="28.653" y2="26.309" gradientUnits="userSpaceOnUse"><stop class="uug2ubxhk"/><stop offset="1" class="deyia0bkx"/></linearGradient><linearGradient id="iPXPLDb" x1="26.723" x2="26.364" y1="27.09" y2="27.34" gradientUnits="userSpaceOnUse"><stop class="p8mdyfi9b"/><stop offset="1" class="g6zbvk7ui"/></linearGradient><linearGradient id="ij6Ri1f" x1="18.254" x2="20.004" y1="16.356" y2="18.653" gradientUnits="userSpaceOnUse"><stop class="ly5_jc0cc"/><stop offset="1" class="sxo3xwbvl"/></linearGradient><linearGradient id="ijWfPhb" x1="18.145" x2="18.668" y1="16.419" y2="17.184" gradientUnits="userSpaceOnUse"><stop offset=".098" class="iykv72k7v"/><stop offset="1" class="qg5pcsysc"/></linearGradient><linearGradient id="iUOyqwe" x1="13.304" x2="16.167" y1="6.304" y2="6.476" gradientUnits="userSpaceOnUse"><stop class="egm-dub4f"/><stop offset="1" class="zhwoohbuw"/></linearGradient><linearGradient id="i8L1tPb" x1="9.859" x2="7.631" y1="22.898" y2="20.954" gradientUnits="userSpaceOnUse"><stop offset=".211" class="pat1zf4-w"/><stop offset="1" class="wtea7v6lu"/></linearGradient><linearGradient id="i81bVxe" x1="12.086" x2="12.086" y1="16.085" y2="16.429" gradientUnits="userSpaceOnUse"><stop offset=".136" class="x5p6yzbmf"/><stop offset="1" class="cnh3p8b3x"/></linearGradient><linearGradient id="iXl61qe" x1="17.554" x2="17.468" y1="29.632" y2="29.319" gradientUnits="userSpaceOnUse"><stop class="l138bfbcs"/><stop offset="1" class="oxce79bcz"/></linearGradient><linearGradient id="iVPlhFb" x1="15.586" x2="16.164" y1="30.007" y2="29.788" gradientUnits="userSpaceOnUse"><stop offset=".064" class="lhdz7oxfj"/><stop offset="1" class="csaq2_bel"/></linearGradient><linearGradient id="iJ627hb" x1="6.976" x2="6.383" y1="27.991" y2="28.163" gradientUnits="userSpaceOnUse"><stop class="oxg1n1wjw"/><stop offset="1" class="y0g_czb9f"/></linearGradient><linearGradient id="iaAYIDc" x1="4.851" x2="5.031" y1="28.065" y2="27.917" gradientUnits="userSpaceOnUse"><stop class="p6qc3nb-j"/><stop offset="0" class="ezcqmvbni"/><stop offset="1" class="stwbr2bhy"/></linearGradient><linearGradient id="igTLwTv" x1="15.133" x2="14.258" y1="12.851" y2="10.46" gradientUnits="userSpaceOnUse"><stop class="t55apucyo"/><stop offset=".787" class="biw5o_cgj"/></linearGradient><linearGradient id="ix1G3ae" x1="11.101" x2="9.992" y1="9.132" y2="12.585" gradientUnits="userSpaceOnUse"><stop offset=".118" class="u1dukib7n"/><stop offset="1" class="mk0srdu2z"/></linearGradient><linearGradient id="ipECBte" x1="-.007" x2=".179" y1=".05" y2=".11" gradientUnits="userSpaceOnUse"><stop class="vc--wpv5i"/><stop offset="1" class="stui2mbih"/></linearGradient><linearGradient id="iSEwu8S" x1="15.758" x2="11.133" y1="27.429" y2="17.288" gradientUnits="userSpaceOnUse"><stop class="v9kimlbms"/><stop offset="1" class="g24ahctiy"/></linearGradient><linearGradient id="i5focee" x1="5.613" x2="9.924" y1="25.338" y2="19.966" gradientUnits="userSpaceOnUse"><stop class="ckhjb_bgt"/><stop offset="1" class="rnrhdzckq"/></linearGradient><filter id="i79u1tc" width="7.179" height="6.928" x="12.69" y="10.876" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.5" dy="-.75"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.760784 0 0 0 0 0.447059 0 0 0 0 0.180392 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_2895"/></filter><filter id="iYS2iUd" width="2.607" height="2.722" x="17.061" y="15.147" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_2_2895" stdDeviation=".05"/></filter><filter id="ij3uQbc" width="8.674" height="11.796" x="19.144" y="17.479" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.741176 0 0 0 0 0.647059 0 0 0 0 0.811765 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_2895"/></filter><filter id="iSuj5Zc" width="1.68" height="1.68" x="26.703" y="28.223" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.835294 0 0 0 0 0.819608 0 0 0 0 0.835294 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_2895"/></filter><filter id="iYaE0Xc" width="2.726" height="3.079" x="17.736" y="15.915" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.211765 0 0 0 0 0.133333 0 0 0 0 0.27451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_2895"/></filter><filter id="i4fqhcc" width="1.093" height="1.661" x="18.724" y="15.54" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.15"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.933333 0 0 0 0 0.678431 0 0 0 0 0.105882 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_2895"/></filter><filter id="iBD2hwd" width="4.493" height="5.449" x="11.674" y="3.163" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25" dy="-.4"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.85098 0 0 0 0 0.54902 0 0 0 0 0.227451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_2895"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.15" dy="-.05"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.737255 0 0 0 0 0.4 0 0 0 0 0.0470588 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_2_2895" result="effect2_innerShadow_2_2895"/></filter><filter id="idIcKQc" width="6.813" height="7.403" x="9.515" y="1.701" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.4" dy=".4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.843137 0 0 0 0 0.207843 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_2895"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.607843 0 0 0 0 0.117647 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_2_2895" result="effect2_innerShadow_2_2895"/></filter><filter id="itcmwHe" width="8.674" height="14.771" x="3.72" y="15.476" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".75" dy="-.75"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.439216 0 0 0 0 0.388235 0 0 0 0 0.486275 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_2895"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.537255 0 0 0 0 0.423529 0 0 0 0 0.635294 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_2_2895" result="effect2_innerShadow_2_2895"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy=".25"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.529412 0 0 0 0 0.490196 0 0 0 0 0.537255 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_2_2895" result="effect3_innerShadow_2_2895"/></filter><filter id="i0yQkXa" width="10.972" height="14.104" x="9.478" y="15.994" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy="-.2"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.619608 0 0 0 0 0.592157 0 0 0 0 0.611765 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_2895"/></filter><filter id="iwY2EGd" width="5.442" height="5.875" x="8.111" y="8.468" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_2_2895" stdDeviation=".375"/></filter><filter id="i5SoE5b" width="7.59" height="10.511" x="4.352" y="9.157" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.901961 0 0 0 0 0.623529 0 0 0 0 0.188235 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_2895"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.4" dy=".4"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.835294 0 0 0 0 0.25098 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_2_2895" result="effect2_innerShadow_2_2895"/></filter><filter id="ib0qVcb" width="4.758" height="4.525" x="8.445" y="8.654" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.15"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.392157 0 0 0 0 0.254902 0 0 0 0 0.639216 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_2895"/></filter><filter id="idcQYjc" width="1.013" height=".568" x="14.492" y="4.306" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.682353 0 0 0 0 0.219608 0 0 0 0 0.133333 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_2895"/></filter><filter id="if2nU5d" width="6.844" height="12.891" x="10.133" y="16.116" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_2_2895" stdDeviation=".5"/></filter><filter id="ixct41t" width="6.45" height="8.475" x="4.578" y="18.044" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_2_2895" stdDeviation=".375"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:woman-with-white-cane-facing-right" /></template>
<style>
.a5_lx-bnb {
  stop-color: var(--svg-color--ccaae9, #CCAAE9);
}

.a541b3bqx {
  stop-color: var(--svg-color--515279, #515279);
}

.a7cdq8ifc {
  stop-color: var(--svg-color--d2941c, #D2941C);
}

.admd7db0k {
  stop-color: var(--svg-color--ffab1d, #FFAB1D);
  stop-opacity: 0;
}

.am9uocbqt {
  cx: 0.551px;
  cy: 0.551px;
  r: 0.551px;
}

.appbbetkk {
  fill: var(--svg-color--725ca6, #725CA6);
  d: path("M12.308 8.612c-.89 0-1.136.215-1.433.407L9.85 11.616c-.3 1.4-.364 3.636-.36 4.578h4.767c.257-.656.677-2.675.515-4.578c-.164-1.93-1.207-2.902-2.465-3.004");
}

.b4mjy6b9e {
  stop-color: var(--svg-color--d2941c, #D2941C);
  stop-opacity: 0;
}

.bervkqbmz {
  stop-color: var(--svg-color--ffd040, #FFD040);
}

.biw5o_cgj {
  stop-color: var(--svg-color--816fa6, #816FA6);
}

.c479w-bpn {
  stop-color: var(--svg-color--fead30, #FEAD30);
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

.d-yf4yoik {
  d: path("m15.238 28.636l.391 1.285a.25.25 0 0 0 .315.166l3.737-1.183c.195-.062.326-.265.244-.452c-.107-.245-.332-.5-.886-.656c-.59-.167-1.673-.262-2.306-.318l-.21-.018v-.002z");
}

.d69nsybly {
  stop-color: var(--svg-color--e99f2e, #E99F2E);
}

.d7kch3t0q {
  stop-color: var(--svg-color--ffab1d, #FFAB1D);
}

.deyia0bkx {
  stop-color: var(--svg-color--f3386a, #F3386A);
}

.dgcxumb4u {
  stop-color: var(--svg-color--a76445, #A76445);
}

.dkjt4cbcx {
  stop-color: var(--svg-color--7966a4, #7966A4);
}

.dvcrl_y_s {
  stop-color: var(--svg-color--6c5d89, #6C5D89);
}

.egj5webql {
  d: path("M18.915 15.998a.2.2 0 0 0-.28-.045l-.816.59a.2.2 0 0 0-.045.28l1.509 2.089a.2.2 0 0 0 .279.044l.817-.59a.2.2 0 0 0 .045-.28z");
}

.egm-dub4f {
  stop-color: var(--svg-color--ffc33e, #FFC33E);
}

.eluf2xb_e {
  stop-color: var(--svg-color--ce853f, #CE853F);
}

.ex23x-brg {
  stop-color: var(--svg-color--8c8388, #8C8388);
  stop-opacity: 0;
}

.ezcqmvbni {
  stop-color: var(--svg-color--443a80, #443A80);
}

.f00xt4bzn {
  stroke: var(--svg-color--33241a, #33241A);
  stroke-width: var(--svg-stroke-width--0-35px, 0.35px);
  d: path("M19.508 15.973a1.21 1.21 0 1 0-.101 1.24");
}

.f3j6dkfip {
  stop-color: var(--svg-color--99919a, #99919A);
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

.g24ahctiy {
  stop-color: var(--svg-color--94899e, #94899E);
  stop-opacity: 0;
}

.g41565bda {
  stop-color: var(--svg-color--8272a4, #8272A4);
}

.g6zbvk7ui {
  stop-color: var(--svg-color--f35886, #F35886);
  stop-opacity: 0;
}

.geodi6uui {
  fill: var(--svg-color--8c8393, #8C8393);
  d: path("M15.015 18.577c-.383-1.05-.716-2.029-.773-2.383H9.5c-.1 1.375.144 1.712.773 2.422c.693.782 2.172 2.43 2.54 2.895c.35.35.5.789.554.98l2.262 7.43a.25.25 0 0 0 .315.166l3.737-1.183c.195-.061.326-.265.244-.452c-.107-.245-.332-.5-.886-.656c-.663-.188-1.943-.284-2.516-.336c-.213-1.766-.66-5.431-.734-5.969c-.094-.672-.227-1.414-.774-2.914");
}

.ghq9gsa-q {
  cx: 0.84px;
  cy: 0.84px;
  r: 0.84px;
}

.gv3iwdbvq {
  stop-color: var(--svg-color--666361, #666361);
}

.hdzwkybza {
  stop-color: var(--svg-color--63617e, #63617E);
  stop-opacity: 0;
}

.hm5ipfb1e {
  fill: var(--svg-color--eb9a29, #EB9A29);
  fill-rule: evenodd;
  d: path("M13.781 11.732a1.05 1.05 0 0 0-.485 1.403c1.832 3.77 4.235 4.912 5.72 4.627a1.05 1.05 0 0 0-.396-2.062s-.026.004-.082 0a1.2 1.2 0 0 1-.24-.044a2.7 2.7 0 0 1-.803-.404c-.65-.457-1.494-1.354-2.31-3.035a1.05 1.05 0 0 0-1.404-.485");
}

.htt-kcc6h {
  d: path("m24.911 26.21l2.092 2.88a.45.45 0 1 0 .728-.53l-2.092-2.878z");
}

.hyb__5ivb {
  stop-color: var(--svg-color--e4d4ea, #E4D4EA);
}

.i9n-zdbqk {
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M19.523 16.003a1.211 1.211 0 1 0-.117 1.212");
}

.iuvw09bxv {
  d: path("M12.308 8.612c-.89 0-1.136.215-1.433.407L9.85 11.616c-.3 1.4-.364 3.636-.36 4.578h4.767c.257-.656.677-2.675.515-4.578c-.164-1.93-1.207-2.902-2.465-3.004");
}

.iykv72k7v {
  stop-color: var(--svg-color--62516b, #62516B);
}

.j04p-ebdr {
  stop-color: var(--svg-color--cc7716, #CC7716);
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

.kqh0ncb_u {
  stop-color: var(--svg-color--885876, #885876);
  stop-opacity: 0;
}

.ktz675vef {
  fill: var(--svg-color--87014d, #87014D);
  fill-rule: evenodd;
  d: path("M14.887 6.77a.125.125 0 0 0 .002.178c.238.233.582.293.692.304a.125.125 0 1 0 .025-.248c-.093-.01-.366-.062-.542-.235a.125.125 0 0 0-.177.002");
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

.lt5g8e_rr {
  fill: var(--svg-color--2f2c2d, #2F2C2D);
  d: path("M14.607 5.146c.131-.131.35-.161.442-.16l-.303.467c-.147-.008-.303-.143-.139-.307");
}

.ly5_jc0cc {
  stop-color: var(--svg-color--4d3b5c, #4D3B5C);
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

.mk0srdu2z {
  stop-color: var(--svg-color--7759b2, #7759B2);
}

.mngz2ebss {
  stop-color: var(--svg-color--897998, #897998);
}

.n6l6ilaec {
  stop-color: var(--svg-color--d4c6dc, #D4C6DC);
}

.n9r91ylyy {
  stop-color: var(--svg-color--824d44, #824D44);
}

.nauosacxo {
  width: 0.832px;
  height: 1.669px;
  fill: var(--svg-color--ffbd35, #FFBD35);
  rx: 0.416px;
}

.nf6zt45gt {
  d: path("m15.223 5.657l-.005-.072c0-.186.08-.336.176-.336c.097 0 .176.15.176.336l-.004.072z");
}

.nzba4kbzo {
  stop-color: var(--svg-color--ffc146, #FFC146);
}

.o52vxyscb {
  stop-color: var(--svg-color--443d44, #443D44);
}

.o9wm0bbzg {
  d: path("M15.015 18.577c-.383-1.05-.716-2.029-.773-2.383H9.5c-.1 1.375.144 1.712.773 2.422c.693.782 2.172 2.43 2.54 2.895c.35.35.5.789.554.98l2.262 7.43a.25.25 0 0 0 .315.166l3.737-1.183c.195-.061.326-.265.244-.452c-.107-.245-.332-.5-.886-.656c-.663-.188-1.943-.284-2.516-.336c-.213-1.766-.66-5.431-.734-5.969c-.094-.672-.227-1.414-.774-2.914");
}

.oiy_54b9a {
  stop-color: var(--svg-color--887e8b, #887E8B);
}

.oq2q2abrd {
  stop-color: var(--svg-color--48234a, #48234A);
  stop-opacity: 0;
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

.p8mdyfi9b {
  stop-color: var(--svg-color--f35886, #F35886);
}

.pat1zf4-w {
  stop-color: var(--svg-color--8b8290, #8B8290);
}

.pt5v4qb1w {
  stop-color: var(--svg-color--9075ca, #9075CA);
  stop-opacity: 0;
}

.q7l9pkmfb {
  d: path("M16.259 3.516c.171-.41-.017-.843-.113-.992c-.367-.672-1.128-.716-1.567-.523c-.516.226-.67.347-1.504.11c-.836-.24-1.867-.13-2.406.839s.047 2.059-.086 2.652c-.133.594-.512.653-.652 1.34c-.118.953.472 1.574.996 1.715c.523.14 1.601 0 1.953-.875c.575-1.432.184-2.11.309-2.828c.125-.719.555-.922 1.336-.766c.92.184 1.505-.126 1.734-.672");
}

.qg5pcsysc {
  stop-color: var(--svg-color--483a55, #483A55);
  stop-opacity: 0;
}

.r0bikq6kj {
  fill: var(--svg-color--ffb629, #FFB629);
  d: path("M16.259 3.516c.171-.41-.017-.843-.113-.992c-.367-.672-1.128-.716-1.567-.523c-.516.226-.67.347-1.504.11c-.836-.24-1.867-.13-2.406.839s.047 2.059-.086 2.652c-.133.594-.512.653-.652 1.34c-.118.953.472 1.574.996 1.715c.523.14 1.601 0 1.953-.875c.575-1.432.184-2.11.309-2.828c.125-.719.555-.922 1.336-.766c.92.184 1.505-.126 1.734-.672");
}

.rdk9y-boj {
  fill-rule: evenodd;
  d: path("M19.33 17.766a.45.45 0 0 0-.1.628l7.773 10.695a.45.45 0 0 0 .728-.529l-7.773-10.695a.45.45 0 0 0-.629-.1");
}

.rh704p7-v {
  d: path("m8.663 19.96l.891-3.734h1.781c.052.614.152 2.215.29 3.515s-.492 2.032-.766 2.313l-4.446 4.312c.198.662.627 2.025.728 2.625c.076.462-.146.768-.352.953c-.093.083-.234.064-.318-.03L3.784 26.92a.25.25 0 0 1 .019-.353l.985-.887c1.042-1.365 3.191-4.194 3.454-4.594c.181-.276.39-.917.421-1.125");
}

.rjm7vebtj {
  fill-rule: evenodd;
  d: path("M13.781 11.732a1.05 1.05 0 0 0-.485 1.403c1.832 3.77 4.235 4.912 5.72 4.627a1.05 1.05 0 0 0-.396-2.062s-.026.004-.082 0a1.2 1.2 0 0 1-.24-.044a2.7 2.7 0 0 1-.803-.404c-.65-.457-1.494-1.354-2.31-3.035a1.05 1.05 0 0 0-1.404-.485");
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

.ry392sb1p {
  d: path("M14.617 10.515c-.281-.713-.774-1.224-.984-1.391l.039 4.469l1.785-.836c-.278-.524-.489-1.352-.84-2.242");
}

.ryq0o3qru {
  stop-color: var(--svg-color--a19da6, #A19DA6);
}

.sd64plbcm {
  fill: var(--svg-color--ffbf35, #FFBF35);
  fill-rule: evenodd;
  d: path("M5.996 19.238a.614.614 0 0 0 .776-.407c1.215-3.922 3.166-6.29 4.541-7.545c.438-.4.516-1.082.128-1.53c-.346-.401-.944-.472-1.348-.13c-1.626 1.38-3.91 3.976-5.316 8.605a.59.59 0 0 0 .383.73z");
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

.sxo3xwbvl {
  stop-color: var(--svg-color--3f3647, #3F3647);
}

.t55apucyo {
  stop-color: var(--svg-color--725d9d, #725D9D);
}

.tdu96mbso {
  d: path("M13.375 6.323c.05 0 .085-.046.079-.096l-.174-1.249c-.007-.055-.059-.094-.112-.078a.727.727 0 0 0 .207 1.423");
}

.tl0sw7mkk {
  stop-color: var(--svg-color--e9d9f5, #E9D9F5);
}

.tqwucabqb {
  d: path("M16.139 4.863c-.038-.8-.298-1.187-.42-1.3h-3.732l-.063 3.164c.866 2.121 3.511 2.212 3.906 1.445s.354-2.381.309-3.309");
}

.ttsumpbek {
  stop-color: var(--svg-color--897998, #897998);
  stop-opacity: 0;
}

.u-867gbtx {
  stop-color: var(--svg-color--443d44, #443D44);
  stop-opacity: 0;
}

.u1dukib7n {
  stop-color: var(--svg-color--8265b5, #8265B5);
}

.ubyl24bdb {
  stop-color: var(--svg-color--565352, #565352);
}

.uug2ubxhk {
  stop-color: var(--svg-color--e82b8e, #E82B8E);
}

.ux4w7lb6c {
  stop-color: var(--svg-color--8c8388, #8C8388);
}

.v1-jeibjs {
  fill: var(--svg-color--45437a, #45437A);
  d: path("m4.797 25.668l1.638.678l-.022.02l.108.355c.216.713.535 1.764.62 2.27c.076.462-.146.768-.352.953c-.093.083-.234.064-.318-.03L3.784 26.92a.25.25 0 0 1 .018-.353l.986-.887z");
}

.v5lz4sb9o {
  stop-color: var(--svg-color--695c75, #695C75);
}

.v7b318o3j {
  d: path("M12.444 11.218a1.355 1.355 0 1 0-1.729-2.088c-.95.692-1.79 1.592-2.27 2.135l2.04 1.914a154 154 0 0 1 1.959-1.961");
}

.v9kimlbms {
  stop-color: var(--svg-color--94899e, #94899E);
}

.vc--wpv5i {
  stop-color: var(--svg-color--fff, #fff);
}

.vjqn9lx3p {
  stop-color: var(--svg-color--cdb4e3, #CDB4E3);
}

.vrhoeqozk {
  d: path("M15.027 5.657v-.004c0-.32.137-.58.307-.58s.306.26.306.58v.004z");
}

.vtslwgb8s {
  fill: var(--svg-color--af5247, #AF5247);
  fill-rule: evenodd;
  d: path("M15.12 4.624a.8.8 0 0 1 .217-.015a.15.15 0 0 0 .037-.298a1 1 0 0 0-.313.02a1 1 0 0 0-.408.172a.15.15 0 0 0 .178.242c.085-.063.19-.1.289-.12");
}

.w9ku-ifwq {
  stop-color: var(--svg-color--7966a4, #7966A4);
  stop-opacity: 0;
}

.wfraawh3t {
  stop-color: var(--svg-color--e4d4ea, #E4D4EA);
  stop-opacity: 0;
}

.wtea7v6lu {
  stop-color: var(--svg-color--9f9c9f, #9F9C9F);
}

.wyxgftiql {
  fill: var(--svg-color--442e79, #442E79);
  d: path("M12.597 10.985c.31-.248.178-.39.178-.818c0-.749-.013-.95-.762-.95a1.35 1.35 0 0 0-.883.327c-.95.692-1.789 1.592-2.27 2.135l2.04 1.914a58 58 0 0 0 1.697-2.608");
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

.xrg2by5ae {
  fill: var(--svg-color--fff, #fff);
  d: path("M15.633 5.657h-.989c0-.391.222-.709.494-.709c.273 0 .495.318.495.71");
}

.xu259ab4x {
  stop-color: var(--svg-color--e9d9f5, #E9D9F5);
  stop-opacity: 0;
}

.y0g_czb9f {
  stop-color: var(--svg-color--5a577e, #5A577E);
  stop-opacity: 0;
}

.ye175uikr {
  stop-color: var(--svg-color--ffc146, #FFC146);
  stop-opacity: 0;
}

.yfqxgqb1h {
  stop-color: var(--svg-color--a19da6, #A19DA6);
  stop-opacity: 0;
}

.ygdc80fko {
  stop-color: var(--svg-color--d8cbdd, #D8CBDD);
}

.ymlbtkbyk {
  d: path("m14.633 21.194l1.343 6.5l-.36.313l-1.468-6.531l-3.015-3.875l.703-.485z");
}

.yr6_3jk-x {
  d: path("M8.805 21.142L5.328 25.57l.514.199l3.485-3.708a3 3 0 0 0 .76-1.493l.191-1l-.752-.774l-.543 1.994a1 1 0 0 1-.178.354");
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

.zette2dgx {
  d: path("M16.363 5.827a1 1 0 0 1-.258-.457h-.18v1.125c.215.137.523.115.614-.09c.078-.176.02-.394-.176-.578");
}

.zhwoohbuw {
  stop-color: var(--svg-color--ffc247, #FFC247);
}

.zwa6vrpwb {
  d: path("m4.797 25.668l1.638.678l-.022.02l.108.355c.216.713.535 1.764.62 2.27c.076.462-.146.768-.352.953c-.093.083-.234.064-.318-.03L3.784 26.92a.25.25 0 0 1 .018-.353l.986-.887z");
}

</style>
