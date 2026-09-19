<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iFOsCdc)" transform="scale(-1 1)rotate(-4.337 82.124 185.73)" class="z8jy9-b3h"/><path fill="url(#igayXtH)" transform="scale(-1 1)rotate(-4.337 82.124 185.73)" class="z8jy9-b3h"/><path fill="url(#iZ0gLke)" transform="scale(-1 1)rotate(-4.337 82.124 185.73)" class="z8jy9-b3h"/><path fill="url(#izPsd5c)" class="s-g161bqt"/><g filter="url(#iey5FMc)"><path fill="url(#ipx1pGc)" class="tadbet4hb"/><path fill="url(#iPncCQe)" class="tadbet4hb"/><path fill="url(#imZArDe)" class="tadbet4hb"/><path fill="url(#iq20X1b)" class="tadbet4hb"/></g><g filter="url(#iazyZHF)"><path fill="url(#i47wEMB)" class="ve46_g1lk"/><path fill="url(#iS0Hbcc)" class="ve46_g1lk"/><path fill="url(#iB7d0ac)" class="ve46_g1lk"/><path fill="url(#iCfJ8ed)" class="ve46_g1lk"/></g><path fill="url(#i971J8d)" class="kj46gabnl"/><path fill="url(#ixhrK4c)" class="kj46gabnl"/><g filter="url(#ircfwNc)"><path fill="url(#ifiuZpe)" class="uyi74zbuf"/><path fill="url(#in7H5KE)" class="uyi74zbuf"/><path fill="url(#iRGvjqc)" class="uyi74zbuf"/></g><g filter="url(#izKHonc)"><path class="myq9eabfw"/><path fill="url(#in9pNLc)" class="a18cgebwg"/><path fill="url(#i4VKJFb)" class="a18cgebwg"/><path fill="url(#iYa8n8d)" class="a18cgebwg"/><path fill="url(#iWhSB9E)" class="a18cgebwg"/><path fill="url(#i5QPTke)" class="a18cgebwg"/></g><path fill="url(#iIyaeue)" class="qhpv1urou"/><path fill="url(#ilCjqTc)" class="qhpv1urou"/><path fill="url(#i70Vnhb)" class="qhpv1urou"/><path fill="url(#i7HCu4c)" class="qhpv1urou"/><path fill="url(#iH5Lx2c)" class="qhpv1urou"/><path class="oeqsi5agv"/><path fill="url(#id1rZnM)" class="v31hj0bvo"/><path fill="url(#irT6sNe)" class="v31hj0bvo"/><path fill="url(#iooA69y)" class="v31hj0bvo"/><g filter="url(#iIKfaEb)"><path clip-rule="evenodd" class="ao8yt0btw"/><path fill="url(#ii4il3d)" clip-rule="evenodd" class="pg17md4yk"/><path fill="url(#itaSgAb)" clip-rule="evenodd" class="pg17md4yk"/></g><path class="dl1_whaqb"/><g filter="url(#iWNWQjd)"><path stroke="url(#iDMDtcd)" class="jvgc_-gud"/></g><g filter="url(#iZ1WjEb)"><path fill="url(#ixiClDa)" clip-rule="evenodd" class="now42z6pk"/></g><path fill="url(#iJN5uxb)" class="kher6vnjv"/><path fill="url(#iqLOmmc)" class="kher6vnjv"/><g filter="url(#iAs2dJe)"><circle fill="url(#iUctc4d)" transform="matrix(-1 0 0 1 28.389 28.238)" class="ghq9gsa-q"/><circle fill="url(#iETpATd)" transform="matrix(-1 0 0 1 28.389 28.238)" class="ghq9gsa-q"/><circle fill="url(#iPmd0rd)" transform="matrix(-1 0 0 1 28.389 28.238)" class="ghq9gsa-q"/></g><g filter="url(#ipEngjb)"><path fill="url(#imj8XHO)" class="fxmcdkbqm"/><path fill="url(#igwd64R)" class="fxmcdkbqm"/></g><g filter="url(#iXoEGyc)"><rect transform="scale(-1 1)rotate(-7.657 106.717 156.292)" class="sxdomfxyu"/></g><path fill="url(#i487aeb)" class="y3bhiibho"/><path fill="url(#i2KXtcc)" class="c0d4izb9h"/><path fill="url(#iAp8ITb)" class="c0d4izb9h"/><path fill="url(#i1AnQyU)" class="c0d4izb9h"/><path fill="url(#iXd8u9d)" class="c0d4izb9h"/><circle fill="url(#izN5vbc)" transform="matrix(-1 0 0 1 7.447 17.476)" class="am9uocbqt"/><g filter="url(#i1TtYQb)"><path clip-rule="evenodd" class="mp_6n8ltb"/></g><g filter="url(#izmWA5b)"><path class="zur60-b5i"/></g><path fill="url(#ibGgDUd)" class="zhp7rumpf"/><path fill="url(#i7Yo6Eb)" class="zhp7rumpf"/><path fill="url(#isl2iMc)" class="zhp7rumpf"/><path clip-rule="evenodd" class="ej0rqcbmd"/><g filter="url(#iRLCxbb)"><path clip-rule="evenodd" class="m4b5f-bxw"/></g><path class="sa2skx9xg"/><path fill="url(#itbChTd)" class="q5mgiq5sp"/><path fill="url(#iQqCGcc)" class="ssn5ajz8v"/><ellipse fill="url(#ipECBte)" transform="scale(-1 1)rotate(24.61 -19.62 -32.88)" class="m1l7k9jve"/><g filter="url(#ix0O1Cb)"><path fill="url(#iKWcXIe)" class="gap6upynm"/></g><g filter="url(#i6M6Kwb)"><path fill="url(#iKOEAEc)" class="gevu3lbtd"/></g><g filter="url(#iYaf3fn)"><path fill="url(#iAADvie)" class="ch-_hmxrc"/></g><defs><radialGradient id="iFOsCdc" cx="0" cy="0" r="1" gradientTransform="matrix(-.05152 -2.21336 1.59858 -.0372 1.708 2.01)" gradientUnits="userSpaceOnUse"><stop offset=".116" class="tsuuox2ro"/><stop offset="1" class="h1cr42h7h"/></radialGradient><radialGradient id="igayXtH" cx="0" cy="0" r="1" gradientTransform="matrix(-.53617 .66448 -.89991 -.72614 2.062 .438)" gradientUnits="userSpaceOnUse"><stop class="g9t63ub0s"/><stop offset="1" class="oovpwlbmg"/></radialGradient><radialGradient id="iZ0gLke" cx="0" cy="0" r="1" gradientTransform="matrix(.01105 -.86884 .23985 .00305 .214 2.413)" gradientUnits="userSpaceOnUse"><stop class="lzq15abom"/><stop offset="1" class="jtmedjbua"/></radialGradient><radialGradient id="izPsd5c" cx="0" cy="0" r="1" gradientTransform="rotate(151.587 7.541 5.234)scale(.54183 .76481)" gradientUnits="userSpaceOnUse"><stop offset=".101" class="ss7zei8xw"/><stop offset=".684" class="d4kn2qv1f"/></radialGradient><radialGradient id="iPncCQe" cx="0" cy="0" r="1" gradientTransform="matrix(.84375 -.04687 .05715 1.0287 12.986 5.547)" gradientUnits="userSpaceOnUse"><stop offset=".156" class="cm3jz64eh"/><stop offset="1" class="lu7jcxbxj"/></radialGradient><radialGradient id="imZArDe" cx="0" cy="0" r="1" gradientTransform="matrix(0 -5.1875 1.40625 0 15.883 6.734)" gradientUnits="userSpaceOnUse"><stop offset=".163" class="hrqvsac6m"/><stop offset="1" class="fblnbo7cb"/></radialGradient><radialGradient id="iq20X1b" cx="0" cy="0" r="1" gradientTransform="matrix(0 .39063 -.60919 0 15.054 5.593)" gradientUnits="userSpaceOnUse"><stop offset=".155" class="o5l8xobeq"/><stop offset="1" class="plhowgx4z"/></radialGradient><radialGradient id="i47wEMB" cx="0" cy="0" r="1" gradientTransform="matrix(-2.40688 -1.94794 2.96121 -3.65888 13.832 4.59)" gradientUnits="userSpaceOnUse"><stop offset=".194" class="nqgqms1jm"/><stop offset="1" class="w55-gkb2p"/></radialGradient><radialGradient id="iS0Hbcc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.20044 -.875 1.4077 -1.93129 16.099 3.078)" gradientUnits="userSpaceOnUse"><stop class="khzpeo26k"/><stop offset="1" class="xktf9pbat"/></radialGradient><radialGradient id="iB7d0ac" cx="0" cy="0" r="1" gradientTransform="matrix(.52344 .14844 -.07293 .25719 11.266 6.421)" gradientUnits="userSpaceOnUse"><stop offset=".197" class="jiuqa9mgc"/><stop offset="1" class="wyd1xpdro"/></radialGradient><radialGradient id="iCfJ8ed" cx="0" cy="0" r="1" gradientTransform="matrix(-.89062 -.21094 .5652 -2.38632 13.203 4.937)" gradientUnits="userSpaceOnUse"><stop offset=".353" class="dzmi4fing"/><stop offset=".584" class="plkel1bga"/></radialGradient><radialGradient id="i971J8d" cx="0" cy="0" r="1" gradientTransform="rotate(-163.812 6.992 1.775)scale(.75656 .36927)" gradientUnits="userSpaceOnUse"><stop offset=".17" class="o1rzobcjq"/><stop offset="1" class="v23x_cgsr"/></radialGradient><radialGradient id="in7H5KE" cx="0" cy="0" r="1" gradientTransform="matrix(-2.45369 2.93958 -5.96661 -4.98038 10.874 18.024)" gradientUnits="userSpaceOnUse"><stop offset=".434" class="oiy_54b9a"/><stop offset="1" class="rm4aiz5dn"/></radialGradient><radialGradient id="iRGvjqc" cx="0" cy="0" r="1" gradientTransform="rotate(143.616 2.466 11.358)scale(1.10629 6.64432)" gradientUnits="userSpaceOnUse"><stop offset=".043" class="v5lz4sb9o"/><stop offset="1" class="m_uy2vb_d"/></radialGradient><radialGradient id="in9pNLc" cx="0" cy="0" r="1" gradientTransform="rotate(-122.302 11.737 7.144)scale(6.08182 1.60193)" gradientUnits="userSpaceOnUse"><stop offset=".07" class="mngz2ebss"/><stop offset="1" class="ttsumpbek"/></radialGradient><radialGradient id="i4VKJFb" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.42188 -1.38588 0 11.158 16.18)" gradientUnits="userSpaceOnUse"><stop class="f3j6dkfip"/><stop offset="1" class="fxoxl0blj"/></radialGradient><radialGradient id="iWhSB9E" cx="0" cy="0" r="1" gradientTransform="matrix(-.14062 -.17969 .6458 -.50541 15.853 28.093)" gradientUnits="userSpaceOnUse"><stop class="ryq0o3qru"/><stop offset="1" class="yfqxgqb1h"/></radialGradient><radialGradient id="i5QPTke" cx="0" cy="0" r="1" gradientTransform="matrix(-6.375 -1.81248 4.6745 -16.4415 15.533 19.226)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="ex23x-brg"/><stop offset="1" class="ux4w7lb6c"/></radialGradient><radialGradient id="iIyaeue" cx="0" cy="0" r="1" gradientTransform="matrix(.09374 -1.53125 2.45635 .15037 16.985 29.445)" gradientUnits="userSpaceOnUse"><stop class="cl2mlwbhs"/><stop offset="1" class="yvuyjoqpy"/></radialGradient><radialGradient id="ilCjqTc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.0625 -.21876 .15137 -.73521 20.096 28.508)" gradientUnits="userSpaceOnUse"><stop class="m3n9jy0fh"/><stop offset="1" class="hdzwkybza"/></radialGradient><radialGradient id="i70Vnhb" cx="0" cy="0" r="1" gradientTransform="matrix(-.59376 -1.71875 .84778 -.29287 16.08 29.742)" gradientUnits="userSpaceOnUse"><stop offset=".08" class="a541b3bqx"/><stop offset="1" class="zc8ie-1dg"/></radialGradient><radialGradient id="iooA69y" cx="0" cy="0" r="1" gradientTransform="rotate(-47.125 33.067 9.024)scale(1.99789 1.10527)" gradientUnits="userSpaceOnUse"><stop class="xh_da2q2q"/><stop offset="1" class="stwbr2bhy"/></radialGradient><radialGradient id="ii4il3d" cx="0" cy="0" r="1" gradientTransform="matrix(2.34375 2.75 -.60904 .51907 15.463 12.511)" gradientUnits="userSpaceOnUse"><stop class="m6i2bq-zr"/><stop offset="1" class="rlzre8bgt"/></radialGradient><radialGradient id="itaSgAb" cx="0" cy="0" r="1" gradientTransform="rotate(176.424 9.29 8.444)scale(1.50293 1.62478)" gradientUnits="userSpaceOnUse"><stop class="p9xld1k9p"/><stop offset="1" class="udv4m93uo"/></radialGradient><radialGradient id="iUctc4d" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.57031 -1.46069 0 .84 .234)" gradientUnits="userSpaceOnUse"><stop offset=".238" class="ygdc80fko"/><stop offset="1" class="a5_lx-bnb"/></radialGradient><radialGradient id="iETpATd" cx="0" cy="0" r="1" gradientTransform="rotate(-14.821 2.856 -4.348)scale(.48867)" gradientUnits="userSpaceOnUse"><stop class="tl0sw7mkk"/><stop offset="1" class="xu259ab4x"/></radialGradient><radialGradient id="iPmd0rd" cx="0" cy="0" r="1" gradientTransform="matrix(.50415 0 0 .66877 0 .727)" gradientUnits="userSpaceOnUse"><stop class="hyb__5ivb"/><stop offset="1" class="wfraawh3t"/></radialGradient><radialGradient id="i2KXtcc" cx="0" cy="0" r="1" gradientTransform="rotate(107.896 2.291 10.351)scale(6.30507 4.4383)" gradientUnits="userSpaceOnUse"><stop offset=".446" class="pvqp1vbsj"/><stop offset="1" class="jbtp05a5b"/></radialGradient><radialGradient id="iAp8ITb" cx="0" cy="0" r="1" gradientTransform="matrix(-3.0625 2.84375 -4.8238 -5.19485 14.502 9.726)" gradientUnits="userSpaceOnUse"><stop class="v6cmgr7lo"/><stop offset="1" class="zvi2r2b9j"/></radialGradient><radialGradient id="i1AnQyU" cx="0" cy="0" r="1" gradientTransform="rotate(102.458 1.146 10)scale(2.75231 1.4881)" gradientUnits="userSpaceOnUse"><stop class="wb44sjbzz"/><stop offset="1" class="w8350jbiw"/></radialGradient><radialGradient id="iXd8u9d" cx="0" cy="0" r="1" gradientTransform="matrix(2.71802 .3081 -.16137 1.42362 11.127 8.597)" gradientUnits="userSpaceOnUse"><stop offset=".213" class="ayezflb3j"/><stop offset="1" class="ujjr06bwy"/></radialGradient><radialGradient id="izN5vbc" cx="0" cy="0" r="1" gradientTransform="rotate(90 .008 .406)scale(.90625)" gradientUnits="userSpaceOnUse"><stop offset=".256" class="x_9ov7g-b"/><stop offset="1" class="p6vh5wb5l"/></radialGradient><radialGradient id="i7Yo6Eb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.72656 -.10938 .20535 -3.24138 12.947 10.523)" gradientUnits="userSpaceOnUse"><stop offset=".235" class="ou5ot-gfg"/><stop offset="1" class="uz8jx9bci"/></radialGradient><radialGradient id="isl2iMc" cx="0" cy="0" r="1" gradientTransform="matrix(.40625 -3.15625 3.68021 .4737 10.97 11.758)" gradientUnits="userSpaceOnUse"><stop offset=".839" class="z7rq8royu"/><stop offset=".958" class="p1zm9vufc"/></radialGradient><radialGradient id="itbChTd" cx="0" cy="0" r="1" gradientTransform="matrix(-.27344 0 0 -.53125 15.35 5.62)" gradientUnits="userSpaceOnUse"><stop offset=".895" class="l0aricxam"/><stop offset="1" class="n9r91ylyy"/></radialGradient><radialGradient id="iQqCGcc" cx="0" cy="0" r="1" gradientTransform="matrix(-.25 0 0 -.54102 15.517 5.642)" gradientUnits="userSpaceOnUse"><stop class="gv3iwdbvq"/><stop offset=".813" class="ubyl24bdb"/></radialGradient><linearGradient id="ipx1pGc" x1="13.299" x2="16.161" y1="6.289" y2="6.461" gradientUnits="userSpaceOnUse"><stop class="bmcblacal"/><stop offset="1" class="d0kv1cyul"/></linearGradient><linearGradient id="ixhrK4c" x1="13.246" x2="13.133" y1="5.496" y2="5.511" gradientUnits="userSpaceOnUse"><stop class="uysgu56cq"/><stop offset="1" class="ve-3ak5rg"/></linearGradient><linearGradient id="ifiuZpe" x1="9.853" x2="7.625" y1="22.883" y2="20.939" gradientUnits="userSpaceOnUse"><stop offset=".211" class="pat1zf4-w"/><stop offset="1" class="wtea7v6lu"/></linearGradient><linearGradient id="iYa8n8d" x1="12.08" x2="12.08" y1="16.07" y2="16.414" gradientUnits="userSpaceOnUse"><stop offset=".136" class="x5p6yzbmf"/><stop offset="1" class="cnh3p8b3x"/></linearGradient><linearGradient id="i7HCu4c" x1="17.549" x2="17.463" y1="29.617" y2="29.304" gradientUnits="userSpaceOnUse"><stop class="l138bfbcs"/><stop offset="1" class="oxce79bcz"/></linearGradient><linearGradient id="iH5Lx2c" x1="15.58" x2="16.158" y1="29.992" y2="29.773" gradientUnits="userSpaceOnUse"><stop offset=".064" class="lhdz7oxfj"/><stop offset="1" class="csaq2_bel"/></linearGradient><linearGradient id="id1rZnM" x1="6.97" x2="6.377" y1="27.976" y2="28.148" gradientUnits="userSpaceOnUse"><stop class="oxg1n1wjw"/><stop offset="1" class="y0g_czb9f"/></linearGradient><linearGradient id="irT6sNe" x1="4.845" x2="5.025" y1="28.051" y2="27.902" gradientUnits="userSpaceOnUse"><stop class="p6qc3nb-j"/><stop offset="0" class="ezcqmvbni"/><stop offset="1" class="stwbr2bhy"/></linearGradient><linearGradient id="iDMDtcd" x1="17.674" x2="19.557" y1="15.535" y2="17.574" gradientUnits="userSpaceOnUse"><stop class="o52vxyscb"/><stop offset="1" class="u-867gbtx"/></linearGradient><linearGradient id="ixiClDa" x1="23.119" x2="21.869" y1="21.824" y2="22.762" gradientUnits="userSpaceOnUse"><stop class="n6l6ilaec"/><stop offset="1" class="vjqn9lx3p"/></linearGradient><linearGradient id="iJN5uxb" x1="26.783" x2="25.049" y1="28.668" y2="26.324" gradientUnits="userSpaceOnUse"><stop class="uug2ubxhk"/><stop offset="1" class="deyia0bkx"/></linearGradient><linearGradient id="iqLOmmc" x1="26.729" x2="26.37" y1="27.105" y2="27.355" gradientUnits="userSpaceOnUse"><stop class="p8mdyfi9b"/><stop offset="1" class="g6zbvk7ui"/></linearGradient><linearGradient id="imj8XHO" x1="18.26" x2="20.01" y1="16.371" y2="18.668" gradientUnits="userSpaceOnUse"><stop class="ly5_jc0cc"/><stop offset="1" class="sxo3xwbvl"/></linearGradient><linearGradient id="igwd64R" x1="18.15" x2="18.674" y1="16.433" y2="17.199" gradientUnits="userSpaceOnUse"><stop offset=".098" class="iykv72k7v"/><stop offset="1" class="qg5pcsysc"/></linearGradient><linearGradient id="i487aeb" x1="15.127" x2="14.252" y1="12.836" y2="10.445" gradientUnits="userSpaceOnUse"><stop class="h2o5q3bga"/><stop offset=".787" class="md0ucwkak"/></linearGradient><linearGradient id="ibGgDUd" x1="11.095" x2="9.986" y1="9.117" y2="12.57" gradientUnits="userSpaceOnUse"><stop offset=".118" class="fjz5hab9p"/><stop offset="1" class="ljdv6tb3r"/></linearGradient><linearGradient id="ipECBte" x1="-.007" x2=".179" y1=".05" y2=".11" gradientUnits="userSpaceOnUse"><stop class="vc--wpv5i"/><stop offset="1" class="stui2mbih"/></linearGradient><linearGradient id="iKWcXIe" x1="15.752" x2="11.127" y1="27.414" y2="17.273" gradientUnits="userSpaceOnUse"><stop class="v9kimlbms"/><stop offset="1" class="g24ahctiy"/></linearGradient><linearGradient id="iKOEAEc" x1="5.608" x2="9.918" y1="25.323" y2="19.951" gradientUnits="userSpaceOnUse"><stop class="ckhjb_bgt"/><stop offset="1" class="rnrhdzckq"/></linearGradient><linearGradient id="iAADvie" x1="12.049" x2="11.605" y1="4.923" y2="2.024" gradientUnits="userSpaceOnUse"><stop offset=".421" class="h-bh2_bpf"/><stop offset="1" class="pf-fc7btu"/></linearGradient><filter id="iey5FMc" width="4.443" height="5.249" x="11.718" y="3.348" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2" dy="-.2"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.360784 0 0 0 0 0.172549 0 0 0 0 0.12549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_2963"/></filter><filter id="iazyZHF" width="5.503" height="5.499" x="10.596" y="1.766" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.15"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.14902 0 0 0 0 0.101961 0 0 0 0 0.109804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_2963"/></filter><filter id="ircfwNc" width="8.674" height="14.771" x="3.714" y="15.461" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".75" dy="-.75"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.439216 0 0 0 0 0.388235 0 0 0 0 0.486275 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_2963"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.537255 0 0 0 0 0.423529 0 0 0 0 0.635294 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_2_2963" result="effect2_innerShadow_2_2963"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy=".25"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.529412 0 0 0 0 0.490196 0 0 0 0 0.537255 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_2_2963" result="effect3_innerShadow_2_2963"/></filter><filter id="izKHonc" width="10.972" height="14.104" x="9.472" y="15.979" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy="-.2"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.619608 0 0 0 0 0.592157 0 0 0 0 0.611765 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_2963"/></filter><filter id="iIKfaEb" width="7.179" height="6.928" x="12.696" y="10.891" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.5" dy="-.75"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.223529 0 0 0 0 0.121569 0 0 0 0 0.164706 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_2963"/></filter><filter id="iWNWQjd" width="2.607" height="2.722" x="17.067" y="15.162" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_2_2963" stdDeviation=".05"/></filter><filter id="iZ1WjEb" width="8.674" height="11.796" x="19.15" y="17.494" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.741176 0 0 0 0 0.647059 0 0 0 0 0.811765 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_2963"/></filter><filter id="iAs2dJe" width="1.68" height="1.68" x="26.709" y="28.238" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.835294 0 0 0 0 0.819608 0 0 0 0 0.835294 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_2963"/></filter><filter id="ipEngjb" width="2.726" height="3.079" x="17.741" y="15.93" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.211765 0 0 0 0 0.133333 0 0 0 0 0.27451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_2963"/></filter><filter id="iXoEGyc" width="1.093" height="1.661" x="18.729" y="15.555" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.15"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.286275 0 0 0 0 0.168627 0 0 0 0 0.160784 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_2963"/></filter><filter id="i1TtYQb" width="7.59" height="10.511" x="4.346" y="9.143" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.266667 0 0 0 0 0.156863 0 0 0 0 0.231373 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_2963"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.4" dy=".4"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.376471 0 0 0 0 0.305882 0 0 0 0 0.301961 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_2_2963" result="effect2_innerShadow_2_2963"/></filter><filter id="izmWA5b" width="5.631" height="8.6" x="4.809" y="10.544" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_2_2963" stdDeviation=".3"/></filter><filter id="iRLCxbb" width="1.013" height=".568" x="14.486" y="4.292" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0666667 0 0 0 0 0.0627451 0 0 0 0 0.0627451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_2963"/></filter><filter id="ix0O1Cb" width="6.844" height="12.891" x="10.127" y="16.101" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_2_2963" stdDeviation=".5"/></filter><filter id="i6M6Kwb" width="6.45" height="8.475" x="4.572" y="18.029" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_2_2963" stdDeviation=".375"/></filter><filter id="iYaf3fn" width="2.262" height="3.469" x="10.742" y="2.322" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_2_2963" stdDeviation=".25"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:person-with-white-cane-facing-right-dark" /></template>
<style>
.a18cgebwg {
  d: path("M15.01 18.562c-.384-1.05-.717-2.028-.774-2.383H9.494c-.1 1.375.144 1.713.773 2.422c.693.782 2.172 2.43 2.54 2.895c.35.35.5.789.554.98l2.262 7.43a.25.25 0 0 0 .315.166l3.737-1.183c.195-.061.326-.265.244-.452c-.107-.245-.332-.5-.886-.656c-.663-.187-1.943-.284-2.516-.336a912 912 0 0 0-.734-5.969c-.094-.672-.227-1.414-.774-2.914");
}

.a5_lx-bnb {
  stop-color: var(--svg-color--ccaae9, #CCAAE9);
}

.a541b3bqx {
  stop-color: var(--svg-color--515279, #515279);
}

.am9uocbqt {
  cx: 0.551px;
  cy: 0.551px;
  r: 0.551px;
}

.ao8yt0btw {
  fill: var(--svg-color--45302d, #45302D);
  fill-rule: evenodd;
  d: path("M13.787 11.747a1.05 1.05 0 0 0-.486 1.403c1.833 3.77 4.236 4.912 5.721 4.627a1.05 1.05 0 1 0-.396-2.062s-.026.004-.082 0a1.2 1.2 0 0 1-.24-.044a2.7 2.7 0 0 1-.803-.404c-.65-.457-1.494-1.354-2.31-3.035a1.05 1.05 0 0 0-1.404-.485");
}

.ayezflb3j {
  stop-color: var(--svg-color--fc8c16, #FC8C16);
}

.bmcblacal {
  stop-color: var(--svg-color--492f32, #492F32);
}

.c0d4izb9h {
  d: path("M12.302 8.597c-.89 0-1.136.215-1.433.407L9.845 11.6c-.3 1.4-.364 3.636-.359 4.578h4.766c.257-.656.677-2.675.515-4.578c-.164-1.93-1.207-2.902-2.465-3.004");
}

.ch-_hmxrc {
  d: path("M12.45 3.77a13 13 0 0 0-.277 1.52a2.9 2.9 0 0 1-.928-1.871c-.05-.498.575-.757.999-.49c.306.192.292.49.206.84");
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

.d0kv1cyul {
  stop-color: var(--svg-color--5b4542, #5B4542);
}

.d4kn2qv1f {
  stop-color: var(--svg-color--41212e, #41212E);
}

.deyia0bkx {
  stop-color: var(--svg-color--f3386a, #F3386A);
}

.dl1_whaqb {
  stroke: var(--svg-color--33241a, #33241A);
  stroke-width: var(--svg-stroke-width--0-35px, 0.35px);
  d: path("M19.514 15.988a1.211 1.211 0 1 0-.101 1.24");
}

.dzmi4fing {
  stop-color: var(--svg-color--363131, #363131);
}

.ej0rqcbmd {
  fill: var(--svg-color--280017, #280017);
  fill-rule: evenodd;
  d: path("M14.881 6.756a.125.125 0 0 0 .002.177c.238.233.582.293.692.304a.125.125 0 0 0 .025-.248c-.093-.01-.366-.062-.542-.235a.125.125 0 0 0-.177.002");
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

.fxmcdkbqm {
  d: path("M18.92 16.013a.2.2 0 0 0-.278-.045l-.818.59a.2.2 0 0 0-.045.28l1.51 2.088a.2.2 0 0 0 .279.045l.817-.59a.2.2 0 0 0 .045-.28z");
}

.fxoxl0blj {
  stop-color: var(--svg-color--8c8393, #8C8393);
  stop-opacity: 0;
}

.g24ahctiy {
  stop-color: var(--svg-color--94899e, #94899E);
  stop-opacity: 0;
}

.g6zbvk7ui {
  stop-color: var(--svg-color--f35886, #F35886);
  stop-opacity: 0;
}

.g9t63ub0s {
  stop-color: var(--svg-color--271213, #271213);
}

.gap6upynm {
  d: path("m14.627 21.18l1.343 6.5l-.359.312l-1.469-6.531l-3.015-3.875l.703-.485z");
}

.gevu3lbtd {
  d: path("m8.799 21.127l-3.476 4.428l.513.199l3.485-3.708a3 3 0 0 0 .76-1.493l.191-1l-.751-.774l-.544 1.994a1 1 0 0 1-.178.354");
}

.ghq9gsa-q {
  cx: 0.84px;
  cy: 0.84px;
  r: 0.84px;
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

.hyb__5ivb {
  stop-color: var(--svg-color--e4d4ea, #E4D4EA);
}

.iykv72k7v {
  stop-color: var(--svg-color--62516b, #62516B);
}

.jbtp05a5b {
  stop-color: var(--svg-color--d34015, #D34015);
}

.jiuqa9mgc {
  stop-color: var(--svg-color--464243, #464243);
}

.jtmedjbua {
  stop-color: var(--svg-color--614e4a, #614E4A);
  stop-opacity: 0;
}

.jvgc_-gud {
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M19.529 16.017a1.211 1.211 0 1 0-.117 1.213");
}

.kher6vnjv {
  d: path("m24.917 26.225l2.092 2.879a.45.45 0 1 0 .728-.53l-2.092-2.878z");
}

.khzpeo26k {
  stop-color: var(--svg-color--564c49, #564C49);
}

.kj46gabnl {
  d: path("m13.363 6.303l-.2-1.44a.727.727 0 0 0 .2 1.44");
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

.lu7jcxbxj {
  stop-color: var(--svg-color--34191a, #34191A);
  stop-opacity: 0;
}

.ly5_jc0cc {
  stop-color: var(--svg-color--4d3b5c, #4D3B5C);
}

.lzq15abom {
  stop-color: var(--svg-color--614e4a, #614E4A);
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

.m4b5f-bxw {
  fill: var(--svg-color--2c2929, #2C2929);
  fill-rule: evenodd;
  d: path("M15.114 4.61a.8.8 0 0 1 .217-.016a.15.15 0 1 0 .037-.298a1 1 0 0 0-.313.02a1 1 0 0 0-.408.172a.15.15 0 1 0 .178.242a.7.7 0 0 1 .29-.12");
}

.m6i2bq-zr {
  stop-color: var(--svg-color--5c4844, #5C4844);
}

.md0ucwkak {
  stop-color: var(--svg-color--ea6f3e, #EA6F3E);
}

.mngz2ebss {
  stop-color: var(--svg-color--897998, #897998);
}

.mp_6n8ltb {
  fill: var(--svg-color--462c2f, #462C2F);
  fill-rule: evenodd;
  d: path("M5.99 19.223a.614.614 0 0 0 .776-.407c1.215-3.921 3.166-6.29 4.541-7.545c.438-.4.516-1.082.129-1.53c-.347-.4-.945-.472-1.349-.129c-1.626 1.38-3.91 3.975-5.316 8.605a.59.59 0 0 0 .383.729z");
}

.myq9eabfw {
  fill: var(--svg-color--8c8393, #8C8393);
  d: path("M15.01 18.562c-.384-1.05-.717-2.028-.774-2.383H9.494c-.1 1.375.144 1.713.773 2.422c.693.782 2.172 2.43 2.54 2.895c.35.35.5.789.554.98l2.262 7.43a.25.25 0 0 0 .315.166l3.737-1.183c.195-.061.326-.265.244-.452c-.107-.245-.332-.5-.886-.656c-.663-.187-1.943-.284-2.516-.336a912 912 0 0 0-.734-5.969c-.094-.672-.227-1.414-.774-2.914");
}

.n6l6ilaec {
  stop-color: var(--svg-color--d4c6dc, #D4C6DC);
}

.n9r91ylyy {
  stop-color: var(--svg-color--824d44, #824D44);
}

.now42z6pk {
  fill-rule: evenodd;
  d: path("M19.335 17.78a.45.45 0 0 0-.1.629l7.774 10.695a.45.45 0 1 0 .728-.529L19.964 17.88a.45.45 0 0 0-.629-.1");
}

.nqgqms1jm {
  stop-color: var(--svg-color--22191d, #22191D);
}

.o1rzobcjq {
  stop-color: var(--svg-color--635251, #635251);
}

.o52vxyscb {
  stop-color: var(--svg-color--443d44, #443D44);
}

.o5l8xobeq {
  stop-color: var(--svg-color--472f2c, #472F2C);
}

.oeqsi5agv {
  fill: var(--svg-color--45437a, #45437A);
  d: path("m4.79 25.653l1.639.678l-.022.02l.108.355c.216.713.535 1.764.62 2.27c.076.462-.145.768-.352.953c-.093.083-.234.064-.318-.03l-2.687-2.995a.25.25 0 0 1 .019-.352l.985-.888z");
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

.p6qc3nb-j {
  stop-color: var(--svg-color--492d85, #492D85);
}

.p6vh5wb5l {
  stop-color: var(--svg-color--3d1f32, #3D1F32);
}

.p8mdyfi9b {
  stop-color: var(--svg-color--f35886, #F35886);
}

.p9xld1k9p {
  stop-color: var(--svg-color--453837, #453837);
}

.pat1zf4-w {
  stop-color: var(--svg-color--8b8290, #8B8290);
}

.pf-fc7btu {
  stop-color: var(--svg-color--454143, #454143);
  stop-opacity: 0;
}

.pg17md4yk {
  fill-rule: evenodd;
  d: path("M13.787 11.747a1.05 1.05 0 0 0-.486 1.403c1.833 3.77 4.236 4.912 5.721 4.627a1.05 1.05 0 1 0-.396-2.062s-.026.004-.082 0a1.2 1.2 0 0 1-.24-.044a2.7 2.7 0 0 1-.803-.404c-.65-.457-1.494-1.354-2.31-3.035a1.05 1.05 0 0 0-1.404-.485");
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

.q5mgiq5sp {
  d: path("M15.021 5.642v-.004c0-.32.137-.58.307-.58s.306.26.306.58v.004z");
}

.qg5pcsysc {
  stop-color: var(--svg-color--483a55, #483A55);
  stop-opacity: 0;
}

.qhpv1urou {
  d: path("m15.232 28.62l.391 1.286a.25.25 0 0 0 .315.166l3.737-1.183c.195-.061.326-.265.244-.452c-.107-.245-.332-.5-.886-.656c-.59-.167-1.672-.262-2.306-.317l-.21-.019v-.002z");
}

.rlzre8bgt {
  stop-color: var(--svg-color--5c4844, #5C4844);
  stop-opacity: 0;
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

.s-g161bqt {
  d: path("M16.374 5.812a1 1 0 0 1-.258-.457h-.18V6.48c.215.137.522.115.613-.09c.079-.175.02-.394-.175-.578");
}

.sa2skx9xg {
  fill: var(--svg-color--fff, #fff);
  d: path("M15.627 5.642h-.989c0-.391.222-.709.495-.709s.494.318.494.71");
}

.ss7zei8xw {
  stop-color: var(--svg-color--68534f, #68534F);
}

.ssn5ajz8v {
  d: path("m15.217 5.642l-.004-.072c0-.185.078-.336.175-.336c.098 0 .176.15.176.336l-.004.072z");
}

.stui2mbih {
  stop-color: var(--svg-color--fff, #fff);
  stop-opacity: 0;
}

.stwbr2bhy {
  stop-color: var(--svg-color--46437b, #46437B);
  stop-opacity: 0;
}

.sxdomfxyu {
  width: 0.832px;
  height: 1.669px;
  fill: var(--svg-color--594644, #594644);
  rx: 0.416px;
}

.sxo3xwbvl {
  stop-color: var(--svg-color--3f3647, #3F3647);
}

.tadbet4hb {
  d: path("M16.133 4.848c-.038-.8-.298-1.187-.42-1.3H11.98l-.063 3.164c.867 2.121 3.512 2.212 3.907 1.445s.353-2.381.308-3.309");
}

.tl0sw7mkk {
  stop-color: var(--svg-color--e9d9f5, #E9D9F5);
}

.tsuuox2ro {
  stop-color: var(--svg-color--564341, #564341);
}

.ttsumpbek {
  stop-color: var(--svg-color--897998, #897998);
  stop-opacity: 0;
}

.u-867gbtx {
  stop-color: var(--svg-color--443d44, #443D44);
  stop-opacity: 0;
}

.ubyl24bdb {
  stop-color: var(--svg-color--565352, #565352);
}

.udv4m93uo {
  stop-color: var(--svg-color--453837, #453837);
  stop-opacity: 0;
}

.ujjr06bwy {
  stop-color: var(--svg-color--fc8c16, #FC8C16);
  stop-opacity: 0;
}

.uug2ubxhk {
  stop-color: var(--svg-color--e82b8e, #E82B8E);
}

.ux4w7lb6c {
  stop-color: var(--svg-color--8c8388, #8C8388);
}

.uyi74zbuf {
  d: path("m8.658 19.945l.89-3.734h1.781c.053.614.152 2.215.29 3.515s-.492 2.032-.766 2.313L6.408 26.35c.198.662.627 2.025.727 2.625c.077.462-.145.768-.351.953c-.094.083-.235.064-.319-.03l-2.687-2.995a.25.25 0 0 1 .019-.352l.986-.888c1.041-1.365 3.19-4.194 3.453-4.594c.181-.276.39-.917.422-1.125");
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

.v31hj0bvo {
  d: path("m4.79 25.653l1.639.678l-.022.02l.108.355c.216.713.535 1.764.62 2.27c.076.462-.145.768-.352.953c-.093.083-.234.064-.318-.03l-2.687-2.995a.25.25 0 0 1 .019-.352l.985-.888z");
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

.ve46_g1lk {
  d: path("M15.983 2.496a1.025 1.025 0 0 0-.985-.578c-.86.046-.976.343-1.754.183c-.821-.169-1.226-.12-1.578.04l-.007.002c-.346.158-1.063.484-1.063 1.95c0 1.352.482 2.066.715 2.32l-.046.017c-.232.084-.327.33-.244.562c.072.197.322.311.637.262c.36-.057.625-.106.832-.147a.25.25 0 0 0 .2-.245V5.75c0-.47.33-.749.476-.832c.016-.485.164-.707.406-.825c.401-.194.526-.098 1.485-.156c.965-.058 1.222-.832.925-1.441");
}

.vjqn9lx3p {
  stop-color: var(--svg-color--cdb4e3, #CDB4E3);
}

.w55-gkb2p {
  stop-color: var(--svg-color--342d30, #342D30);
}

.w8350jbiw {
  stop-color: var(--svg-color--dd3e06, #DD3E06);
  stop-opacity: 0;
}

.wb44sjbzz {
  stop-color: var(--svg-color--dd3e06, #DD3E06);
}

.wfraawh3t {
  stop-color: var(--svg-color--e4d4ea, #E4D4EA);
  stop-opacity: 0;
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

.xu259ab4x {
  stop-color: var(--svg-color--e9d9f5, #E9D9F5);
  stop-opacity: 0;
}

.y0g_czb9f {
  stop-color: var(--svg-color--5a577e, #5A577E);
  stop-opacity: 0;
}

.y3bhiibho {
  d: path("M14.611 10.5c-.281-.713-.773-1.224-.984-1.39l.039 4.468l1.785-.836c-.277-.524-.488-1.352-.84-2.242");
}

.yfqxgqb1h {
  stop-color: var(--svg-color--a19da6, #A19DA6);
  stop-opacity: 0;
}

.ygdc80fko {
  stop-color: var(--svg-color--d8cbdd, #D8CBDD);
}

.yvuyjoqpy {
  stop-color: var(--svg-color--47456f, #47456F);
}

.z7rq8royu {
  stop-color: var(--svg-color--f07f0f, #F07F0F);
  stop-opacity: 0;
}

.z8jy9-b3h {
  d: path("M0 0h1.946v3.44H0z");
}

.zc8ie-1dg {
  stop-color: var(--svg-color--515279, #515279);
  stop-opacity: 0;
}

.zhp7rumpf {
  d: path("M12.438 11.203a1.355 1.355 0 1 0-1.729-2.088c-.95.692-1.79 1.592-2.27 2.135l2.04 1.914c.307-.32 1.381-1.393 1.959-1.96");
}

.zur60-b5i {
  stroke: var(--svg-color--604e4d, #604E4D);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M9.64 11.344c-.895.76-2.956 3.225-4.03 7");
}

.zvi2r2b9j {
  stop-color: var(--svg-color--f08337, #F08337);
  stop-opacity: 0;
}

</style>
