<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#ioQbO7c)"><path clip-rule="evenodd" class="zzo0wlbgq"/><path fill="url(#i8pNPZc)" clip-rule="evenodd" class="t14t_4xor"/><path fill="url(#iwXZFic)" clip-rule="evenodd" class="t14t_4xor"/></g><path class="ehbronbiy"/><g filter="url(#iUjzNse)"><path stroke="url(#itWZufc)" class="n_kc0dbfx"/></g><g filter="url(#ih1tJcr)"><path fill="url(#iNiKYUb)" clip-rule="evenodd" class="yprzcmb3x"/></g><path fill="url(#iriqPGc)" class="bqm4v1b4g"/><path fill="url(#iH0GsBe)" class="bqm4v1b4g"/><g filter="url(#iSXdkxR)"><circle fill="url(#iUctc4d)" transform="matrix(-1 0 0 1 28.397 28.308)" class="ghq9gsa-q"/><circle fill="url(#iETpATd)" transform="matrix(-1 0 0 1 28.397 28.308)" class="ghq9gsa-q"/><circle fill="url(#iPmd0rd)" transform="matrix(-1 0 0 1 28.397 28.308)" class="ghq9gsa-q"/></g><g filter="url(#icGyKxP)"><path fill="url(#isHL9Oc)" class="tm-z33jrn"/><path fill="url(#idwAJBd)" class="tm-z33jrn"/></g><g filter="url(#ivrOPlg)"><rect transform="scale(-1 1)rotate(-7.657 107.238 156.392)" class="zel2068zd"/></g><path fill="url(#iPbDBid)" class="hzb6zjbxx"/><path fill="url(#i7MrvSc)" transform="scale(-1 1)rotate(-4.337 82.128 185.618)" class="z8jy9-b3h"/><path fill="url(#io7udiX)" transform="scale(-1 1)rotate(-4.337 82.128 185.618)" class="z8jy9-b3h"/><path fill="url(#iel5u4c)" transform="scale(-1 1)rotate(-4.337 82.128 185.618)" class="z8jy9-b3h"/><path fill="url(#iNvXt5h)" class="jb4e9iyvc"/><path fill="url(#i8201vA)" class="jb4e9iyvc"/><g filter="url(#iz7VLzd)"><path fill="url(#icU2vne)" class="ui5e3_88b"/><path fill="url(#ibyTzDb)" class="ui5e3_88b"/><path fill="url(#i9FVifD)" class="ui5e3_88b"/><path fill="url(#iLcVp5c)" class="ui5e3_88b"/></g><g filter="url(#iTXH1Ae)"><path fill="url(#iITXlqb)" class="gm4mrvjmb"/><path fill="url(#iH9AYjx)" class="gm4mrvjmb"/><path fill="url(#icvannH)" class="gm4mrvjmb"/><path fill="url(#iWCT9bc)" class="gm4mrvjmb"/></g><path fill="url(#inQkcLL)" class="r8__hjblf"/><path fill="url(#iA15Kid)" class="r8__hjblf"/><path fill="url(#iz18Z2C)" class="r8__hjblf"/><g filter="url(#ifL7kXc)"><path fill="url(#ig3bnQe)" class="q9foblbae"/><path fill="url(#isypUoc)" class="q9foblbae"/><path fill="url(#iVaEyjc)" class="q9foblbae"/></g><g filter="url(#i7hTq6f)"><path class="jldwtub7g"/><path fill="url(#inCctbe)" class="asrjd_b-f"/><path fill="url(#iMGoCVc)" class="asrjd_b-f"/><path fill="url(#iKeWFOd)" class="asrjd_b-f"/><path fill="url(#it8Pa4x)" class="asrjd_b-f"/><path fill="url(#iMzNOTd)" class="asrjd_b-f"/></g><path fill="url(#iehu5oc)" class="gzvhcfnta"/><path fill="url(#iUMToHc)" class="gzvhcfnta"/><path fill="url(#i9ilCTd)" class="gzvhcfnta"/><path fill="url(#ibhkUOe)" class="gzvhcfnta"/><path fill="url(#ivxhY5l)" class="gzvhcfnta"/><path class="p59n7-b7i"/><path fill="url(#iC8zA6b)" class="fwhc4b_kd"/><path fill="url(#i0OK93c)" class="fwhc4b_kd"/><path fill="url(#ioI5XVn)" class="fwhc4b_kd"/><path fill="url(#iPbDBid)" class="hzb6zjbxx"/><path fill="url(#i6KWPYn)" class="ix422bc1r"/><path fill="url(#ihVFJsd)" class="ix422bc1r"/><path fill="url(#iU9FEpe)" class="ix422bc1r"/><path fill="url(#iLq3Kee)" class="ix422bc1r"/><circle fill="url(#iBmeYYs)" transform="matrix(-1 0 0 1 7.439 17.476)" class="am9uocbqt"/><g filter="url(#iAM8bCb)"><path clip-rule="evenodd" class="a9zgymbwq"/></g><g filter="url(#iPtTEkL)"><path class="b2bbif3tu"/></g><path fill="url(#iYZD4Je)" class="gsb47ubvc"/><path fill="url(#iVpkvXd)" class="gsb47ubvc"/><path fill="url(#i1fFZMd)" class="gsb47ubvc"/><path clip-rule="evenodd" class="t34we7evd"/><g filter="url(#ir2wVKb)"><path clip-rule="evenodd" class="wuoo7gb0s"/></g><path class="ysioi4b-l"/><path fill="url(#irlTKod)" class="w7a5_abxd"/><path fill="url(#ifPFfWc)" class="h433dobwy"/><ellipse fill="url(#ipECBte)" transform="scale(-1 1)rotate(24.61 -19.616 -32.86)" class="m1l7k9jve"/><g filter="url(#itFAEdd)"><path fill="url(#ituA9vb)" class="bdzya463y"/></g><g filter="url(#iF2XA8F)"><path fill="url(#iuMU75c)" class="zqaf4jb2g"/></g><g filter="url(#i6MRevc)"><path fill="url(#iZlRwSc)" class="pz20zvult"/></g><defs><radialGradient id="i8pNPZc" cx="0" cy="0" r="1" gradientTransform="matrix(2.34375 2.75 -.60904 .51907 15.471 12.582)" gradientUnits="userSpaceOnUse"><stop class="p8cjc8bgx"/><stop offset="1" class="o7s7rsbjo"/></radialGradient><radialGradient id="iwXZFic" cx="0" cy="0" r="1" gradientTransform="rotate(176.424 9.293 8.48)scale(1.50293 1.62478)" gradientUnits="userSpaceOnUse"><stop class="ppddtcccf"/><stop offset="1" class="ircb6-b3r"/></radialGradient><radialGradient id="iUctc4d" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.57031 -1.46069 0 .84 .234)" gradientUnits="userSpaceOnUse"><stop offset=".238" class="ygdc80fko"/><stop offset="1" class="a5_lx-bnb"/></radialGradient><radialGradient id="iETpATd" cx="0" cy="0" r="1" gradientTransform="rotate(-14.821 2.856 -4.348)scale(.48867)" gradientUnits="userSpaceOnUse"><stop class="tl0sw7mkk"/><stop offset="1" class="xu259ab4x"/></radialGradient><radialGradient id="iPmd0rd" cx="0" cy="0" r="1" gradientTransform="matrix(.50415 0 0 .66877 0 .727)" gradientUnits="userSpaceOnUse"><stop class="hyb__5ivb"/><stop offset="1" class="wfraawh3t"/></radialGradient><radialGradient id="i7MrvSc" cx="0" cy="0" r="1" gradientTransform="matrix(-.05152 -2.21336 1.59858 -.0372 1.708 2.01)" gradientUnits="userSpaceOnUse"><stop offset=".116" class="u598_4blb"/><stop offset="1" class="poxe0lb6u"/></radialGradient><radialGradient id="io7udiX" cx="0" cy="0" r="1" gradientTransform="matrix(-.53617 .66448 -.89991 -.72614 2.062 .438)" gradientUnits="userSpaceOnUse"><stop class="w1ctt_hwm"/><stop offset="1" class="c6t644beu"/></radialGradient><radialGradient id="iel5u4c" cx="0" cy="0" r="1" gradientTransform="matrix(.01105 -.86884 .23985 .00305 .214 2.413)" gradientUnits="userSpaceOnUse"><stop class="mvum_2bof"/><stop offset="1" class="e7u9e_b9n"/></radialGradient><radialGradient id="iNvXt5h" cx="0" cy="0" r="1" gradientTransform="rotate(151.587 7.53 5.232)scale(.54183 .76481)" gradientUnits="userSpaceOnUse"><stop offset=".101" class="hymklqb8k"/><stop offset=".684" class="s2f2c_bct"/></radialGradient><radialGradient id="i8201vA" cx="0" cy="0" r="1" gradientTransform="matrix(.12006 -.29152 .4375 .18018 16.238 6.567)" gradientUnits="userSpaceOnUse"><stop class="zkj259b3a"/><stop offset="1" class="iv0p50s_n"/></radialGradient><radialGradient id="ibyTzDb" cx="0" cy="0" r="1" gradientTransform="matrix(.84375 -.04687 .05715 1.0287 12.978 5.547)" gradientUnits="userSpaceOnUse"><stop offset=".156" class="l7mbhnbzh"/><stop offset="1" class="biuc-6bfh"/></radialGradient><radialGradient id="i9FVifD" cx="0" cy="0" r="1" gradientTransform="matrix(0 -5.1875 2.01562 0 15.874 6.734)" gradientUnits="userSpaceOnUse"><stop offset=".219" class="wcectbccf"/><stop offset="1" class="b3jcjo1jv"/></radialGradient><radialGradient id="iLcVp5c" cx="0" cy="0" r="1" gradientTransform="matrix(0 .39063 -.60919 0 15.046 5.593)" gradientUnits="userSpaceOnUse"><stop offset=".155" class="ie_w39bfj"/><stop offset="1" class="dx40lk_kc"/></radialGradient><radialGradient id="iITXlqb" cx="0" cy="0" r="1" gradientTransform="matrix(-2.40688 -1.94794 2.96121 -3.65888 13.823 4.59)" gradientUnits="userSpaceOnUse"><stop offset=".194" class="nqgqms1jm"/><stop offset="1" class="w55-gkb2p"/></radialGradient><radialGradient id="iH9AYjx" cx="0" cy="0" r="1" gradientTransform="matrix(-1.20044 -.875 1.4077 -1.93129 16.09 3.078)" gradientUnits="userSpaceOnUse"><stop class="khzpeo26k"/><stop offset="1" class="xktf9pbat"/></radialGradient><radialGradient id="icvannH" cx="0" cy="0" r="1" gradientTransform="matrix(.52344 .14844 -.07293 .25719 11.257 6.421)" gradientUnits="userSpaceOnUse"><stop offset=".197" class="jiuqa9mgc"/><stop offset="1" class="wyd1xpdro"/></radialGradient><radialGradient id="iWCT9bc" cx="0" cy="0" r="1" gradientTransform="matrix(-.89062 -.21094 .5652 -2.38632 13.194 4.937)" gradientUnits="userSpaceOnUse"><stop offset=".353" class="dzmi4fing"/><stop offset=".584" class="plkel1bga"/></radialGradient><radialGradient id="inQkcLL" cx="0" cy="0" r="1" gradientTransform="rotate(-163.812 6.987 1.776)scale(.75656 .36927)" gradientUnits="userSpaceOnUse"><stop offset=".17" class="i8aj4_5_r"/><stop offset="1" class="u2yjj3mld"/></radialGradient><radialGradient id="iA15Kid" cx="0" cy="0" r="1" gradientTransform="rotate(100.843 4.466 8.008)scale(1.20119 1.25169)" gradientUnits="userSpaceOnUse"><stop offset=".556" class="chiqx4b_a"/><stop offset="1" class="vmk6x9_kg"/><stop offset="1" class="hq1ekobkc"/></radialGradient><radialGradient id="isypUoc" cx="0" cy="0" r="1" gradientTransform="matrix(-2.45369 2.93958 -5.96661 -4.98038 10.865 18.024)" gradientUnits="userSpaceOnUse"><stop offset=".434" class="oiy_54b9a"/><stop offset="1" class="rm4aiz5dn"/></radialGradient><radialGradient id="iVaEyjc" cx="0" cy="0" r="1" gradientTransform="rotate(143.616 2.462 11.357)scale(1.10629 6.64432)" gradientUnits="userSpaceOnUse"><stop offset=".043" class="v5lz4sb9o"/><stop offset="1" class="m_uy2vb_d"/></radialGradient><radialGradient id="inCctbe" cx="0" cy="0" r="1" gradientTransform="rotate(-122.302 11.733 7.147)scale(6.08182 1.60193)" gradientUnits="userSpaceOnUse"><stop offset=".07" class="mngz2ebss"/><stop offset="1" class="ttsumpbek"/></radialGradient><radialGradient id="iMGoCVc" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.42188 -1.38588 0 11.15 16.18)" gradientUnits="userSpaceOnUse"><stop class="f3j6dkfip"/><stop offset="1" class="fxoxl0blj"/></radialGradient><radialGradient id="it8Pa4x" cx="0" cy="0" r="1" gradientTransform="matrix(-.14062 -.17969 .6458 -.50541 15.845 28.093)" gradientUnits="userSpaceOnUse"><stop class="ryq0o3qru"/><stop offset="1" class="yfqxgqb1h"/></radialGradient><radialGradient id="iMzNOTd" cx="0" cy="0" r="1" gradientTransform="matrix(-6.375 -1.81248 4.6745 -16.4415 15.524 19.226)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="ex23x-brg"/><stop offset="1" class="ux4w7lb6c"/></radialGradient><radialGradient id="iehu5oc" cx="0" cy="0" r="1" gradientTransform="matrix(.09374 -1.53125 2.45635 .15037 16.978 29.445)" gradientUnits="userSpaceOnUse"><stop class="cl2mlwbhs"/><stop offset="1" class="yvuyjoqpy"/></radialGradient><radialGradient id="iUMToHc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.0625 -.21876 .15137 -.73521 20.087 28.508)" gradientUnits="userSpaceOnUse"><stop class="m3n9jy0fh"/><stop offset="1" class="hdzwkybza"/></radialGradient><radialGradient id="i9ilCTd" cx="0" cy="0" r="1" gradientTransform="matrix(-.59376 -1.71875 .84778 -.29287 16.071 29.742)" gradientUnits="userSpaceOnUse"><stop offset=".08" class="a541b3bqx"/><stop offset="1" class="zc8ie-1dg"/></radialGradient><radialGradient id="ioI5XVn" cx="0" cy="0" r="1" gradientTransform="rotate(-47.125 33.063 9.034)scale(1.99789 1.10527)" gradientUnits="userSpaceOnUse"><stop class="xh_da2q2q"/><stop offset="1" class="stwbr2bhy"/></radialGradient><radialGradient id="i6KWPYn" cx="0" cy="0" r="1" gradientTransform="rotate(107.896 2.287 10.348)scale(6.30507 4.4383)" gradientUnits="userSpaceOnUse"><stop offset=".446" class="pvqp1vbsj"/><stop offset="1" class="jbtp05a5b"/></radialGradient><radialGradient id="ihVFJsd" cx="0" cy="0" r="1" gradientTransform="matrix(-3.0625 2.84375 -4.8238 -5.19485 14.493 9.726)" gradientUnits="userSpaceOnUse"><stop class="v6cmgr7lo"/><stop offset="1" class="zvi2r2b9j"/></radialGradient><radialGradient id="iU9FEpe" cx="0" cy="0" r="1" gradientTransform="rotate(102.458 1.142 9.997)scale(2.75231 1.4881)" gradientUnits="userSpaceOnUse"><stop class="wb44sjbzz"/><stop offset="1" class="w8350jbiw"/></radialGradient><radialGradient id="iLq3Kee" cx="0" cy="0" r="1" gradientTransform="matrix(2.71802 .3081 -.16137 1.42362 11.118 8.597)" gradientUnits="userSpaceOnUse"><stop offset=".213" class="ayezflb3j"/><stop offset="1" class="ujjr06bwy"/></radialGradient><radialGradient id="iBmeYYs" cx="0" cy="0" r="1" gradientTransform="rotate(90 .008 .406)scale(.90625)" gradientUnits="userSpaceOnUse"><stop offset=".256" class="qf2lyobnm"/><stop offset="1" class="l21zq2bsp"/></radialGradient><radialGradient id="iVpkvXd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.72656 -.10938 .20535 -3.24138 12.939 10.523)" gradientUnits="userSpaceOnUse"><stop offset=".235" class="ou5ot-gfg"/><stop offset="1" class="uz8jx9bci"/></radialGradient><radialGradient id="i1fFZMd" cx="0" cy="0" r="1" gradientTransform="matrix(.40625 -3.15625 3.68021 .4737 10.962 11.758)" gradientUnits="userSpaceOnUse"><stop offset=".839" class="z7rq8royu"/><stop offset=".958" class="p1zm9vufc"/></radialGradient><radialGradient id="irlTKod" cx="0" cy="0" r="1" gradientTransform="matrix(-.27344 0 0 -.53125 15.34 5.62)" gradientUnits="userSpaceOnUse"><stop offset=".895" class="l0aricxam"/><stop offset="1" class="n9r91ylyy"/></radialGradient><radialGradient id="ifPFfWc" cx="0" cy="0" r="1" gradientTransform="matrix(-.25 0 0 -.54102 15.509 5.642)" gradientUnits="userSpaceOnUse"><stop class="gv3iwdbvq"/><stop offset=".813" class="ubyl24bdb"/></radialGradient><linearGradient id="itWZufc" x1="17.682" x2="19.565" y1="15.605" y2="17.644" gradientUnits="userSpaceOnUse"><stop class="o52vxyscb"/><stop offset="1" class="u-867gbtx"/></linearGradient><linearGradient id="iNiKYUb" x1="23.128" x2="21.878" y1="21.894" y2="22.832" gradientUnits="userSpaceOnUse"><stop class="n6l6ilaec"/><stop offset="1" class="vjqn9lx3p"/></linearGradient><linearGradient id="iriqPGc" x1="26.792" x2="25.057" y1="28.738" y2="26.394" gradientUnits="userSpaceOnUse"><stop class="uug2ubxhk"/><stop offset="1" class="deyia0bkx"/></linearGradient><linearGradient id="iH0GsBe" x1="26.737" x2="26.378" y1="27.175" y2="27.425" gradientUnits="userSpaceOnUse"><stop class="p8mdyfi9b"/><stop offset="1" class="g6zbvk7ui"/></linearGradient><linearGradient id="isHL9Oc" x1="18.268" x2="20.018" y1="16.441" y2="18.738" gradientUnits="userSpaceOnUse"><stop class="ly5_jc0cc"/><stop offset="1" class="sxo3xwbvl"/></linearGradient><linearGradient id="idwAJBd" x1="18.159" x2="18.682" y1="16.503" y2="17.269" gradientUnits="userSpaceOnUse"><stop offset=".098" class="iykv72k7v"/><stop offset="1" class="qg5pcsysc"/></linearGradient><linearGradient id="iPbDBid" x1="15.118" x2="14.243" y1="12.836" y2="10.445" gradientUnits="userSpaceOnUse"><stop class="h2o5q3bga"/><stop offset=".787" class="md0ucwkak"/></linearGradient><linearGradient id="icU2vne" x1="13.29" x2="16.152" y1="6.289" y2="6.461" gradientUnits="userSpaceOnUse"><stop class="dxjajos_o"/><stop offset="1" class="gu4uskbqq"/></linearGradient><linearGradient id="iz18Z2C" x1="13.257" x2="13.108" y1="5.498" y2="5.51" gradientUnits="userSpaceOnUse"><stop class="o01zddb6n"/><stop offset="1" class="h5b83fbqu"/></linearGradient><linearGradient id="ig3bnQe" x1="9.845" x2="7.616" y1="22.883" y2="20.939" gradientUnits="userSpaceOnUse"><stop offset=".211" class="pat1zf4-w"/><stop offset="1" class="wtea7v6lu"/></linearGradient><linearGradient id="iKeWFOd" x1="12.071" x2="12.071" y1="16.07" y2="16.414" gradientUnits="userSpaceOnUse"><stop offset=".136" class="x5p6yzbmf"/><stop offset="1" class="cnh3p8b3x"/></linearGradient><linearGradient id="ibhkUOe" x1="17.54" x2="17.454" y1="29.617" y2="29.305" gradientUnits="userSpaceOnUse"><stop class="l138bfbcs"/><stop offset="1" class="oxce79bcz"/></linearGradient><linearGradient id="ivxhY5l" x1="15.571" x2="16.149" y1="29.992" y2="29.773" gradientUnits="userSpaceOnUse"><stop offset=".064" class="lhdz7oxfj"/><stop offset="1" class="csaq2_bel"/></linearGradient><linearGradient id="iC8zA6b" x1="6.962" x2="6.368" y1="27.976" y2="28.148" gradientUnits="userSpaceOnUse"><stop class="oxg1n1wjw"/><stop offset="1" class="y0g_czb9f"/></linearGradient><linearGradient id="i0OK93c" x1="4.837" x2="5.017" y1="28.051" y2="27.902" gradientUnits="userSpaceOnUse"><stop class="p6qc3nb-j"/><stop offset="0" class="ezcqmvbni"/><stop offset="1" class="stwbr2bhy"/></linearGradient><linearGradient id="iYZD4Je" x1="11.087" x2="9.978" y1="9.117" y2="12.57" gradientUnits="userSpaceOnUse"><stop offset=".118" class="fjz5hab9p"/><stop offset="1" class="ljdv6tb3r"/></linearGradient><linearGradient id="ipECBte" x1="-.007" x2=".179" y1=".05" y2=".11" gradientUnits="userSpaceOnUse"><stop class="vc--wpv5i"/><stop offset="1" class="stui2mbih"/></linearGradient><linearGradient id="ituA9vb" x1="15.743" x2="11.118" y1="27.414" y2="17.273" gradientUnits="userSpaceOnUse"><stop class="v9kimlbms"/><stop offset="1" class="g24ahctiy"/></linearGradient><linearGradient id="iuMU75c" x1="5.599" x2="9.91" y1="25.323" y2="19.951" gradientUnits="userSpaceOnUse"><stop class="ckhjb_bgt"/><stop offset="1" class="rnrhdzckq"/></linearGradient><linearGradient id="iZlRwSc" x1="12.041" x2="11.596" y1="4.923" y2="2.024" gradientUnits="userSpaceOnUse"><stop offset=".421" class="h-bh2_bpf"/><stop offset="1" class="pf-fc7btu"/></linearGradient><filter id="ioQbO7c" width="7.179" height="6.928" x="12.704" y="10.961" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.5" dy="-.75"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.760784 0 0 0 0 0.501961 0 0 0 0 0.513726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_3369"/></filter><filter id="iUjzNse" width="2.607" height="2.722" x="17.075" y="15.232" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_2_3369" stdDeviation=".05"/></filter><filter id="ih1tJcr" width="8.674" height="11.796" x="19.158" y="17.564" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.741176 0 0 0 0 0.647059 0 0 0 0 0.811765 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_3369"/></filter><filter id="iSXdkxR" width="1.68" height="1.68" x="26.718" y="28.308" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.835294 0 0 0 0 0.819608 0 0 0 0 0.835294 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_3369"/></filter><filter id="icGyKxP" width="2.726" height="3.079" x="17.75" y="16" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.211765 0 0 0 0 0.133333 0 0 0 0 0.27451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_3369"/></filter><filter id="ivrOPlg" width="1.093" height="1.661" x="18.738" y="15.625" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.15"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.858824 0 0 0 0 0.639216 0 0 0 0 0.592157 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_3369"/></filter><filter id="iz7VLzd" width="4.443" height="5.249" x="11.71" y="3.348" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2" dy="-.2"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.913725 0 0 0 0 0.611765 0 0 0 0 0.545098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_3369"/></filter><filter id="iTXH1Ae" width="5.503" height="5.499" x="10.587" y="1.766" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.15"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.14902 0 0 0 0 0.101961 0 0 0 0 0.109804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_3369"/></filter><filter id="ifL7kXc" width="8.674" height="14.771" x="3.706" y="15.461" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".75" dy="-.75"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.439216 0 0 0 0 0.388235 0 0 0 0 0.486275 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_3369"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.537255 0 0 0 0 0.423529 0 0 0 0 0.635294 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_2_3369" result="effect2_innerShadow_2_3369"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy=".25"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.529412 0 0 0 0 0.490196 0 0 0 0 0.537255 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_2_3369" result="effect3_innerShadow_2_3369"/></filter><filter id="i7hTq6f" width="10.972" height="14.104" x="9.464" y="15.979" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy="-.2"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.619608 0 0 0 0 0.592157 0 0 0 0 0.611765 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_3369"/></filter><filter id="iAM8bCb" width="7.59" height="10.511" x="4.337" y="9.143" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.909804 0 0 0 0 0.678431 0 0 0 0 0.639216 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_3369"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.4" dy=".4"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.980392 0 0 0 0 0.807843 0 0 0 0 0.713726 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_2_3369" result="effect2_innerShadow_2_3369"/></filter><filter id="iPtTEkL" width="5.631" height="8.6" x="4.801" y="10.544" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_2_3369" stdDeviation=".3"/></filter><filter id="ir2wVKb" width="1.013" height=".568" x="14.478" y="4.292" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0705882 0 0 0 0 0.0588235 0 0 0 0 0.054902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_3369"/></filter><filter id="itFAEdd" width="6.844" height="12.891" x="10.118" y="16.101" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_2_3369" stdDeviation=".5"/></filter><filter id="iF2XA8F" width="6.45" height="8.475" x="4.564" y="18.029" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_2_3369" stdDeviation=".375"/></filter><filter id="i6MRevc" width="2.262" height="3.469" x="10.733" y="2.322" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_2_3369" stdDeviation=".25"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:person-with-white-cane-facing-right-light" /></template>
<style>
.a5_lx-bnb {
  stop-color: var(--svg-color--ccaae9, #CCAAE9);
}

.a541b3bqx {
  stop-color: var(--svg-color--515279, #515279);
}

.a9zgymbwq {
  fill: var(--svg-color--f0b6a6, #F0B6A6);
  fill-rule: evenodd;
  d: path("M5.981 19.223a.614.614 0 0 0 .776-.407c1.215-3.921 3.166-6.29 4.542-7.545c.438-.4.516-1.082.128-1.53c-.346-.4-.944-.472-1.348-.129c-1.626 1.38-3.91 3.975-5.317 8.605a.59.59 0 0 0 .383.729z");
}

.am9uocbqt {
  cx: 0.551px;
  cy: 0.551px;
  r: 0.551px;
}

.asrjd_b-f {
  d: path("M15.001 18.562c-.383-1.05-.716-2.028-.773-2.383H9.485c-.1 1.375.145 1.713.774 2.422c.693.782 2.172 2.43 2.539 2.895c.35.35.5.789.555.98l2.262 7.43a.25.25 0 0 0 .315.166l3.737-1.183c.195-.061.326-.265.244-.452c-.107-.245-.333-.5-.886-.656c-.663-.187-1.943-.284-2.516-.336a941 941 0 0 0-.734-5.969c-.094-.672-.227-1.414-.774-2.914");
}

.ayezflb3j {
  stop-color: var(--svg-color--fc8c16, #FC8C16);
}

.b2bbif3tu {
  stroke: var(--svg-color--ffd0bb, #FFD0BB);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M9.632 11.344c-.896.76-2.956 3.225-4.031 7");
}

.b3jcjo1jv {
  stop-color: var(--svg-color--ffcdb7, #FFCDB7);
  stop-opacity: 0;
}

.bdzya463y {
  d: path("m14.618 21.18l1.344 6.5l-.36.312l-1.468-6.531l-3.016-3.875l.703-.485z");
}

.biuc-6bfh {
  stop-color: var(--svg-color--eeb298, #EEB298);
  stop-opacity: 0;
}

.bqm4v1b4g {
  d: path("m24.925 26.296l2.093 2.878a.45.45 0 1 0 .728-.529l-2.092-2.878z");
}

.c6t644beu {
  stop-color: var(--svg-color--e0a489, #E0A489);
  stop-opacity: 0;
}

.chiqx4b_a {
  stop-color: var(--svg-color--e7a792, #E7A792);
  stop-opacity: 0;
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

.deyia0bkx {
  stop-color: var(--svg-color--f3386a, #F3386A);
}

.dx40lk_kc {
  stop-color: var(--svg-color--fabfa4, #FABFA4);
  stop-opacity: 0;
}

.dxjajos_o {
  stop-color: var(--svg-color--f0b5a2, #F0B5A2);
}

.dzmi4fing {
  stop-color: var(--svg-color--363131, #363131);
}

.e7u9e_b9n {
  stop-color: var(--svg-color--f0a48b, #F0A48B);
  stop-opacity: 0;
}

.ehbronbiy {
  stroke: var(--svg-color--33241a, #33241A);
  stroke-width: var(--svg-stroke-width--0-35px, 0.35px);
  d: path("M19.523 16.058a1.21 1.21 0 1 0-.102 1.24");
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

.fjz5hab9p {
  stop-color: var(--svg-color--f67e18, #F67E18);
}

.ft5dv1b6b {
  fill: none;
}

.fwhc4b_kd {
  d: path("m4.783 25.653l1.637.678l-.02.02l.106.355c.217.713.536 1.764.62 2.27c.077.462-.145.768-.35.953c-.094.083-.236.064-.32-.03L3.77 26.905a.25.25 0 0 1 .02-.352l.985-.888z");
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

.ghq9gsa-q {
  cx: 0.84px;
  cy: 0.84px;
  r: 0.84px;
}

.gm4mrvjmb {
  d: path("M15.974 2.496a1.025 1.025 0 0 0-.985-.578c-.859.046-.976.343-1.754.183c-.821-.169-1.226-.12-1.577.04l-.008.002c-.346.158-1.063.484-1.063 1.95c0 1.352.482 2.066.715 2.32l-.046.017c-.231.084-.327.33-.243.562c.071.197.321.311.636.262c.36-.057.625-.106.832-.147a.25.25 0 0 0 .2-.245V5.75c0-.47.33-.749.476-.832c.016-.485.164-.707.407-.825c.4-.194.525-.098 1.484-.156c.965-.058 1.223-.832.926-1.441");
}

.gsb47ubvc {
  d: path("M12.43 11.203a1.355 1.355 0 1 0-1.73-2.088c-.951.692-1.79 1.592-2.27 2.135l2.039 1.914c.308-.32 1.382-1.393 1.96-1.96");
}

.gu4uskbqq {
  stop-color: var(--svg-color--fac1a8, #FAC1A8);
}

.gv3iwdbvq {
  stop-color: var(--svg-color--666361, #666361);
}

.gzvhcfnta {
  d: path("m15.224 28.621l.391 1.286a.25.25 0 0 0 .315.165l3.737-1.183c.195-.061.326-.265.244-.452c-.107-.245-.333-.5-.886-.656c-.591-.167-1.673-.262-2.306-.317l-.21-.019v-.001z");
}

.h-bh2_bpf {
  stop-color: var(--svg-color--454143, #454143);
}

.h2o5q3bga {
  stop-color: var(--svg-color--f3563a, #F3563A);
}

.h433dobwy {
  d: path("m15.208 5.642l-.004-.072c0-.185.079-.336.176-.336s.176.15.176.336l-.004.072z");
}

.h5b83fbqu {
  stop-color: var(--svg-color--f4bca5, #F4BCA5);
  stop-opacity: 0;
}

.hdzwkybza {
  stop-color: var(--svg-color--63617e, #63617E);
  stop-opacity: 0;
}

.hq1ekobkc {
  stop-color: var(--svg-color--e7a792, #E7A792);
}

.hyb__5ivb {
  stop-color: var(--svg-color--e4d4ea, #E4D4EA);
}

.hymklqb8k {
  stop-color: var(--svg-color--ffd4b7, #FFD4B7);
}

.hzb6zjbxx {
  d: path("M14.603 10.5c-.282-.713-.774-1.224-.985-1.39l.04 4.468l1.785-.836c-.278-.524-.489-1.352-.84-2.242");
}

.i8aj4_5_r {
  stop-color: var(--svg-color--fac7b1, #FAC7B1);
}

.ie_w39bfj {
  stop-color: var(--svg-color--fabfa4, #FABFA4);
}

.ircb6-b3r {
  stop-color: var(--svg-color--d29b87, #D29B87);
  stop-opacity: 0;
}

.iv0p50s_n {
  stop-color: var(--svg-color--f0aa89, #F0AA89);
  stop-opacity: 0;
}

.ix422bc1r {
  d: path("M12.294 8.597c-.89 0-1.137.215-1.434.407L9.837 11.6c-.3 1.4-.365 3.636-.36 4.578h4.766c.258-.656.678-2.675.516-4.578c-.164-1.93-1.207-2.902-2.465-3.004");
}

.iykv72k7v {
  stop-color: var(--svg-color--62516b, #62516B);
}

.jb4e9iyvc {
  d: path("M16.353 5.812a1 1 0 0 1-.258-.457h-.18V6.48c.215.137.522.115.613-.09c.079-.175.02-.394-.175-.578");
}

.jbtp05a5b {
  stop-color: var(--svg-color--d34015, #D34015);
}

.jiuqa9mgc {
  stop-color: var(--svg-color--464243, #464243);
}

.jldwtub7g {
  fill: var(--svg-color--8c8393, #8C8393);
  d: path("M15.001 18.562c-.383-1.05-.716-2.028-.773-2.383H9.485c-.1 1.375.145 1.713.774 2.422c.693.782 2.172 2.43 2.539 2.895c.35.35.5.789.555.98l2.262 7.43a.25.25 0 0 0 .315.166l3.737-1.183c.195-.061.326-.265.244-.452c-.107-.245-.333-.5-.886-.656c-.663-.187-1.943-.284-2.516-.336a941 941 0 0 0-.734-5.969c-.094-.672-.227-1.414-.774-2.914");
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

.l21zq2bsp {
  stop-color: var(--svg-color--dc9c9a, #DC9C9A);
}

.l7mbhnbzh {
  stop-color: var(--svg-color--eeb298, #EEB298);
}

.lhdz7oxfj {
  stop-color: var(--svg-color--444571, #444571);
}

.ljdv6tb3r {
  stop-color: var(--svg-color--ee462e, #EE462E);
}

.ly5_jc0cc {
  stop-color: var(--svg-color--4d3b5c, #4D3B5C);
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

.md0ucwkak {
  stop-color: var(--svg-color--ea6f3e, #EA6F3E);
}

.mngz2ebss {
  stop-color: var(--svg-color--897998, #897998);
}

.mvum_2bof {
  stop-color: var(--svg-color--ffbaa2, #FFBAA2);
}

.n_kc0dbfx {
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M19.537 16.088a1.211 1.211 0 1 0-.117 1.212");
}

.n6l6ilaec {
  stop-color: var(--svg-color--d4c6dc, #D4C6DC);
}

.n9r91ylyy {
  stop-color: var(--svg-color--824d44, #824D44);
}

.nqgqms1jm {
  stop-color: var(--svg-color--22191d, #22191D);
}

.o01zddb6n {
  stop-color: var(--svg-color--f4b9a2, #F4B9A2);
}

.o52vxyscb {
  stop-color: var(--svg-color--443d44, #443D44);
}

.o7s7rsbjo {
  stop-color: var(--svg-color--f0b8a0, #F0B8A0);
  stop-opacity: 0;
}

.oiy_54b9a {
  stop-color: var(--svg-color--887e8b, #887E8B);
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

.p59n7-b7i {
  fill: var(--svg-color--45437a, #45437A);
  d: path("m4.783 25.653l1.637.678l-.02.02l.106.355c.217.713.536 1.764.62 2.27c.077.462-.145.768-.35.953c-.094.083-.236.064-.32-.03L3.77 26.905a.25.25 0 0 1 .02-.352l.985-.888z");
}

.p6qc3nb-j {
  stop-color: var(--svg-color--492d85, #492D85);
}

.p8cjc8bgx {
  stop-color: var(--svg-color--f0b8a0, #F0B8A0);
}

.p8mdyfi9b {
  stop-color: var(--svg-color--f35886, #F35886);
}

.pat1zf4-w {
  stop-color: var(--svg-color--8b8290, #8B8290);
}

.pf-fc7btu {
  stop-color: var(--svg-color--454143, #454143);
  stop-opacity: 0;
}

.plkel1bga {
  stop-color: var(--svg-color--363131, #363131);
  stop-opacity: 0;
}

.poxe0lb6u {
  stop-color: var(--svg-color--eda68d, #EDA68D);
}

.ppddtcccf {
  stop-color: var(--svg-color--d29b87, #D29B87);
}

.pvqp1vbsj {
  stop-color: var(--svg-color--e9672b, #E9672B);
}

.pz20zvult {
  d: path("M12.441 3.77a13 13 0 0 0-.277 1.52a2.9 2.9 0 0 1-.928-1.871c-.05-.498.575-.757.999-.49c.306.192.292.49.206.84");
}

.q9foblbae {
  d: path("m8.65 19.945l.89-3.734h1.781c.052.614.152 2.215.29 3.515s-.493 2.032-.766 2.313L6.399 26.35c.198.662.627 2.025.727 2.625c.077.462-.145.768-.35.953c-.094.083-.236.064-.319-.03l-2.688-2.995a.25.25 0 0 1 .02-.352l.985-.888c1.042-1.365 3.19-4.194 3.453-4.594c.182-.276.391-.917.422-1.125");
}

.qf2lyobnm {
  stop-color: var(--svg-color--e8a99a, #E8A99A);
}

.qg5pcsysc {
  stop-color: var(--svg-color--483a55, #483A55);
  stop-opacity: 0;
}

.r8__hjblf {
  d: path("m13.354 6.303l-.2-1.44a.727.727 0 0 0 .2 1.44");
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

.s2f2c_bct {
  stop-color: var(--svg-color--ffc4a7, #FFC4A7);
}

.stui2mbih {
  stop-color: var(--svg-color--fff, #fff);
  stop-opacity: 0;
}

.stwbr2bhy {
  stop-color: var(--svg-color--46437b, #46437B);
  stop-opacity: 0;
}

.sxo3xwbvl {
  stop-color: var(--svg-color--3f3647, #3F3647);
}

.t14t_4xor {
  fill-rule: evenodd;
  d: path("M13.796 11.817a1.05 1.05 0 0 0-.486 1.403c1.832 3.77 4.236 4.912 5.72 4.627a1.05 1.05 0 1 0-.395-2.062s-.027.004-.082 0a1.2 1.2 0 0 1-.24-.044a2.7 2.7 0 0 1-.804-.404c-.65-.457-1.493-1.354-2.31-3.035a1.05 1.05 0 0 0-1.403-.485");
}

.t34we7evd {
  fill: var(--svg-color--86004c, #86004C);
  fill-rule: evenodd;
  d: path("M14.873 6.756a.125.125 0 0 0 .002.177c.238.233.582.293.691.304a.125.125 0 0 0 .026-.248c-.094-.01-.367-.062-.542-.235a.125.125 0 0 0-.177.002");
}

.tl0sw7mkk {
  stop-color: var(--svg-color--e9d9f5, #E9D9F5);
}

.tm-z33jrn {
  d: path("M18.93 16.083a.2.2 0 0 0-.28-.045l-.817.59a.2.2 0 0 0-.045.28l1.509 2.089a.2.2 0 0 0 .28.044l.817-.59a.2.2 0 0 0 .045-.28z");
}

.ttsumpbek {
  stop-color: var(--svg-color--897998, #897998);
  stop-opacity: 0;
}

.u-867gbtx {
  stop-color: var(--svg-color--443d44, #443D44);
  stop-opacity: 0;
}

.u2yjj3mld {
  stop-color: var(--svg-color--ecb39e, #ECB39E);
}

.u598_4blb {
  stop-color: var(--svg-color--f5bda3, #F5BDA3);
}

.ubyl24bdb {
  stop-color: var(--svg-color--565352, #565352);
}

.ui5e3_88b {
  d: path("M16.125 4.848c-.039-.8-.298-1.187-.42-1.3h-3.733l-.062 3.164c.866 2.121 3.511 2.212 3.906 1.445s.353-2.381.309-3.309");
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

.vjqn9lx3p {
  stop-color: var(--svg-color--cdb4e3, #CDB4E3);
}

.vmk6x9_kg {
  stop-color: var(--svg-color--dd9a7e, #DD9A7E);
}

.w1ctt_hwm {
  stop-color: var(--svg-color--d09475, #D09475);
}

.w55-gkb2p {
  stop-color: var(--svg-color--342d30, #342D30);
}

.w7a5_abxd {
  d: path("M15.013 5.642v-.004c0-.32.137-.58.306-.58c.17 0 .307.26.307.58v.004z");
}

.w8350jbiw {
  stop-color: var(--svg-color--dd3e06, #DD3E06);
  stop-opacity: 0;
}

.wb44sjbzz {
  stop-color: var(--svg-color--dd3e06, #DD3E06);
}

.wcectbccf {
  stop-color: var(--svg-color--ffcdb7, #FFCDB7);
}

.wfraawh3t {
  stop-color: var(--svg-color--e4d4ea, #E4D4EA);
  stop-opacity: 0;
}

.wtea7v6lu {
  stop-color: var(--svg-color--9f9c9f, #9F9C9F);
}

.wuoo7gb0s {
  fill: var(--svg-color--2c2828, #2C2828);
  fill-rule: evenodd;
  d: path("M15.106 4.61a.8.8 0 0 1 .216-.016a.15.15 0 0 0 .038-.298a1 1 0 0 0-.313.02a1 1 0 0 0-.408.173a.15.15 0 1 0 .178.24c.085-.062.19-.1.289-.12");
}

.wyd1xpdro {
  stop-color: var(--svg-color--464243, #464243);
  stop-opacity: 0;
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

.yfqxgqb1h {
  stop-color: var(--svg-color--a19da6, #A19DA6);
  stop-opacity: 0;
}

.ygdc80fko {
  stop-color: var(--svg-color--d8cbdd, #D8CBDD);
}

.yprzcmb3x {
  fill-rule: evenodd;
  d: path("M19.344 17.85a.45.45 0 0 0-.1.629l7.774 10.695a.45.45 0 1 0 .728-.529L19.972 17.95a.45.45 0 0 0-.628-.1");
}

.ysioi4b-l {
  fill: var(--svg-color--fff, #fff);
  d: path("M15.618 5.642h-.988c0-.391.221-.709.494-.709s.494.318.494.71");
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

.zel2068zd {
  width: 0.832px;
  height: 1.669px;
  fill: var(--svg-color--dfab9d, #DFAB9D);
  rx: 0.416px;
}

.zkj259b3a {
  stop-color: var(--svg-color--f0aa89, #F0AA89);
}

.zqaf4jb2g {
  d: path("m8.79 21.127l-3.476 4.428l.514.199l3.484-3.708a3 3 0 0 0 .761-1.493l.19-1l-.751-.774l-.544 1.994a1 1 0 0 1-.178.354");
}

.zvi2r2b9j {
  stop-color: var(--svg-color--f08337, #F08337);
  stop-opacity: 0;
}

.zzo0wlbgq {
  fill: var(--svg-color--e4aa95, #E4AA95);
  fill-rule: evenodd;
  d: path("M13.796 11.817a1.05 1.05 0 0 0-.486 1.403c1.832 3.77 4.236 4.912 5.72 4.627a1.05 1.05 0 1 0-.395-2.062s-.027.004-.082 0a1.2 1.2 0 0 1-.24-.044a2.7 2.7 0 0 1-.804-.404c-.65-.457-1.493-1.354-2.31-3.035a1.05 1.05 0 0 0-1.403-.485");
}

</style>
