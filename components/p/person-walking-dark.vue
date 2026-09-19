<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iVimwib)" transform="rotate(-4.337 14.017 6.742)" class="ovtrtzbnn"/><path fill="url(#iuYxOhb)" transform="rotate(-4.337 14.017 6.742)" class="ovtrtzbnn"/><path fill="url(#iIzVS1n)" transform="rotate(-4.337 14.017 6.742)" class="ovtrtzbnn"/><path fill="url(#ieuKo5c)" class="yksvfmboe"/><g filter="url(#i6SHFFF)"><path fill="url(#i8t6yob)" class="mi5aoybnn"/><path fill="url(#itqdGSb)" class="mi5aoybnn"/><path fill="url(#iz6T0bc)" class="mi5aoybnn"/><path fill="url(#iuXaD0b)" class="mi5aoybnn"/></g><g filter="url(#iFY9dTc)"><path fill="url(#ivXoZvr)" class="s6cwacbdr"/><path fill="url(#irEJwzd)" class="s6cwacbdr"/><path fill="url(#iHEvate)" class="s6cwacbdr"/><path fill="url(#iTpdvOb)" class="s6cwacbdr"/></g><path fill="url(#ivA9pye)" class="ftmtmebzh"/><path fill="url(#iFiYCld)" class="ftmtmebzh"/><g filter="url(#iZ3s79c)"><path fill="url(#iXyorjQ)" class="nljne-bpa"/><path fill="url(#ij8hGNc)" class="nljne-bpa"/><path fill="url(#ihGxjvb)" class="nljne-bpa"/></g><g filter="url(#ib1cRyd)"><path class="lo_j8f4ob"/><path fill="url(#iCnE2Xc)" class="ytqhxrbga"/><path fill="url(#is2MSRb)" class="ytqhxrbga"/><path fill="url(#i46a4ze)" class="ytqhxrbga"/><path fill="url(#iltAinO)" class="ytqhxrbga"/><path fill="url(#i1no2fe)" class="ytqhxrbga"/></g><path fill="url(#iUn3YLd)" class="p41usu8bh"/><path fill="url(#iOKi3Hd)" class="p41usu8bh"/><path fill="url(#iAkHyTq)" class="p41usu8bh"/><path fill="url(#ipGsseB)" class="p41usu8bh"/><path fill="url(#iUYS8Hb)" class="p41usu8bh"/><path class="t1hx-ibvq"/><path fill="url(#ikST0OT)" class="p4x11s6-u"/><path fill="url(#iifnuWc)" class="p4x11s6-u"/><path fill="url(#ihR4Crd)" class="p4x11s6-u"/><g filter="url(#isASy3c)"><path clip-rule="evenodd" class="ln2r3ufnd"/><path fill="url(#i3jErjj)" clip-rule="evenodd" class="k54qpabhe"/><path fill="url(#ickaw9b)" clip-rule="evenodd" class="k54qpabhe"/></g><path fill="url(#ihI0Oeb)" class="xyt681btr"/><path fill="url(#inXnLOb)" class="m-n1_xe-s"/><path fill="url(#i4gPRHd)" class="m-n1_xe-s"/><path fill="url(#iTgYT8b)" class="m-n1_xe-s"/><path fill="url(#ibMGSJd)" class="m-n1_xe-s"/><circle fill="url(#izDjNmc)" class="rayucyv4q"/><g filter="url(#iw8sOzb)"><path clip-rule="evenodd" class="kgk40acgn"/></g><g filter="url(#iK9vKfc)"><path class="rb392hb8f"/></g><path fill="url(#iNvDiId)" class="d_u_riyxa"/><path fill="url(#i8Anpne)" class="d_u_riyxa"/><path fill="url(#iEQ0pob)" class="d_u_riyxa"/><path fill="url(#i2Jnxvd)" class="exqbqfbox"/><path fill="url(#iFXeqWc)" class="exqbqfbox"/><path clip-rule="evenodd" class="jrvhe6bix"/><g filter="url(#iOsXxod)"><path clip-rule="evenodd" class="e8whhho_w"/></g><path class="dewlk8egf"/><path fill="url(#iewbKse)" class="t6khnfd4i"/><path fill="url(#iCfHhDc)" class="ifehhsb9l"/><ellipse fill="url(#inn7BZI)" transform="rotate(24.61 12.373 5.29)" class="sb_t_0b6s"/><g filter="url(#iejYQpc)"><path fill="url(#iZWOoDf)" class="lkp-rxh5n"/></g><g filter="url(#ixuPdgS)"><path fill="url(#iDiU5Le)" class="ari0bjqpi"/></g><g filter="url(#is7qwfe)"><path fill="url(#itXJc4c)" class="w59t37b_l"/></g><defs><radialGradient id="iVimwib" cx="0" cy="0" r="1" gradientTransform="matrix(-.05152 -2.21336 1.59858 -.0372 15.725 8.752)" gradientUnits="userSpaceOnUse"><stop offset=".116" class="tsuuox2ro"/><stop offset="1" class="h1cr42h7h"/></radialGradient><radialGradient id="iuYxOhb" cx="0" cy="0" r="1" gradientTransform="matrix(-.53617 .66448 -.89991 -.72614 16.078 7.18)" gradientUnits="userSpaceOnUse"><stop class="g9t63ub0s"/><stop offset="1" class="oovpwlbmg"/></radialGradient><radialGradient id="iIzVS1n" cx="0" cy="0" r="1" gradientTransform="matrix(.01105 -.86884 .23985 .00305 14.23 9.156)" gradientUnits="userSpaceOnUse"><stop class="lzq15abom"/><stop offset="1" class="jtmedjbua"/></radialGradient><radialGradient id="ieuKo5c" cx="0" cy="0" r="1" gradientTransform="matrix(.47656 .25781 -.36391 .67269 11.162 6.25)" gradientUnits="userSpaceOnUse"><stop offset=".101" class="ss7zei8xw"/><stop offset=".684" class="d4kn2qv1f"/></radialGradient><radialGradient id="itqdGSb" cx="0" cy="0" r="1" gradientTransform="matrix(-.84375 -.04688 .05715 -1.0287 14.84 5.547)" gradientUnits="userSpaceOnUse"><stop offset=".156" class="cm3jz64eh"/><stop offset="1" class="lu7jcxbxj"/></radialGradient><radialGradient id="iz6T0bc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -5.1875 1.40625 0 11.944 6.734)" gradientUnits="userSpaceOnUse"><stop offset=".163" class="hrqvsac6m"/><stop offset="1" class="fblnbo7cb"/></radialGradient><radialGradient id="iuXaD0b" cx="0" cy="0" r="1" gradientTransform="matrix(0 .39063 -.60919 0 12.772 5.593)" gradientUnits="userSpaceOnUse"><stop offset=".155" class="o5l8xobeq"/><stop offset="1" class="plhowgx4z"/></radialGradient><radialGradient id="ivXoZvr" cx="0" cy="0" r="1" gradientTransform="matrix(2.40688 -1.94794 2.96121 3.65888 13.994 4.59)" gradientUnits="userSpaceOnUse"><stop offset=".194" class="nqgqms1jm"/><stop offset="1" class="w55-gkb2p"/></radialGradient><radialGradient id="irEJwzd" cx="0" cy="0" r="1" gradientTransform="matrix(1.20044 -.875 1.4077 1.93128 11.728 3.078)" gradientUnits="userSpaceOnUse"><stop class="khzpeo26k"/><stop offset="1" class="xktf9pbat"/></radialGradient><radialGradient id="iHEvate" cx="0" cy="0" r="1" gradientTransform="matrix(-.52344 .14843 -.07293 -.25719 16.56 6.422)" gradientUnits="userSpaceOnUse"><stop offset=".197" class="jiuqa9mgc"/><stop offset="1" class="wyd1xpdro"/></radialGradient><radialGradient id="iTpdvOb" cx="0" cy="0" r="1" gradientTransform="rotate(-13.323 28.445 -60.13)scale(.91526 2.45235)" gradientUnits="userSpaceOnUse"><stop offset=".353" class="dzmi4fing"/><stop offset=".584" class="plkel1bga"/></radialGradient><radialGradient id="ivA9pye" cx="0" cy="0" r="1" gradientTransform="matrix(.72656 -.21094 .10296 .35463 14.616 5.43)" gradientUnits="userSpaceOnUse"><stop offset=".17" class="o1rzobcjq"/><stop offset="1" class="v23x_cgsr"/></radialGradient><radialGradient id="ij8hGNc" cx="0" cy="0" r="1" gradientTransform="matrix(2.45369 2.93958 -5.96661 4.98038 16.952 18.024)" gradientUnits="userSpaceOnUse"><stop offset=".434" class="oiy_54b9a"/><stop offset="1" class="rm4aiz5dn"/></radialGradient><radialGradient id="ihGxjvb" cx="0" cy="0" r="1" gradientTransform="matrix(.89062 .65625 -3.9414 5.34905 16.637 19.039)" gradientUnits="userSpaceOnUse"><stop offset=".043" class="v5lz4sb9o"/><stop offset="1" class="m_uy2vb_d"/></radialGradient><radialGradient id="iCnE2Xc" cx="0" cy="0" r="1" gradientTransform="matrix(3.25001 -5.14062 1.35402 .85604 15.855 20.883)" gradientUnits="userSpaceOnUse"><stop offset=".07" class="mngz2ebss"/><stop offset="1" class="ttsumpbek"/></radialGradient><radialGradient id="is2MSRb" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.42188 -1.38588 0 16.668 16.18)" gradientUnits="userSpaceOnUse"><stop class="f3j6dkfip"/><stop offset="1" class="fxoxl0blj"/></radialGradient><radialGradient id="iltAinO" cx="0" cy="0" r="1" gradientTransform="matrix(.14063 -.17968 .6458 .50543 11.972 28.093)" gradientUnits="userSpaceOnUse"><stop class="ryq0o3qru"/><stop offset="1" class="yfqxgqb1h"/></radialGradient><radialGradient id="i1no2fe" cx="0" cy="0" r="1" gradientTransform="matrix(6.375 -1.8125 4.67455 16.4415 12.293 19.226)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="ex23x-brg"/><stop offset="1" class="ux4w7lb6c"/></radialGradient><radialGradient id="iUn3YLd" cx="0" cy="0" r="1" gradientTransform="matrix(-.09375 -1.53125 2.45635 -.15039 10.84 29.445)" gradientUnits="userSpaceOnUse"><stop class="cl2mlwbhs"/><stop offset="1" class="yvuyjoqpy"/></radialGradient><radialGradient id="iOKi3Hd" cx="0" cy="0" r="1" gradientTransform="matrix(1.0625 -.21875 .15137 .73521 7.73 28.508)" gradientUnits="userSpaceOnUse"><stop class="m3n9jy0fh"/><stop offset="1" class="hdzwkybza"/></radialGradient><radialGradient id="iAkHyTq" cx="0" cy="0" r="1" gradientTransform="rotate(-70.942 26.744 6.628)scale(1.81842 .89694)" gradientUnits="userSpaceOnUse"><stop offset=".08" class="a541b3bqx"/><stop offset="1" class="zc8ie-1dg"/></radialGradient><radialGradient id="ihR4Crd" cx="0" cy="0" r="1" gradientTransform="rotate(-132.875 17.849 8.353)scale(1.99789 1.10527)" gradientUnits="userSpaceOnUse"><stop class="xh_da2q2q"/><stop offset="1" class="stwbr2bhy"/></radialGradient><radialGradient id="i3jErjj" cx="0" cy="0" r="1" gradientTransform="matrix(1.0625 -.07813 .1783 2.42485 7.694 17.11)" gradientUnits="userSpaceOnUse"><stop class="g8jnmtmzx"/><stop offset="1" class="mizo-gt3p"/></radialGradient><radialGradient id="ickaw9b" cx="0" cy="0" r="1" gradientTransform="rotate(130.815 3.344 9.156)scale(2.27101 1.05465)" gradientUnits="userSpaceOnUse"><stop class="iuhc-tvqs"/><stop offset="1" class="it0-i6eez"/></radialGradient><radialGradient id="inXnLOb" cx="0" cy="0" r="1" gradientTransform="matrix(1.9375 6 -4.22355 1.36385 14.98 11.351)" gradientUnits="userSpaceOnUse"><stop offset=".446" class="pvqp1vbsj"/><stop offset="1" class="jbtp05a5b"/></radialGradient><radialGradient id="i4gPRHd" cx="0" cy="0" r="1" gradientTransform="matrix(3.0625 2.84375 -4.8238 5.19486 13.325 9.726)" gradientUnits="userSpaceOnUse"><stop class="v6cmgr7lo"/><stop offset="1" class="zvi2r2b9j"/></radialGradient><radialGradient id="iTgYT8b" cx="0" cy="0" r="1" gradientTransform="matrix(.59375 2.6875 -1.45306 .32102 16.668 11.039)" gradientUnits="userSpaceOnUse"><stop class="wb44sjbzz"/><stop offset="1" class="w8350jbiw"/></radialGradient><radialGradient id="ibMGSJd" cx="0" cy="0" r="1" gradientTransform="rotate(173.533 8.107 4.77)scale(2.73543 1.43274)" gradientUnits="userSpaceOnUse"><stop offset=".213" class="ayezflb3j"/><stop offset="1" class="ujjr06bwy"/></radialGradient><radialGradient id="izDjNmc" cx="0" cy="0" r="1" gradientTransform="rotate(90 1.46 19.334)scale(.90625)" gradientUnits="userSpaceOnUse"><stop offset=".256" class="x_9ov7g-b"/><stop offset="1" class="p6vh5wb5l"/></radialGradient><radialGradient id="i8Anpne" cx="0" cy="0" r="1" gradientTransform="matrix(1.72656 -.10937 .20534 3.24138 14.88 10.523)" gradientUnits="userSpaceOnUse"><stop offset=".235" class="ou5ot-gfg"/><stop offset="1" class="uz8jx9bci"/></radialGradient><radialGradient id="iEQ0pob" cx="0" cy="0" r="1" gradientTransform="rotate(-97.334 13.599 -1.534)scale(3.18229 3.71057)" gradientUnits="userSpaceOnUse"><stop offset=".839" class="z7rq8royu"/><stop offset=".958" class="p1zm9vufc"/></radialGradient><radialGradient id="i2Jnxvd" cx="0" cy="0" r="1" gradientTransform="matrix(.8373 -.05636 .04467 .6636 8.005 16.579)" gradientUnits="userSpaceOnUse"><stop class="al1miny5m"/><stop offset="1" class="avzqw9b1i"/></radialGradient><radialGradient id="iFXeqWc" cx="0" cy="0" r="1" gradientTransform="matrix(-.3295 .27291 -.22275 -.26894 8.961 16.527)" gradientUnits="userSpaceOnUse"><stop class="vi9njcc_v"/><stop offset="1" class="u58vaovxu"/></radialGradient><radialGradient id="iewbKse" cx="0" cy="0" r="1" gradientTransform="matrix(.27344 0 0 .53125 12.477 5.62)" gradientUnits="userSpaceOnUse"><stop offset=".895" class="l0aricxam"/><stop offset="1" class="n9r91ylyy"/></radialGradient><radialGradient id="iCfHhDc" cx="0" cy="0" r="1" gradientTransform="matrix(.25 0 0 .54102 12.309 5.642)" gradientUnits="userSpaceOnUse"><stop class="gv3iwdbvq"/><stop offset=".813" class="ubyl24bdb"/></radialGradient><linearGradient id="i8t6yob" x1="14.528" x2="11.665" y1="6.289" y2="6.461" gradientUnits="userSpaceOnUse"><stop class="bmcblacal"/><stop offset="1" class="d0kv1cyul"/></linearGradient><linearGradient id="iFiYCld" x1="14.58" x2="14.694" y1="5.496" y2="5.511" gradientUnits="userSpaceOnUse"><stop class="uysgu56cq"/><stop offset="1" class="ve-3ak5rg"/></linearGradient><linearGradient id="iXyorjQ" x1="17.973" x2="20.201" y1="22.883" y2="20.939" gradientUnits="userSpaceOnUse"><stop offset=".211" class="pat1zf4-w"/><stop offset="1" class="wtea7v6lu"/></linearGradient><linearGradient id="i46a4ze" x1="15.746" x2="15.746" y1="16.07" y2="16.414" gradientUnits="userSpaceOnUse"><stop offset=".136" class="x5p6yzbmf"/><stop offset="1" class="cnh3p8b3x"/></linearGradient><linearGradient id="ipGsseB" x1="10.278" x2="10.364" y1="29.617" y2="29.305" gradientUnits="userSpaceOnUse"><stop class="l138bfbcs"/><stop offset="1" class="oxce79bcz"/></linearGradient><linearGradient id="iUYS8Hb" x1="12.246" x2="11.668" y1="29.992" y2="29.773" gradientUnits="userSpaceOnUse"><stop offset=".064" class="lhdz7oxfj"/><stop offset="1" class="csaq2_bel"/></linearGradient><linearGradient id="ikST0OT" x1="20.856" x2="21.45" y1="27.976" y2="28.148" gradientUnits="userSpaceOnUse"><stop class="oxg1n1wjw"/><stop offset="1" class="y0g_czb9f"/></linearGradient><linearGradient id="iifnuWc" x1="22.981" x2="22.801" y1="28.051" y2="27.902" gradientUnits="userSpaceOnUse"><stop class="p6qc3nb-j"/><stop offset="0" class="ezcqmvbni"/><stop offset="1" class="stwbr2bhy"/></linearGradient><linearGradient id="ihI0Oeb" x1="12.7" x2="13.575" y1="12.836" y2="10.445" gradientUnits="userSpaceOnUse"><stop class="h2o5q3bga"/><stop offset=".787" class="md0ucwkak"/></linearGradient><linearGradient id="iNvDiId" x1="16.731" x2="17.84" y1="9.117" y2="12.57" gradientUnits="userSpaceOnUse"><stop offset=".118" class="fjz5hab9p"/><stop offset="1" class="ljdv6tb3r"/></linearGradient><linearGradient id="inn7BZI" x1="12.302" x2="12.488" y1="5.252" y2="5.313" gradientUnits="userSpaceOnUse"><stop class="vc--wpv5i"/><stop offset="1" class="stui2mbih"/></linearGradient><linearGradient id="iZWOoDf" x1="12.075" x2="16.7" y1="27.414" y2="17.273" gradientUnits="userSpaceOnUse"><stop class="v9kimlbms"/><stop offset="1" class="g24ahctiy"/></linearGradient><linearGradient id="iDiU5Le" x1="22.219" x2="17.908" y1="25.323" y2="19.951" gradientUnits="userSpaceOnUse"><stop class="ckhjb_bgt"/><stop offset="1" class="rnrhdzckq"/></linearGradient><linearGradient id="itXJc4c" x1="15.777" x2="16.222" y1="4.923" y2="2.024" gradientUnits="userSpaceOnUse"><stop offset=".421" class="h-bh2_bpf"/><stop offset="1" class="pf-fc7btu"/></linearGradient><filter id="i6SHFFF" width="4.443" height="5.249" x="11.465" y="3.348" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2" dy="-.2"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.360784 0 0 0 0 0.172549 0 0 0 0 0.12549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_97"/></filter><filter id="iFY9dTc" width="5.503" height="5.499" x="11.728" y="1.766" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.15"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.14902 0 0 0 0 0.101961 0 0 0 0 0.109804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_97"/></filter><filter id="iZ3s79c" width="8.674" height="14.771" x="16.188" y="15.461" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".75" dy="-.75"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.439216 0 0 0 0 0.388235 0 0 0 0 0.486275 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_97"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.537255 0 0 0 0 0.423529 0 0 0 0 0.635294 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_97" result="effect2_innerShadow_4002_97"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy=".25"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.529412 0 0 0 0 0.490196 0 0 0 0 0.537255 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_4002_97" result="effect3_innerShadow_4002_97"/></filter><filter id="ib1cRyd" width="10.972" height="14.104" x="7.882" y="15.979" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy="-.2"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.619608 0 0 0 0 0.592157 0 0 0 0 0.611765 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_97"/></filter><filter id="isASy3c" width="8.438" height="7.859" x="6.785" y="10.609" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-1"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.239216 0 0 0 0 0.12549 0 0 0 0 0.184314 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_97"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.266667 0 0 0 0 0.188235 0 0 0 0 0.247059 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_97" result="effect2_innerShadow_4002_97"/></filter><filter id="iw8sOzb" width="7.59" height="10.511" x="15.741" y="9.142" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.266667 0 0 0 0 0.156863 0 0 0 0 0.231373 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_97"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.4" dy=".4"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.376471 0 0 0 0 0.305882 0 0 0 0 0.301961 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_97" result="effect2_innerShadow_4002_97"/></filter><filter id="iK9vKfc" width="5.631" height="8.6" x="17.386" y="10.544" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_97" stdDeviation=".3"/></filter><filter id="iOsXxod" width="1.013" height=".568" x="12.227" y="4.292" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0666667 0 0 0 0 0.0627451 0 0 0 0 0.0627451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_97"/></filter><filter id="iejYQpc" width="6.844" height="12.891" x="10.856" y="16.101" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_97" stdDeviation=".5"/></filter><filter id="ixuPdgS" width="6.45" height="8.475" x="16.804" y="18.029" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_97" stdDeviation=".375"/></filter><filter id="is7qwfe" width="2.262" height="3.469" x="14.823" y="2.322" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_97" stdDeviation=".25"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:person-walking-dark" /></template>
<style>
.a541b3bqx {
  stop-color: var(--svg-color--515279, #515279);
}

.al1miny5m {
  stop-color: var(--svg-color--67524e, #67524E);
}

.ari0bjqpi {
  d: path("m19.028 21.127l3.476 4.428l-.514.199l-3.484-3.708a3 3 0 0 1-.761-1.493l-.19-1l.751-.774l.544 1.994a1 1 0 0 0 .178.354");
}

.avzqw9b1i {
  stop-color: var(--svg-color--3d2329, #3D2329);
}

.ayezflb3j {
  stop-color: var(--svg-color--fc8c16, #FC8C16);
}

.bmcblacal {
  stop-color: var(--svg-color--492f32, #492F32);
}

.ckhjb_bgt {
  stop-color: var(--svg-color--a39fa7, #A39FA7);
}

.cl2mlwbhs {
  stop-color: var(--svg-color--4a4b75, #4A4B75);
}

.cm3jz64eh {
  stop-color: var(--svg-color--34191a, #34191A);
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

.d0kv1cyul {
  stop-color: var(--svg-color--5b4542, #5B4542);
}

.d4kn2qv1f {
  stop-color: var(--svg-color--41212e, #41212E);
}

.dewlk8egf {
  fill: var(--svg-color--fff, #fff);
  d: path("M12.2 5.642h.988c0-.391-.221-.709-.494-.709s-.494.318-.494.71");
}

.dzmi4fing {
  stop-color: var(--svg-color--363131, #363131);
}

.e8whhho_w {
  fill: var(--svg-color--2c2929, #2C2929);
  fill-rule: evenodd;
  d: path("M12.712 4.61a.8.8 0 0 0-.216-.016a.15.15 0 0 1-.038-.298a1 1 0 0 1 .313.02c.128.025.278.076.409.173a.15.15 0 0 1-.179.24a.7.7 0 0 0-.289-.12");
}

.ex23x-brg {
  stop-color: var(--svg-color--8c8388, #8C8388);
  stop-opacity: 0;
}

.exqbqfbox {
  d: path("m8.657 16.012l.496.051c.21.022.374.192.388.403a.38.38 0 0 1-.077.267c-.264.33-.524.365-.721.407c-.22.047-.676-.191-.59-.691a.53.53 0 0 1 .504-.437");
}

.ezcqmvbni {
  stop-color: var(--svg-color--443a80, #443A80);
}

.f3j6dkfip {
  stop-color: var(--svg-color--99919a, #99919A);
}

.fblnbo7cb {
  stop-color: var(--svg-color--614c49, #614C49);
  stop-opacity: 0;
}

.fjz5hab9p {
  stop-color: var(--svg-color--f67e18, #F67E18);
}

.ft5dv1b6b {
  fill: none;
}

.ftmtmebzh {
  d: path("m14.464 6.303l.2-1.44a.727.727 0 0 1-.2 1.44");
}

.fxoxl0blj {
  stop-color: var(--svg-color--8c8393, #8C8393);
  stop-opacity: 0;
}

.g24ahctiy {
  stop-color: var(--svg-color--94899e, #94899E);
  stop-opacity: 0;
}

.g8jnmtmzx {
  stop-color: var(--svg-color--6a5450, #6A5450);
}

.g9t63ub0s {
  stop-color: var(--svg-color--271213, #271213);
}

.gv3iwdbvq {
  stop-color: var(--svg-color--666361, #666361);
}

.h-bh2_bpf {
  stop-color: var(--svg-color--454143, #454143);
}

.h1cr42h7h {
  stop-color: var(--svg-color--3d2323, #3D2323);
}

.h2o5q3bga {
  stop-color: var(--svg-color--f3563a, #F3563A);
}

.hdzwkybza {
  stop-color: var(--svg-color--63617e, #63617E);
  stop-opacity: 0;
}

.hrqvsac6m {
  stop-color: var(--svg-color--614c49, #614C49);
}

.ifehhsb9l {
  d: path("m12.61 5.642l.004-.072c0-.185-.08-.336-.176-.336c-.097 0-.176.15-.176.336q0 .038.004.072z");
}

.it0-i6eez {
  stop-color: var(--svg-color--604a46, #604A46);
  stop-opacity: 0;
}

.iuhc-tvqs {
  stop-color: var(--svg-color--604a46, #604A46);
}

.jbtp05a5b {
  stop-color: var(--svg-color--d34015, #D34015);
}

.jiuqa9mgc {
  stop-color: var(--svg-color--464243, #464243);
}

.jrvhe6bix {
  fill: var(--svg-color--280017, #280017);
  fill-rule: evenodd;
  d: path("M12.945 6.756a.125.125 0 0 1-.002.177c-.238.233-.582.293-.692.304a.125.125 0 0 1-.025-.248c.093-.01.366-.062.542-.235a.125.125 0 0 1 .177.002");
}

.jtmedjbua {
  stop-color: var(--svg-color--614e4a, #614E4A);
  stop-opacity: 0;
}

.k54qpabhe {
  fill-rule: evenodd;
  d: path("M9.169 18.391a.85.85 0 0 1-1.13-.433l-.19-.426a.755.755 0 0 1 .383-.993c1.533-.704 4.023-2.149 4.983-5.93l2.008.524c-1.185 4.668-4.29 6.44-6.054 7.258");
}

.kgk40acgn {
  fill: var(--svg-color--462c2f, #462C2F);
  fill-rule: evenodd;
  d: path("M21.837 19.223a.614.614 0 0 1-.776-.407c-1.215-3.921-3.166-6.29-4.542-7.545c-.438-.4-.516-1.082-.128-1.53c.346-.401.944-.472 1.348-.13c1.626 1.381 3.91 3.976 5.316 8.605a.59.59 0 0 1-.382.73z");
}

.khzpeo26k {
  stop-color: var(--svg-color--564c49, #564C49);
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

.ln2r3ufnd {
  fill: var(--svg-color--47302d, #47302D);
  fill-rule: evenodd;
  d: path("M9.169 18.391a.85.85 0 0 1-1.13-.433l-.19-.426a.755.755 0 0 1 .383-.993c1.533-.704 4.023-2.149 4.983-5.93l2.008.524c-1.185 4.668-4.29 6.44-6.054 7.258");
}

.lo_j8f4ob {
  fill: var(--svg-color--8c8393, #8C8393);
  d: path("M12.817 18.562c.383-1.05.716-2.028.773-2.383h4.742c.1 1.375-.144 1.713-.773 2.422c-.693.782-2.172 2.43-2.54 2.895c-.35.35-.5.789-.554.98l-2.262 7.43a.25.25 0 0 1-.315.166l-3.737-1.183c-.195-.061-.326-.265-.244-.452c.107-.245.333-.5.886-.656c.663-.187 1.943-.284 2.516-.336c.214-1.766.66-5.431.734-5.969c.094-.672.227-1.414.774-2.914");
}

.lu7jcxbxj {
  stop-color: var(--svg-color--34191a, #34191A);
  stop-opacity: 0;
}

.lzq15abom {
  stop-color: var(--svg-color--614e4a, #614E4A);
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

.md0ucwkak {
  stop-color: var(--svg-color--ea6f3e, #EA6F3E);
}

.mi5aoybnn {
  d: path("M11.693 4.848c.039-.8.298-1.187.42-1.3h3.733l.062 3.164c-.866 2.121-3.511 2.212-3.906 1.445s-.354-2.381-.309-3.309");
}

.mizo-gt3p {
  stop-color: var(--svg-color--6a5450, #6A5450);
  stop-opacity: 0;
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

.nqgqms1jm {
  stop-color: var(--svg-color--22191d, #22191D);
}

.o1rzobcjq {
  stop-color: var(--svg-color--635251, #635251);
}

.o5l8xobeq {
  stop-color: var(--svg-color--472f2c, #472F2C);
}

.oiy_54b9a {
  stop-color: var(--svg-color--887e8b, #887E8B);
}

.oovpwlbmg {
  stop-color: var(--svg-color--57423f, #57423F);
  stop-opacity: 0;
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

.p6vh5wb5l {
  stop-color: var(--svg-color--3d1f32, #3D1F32);
}

.pat1zf4-w {
  stop-color: var(--svg-color--8b8290, #8B8290);
}

.pf-fc7btu {
  stop-color: var(--svg-color--454143, #454143);
  stop-opacity: 0;
}

.plhowgx4z {
  stop-color: var(--svg-color--472f2c, #472F2C);
  stop-opacity: 0;
}

.plkel1bga {
  stop-color: var(--svg-color--363131, #363131);
  stop-opacity: 0;
}

.pvqp1vbsj {
  stop-color: var(--svg-color--e9672b, #E9672B);
}

.rayucyv4q {
  cx: 20.93px;
  cy: 18.027px;
  r: 0.551px;
}

.rb392hb8f {
  stroke: var(--svg-color--604e4d, #604E4D);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M18.186 11.344c.896.76 2.956 3.225 4.031 7");
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

.ss7zei8xw {
  stop-color: var(--svg-color--68534f, #68534F);
}

.stui2mbih {
  stop-color: var(--svg-color--fff, #fff);
  stop-opacity: 0;
}

.stwbr2bhy {
  stop-color: var(--svg-color--46437b, #46437B);
  stop-opacity: 0;
}

.t1hx-ibvq {
  fill: var(--svg-color--45437a, #45437A);
  d: path("m23.035 25.653l-1.638.678l.022.02l-.107.355c-.217.713-.536 1.764-.62 2.27c-.077.462.145.768.35.953c.094.083.235.064.319-.03l2.688-2.995a.25.25 0 0 0-.02-.352l-.985-.888z");
}

.t6khnfd4i {
  d: path("M12.805 5.642v-.004c0-.32-.137-.58-.307-.58s-.306.26-.306.58v.004z");
}

.tsuuox2ro {
  stop-color: var(--svg-color--564341, #564341);
}

.ttsumpbek {
  stop-color: var(--svg-color--897998, #897998);
  stop-opacity: 0;
}

.u58vaovxu {
  stop-color: var(--svg-color--3f2329, #3F2329);
  stop-opacity: 0;
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

.uysgu56cq {
  stop-color: var(--svg-color--48302c, #48302C);
}

.uz8jx9bci {
  stop-color: var(--svg-color--f27f2f, #F27F2F);
  stop-opacity: 0;
}

.v23x_cgsr {
  stop-color: var(--svg-color--482c2e, #482C2E);
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

.ve-3ak5rg {
  stop-color: var(--svg-color--48302c, #48302C);
  stop-opacity: 0;
}

.vi9njcc_v {
  stop-color: var(--svg-color--534142, #534142);
}

.w55-gkb2p {
  stop-color: var(--svg-color--342d30, #342D30);
}

.w59t37b_l {
  d: path("M15.377 3.77c.155.635.246 1.244.277 1.52c.63-.577.87-1.287.928-1.871c.05-.498-.575-.757-1-.49c-.305.192-.291.49-.205.84");
}

.w8350jbiw {
  stop-color: var(--svg-color--dd3e06, #DD3E06);
  stop-opacity: 0;
}

.wb44sjbzz {
  stop-color: var(--svg-color--dd3e06, #DD3E06);
}

.wtea7v6lu {
  stop-color: var(--svg-color--9f9c9f, #9F9C9F);
}

.wyd1xpdro {
  stop-color: var(--svg-color--464243, #464243);
  stop-opacity: 0;
}

.x_9ov7g-b {
  stop-color: var(--svg-color--4b3838, #4B3838);
}

.x5p6yzbmf {
  stop-color: var(--svg-color--817076, #817076);
}

.xh_da2q2q {
  stop-color: var(--svg-color--60618d, #60618D);
}

.xktf9pbat {
  stop-color: var(--svg-color--564c49, #564C49);
  stop-opacity: 0;
}

.xyt681btr {
  d: path("M13.215 10.5c.281-.713.774-1.224.985-1.39l-.04 4.468l-1.785-.836c.278-.524.489-1.352.84-2.242");
}

.y0g_czb9f {
  stop-color: var(--svg-color--5a577e, #5A577E);
  stop-opacity: 0;
}

.yfqxgqb1h {
  stop-color: var(--svg-color--a19da6, #A19DA6);
  stop-opacity: 0;
}

.yksvfmboe {
  d: path("M11.453 5.812a1 1 0 0 0 .258-.457h.18V6.48c-.216.137-.523.115-.614-.09c-.078-.175-.02-.394.176-.578");
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

.zvi2r2b9j {
  stop-color: var(--svg-color--f08337, #F08337);
  stop-opacity: 0;
}

</style>
