<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iO4ousL)" transform="rotate(-4.337 14.181 6.729)" class="vi33vey6i"/><path fill="url(#iDQ4F2b)" class="zhrkjbb7n"/><g filter="url(#iTlD1id)"><path fill="url(#iYTGlYH)" class="pdtjsyxpv"/><path fill="url(#id6d2Fb)" class="pdtjsyxpv"/></g><g filter="url(#iDcMICb)"><path class="d5lab6b6s"/></g><path fill="url(#idE3tEd)" class="cv0ocebom"/><path fill="url(#ivcmpBe)" class="luqljkbkk"/><g filter="url(#iikYdhc)"><path fill="url(#ipSh7Ab)" class="f-3dg9neb"/><path fill="url(#ifqYMqQ)" class="f-3dg9neb"/><path fill="url(#i0vVaLx)" class="f-3dg9neb"/></g><g filter="url(#iAHIoxY)"><path class="jtjskiljj"/><path fill="url(#icwFmpc)" class="pu87gqowa"/><path fill="url(#iZllrhd)" class="pu87gqowa"/><path fill="url(#iML24Wb)" class="pu87gqowa"/><path fill="url(#iaFjZcd)" class="pu87gqowa"/><path fill="url(#iGSnOGg)" class="pu87gqowa"/></g><path fill="url(#igghbnd)" class="d3mv4-bwq"/><path fill="url(#iluPkVG)" class="d3mv4-bwq"/><path fill="url(#ix5lz9d)" class="d3mv4-bwq"/><path fill="url(#iPYUKxe)" class="d3mv4-bwq"/><path fill="url(#iQSzi3h)" class="d3mv4-bwq"/><path class="ws8t0ub-u"/><path fill="url(#iujHcGe)" class="ezn4aipdh"/><path fill="url(#ioMwqdd)" class="ezn4aipdh"/><path fill="url(#iAfs6BU)" class="ezn4aipdh"/><g filter="url(#iLU9KGe)"><path clip-rule="evenodd" class="dgxj10bki"/></g><path fill="url(#iLQKQcd)" class="i7ywxfd5f"/><path class="ywie972fs"/><path fill="url(#i7nvgLd)" class="zn6q2i0go"/><path fill="url(#iCu47me)" class="zn6q2i0go"/><path fill="url(#iXBp5Ca)" class="zn6q2i0go"/><path fill="url(#iDcG9Kc)" class="zn6q2i0go"/><path fill="url(#iv2Xuoc)" class="zn6q2i0go"/><circle fill="url(#i9Vmsge)" class="dwt1fld0s"/><g filter="url(#iFHURIc)"><path class="ik_2dacqf"/></g><g filter="url(#iyoQl0c)"><path clip-rule="evenodd" class="vp_xd9b8f"/></g><g filter="url(#iMSnpdc)"><path fill="url(#iSsiqfe)" class="qe_otxnzg"/><path fill="url(#i9wCq7b)" class="qe_otxnzg"/><path fill="url(#ia1iyoc)" class="qe_otxnzg"/></g><path fill="url(#iaCU4vN)" class="kto05ftpk"/><path clip-rule="evenodd" class="l77q_mb0z"/><g filter="url(#ik49Owe)"><path clip-rule="evenodd" class="v0ryunblo"/></g><path class="i5j5t695y"/><path class="hq1t4kbaf"/><path fill="url(#iwqUy0u)" class="u_490kbtp"/><path fill="url(#iu2jm3P)" class="bw39i08st"/><ellipse fill="url(#iZvH4HK)" transform="rotate(24.61 12.373 5.306)" class="yhwv79m6v"/><g filter="url(#ijoKSTb)"><path fill="url(#iX2l1Hf)" class="q79sa3zre"/></g><g filter="url(#iKtroIb)"><path fill="url(#ie0wx9b)" class="szm--fb2k"/></g><defs><radialGradient id="iO4ousL" cx="0" cy="0" r="1" gradientTransform="matrix(-.76278 .55328 -.95792 -1.32064 15.513 8.286)" gradientUnits="userSpaceOnUse"><stop class="j04p-ebdr"/><stop offset="1" class="kyqggpm3k"/></radialGradient><radialGradient id="iDQ4F2b" cx="0" cy="0" r="1" gradientTransform="matrix(.3125 .60583 -.77155 .39799 11.3 5.976)" gradientUnits="userSpaceOnUse"><stop offset=".332" class="fvok_qxen"/><stop offset="1" class="suyap8bzv"/></radialGradient><radialGradient id="id6d2Fb" cx="0" cy="0" r="1" gradientTransform="matrix(-.84375 -.04688 .05715 -1.0287 14.84 5.561)" gradientUnits="userSpaceOnUse"><stop offset=".156" class="d7kch3t0q"/><stop offset="1" class="admd7db0k"/></radialGradient><radialGradient id="idE3tEd" cx="0" cy="0" r="1" gradientTransform="matrix(.84375 5.57813 -4.53655 .6862 15.533 3.384)" gradientUnits="userSpaceOnUse"><stop offset=".718" class="rmg76y8bk"/><stop offset="1" class="dgcxumb4u"/></radialGradient><radialGradient id="ivcmpBe" cx="0" cy="0" r="1" gradientTransform="rotate(115.703 5.833 7.42)scale(1.04478 1.69772)" gradientUnits="userSpaceOnUse"><stop offset=".04" class="bervkqbmz"/><stop offset="1" class="c479w-bpn"/></radialGradient><radialGradient id="ifqYMqQ" cx="0" cy="0" r="1" gradientTransform="matrix(2.45369 2.93958 -5.96661 4.98038 16.953 18.038)" gradientUnits="userSpaceOnUse"><stop offset=".434" class="oiy_54b9a"/><stop offset="1" class="rm4aiz5dn"/></radialGradient><radialGradient id="i0vVaLx" cx="0" cy="0" r="1" gradientTransform="matrix(.89062 .65625 -3.9414 5.34905 16.637 19.054)" gradientUnits="userSpaceOnUse"><stop offset=".043" class="v5lz4sb9o"/><stop offset="1" class="m_uy2vb_d"/></radialGradient><radialGradient id="icwFmpc" cx="0" cy="0" r="1" gradientTransform="matrix(3.25 -5.14063 1.35402 .85604 15.856 20.898)" gradientUnits="userSpaceOnUse"><stop offset=".07" class="mngz2ebss"/><stop offset="1" class="ttsumpbek"/></radialGradient><radialGradient id="iZllrhd" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.42188 -1.38588 0 16.668 16.194)" gradientUnits="userSpaceOnUse"><stop class="f3j6dkfip"/><stop offset="1" class="fxoxl0blj"/></radialGradient><radialGradient id="iaFjZcd" cx="0" cy="0" r="1" gradientTransform="matrix(.14063 -.17968 .6458 .50543 11.973 28.108)" gradientUnits="userSpaceOnUse"><stop class="ryq0o3qru"/><stop offset="1" class="yfqxgqb1h"/></radialGradient><radialGradient id="iGSnOGg" cx="0" cy="0" r="1" gradientTransform="matrix(6.375 -1.8125 4.67455 16.4415 12.293 19.241)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="ex23x-brg"/><stop offset="1" class="ux4w7lb6c"/></radialGradient><radialGradient id="igghbnd" cx="0" cy="0" r="1" gradientTransform="matrix(-.09375 -1.53125 2.45635 -.15039 10.84 29.46)" gradientUnits="userSpaceOnUse"><stop class="cl2mlwbhs"/><stop offset="1" class="yvuyjoqpy"/></radialGradient><radialGradient id="iluPkVG" cx="0" cy="0" r="1" gradientTransform="matrix(1.0625 -.21875 .15137 .73521 7.73 28.523)" gradientUnits="userSpaceOnUse"><stop class="m3n9jy0fh"/><stop offset="1" class="hdzwkybza"/></radialGradient><radialGradient id="ix5lz9d" cx="0" cy="0" r="1" gradientTransform="rotate(-70.942 26.754 6.636)scale(1.81842 .89694)" gradientUnits="userSpaceOnUse"><stop offset=".08" class="a541b3bqx"/><stop offset="1" class="zc8ie-1dg"/></radialGradient><radialGradient id="iAfs6BU" cx="0" cy="0" r="1" gradientTransform="rotate(-132.875 17.852 8.36)scale(1.99789 1.10527)" gradientUnits="userSpaceOnUse"><stop class="xh_da2q2q"/><stop offset="1" class="stwbr2bhy"/></radialGradient><radialGradient id="i7nvgLd" cx="0" cy="0" r="1" gradientTransform="matrix(-.09377 -4.95122 1.33998 -.02538 16.564 16.194)" gradientUnits="userSpaceOnUse"><stop class="dkjt4cbcx"/><stop offset="1" class="w9ku-ifwq"/></radialGradient><radialGradient id="iCu47me" cx="0" cy="0" r="1" gradientTransform="matrix(3.65186 0 0 15.6875 14.689 14.306)" gradientUnits="userSpaceOnUse"><stop offset=".436" class="p0p0ijbbx"/><stop offset=".967" class="dvcrl_y_s"/></radialGradient><radialGradient id="iXBp5Ca" cx="0" cy="0" r="1" gradientTransform="matrix(-4.78125 .78125 -1.79108 -10.96143 18.064 15.118)" gradientUnits="userSpaceOnUse"><stop offset=".781" class="jx6m9tune"/><stop offset=".931" class="g41565bda"/></radialGradient><radialGradient id="iDcG9Kc" cx="0" cy="0" r="1" gradientTransform="matrix(.51562 1.34375 -3.67742 1.4111 14.626 8.274)" gradientUnits="userSpaceOnUse"><stop offset=".297" class="p663aq61v"/><stop offset="1" class="kqh0ncb_u"/></radialGradient><radialGradient id="iv2Xuoc" cx="0" cy="0" r="1" gradientTransform="matrix(-.67188 .9433 -1.66927 -1.18897 16.439 8.612)" gradientUnits="userSpaceOnUse"><stop class="jq_uanbes"/><stop offset="1" class="oq2q2abrd"/></radialGradient><radialGradient id="i9Vmsge" cx="0" cy="0" r="1" gradientTransform="rotate(90 1.452 19.341)scale(.90625)" gradientUnits="userSpaceOnUse"><stop offset=".256" class="d69nsybly"/><stop offset="1" class="eluf2xb_e"/></radialGradient><radialGradient id="i9wCq7b" cx="0" cy="0" r="1" gradientTransform="matrix(1.0907 .20313 -.42058 2.25834 14.88 10.352)" gradientUnits="userSpaceOnUse"><stop offset=".12" class="xot8u71lw"/><stop offset="1" class="jjp3z2beb"/></radialGradient><radialGradient id="ia1iyoc" cx="0" cy="0" r="1" gradientTransform="matrix(1.90625 1.84375 -1.04604 1.0815 17.939 10.087)" gradientUnits="userSpaceOnUse"><stop offset=".204" class="lz70c3nqo"/><stop offset="1" class="pt5v4qb1w"/></radialGradient><radialGradient id="iaCU4vN" cx="0" cy="0" r="1" gradientTransform="matrix(1.09375 .1806 -.14313 .86684 8.324 16.412)" gradientUnits="userSpaceOnUse"><stop class="j4xesqbgr"/><stop offset=".839" class="fa3xzswyd"/></radialGradient><radialGradient id="iwqUy0u" cx="0" cy="0" r="1" gradientTransform="matrix(.27344 0 0 .53125 12.477 5.636)" gradientUnits="userSpaceOnUse"><stop offset=".895" class="l0aricxam"/><stop offset="1" class="n9r91ylyy"/></radialGradient><radialGradient id="iu2jm3P" cx="0" cy="0" r="1" gradientTransform="matrix(.25 0 0 .54102 12.309 5.657)" gradientUnits="userSpaceOnUse"><stop class="gv3iwdbvq"/><stop offset=".813" class="ubyl24bdb"/></radialGradient><linearGradient id="iYTGlYH" x1="14.528" x2="11.665" y1="6.304" y2="6.476" gradientUnits="userSpaceOnUse"><stop class="egm-dub4f"/><stop offset="1" class="zhwoohbuw"/></linearGradient><linearGradient id="ipSh7Ab" x1="17.973" x2="20.202" y1="22.898" y2="20.954" gradientUnits="userSpaceOnUse"><stop offset=".211" class="pat1zf4-w"/><stop offset="1" class="wtea7v6lu"/></linearGradient><linearGradient id="iML24Wb" x1="15.746" x2="15.746" y1="16.085" y2="16.429" gradientUnits="userSpaceOnUse"><stop offset=".136" class="x5p6yzbmf"/><stop offset="1" class="cnh3p8b3x"/></linearGradient><linearGradient id="iPYUKxe" x1="10.278" x2="10.364" y1="29.632" y2="29.319" gradientUnits="userSpaceOnUse"><stop class="l138bfbcs"/><stop offset="1" class="oxce79bcz"/></linearGradient><linearGradient id="iQSzi3h" x1="12.246" x2="11.668" y1="30.007" y2="29.788" gradientUnits="userSpaceOnUse"><stop offset=".064" class="lhdz7oxfj"/><stop offset="1" class="csaq2_bel"/></linearGradient><linearGradient id="iujHcGe" x1="20.856" x2="21.45" y1="27.991" y2="28.163" gradientUnits="userSpaceOnUse"><stop class="oxg1n1wjw"/><stop offset="1" class="y0g_czb9f"/></linearGradient><linearGradient id="ioMwqdd" x1="22.981" x2="22.801" y1="28.065" y2="27.917" gradientUnits="userSpaceOnUse"><stop class="p6qc3nb-j"/><stop offset="0" class="ezcqmvbni"/><stop offset="1" class="stwbr2bhy"/></linearGradient><linearGradient id="iLQKQcd" x1="12.7" x2="13.575" y1="12.851" y2="10.46" gradientUnits="userSpaceOnUse"><stop class="t55apucyo"/><stop offset=".787" class="biw5o_cgj"/></linearGradient><linearGradient id="iSsiqfe" x1="16.731" x2="17.84" y1="9.132" y2="12.585" gradientUnits="userSpaceOnUse"><stop offset=".118" class="u1dukib7n"/><stop offset="1" class="mk0srdu2z"/></linearGradient><linearGradient id="iZvH4HK" x1="12.302" x2="12.488" y1="5.267" y2="5.328" gradientUnits="userSpaceOnUse"><stop class="vc--wpv5i"/><stop offset="1" class="stui2mbih"/></linearGradient><linearGradient id="iX2l1Hf" x1="12.075" x2="16.7" y1="27.429" y2="17.288" gradientUnits="userSpaceOnUse"><stop class="v9kimlbms"/><stop offset="1" class="g24ahctiy"/></linearGradient><linearGradient id="ie0wx9b" x1="22.219" x2="17.908" y1="25.338" y2="19.966" gradientUnits="userSpaceOnUse"><stop class="ckhjb_bgt"/><stop offset="1" class="rnrhdzckq"/></linearGradient><filter id="iTlD1id" width="4.493" height="5.449" x="11.415" y="3.163" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25" dy="-.4"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.85098 0 0 0 0 0.54902 0 0 0 0 0.227451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_95"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.15" dy="-.05"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.737255 0 0 0 0 0.4 0 0 0 0 0.0470588 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_95" result="effect2_innerShadow_4002_95"/></filter><filter id="iDcMICb" width="6.813" height="7.403" x="11.104" y="1.701" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.4" dy=".4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.843137 0 0 0 0 0.207843 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_95"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.607843 0 0 0 0 0.117647 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_95" result="effect2_innerShadow_4002_95"/></filter><filter id="iikYdhc" width="8.674" height="14.771" x="16.188" y="15.476" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".75" dy="-.75"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.439216 0 0 0 0 0.388235 0 0 0 0 0.486275 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_95"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.537255 0 0 0 0 0.423529 0 0 0 0 0.635294 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_95" result="effect2_innerShadow_4002_95"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy=".25"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.529412 0 0 0 0 0.490196 0 0 0 0 0.537255 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_4002_95" result="effect3_innerShadow_4002_95"/></filter><filter id="iAHIoxY" width="10.972" height="14.104" x="7.882" y="15.994" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy="-.2"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.619608 0 0 0 0 0.592157 0 0 0 0 0.611765 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_95"/></filter><filter id="iLU9KGe" width="8.438" height="7.859" x="6.785" y="10.624" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-1"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.894118 0 0 0 0 0.505882 0 0 0 0 0.137255 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_95"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.752941 0 0 0 0 0.466667 0 0 0 0 0.254902 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_95" result="effect2_innerShadow_4002_95"/></filter><filter id="iFHURIc" width="5.442" height="5.875" x="14.28" y="8.468" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_95" stdDeviation=".375"/></filter><filter id="iyoQl0c" width="7.59" height="10.511" x="15.741" y="9.157" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.901961 0 0 0 0 0.623529 0 0 0 0 0.188235 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_95"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.4" dy=".4"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.835294 0 0 0 0 0.25098 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_95" result="effect2_innerShadow_4002_95"/></filter><filter id="iMSnpdc" width="4.758" height="4.525" x="14.879" y="8.654" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.15"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.392157 0 0 0 0 0.254902 0 0 0 0 0.639216 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_95"/></filter><filter id="ik49Owe" width="1.013" height=".568" x="12.227" y="4.307" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.682353 0 0 0 0 0.219608 0 0 0 0 0.133333 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_95"/></filter><filter id="ijoKSTb" width="6.844" height="12.891" x="10.856" y="16.116" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_95" stdDeviation=".5"/></filter><filter id="iKtroIb" width="6.45" height="8.475" x="16.804" y="18.044" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_95" stdDeviation=".375"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:woman-walking" /></template>
<style>
.a541b3bqx {
  stop-color: var(--svg-color--515279, #515279);
}

.admd7db0k {
  stop-color: var(--svg-color--ffab1d, #FFAB1D);
  stop-opacity: 0;
}

.bervkqbmz {
  stop-color: var(--svg-color--ffd040, #FFD040);
}

.biw5o_cgj {
  stop-color: var(--svg-color--816fa6, #816FA6);
}

.bw39i08st {
  d: path("m12.61 5.657l.004-.072c0-.186-.08-.336-.176-.336c-.097 0-.176.15-.176.336q0 .038.004.072z");
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

.cv0ocebom {
  d: path("M11.574 3.517c-.172-.41.016-.844.113-.993c.367-.672 1.128-.716 1.566-.523c.516.226.67.347 1.504.11c.837-.239 1.867-.13 2.406.84c.54.968-.046 2.058.086 2.651c.133.594.513.653.653 1.34c.117.953-.473 1.575-.996 1.715c-.524.14-1.602 0-1.953-.875c-.576-1.431-.185-2.11-.31-2.828c-.125-.719-.554-.922-1.336-.766c-.92.184-1.505-.126-1.734-.671");
}

.d3mv4-bwq {
  d: path("m12.594 28.636l-.391 1.285a.25.25 0 0 1-.315.166l-3.737-1.183c-.195-.061-.326-.265-.244-.452c.107-.245.333-.5.886-.656c.59-.167 1.673-.262 2.306-.317l.21-.019v-.002z");
}

.d5lab6b6s {
  fill: var(--svg-color--ffb629, #FFB629);
  d: path("M11.574 3.517c-.172-.41.016-.844.113-.993c.367-.672 1.128-.716 1.566-.523c.516.226.67.347 1.504.11c.837-.239 1.867-.13 2.406.84c.54.968-.046 2.058.086 2.651c.133.594.513.653.653 1.34c.117.953-.473 1.575-.996 1.715c-.524.14-1.602 0-1.953-.875c-.576-1.431-.185-2.11-.31-2.828c-.125-.719-.554-.922-1.336-.766c-.92.184-1.505-.126-1.734-.671");
}

.d69nsybly {
  stop-color: var(--svg-color--e99f2e, #E99F2E);
}

.d7kch3t0q {
  stop-color: var(--svg-color--ffab1d, #FFAB1D);
}

.dgcxumb4u {
  stop-color: var(--svg-color--a76445, #A76445);
}

.dgxj10bki {
  fill: var(--svg-color--f5b02e, #F5B02E);
  fill-rule: evenodd;
  d: path("M9.169 18.406a.85.85 0 0 1-1.13-.433l-.19-.427a.755.755 0 0 1 .383-.992c1.533-.704 4.023-2.149 4.983-5.93l2.008.524c-1.185 4.668-4.29 6.44-6.054 7.258");
}

.dkjt4cbcx {
  stop-color: var(--svg-color--7966a4, #7966A4);
}

.dvcrl_y_s {
  stop-color: var(--svg-color--6c5d89, #6C5D89);
}

.dwt1fld0s {
  cx: 20.93px;
  cy: 18.042px;
  r: 0.551px;
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

.ezn4aipdh {
  d: path("m23.035 25.668l-1.638.678l.022.02l-.108.355c-.216.713-.535 1.764-.62 2.27c-.076.462.146.768.352.953c.093.083.234.064.318-.03l2.687-2.995a.25.25 0 0 0-.018-.353l-.986-.887z");
}

.f-3dg9neb {
  d: path("m19.169 19.96l-.89-3.734h-1.782c-.052.614-.152 2.215-.29 3.515s.493 2.032.766 2.313l4.446 4.312c-.198.662-.627 2.025-.727 2.625c-.077.462.145.768.35.953c.094.083.235.064.319-.03l2.688-2.995a.25.25 0 0 0-.02-.353l-.985-.887c-1.042-1.365-3.19-4.194-3.453-4.594c-.182-.276-.391-.917-.422-1.125");
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

.hdzwkybza {
  stop-color: var(--svg-color--63617e, #63617E);
  stop-opacity: 0;
}

.hq1t4kbaf {
  fill: var(--svg-color--fff, #fff);
  d: path("M12.2 5.657h.988c0-.391-.222-.709-.494-.709c-.273 0-.495.318-.495.71");
}

.i5j5t695y {
  fill: var(--svg-color--2f2c2d, #2F2C2D);
  d: path("M13.225 5.146c-.131-.131-.349-.161-.442-.16l.303.467c.147-.008.303-.143.139-.307");
}

.i7ywxfd5f {
  d: path("M13.215 10.515c.281-.713.774-1.224.985-1.391l-.04 4.469l-1.785-.836c.278-.524.489-1.352.84-2.242");
}

.ik_2dacqf {
  fill: var(--svg-color--442e79, #442E79);
  d: path("M15.236 10.985c-.31-.248-.178-.39-.178-.818c0-.749.013-.95.761-.95c.338 0 .646.124.883.327c.95.692 1.79 1.592 2.27 2.135l-2.04 1.914a58 58 0 0 1-1.696-2.608");
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

.jtjskiljj {
  fill: var(--svg-color--8c8393, #8C8393);
  d: path("M12.817 18.577c.383-1.05.716-2.029.773-2.383h4.742c.1 1.375-.144 1.712-.773 2.422c-.693.782-2.172 2.43-2.54 2.895c-.35.35-.5.789-.554.98l-2.262 7.43a.25.25 0 0 1-.315.166l-3.737-1.183c-.195-.061-.326-.265-.244-.452c.107-.245.333-.5.886-.656c.663-.188 1.943-.284 2.516-.336c.213-1.766.66-5.431.734-5.969c.094-.672.227-1.414.774-2.914");
}

.jx6m9tune {
  stop-color: var(--svg-color--8272a4, #8272A4);
  stop-opacity: 0;
}

.kqh0ncb_u {
  stop-color: var(--svg-color--885876, #885876);
  stop-opacity: 0;
}

.kto05ftpk {
  d: path("m8.657 16.026l.496.052c.21.022.374.192.388.403a.38.38 0 0 1-.076.266c-.264.33-.525.366-.722.408c-.219.047-.676-.191-.59-.691a.53.53 0 0 1 .504-.438");
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

.l77q_mb0z {
  fill: var(--svg-color--87014d, #87014D);
  fill-rule: evenodd;
  d: path("M12.945 6.77a.125.125 0 0 1-.002.178c-.238.233-.582.293-.692.304a.125.125 0 1 1-.025-.248c.093-.01.366-.062.542-.235a.125.125 0 0 1 .177.002");
}

.lhdz7oxfj {
  stop-color: var(--svg-color--444571, #444571);
}

.luqljkbkk {
  d: path("M14.458 6.323c-.05 0-.086-.046-.079-.096l.173-1.249c.008-.055.06-.094.113-.078a.727.727 0 0 1-.207 1.423");
}

.lz70c3nqo {
  stop-color: var(--svg-color--9075ca, #9075CA);
}

.m_uy2vb_d {
  stop-color: var(--svg-color--695c75, #695C75);
  stop-opacity: 0;
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

.n9r91ylyy {
  stop-color: var(--svg-color--824d44, #824D44);
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

.pat1zf4-w {
  stop-color: var(--svg-color--8b8290, #8B8290);
}

.pdtjsyxpv {
  d: path("M11.693 4.863c.039-.8.298-1.187.42-1.3h3.733l.062 3.164c-.866 2.121-3.511 2.212-3.906 1.445s-.354-2.381-.309-3.309");
}

.pt5v4qb1w {
  stop-color: var(--svg-color--9075ca, #9075CA);
  stop-opacity: 0;
}

.pu87gqowa {
  d: path("M12.817 18.577c.383-1.05.716-2.029.773-2.383h4.742c.1 1.375-.144 1.712-.773 2.422c-.693.782-2.172 2.43-2.54 2.895c-.35.35-.5.789-.554.98l-2.262 7.43a.25.25 0 0 1-.315.166l-3.737-1.183c-.195-.061-.326-.265-.244-.452c.107-.245.333-.5.886-.656c.663-.188 1.943-.284 2.516-.336c.213-1.766.66-5.431.734-5.969c.094-.672.227-1.414.774-2.914");
}

.q79sa3zre {
  d: path("m13.2 21.194l-1.344 6.5l.36.313l1.468-6.531L16.7 17.6l-.704-.485z");
}

.qe_otxnzg {
  d: path("M15.388 11.218a1.355 1.355 0 1 1 1.729-2.088c.95.692 1.79 1.592 2.27 2.135l-2.04 1.914a154 154 0 0 0-1.959-1.961");
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

.szm--fb2k {
  d: path("m19.028 21.142l3.476 4.428l-.514.199l-3.484-3.708a3 3 0 0 1-.761-1.493l-.19-1l.751-.774l.544 1.993q.053.196.178.355");
}

.t55apucyo {
  stop-color: var(--svg-color--725d9d, #725D9D);
}

.ttsumpbek {
  stop-color: var(--svg-color--897998, #897998);
  stop-opacity: 0;
}

.u_490kbtp {
  d: path("M12.805 5.657v-.004c0-.32-.137-.58-.307-.58s-.306.26-.306.58v.004z");
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

.v0ryunblo {
  fill: var(--svg-color--af5247, #AF5247);
  fill-rule: evenodd;
  d: path("M12.712 4.624a.8.8 0 0 0-.216-.015a.15.15 0 0 1-.038-.298a1 1 0 0 1 .313.02c.127.025.277.076.408.172a.15.15 0 1 1-.178.242a.7.7 0 0 0-.289-.12");
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

.vi33vey6i {
  d: path("M14.181 6.729h1.946v3.44h-1.946z");
}

.vp_xd9b8f {
  fill: var(--svg-color--ffbf35, #FFBF35);
  fill-rule: evenodd;
  d: path("M21.837 19.238a.614.614 0 0 1-.776-.407c-1.215-3.921-3.166-6.29-4.542-7.545c-.437-.4-.515-1.082-.128-1.53c.346-.401.944-.472 1.348-.13c1.626 1.381 3.91 3.976 5.317 8.605a.59.59 0 0 1-.383.73z");
}

.w9ku-ifwq {
  stop-color: var(--svg-color--7966a4, #7966A4);
  stop-opacity: 0;
}

.ws8t0ub-u {
  fill: var(--svg-color--45437a, #45437A);
  d: path("m23.035 25.668l-1.638.678l.022.02l-.108.355c-.216.713-.535 1.764-.62 2.27c-.076.462.146.768.352.953c.093.083.234.064.318-.03l2.687-2.995a.25.25 0 0 0-.018-.353l-.986-.887z");
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

.yhwv79m6v {
  cx: 12.373px;
  cy: 5.306px;
  rx: 0.064px;
  ry: 0.088px;
}

.yvuyjoqpy {
  stop-color: var(--svg-color--47456f, #47456F);
}

.ywie972fs {
  fill: var(--svg-color--725ca6, #725CA6);
  d: path("M15.524 8.612c.89 0 1.136.215 1.433.407l1.024 2.597c.3 1.4.364 3.636.36 4.578h-4.767c-.257-.656-.677-2.675-.515-4.578c.164-1.93 1.207-2.902 2.465-3.004");
}

.zc8ie-1dg {
  stop-color: var(--svg-color--515279, #515279);
  stop-opacity: 0;
}

.zhrkjbb7n {
  d: path("M11.47 5.827c.156-.147.236-.366.257-.457h.18v1.125c-.215.137-.522.115-.614-.09c-.078-.176-.019-.394.176-.578");
}

.zhwoohbuw {
  stop-color: var(--svg-color--ffc247, #FFC247);
}

.zn6q2i0go {
  d: path("M15.524 8.612c.89 0 1.136.215 1.433.407l1.024 2.597c.3 1.4.364 3.636.36 4.578h-4.767c-.257-.656-.677-2.675-.515-4.578c.164-1.93 1.207-2.902 2.465-3.004");
}

</style>
