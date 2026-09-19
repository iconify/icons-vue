<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iOYOxDc)" transform="rotate(-4.337 14.017 6.742)" class="ovtrtzbnn"/><path fill="url(#idw9IYc)" transform="rotate(-4.337 14.017 6.742)" class="ovtrtzbnn"/><path fill="url(#id1gNWe)" class="k_2x3etap"/><g filter="url(#iqIrYgb)"><path fill="url(#ieJ5OLw)" class="mi5aoybnn"/><path fill="url(#i29Gwub)" class="mi5aoybnn"/></g><g filter="url(#iiVajbW)"><path class="mb8q1mbvd"/><path fill="url(#ipKs8Zd)" class="s6cwacbdr"/><path fill="url(#ilpdWmd)" class="s6cwacbdr"/><path fill="url(#iZQ6kae)" class="s6cwacbdr"/><path fill="url(#i7bLrSN)" class="s6cwacbdr"/><path fill="url(#i2ZkP4c)" class="s6cwacbdr"/></g><path fill="url(#iKhDFGd)" class="ftmtmebzh"/><g filter="url(#izsDWqb)"><path fill="url(#iXyorjQ)" class="nljne-bpa"/><path fill="url(#ij8hGNc)" class="nljne-bpa"/><path fill="url(#ihGxjvb)" class="nljne-bpa"/></g><g filter="url(#iWq8Z7b)"><path class="lo_j8f4ob"/><path fill="url(#iCnE2Xc)" class="ytqhxrbga"/><path fill="url(#is2MSRb)" class="ytqhxrbga"/><path fill="url(#i46a4ze)" class="ytqhxrbga"/><path fill="url(#iltAinO)" class="ytqhxrbga"/><path fill="url(#i1no2fe)" class="ytqhxrbga"/></g><path fill="url(#iUn3YLd)" class="p41usu8bh"/><path fill="url(#iOKi3Hd)" class="p41usu8bh"/><path fill="url(#iAkHyTq)" class="p41usu8bh"/><path fill="url(#ipGsseB)" class="p41usu8bh"/><path fill="url(#iUYS8Hb)" class="p41usu8bh"/><path class="t1hx-ibvq"/><path fill="url(#ikST0OT)" class="p4x11s6-u"/><path fill="url(#iifnuWc)" class="p4x11s6-u"/><path fill="url(#ihR4Crd)" class="p4x11s6-u"/><g filter="url(#id7t8nc)"><path clip-rule="evenodd" class="du17wy7sn"/></g><path fill="url(#ihI0Oeb)" class="xyt681btr"/><path fill="url(#inXnLOb)" class="m-n1_xe-s"/><path fill="url(#i4gPRHd)" class="m-n1_xe-s"/><path fill="url(#iTgYT8b)" class="m-n1_xe-s"/><path fill="url(#ibMGSJd)" class="m-n1_xe-s"/><circle fill="url(#idEwH3i)" class="rayucyv4q"/><g filter="url(#iXzNzXc)"><path clip-rule="evenodd" class="hssagdbjl"/></g><path fill="url(#iNvDiId)" class="d_u_riyxa"/><path fill="url(#i8Anpne)" class="d_u_riyxa"/><path fill="url(#iEQ0pob)" class="d_u_riyxa"/><path fill="url(#i92UI5d)" class="fohl3gbsr"/><path clip-rule="evenodd" class="vid7i5kil"/><g filter="url(#iQJRXmb)"><path clip-rule="evenodd" class="ycy4eq6jz"/></g><path class="dewlk8egf"/><path fill="url(#iewbKse)" class="t6khnfd4i"/><path fill="url(#iCfHhDc)" class="ifehhsb9l"/><ellipse fill="url(#inn7BZI)" transform="rotate(24.61 12.373 5.29)" class="sb_t_0b6s"/><g filter="url(#i3c6yeb)"><path fill="url(#iZWOoDf)" class="lkp-rxh5n"/></g><g filter="url(#i97yWBd)"><path fill="url(#iDiU5Le)" class="ari0bjqpi"/></g><defs><radialGradient id="iOYOxDc" cx="0" cy="0" r="1" gradientTransform="matrix(-.05152 -2.21336 1.59858 -.0372 15.725 8.752)" gradientUnits="userSpaceOnUse"><stop offset=".116" class="xpz0ltqsz"/><stop offset="1" class="vj0bxeigc"/></radialGradient><radialGradient id="idw9IYc" cx="0" cy="0" r="1" gradientTransform="matrix(-.53617 .66448 -.89991 -.72614 16.078 7.18)" gradientUnits="userSpaceOnUse"><stop class="wlrmkubjk"/><stop offset="1" class="bdl3pn0lv"/></radialGradient><radialGradient id="id1gNWe" cx="0" cy="0" r="1" gradientTransform="matrix(.3125 .60583 -.77155 .39799 11.301 5.96)" gradientUnits="userSpaceOnUse"><stop offset=".332" class="fvok_qxen"/><stop offset="1" class="suyap8bzv"/></radialGradient><radialGradient id="i29Gwub" cx="0" cy="0" r="1" gradientTransform="matrix(-.84375 -.04688 .05715 -1.0287 14.84 5.547)" gradientUnits="userSpaceOnUse"><stop offset=".156" class="d7kch3t0q"/><stop offset="1" class="admd7db0k"/></radialGradient><radialGradient id="ipKs8Zd" cx="0" cy="0" r="1" gradientTransform="matrix(1.90805 -1.94145 2.83721 2.78841 15.323 6.982)" gradientUnits="userSpaceOnUse"><stop class="re8izvbqw"/><stop offset="1" class="kgio6d1ee"/></radialGradient><radialGradient id="ilpdWmd" cx="0" cy="0" r="1" gradientTransform="matrix(-2.125 .8906 -1.25029 -2.98321 16.73 3.32)" gradientUnits="userSpaceOnUse"><stop class="u0-djrvhx"/><stop offset="1" class="fj67tibom"/></radialGradient><radialGradient id="iZQ6kae" cx="0" cy="0" r="1" gradientTransform="rotate(-163.909 8.803 2.082)scale(.84563 .39322)" gradientUnits="userSpaceOnUse"><stop class="jkk-xsb9b"/><stop offset="1" class="g6je8pe2z"/></radialGradient><radialGradient id="i7bLrSN" cx="0" cy="0" r="1" gradientTransform="matrix(-1.79687 .32814 -.1515 -.82965 15.098 1.96)" gradientUnits="userSpaceOnUse"><stop offset=".174" class="t5jak8x3h"/><stop offset="1" class="hze7fms1a"/></radialGradient><radialGradient id="i2ZkP4c" cx="0" cy="0" r="1" gradientTransform="matrix(.50781 .47657 -.68826 .73338 12.184 1.875)" gradientUnits="userSpaceOnUse"><stop offset=".117" class="an20q5kfx"/><stop offset="1" class="xh4g4qbuv"/></radialGradient><radialGradient id="iKhDFGd" cx="0" cy="0" r="1" gradientTransform="rotate(115.703 5.886 7.443)scale(1.04478 1.69772)" gradientUnits="userSpaceOnUse"><stop offset=".04" class="bervkqbmz"/><stop offset="1" class="c479w-bpn"/></radialGradient><radialGradient id="ij8hGNc" cx="0" cy="0" r="1" gradientTransform="matrix(2.45369 2.93958 -5.96661 4.98038 16.952 18.024)" gradientUnits="userSpaceOnUse"><stop offset=".434" class="oiy_54b9a"/><stop offset="1" class="rm4aiz5dn"/></radialGradient><radialGradient id="ihGxjvb" cx="0" cy="0" r="1" gradientTransform="matrix(.89062 .65625 -3.9414 5.34905 16.637 19.039)" gradientUnits="userSpaceOnUse"><stop offset=".043" class="v5lz4sb9o"/><stop offset="1" class="m_uy2vb_d"/></radialGradient><radialGradient id="iCnE2Xc" cx="0" cy="0" r="1" gradientTransform="matrix(3.25001 -5.14062 1.35402 .85604 15.855 20.883)" gradientUnits="userSpaceOnUse"><stop offset=".07" class="mngz2ebss"/><stop offset="1" class="ttsumpbek"/></radialGradient><radialGradient id="is2MSRb" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.42188 -1.38588 0 16.668 16.18)" gradientUnits="userSpaceOnUse"><stop class="f3j6dkfip"/><stop offset="1" class="fxoxl0blj"/></radialGradient><radialGradient id="iltAinO" cx="0" cy="0" r="1" gradientTransform="matrix(.14063 -.17968 .6458 .50543 11.972 28.093)" gradientUnits="userSpaceOnUse"><stop class="ryq0o3qru"/><stop offset="1" class="yfqxgqb1h"/></radialGradient><radialGradient id="i1no2fe" cx="0" cy="0" r="1" gradientTransform="matrix(6.375 -1.8125 4.67455 16.4415 12.293 19.226)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="ex23x-brg"/><stop offset="1" class="ux4w7lb6c"/></radialGradient><radialGradient id="iUn3YLd" cx="0" cy="0" r="1" gradientTransform="matrix(-.09375 -1.53125 2.45635 -.15039 10.84 29.445)" gradientUnits="userSpaceOnUse"><stop class="cl2mlwbhs"/><stop offset="1" class="yvuyjoqpy"/></radialGradient><radialGradient id="iOKi3Hd" cx="0" cy="0" r="1" gradientTransform="matrix(1.0625 -.21875 .15137 .73521 7.73 28.508)" gradientUnits="userSpaceOnUse"><stop class="m3n9jy0fh"/><stop offset="1" class="hdzwkybza"/></radialGradient><radialGradient id="iAkHyTq" cx="0" cy="0" r="1" gradientTransform="rotate(-70.942 26.744 6.628)scale(1.81842 .89694)" gradientUnits="userSpaceOnUse"><stop offset=".08" class="a541b3bqx"/><stop offset="1" class="zc8ie-1dg"/></radialGradient><radialGradient id="ihR4Crd" cx="0" cy="0" r="1" gradientTransform="rotate(-132.875 17.849 8.353)scale(1.99789 1.10527)" gradientUnits="userSpaceOnUse"><stop class="xh_da2q2q"/><stop offset="1" class="stwbr2bhy"/></radialGradient><radialGradient id="inXnLOb" cx="0" cy="0" r="1" gradientTransform="matrix(1.9375 6 -4.22355 1.36385 14.98 11.351)" gradientUnits="userSpaceOnUse"><stop offset=".446" class="pvqp1vbsj"/><stop offset="1" class="jbtp05a5b"/></radialGradient><radialGradient id="i4gPRHd" cx="0" cy="0" r="1" gradientTransform="matrix(3.0625 2.84375 -4.8238 5.19486 13.325 9.726)" gradientUnits="userSpaceOnUse"><stop class="v6cmgr7lo"/><stop offset="1" class="zvi2r2b9j"/></radialGradient><radialGradient id="iTgYT8b" cx="0" cy="0" r="1" gradientTransform="matrix(.59375 2.6875 -1.45306 .32102 16.668 11.039)" gradientUnits="userSpaceOnUse"><stop class="wb44sjbzz"/><stop offset="1" class="w8350jbiw"/></radialGradient><radialGradient id="ibMGSJd" cx="0" cy="0" r="1" gradientTransform="rotate(173.533 8.107 4.77)scale(2.73543 1.43274)" gradientUnits="userSpaceOnUse"><stop offset=".213" class="ayezflb3j"/><stop offset="1" class="ujjr06bwy"/></radialGradient><radialGradient id="idEwH3i" cx="0" cy="0" r="1" gradientTransform="rotate(90 1.46 19.334)scale(.90625)" gradientUnits="userSpaceOnUse"><stop offset=".256" class="d69nsybly"/><stop offset="1" class="eluf2xb_e"/></radialGradient><radialGradient id="i8Anpne" cx="0" cy="0" r="1" gradientTransform="matrix(1.72656 -.10937 .20534 3.24138 14.88 10.523)" gradientUnits="userSpaceOnUse"><stop offset=".235" class="ou5ot-gfg"/><stop offset="1" class="uz8jx9bci"/></radialGradient><radialGradient id="iEQ0pob" cx="0" cy="0" r="1" gradientTransform="rotate(-97.334 13.599 -1.534)scale(3.18229 3.71057)" gradientUnits="userSpaceOnUse"><stop offset=".839" class="z7rq8royu"/><stop offset=".958" class="p1zm9vufc"/></radialGradient><radialGradient id="i92UI5d" cx="0" cy="0" r="1" gradientTransform="matrix(1.09375 .1806 -.14313 .86684 8.324 16.398)" gradientUnits="userSpaceOnUse"><stop class="j4xesqbgr"/><stop offset=".839" class="fa3xzswyd"/></radialGradient><radialGradient id="iewbKse" cx="0" cy="0" r="1" gradientTransform="matrix(.27344 0 0 .53125 12.477 5.62)" gradientUnits="userSpaceOnUse"><stop offset=".895" class="l0aricxam"/><stop offset="1" class="n9r91ylyy"/></radialGradient><radialGradient id="iCfHhDc" cx="0" cy="0" r="1" gradientTransform="matrix(.25 0 0 .54102 12.309 5.642)" gradientUnits="userSpaceOnUse"><stop class="gv3iwdbvq"/><stop offset=".813" class="ubyl24bdb"/></radialGradient><linearGradient id="ieJ5OLw" x1="14.528" x2="11.665" y1="6.289" y2="6.461" gradientUnits="userSpaceOnUse"><stop class="egm-dub4f"/><stop offset="1" class="zhwoohbuw"/></linearGradient><linearGradient id="iXyorjQ" x1="17.973" x2="20.201" y1="22.883" y2="20.939" gradientUnits="userSpaceOnUse"><stop offset=".211" class="pat1zf4-w"/><stop offset="1" class="wtea7v6lu"/></linearGradient><linearGradient id="i46a4ze" x1="15.746" x2="15.746" y1="16.07" y2="16.414" gradientUnits="userSpaceOnUse"><stop offset=".136" class="x5p6yzbmf"/><stop offset="1" class="cnh3p8b3x"/></linearGradient><linearGradient id="ipGsseB" x1="10.278" x2="10.364" y1="29.617" y2="29.305" gradientUnits="userSpaceOnUse"><stop class="l138bfbcs"/><stop offset="1" class="oxce79bcz"/></linearGradient><linearGradient id="iUYS8Hb" x1="12.246" x2="11.668" y1="29.992" y2="29.773" gradientUnits="userSpaceOnUse"><stop offset=".064" class="lhdz7oxfj"/><stop offset="1" class="csaq2_bel"/></linearGradient><linearGradient id="ikST0OT" x1="20.856" x2="21.45" y1="27.976" y2="28.148" gradientUnits="userSpaceOnUse"><stop class="oxg1n1wjw"/><stop offset="1" class="y0g_czb9f"/></linearGradient><linearGradient id="iifnuWc" x1="22.981" x2="22.801" y1="28.051" y2="27.902" gradientUnits="userSpaceOnUse"><stop class="p6qc3nb-j"/><stop offset="0" class="ezcqmvbni"/><stop offset="1" class="stwbr2bhy"/></linearGradient><linearGradient id="ihI0Oeb" x1="12.7" x2="13.575" y1="12.836" y2="10.445" gradientUnits="userSpaceOnUse"><stop class="h2o5q3bga"/><stop offset=".787" class="md0ucwkak"/></linearGradient><linearGradient id="iNvDiId" x1="16.731" x2="17.84" y1="9.117" y2="12.57" gradientUnits="userSpaceOnUse"><stop offset=".118" class="fjz5hab9p"/><stop offset="1" class="ljdv6tb3r"/></linearGradient><linearGradient id="inn7BZI" x1="12.302" x2="12.488" y1="5.252" y2="5.313" gradientUnits="userSpaceOnUse"><stop class="vc--wpv5i"/><stop offset="1" class="stui2mbih"/></linearGradient><linearGradient id="iZWOoDf" x1="12.075" x2="16.7" y1="27.414" y2="17.273" gradientUnits="userSpaceOnUse"><stop class="v9kimlbms"/><stop offset="1" class="g24ahctiy"/></linearGradient><linearGradient id="iDiU5Le" x1="22.219" x2="17.908" y1="25.323" y2="19.951" gradientUnits="userSpaceOnUse"><stop class="ckhjb_bgt"/><stop offset="1" class="rnrhdzckq"/></linearGradient><filter id="iqIrYgb" width="4.443" height="5.249" x="11.465" y="3.348" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2" dy="-.2"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.909804 0 0 0 0 0.52549 0 0 0 0 0.215686 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_94"/></filter><filter id="iiVajbW" width="5.503" height="5.499" x="11.728" y="1.766" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.15"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.607843 0 0 0 0 0.117647 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_94"/></filter><filter id="izsDWqb" width="8.674" height="14.771" x="16.188" y="15.461" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".75" dy="-.75"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.439216 0 0 0 0 0.388235 0 0 0 0 0.486275 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_94"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.537255 0 0 0 0 0.423529 0 0 0 0 0.635294 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_94" result="effect2_innerShadow_4002_94"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy=".25"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.529412 0 0 0 0 0.490196 0 0 0 0 0.537255 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_4002_94" result="effect3_innerShadow_4002_94"/></filter><filter id="iWq8Z7b" width="10.972" height="14.104" x="7.882" y="15.979" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy="-.2"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.619608 0 0 0 0 0.592157 0 0 0 0 0.611765 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_94"/></filter><filter id="id7t8nc" width="8.438" height="7.859" x="6.785" y="10.609" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-1"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.894118 0 0 0 0 0.505882 0 0 0 0 0.137255 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_94"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.752941 0 0 0 0 0.466667 0 0 0 0 0.254902 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_94" result="effect2_innerShadow_4002_94"/></filter><filter id="iXzNzXc" width="7.59" height="10.511" x="15.741" y="9.142" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.901961 0 0 0 0 0.623529 0 0 0 0 0.188235 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_94"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.4" dy=".4"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.835294 0 0 0 0 0.25098 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_94" result="effect2_innerShadow_4002_94"/></filter><filter id="iQJRXmb" width="1.013" height=".568" x="12.227" y="4.292" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.682353 0 0 0 0 0.219608 0 0 0 0 0.133333 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_94"/></filter><filter id="i3c6yeb" width="6.844" height="12.891" x="10.856" y="16.101" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_94" stdDeviation=".5"/></filter><filter id="i97yWBd" width="6.45" height="8.475" x="16.804" y="18.029" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_94" stdDeviation=".375"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:person-walking" /></template>
<style>
.a541b3bqx {
  stop-color: var(--svg-color--515279, #515279);
}

.admd7db0k {
  stop-color: var(--svg-color--ffab1d, #FFAB1D);
  stop-opacity: 0;
}

.an20q5kfx {
  stop-color: var(--svg-color--e0a531, #E0A531);
}

.ari0bjqpi {
  d: path("m19.028 21.127l3.476 4.428l-.514.199l-3.484-3.708a3 3 0 0 1-.761-1.493l-.19-1l.751-.774l.544 1.994a1 1 0 0 0 .178.354");
}

.ayezflb3j {
  stop-color: var(--svg-color--fc8c16, #FC8C16);
}

.bdl3pn0lv {
  stop-color: var(--svg-color--fda533, #FDA533);
  stop-opacity: 0;
}

.bervkqbmz {
  stop-color: var(--svg-color--ffd040, #FFD040);
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

.d_u_riyxa {
  d: path("M15.388 11.203a1.355 1.355 0 1 1 1.729-2.088c.951.692 1.79 1.592 2.27 2.135l-2.039 1.914c-.308-.32-1.382-1.393-1.96-1.96");
}

.d69nsybly {
  stop-color: var(--svg-color--e99f2e, #E99F2E);
}

.d7kch3t0q {
  stop-color: var(--svg-color--ffab1d, #FFAB1D);
}

.dewlk8egf {
  fill: var(--svg-color--fff, #fff);
  d: path("M12.2 5.642h.988c0-.391-.221-.709-.494-.709s-.494.318-.494.71");
}

.du17wy7sn {
  fill: var(--svg-color--f5b02e, #F5B02E);
  fill-rule: evenodd;
  d: path("M9.169 18.391a.85.85 0 0 1-1.13-.433l-.19-.426a.755.755 0 0 1 .383-.993c1.533-.704 4.023-2.149 4.983-5.93l2.008.524c-1.185 4.668-4.29 6.44-6.054 7.258");
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

.f3j6dkfip {
  stop-color: var(--svg-color--99919a, #99919A);
}

.fa3xzswyd {
  stop-color: var(--svg-color--eb9f1c, #EB9F1C);
}

.fj67tibom {
  stop-color: var(--svg-color--ffd537, #FFD537);
  stop-opacity: 0;
}

.fjz5hab9p {
  stop-color: var(--svg-color--f67e18, #F67E18);
}

.fohl3gbsr {
  d: path("m8.657 16.011l.496.052c.21.022.374.192.388.403a.38.38 0 0 1-.077.266c-.264.33-.524.366-.721.408c-.22.047-.676-.191-.59-.691a.53.53 0 0 1 .504-.438");
}

.ft5dv1b6b {
  fill: none;
}

.ftmtmebzh {
  d: path("m14.464 6.303l.2-1.44a.727.727 0 0 1-.2 1.44");
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

.g6je8pe2z {
  stop-color: var(--svg-color--ffd237, #FFD237);
  stop-opacity: 0;
}

.gv3iwdbvq {
  stop-color: var(--svg-color--666361, #666361);
}

.h2o5q3bga {
  stop-color: var(--svg-color--f3563a, #F3563A);
}

.hdzwkybza {
  stop-color: var(--svg-color--63617e, #63617E);
  stop-opacity: 0;
}

.hssagdbjl {
  fill: var(--svg-color--ffbf35, #FFBF35);
  fill-rule: evenodd;
  d: path("M21.837 19.223a.614.614 0 0 1-.776-.407c-1.215-3.921-3.166-6.29-4.542-7.545c-.438-.4-.516-1.082-.128-1.53c.346-.401.944-.472 1.348-.13c1.626 1.381 3.91 3.976 5.316 8.605a.59.59 0 0 1-.382.73z");
}

.hze7fms1a {
  stop-color: var(--svg-color--ffbf27, #FFBF27);
  stop-opacity: 0;
}

.ifehhsb9l {
  d: path("m12.61 5.642l.004-.072c0-.185-.08-.336-.176-.336c-.097 0-.176.15-.176.336q0 .038.004.072z");
}

.j4xesqbgr {
  stop-color: var(--svg-color--ffbf3f, #FFBF3F);
}

.jbtp05a5b {
  stop-color: var(--svg-color--d34015, #D34015);
}

.jkk-xsb9b {
  stop-color: var(--svg-color--ffd237, #FFD237);
}

.k_2x3etap {
  d: path("M11.47 5.812c.155-.147.236-.366.257-.457h.18V6.48c-.215.137-.522.115-.614-.09c-.078-.175-.02-.394.176-.578");
}

.kgio6d1ee {
  stop-color: var(--svg-color--ffa526, #FFA526);
  stop-opacity: 0;
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

.ljdv6tb3r {
  stop-color: var(--svg-color--ee462e, #EE462E);
}

.lkp-rxh5n {
  d: path("m13.2 21.18l-1.344 6.5l.36.312l1.468-6.531l3.016-3.875l-.703-.485z");
}

.lo_j8f4ob {
  fill: var(--svg-color--8c8393, #8C8393);
  d: path("M12.817 18.562c.383-1.05.716-2.028.773-2.383h4.742c.1 1.375-.144 1.713-.773 2.422c-.693.782-2.172 2.43-2.54 2.895c-.35.35-.5.789-.554.98l-2.262 7.43a.25.25 0 0 1-.315.166l-3.737-1.183c-.195-.061-.326-.265-.244-.452c.107-.245.333-.5.886-.656c.663-.187 1.943-.284 2.516-.336c.214-1.766.66-5.431.734-5.969c.094-.672.227-1.414.774-2.914");
}

.m_uy2vb_d {
  stop-color: var(--svg-color--695c75, #695C75);
  stop-opacity: 0;
}

.m-n1_xe-s {
  d: path("M15.524 8.597c.89 0 1.137.215 1.434.407L17.98 11.6c.3 1.4.364 3.636.36 4.578h-4.766c-.258-.656-.678-2.675-.516-4.578c.164-1.93 1.207-2.902 2.465-3.004");
}

.m3n9jy0fh {
  stop-color: var(--svg-color--63617e, #63617E);
}

.mb8q1mbvd {
  fill: var(--svg-color--ffba23, #FFBA23);
  d: path("M11.844 2.496c.238-.488.706-.593.984-.578c.86.047.977.343 1.754.183c.822-.169 1.227-.12 1.578.04l.007.003c.347.157 1.064.483 1.064 1.95c0 1.351-.482 2.065-.715 2.32l.046.016c.231.084.327.33.243.562c-.071.197-.322.311-.637.262c-.36-.057-.624-.106-.832-.147a.25.25 0 0 1-.2-.245V5.75a.99.99 0 0 0-.475-.832c-.016-.485-.165-.707-.407-.824c-.4-.195-.526-.099-1.484-.157c-.965-.058-1.223-.832-.926-1.441");
}

.md0ucwkak {
  stop-color: var(--svg-color--ea6f3e, #EA6F3E);
}

.mi5aoybnn {
  d: path("M11.693 4.848c.039-.8.298-1.187.42-1.3h3.733l.062 3.164c-.866 2.121-3.511 2.212-3.906 1.445s-.354-2.381-.309-3.309");
}

.mngz2ebss {
  stop-color: var(--svg-color--897998, #897998);
}

.n9r91ylyy {
  stop-color: var(--svg-color--824d44, #824D44);
}

.nljne-bpa {
  d: path("m19.169 19.945l-.891-3.734h-1.781c-.052.614-.152 2.215-.29 3.515s.492 2.032.766 2.313l4.446 4.312c-.198.662-.627 2.025-.727 2.625c-.077.462.145.768.35.953c.094.083.235.064.319-.03l2.687-2.995a.25.25 0 0 0-.018-.352l-.986-.888c-1.042-1.365-3.191-4.194-3.454-4.594c-.18-.276-.39-.917-.421-1.125");
}

.oiy_54b9a {
  stop-color: var(--svg-color--887e8b, #887E8B);
}

.ou5ot-gfg {
  stop-color: var(--svg-color--f27f2f, #F27F2F);
}

.ovtrtzbnn {
  d: path("M14.017 6.742h1.946v3.44h-1.946z");
}

.oxce79bcz {
  stop-color: var(--svg-color--282955, #282955);
  stop-opacity: 0;
}

.oxg1n1wjw {
  stop-color: var(--svg-color--5a577e, #5A577E);
}

.p1zm9vufc {
  stop-color: var(--svg-color--ef7c07, #EF7C07);
}

.p41usu8bh {
  d: path("m12.594 28.62l-.391 1.286a.25.25 0 0 1-.315.166l-3.737-1.183c-.195-.061-.326-.265-.244-.452c.107-.245.333-.5.886-.656c.591-.167 1.673-.262 2.306-.317l.21-.019v-.002z");
}

.p4x11s6-u {
  d: path("m23.035 25.653l-1.638.678l.022.02l-.107.355c-.217.713-.536 1.764-.62 2.27c-.077.462.145.768.35.953c.094.083.235.064.319-.03l2.688-2.995a.25.25 0 0 0-.02-.352l-.985-.888z");
}

.p6qc3nb-j {
  stop-color: var(--svg-color--492d85, #492D85);
}

.pat1zf4-w {
  stop-color: var(--svg-color--8b8290, #8B8290);
}

.pvqp1vbsj {
  stop-color: var(--svg-color--e9672b, #E9672B);
}

.rayucyv4q {
  cx: 20.93px;
  cy: 18.027px;
  r: 0.551px;
}

.re8izvbqw {
  stop-color: var(--svg-color--ffa526, #FFA526);
}

.rm4aiz5dn {
  stop-color: var(--svg-color--887e8b, #887E8B);
  stop-opacity: 0;
}

.rnrhdzckq {
  stop-color: var(--svg-color--a39fa7, #A39FA7);
  stop-opacity: 0;
}

.ryq0o3qru {
  stop-color: var(--svg-color--a19da6, #A19DA6);
}

.s6cwacbdr {
  d: path("M11.844 2.496c.238-.488.706-.593.984-.578c.86.047.977.343 1.754.183c.822-.169 1.227-.12 1.578.04l.007.003c.347.157 1.064.483 1.064 1.95c0 1.351-.482 2.065-.715 2.32l.046.016c.231.084.327.33.243.562c-.071.197-.322.311-.637.262c-.36-.057-.624-.106-.832-.147a.25.25 0 0 1-.2-.245V5.75a.99.99 0 0 0-.475-.832c-.016-.485-.165-.707-.407-.824c-.4-.195-.526-.099-1.484-.157c-.965-.058-1.223-.832-.926-1.441");
}

.sb_t_0b6s {
  cx: 12.373px;
  cy: 5.291px;
  rx: 0.064px;
  ry: 0.088px;
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

.t1hx-ibvq {
  fill: var(--svg-color--45437a, #45437A);
  d: path("m23.035 25.653l-1.638.678l.022.02l-.107.355c-.217.713-.536 1.764-.62 2.27c-.077.462.145.768.35.953c.094.083.235.064.319-.03l2.688-2.995a.25.25 0 0 0-.02-.352l-.985-.888z");
}

.t5jak8x3h {
  stop-color: var(--svg-color--e4af34, #E4AF34);
}

.t6khnfd4i {
  d: path("M12.805 5.642v-.004c0-.32-.137-.58-.307-.58s-.306.26-.306.58v.004z");
}

.ttsumpbek {
  stop-color: var(--svg-color--897998, #897998);
  stop-opacity: 0;
}

.u0-djrvhx {
  stop-color: var(--svg-color--ffd537, #FFD537);
}

.ubyl24bdb {
  stop-color: var(--svg-color--565352, #565352);
}

.ujjr06bwy {
  stop-color: var(--svg-color--fc8c16, #FC8C16);
  stop-opacity: 0;
}

.ux4w7lb6c {
  stop-color: var(--svg-color--8c8388, #8C8388);
}

.uz8jx9bci {
  stop-color: var(--svg-color--f27f2f, #F27F2F);
  stop-opacity: 0;
}

.v5lz4sb9o {
  stop-color: var(--svg-color--695c75, #695C75);
}

.v6cmgr7lo {
  stop-color: var(--svg-color--f08337, #F08337);
}

.v9kimlbms {
  stop-color: var(--svg-color--94899e, #94899E);
}

.vc--wpv5i {
  stop-color: var(--svg-color--fff, #fff);
}

.vid7i5kil {
  fill: var(--svg-color--87014d, #87014D);
  fill-rule: evenodd;
  d: path("M12.945 6.756a.125.125 0 0 1-.002.177c-.238.233-.582.293-.692.304a.125.125 0 0 1-.025-.248c.093-.01.366-.062.542-.235a.125.125 0 0 1 .177.002");
}

.vj0bxeigc {
  stop-color: var(--svg-color--fba433, #FBA433);
}

.w8350jbiw {
  stop-color: var(--svg-color--dd3e06, #DD3E06);
  stop-opacity: 0;
}

.wb44sjbzz {
  stop-color: var(--svg-color--dd3e06, #DD3E06);
}

.wlrmkubjk {
  stop-color: var(--svg-color--cd7f1a, #CD7F1A);
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

.xh4g4qbuv {
  stop-color: var(--svg-color--e0a531, #E0A531);
  stop-opacity: 0;
}

.xpz0ltqsz {
  stop-color: var(--svg-color--ffcd3e, #FFCD3E);
}

.xyt681btr {
  d: path("M13.215 10.5c.281-.713.774-1.224.985-1.39l-.04 4.468l-1.785-.836c.278-.524.489-1.352.84-2.242");
}

.y0g_czb9f {
  stop-color: var(--svg-color--5a577e, #5A577E);
  stop-opacity: 0;
}

.ycy4eq6jz {
  fill: var(--svg-color--af5247, #AF5247);
  fill-rule: evenodd;
  d: path("M12.712 4.61a.8.8 0 0 0-.216-.016a.15.15 0 0 1-.038-.298a1 1 0 0 1 .313.02c.128.025.278.076.409.173a.15.15 0 0 1-.179.24a.7.7 0 0 0-.289-.12");
}

.yfqxgqb1h {
  stop-color: var(--svg-color--a19da6, #A19DA6);
  stop-opacity: 0;
}

.ytqhxrbga {
  d: path("M12.817 18.562c.383-1.05.716-2.028.773-2.383h4.742c.1 1.375-.144 1.713-.773 2.422c-.693.782-2.172 2.43-2.54 2.895c-.35.35-.5.789-.554.98l-2.262 7.43a.25.25 0 0 1-.315.166l-3.737-1.183c-.195-.061-.326-.265-.244-.452c.107-.245.333-.5.886-.656c.663-.187 1.943-.284 2.516-.336c.214-1.766.66-5.431.734-5.969c.094-.672.227-1.414.774-2.914");
}

.yvuyjoqpy {
  stop-color: var(--svg-color--47456f, #47456F);
}

.z7rq8royu {
  stop-color: var(--svg-color--f07f0f, #F07F0F);
  stop-opacity: 0;
}

.zc8ie-1dg {
  stop-color: var(--svg-color--515279, #515279);
  stop-opacity: 0;
}

.zhwoohbuw {
  stop-color: var(--svg-color--ffc247, #FFC247);
}

.zvi2r2b9j {
  stop-color: var(--svg-color--f08337, #F08337);
  stop-opacity: 0;
}

</style>
