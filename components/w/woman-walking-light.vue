<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iZlcgFy)" transform="rotate(-4.337 14.181 6.729)" class="vi33vey6i"/><path fill="url(#iOkOYAe)" class="qyyjdihbk"/><path fill="url(#isJ3e3b)" class="qyyjdihbk"/><g filter="url(#iGkHlob)"><path fill="url(#iwLbnLe)" class="pdtjsyxpv"/><path fill="url(#iyWKaLd)" class="pdtjsyxpv"/><path fill="url(#i3c4eAc)" class="pdtjsyxpv"/><path fill="url(#ia8MWVb)" class="pdtjsyxpv"/></g><g filter="url(#iZ0s8dc)"><path class="myi01vbpi"/><path fill="url(#iCgiomd)" class="vtnhsob1e"/></g><g filter="url(#iCAmdob)"><path class="zttnlvbeg"/><path fill="url(#iSQs5Rd)" class="vtnhsob1e"/></g><path fill="url(#iahLKjl)" class="bd0zhzbvo"/><path fill="url(#i0hiUpd)" class="bd0zhzbvo"/><path fill="url(#iUPp3oc)" class="bd0zhzbvo"/><g filter="url(#inhJ1bc)"><path fill="url(#iDSp5id)" class="x_2kr5bze"/><path fill="url(#ifqYMqQ)" class="x_2kr5bze"/><path fill="url(#i0vVaLx)" class="x_2kr5bze"/></g><g filter="url(#il2ikXc)"><path class="rgs3hja9j"/><path fill="url(#icwFmpc)" class="p7b9ddycf"/><path fill="url(#iZllrhd)" class="p7b9ddycf"/><path fill="url(#iML24Wb)" class="p7b9ddycf"/><path fill="url(#iaFjZcd)" class="p7b9ddycf"/><path fill="url(#iGSnOGg)" class="p7b9ddycf"/></g><path fill="url(#igghbnd)" class="vp_qxubew"/><path fill="url(#iycJEBd)" class="vp_qxubew"/><path fill="url(#ix5lz9d)" class="vp_qxubew"/><path fill="url(#iPYUKxe)" class="vp_qxubew"/><path fill="url(#iQSzi3h)" class="vp_qxubew"/><path class="t_a45vbzn"/><path fill="url(#iujHcGe)" class="fwkhvmb2c"/><path fill="url(#ioMwqdd)" class="fwkhvmb2c"/><path fill="url(#iAfs6BU)" class="fwkhvmb2c"/><path class="v5j3hrbgo"/><g filter="url(#i46k6bN)"><path clip-rule="evenodd" class="sbtry_g-h"/><path fill="url(#iJXHvke)" clip-rule="evenodd" class="sgc3fpsca"/><path fill="url(#iAuMjRL)" clip-rule="evenodd" class="sgc3fpsca"/></g><path fill="url(#iLQKQcd)" class="i7ywxfd5f"/><path class="fdoftxbqs"/><path fill="url(#i7nvgLd)" class="rbatabzoa"/><path fill="url(#iCu47me)" class="rbatabzoa"/><path fill="url(#iXBp5Ca)" class="rbatabzoa"/><path fill="url(#i7qrlKd)" class="rbatabzoa"/><path fill="url(#iLjNrXc)" class="rbatabzoa"/><circle fill="url(#inRLYEN)" class="dwt1fld0s"/><g filter="url(#iZqVnie)"><path class="ik_2dacqf"/></g><g filter="url(#ivKGqsb)"><path clip-rule="evenodd" class="pj7iwwbcq"/></g><g filter="url(#i9XL0na)"><path class="jge_lpuyc"/></g><g filter="url(#i6td11d)"><path fill="url(#iSsiqfe)" class="rimyswhxd"/><path fill="url(#i9wCq7b)" class="rimyswhxd"/><path fill="url(#ia1iyoc)" class="rimyswhxd"/></g><path fill="url(#ix37qji)" class="hjg1-_xep"/><path fill="url(#izUgOBB)" class="hjg1-_xep"/><path clip-rule="evenodd" class="d08kwlbtn"/><g filter="url(#iMdttjb)"><path clip-rule="evenodd" class="a1xwrybbh"/></g><path class="rq9c-melg"/><path fill="url(#iwqUy0u)" class="u_490kbtp"/><path fill="url(#iu2jm3P)" class="bw39i08st"/><ellipse fill="url(#iZvH4HK)" transform="rotate(24.61 12.373 5.306)" class="yhwv79m6v"/><g filter="url(#i0Mw4Lx)"><path fill="url(#iX2l1Hf)" class="tkltjqapj"/></g><g filter="url(#iglXwsd)"><path fill="url(#ie0wx9b)" class="szm--fb2k"/></g><defs><radialGradient id="iZlcgFy" cx="0" cy="0" r="1" gradientTransform="matrix(-1.30831 .72148 -1.24915 -2.26517 15.512 8.286)" gradientUnits="userSpaceOnUse"><stop class="pxvqh6bla"/><stop offset=".912" class="iz9008bnp"/></radialGradient><radialGradient id="iOkOYAe" cx="0" cy="0" r="1" gradientTransform="matrix(.47656 .25781 -.36391 .67269 11.178 6.265)" gradientUnits="userSpaceOnUse"><stop offset=".101" class="hymklqb8k"/><stop offset=".684" class="s2f2c_bct"/></radialGradient><radialGradient id="isJ3e3b" cx="0" cy="0" r="1" gradientTransform="matrix(-.12005 -.29152 .43751 -.18018 11.583 6.58)" gradientUnits="userSpaceOnUse"><stop class="zkj259b3a"/><stop offset="1" class="iv0p50s_n"/></radialGradient><radialGradient id="iyWKaLd" cx="0" cy="0" r="1" gradientTransform="matrix(-.84375 -.04688 .05715 -1.0287 14.84 5.561)" gradientUnits="userSpaceOnUse"><stop offset=".156" class="l7mbhnbzh"/><stop offset="1" class="biuc-6bfh"/></radialGradient><radialGradient id="i3c4eAc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -5.1875 2.01562 0 11.944 6.749)" gradientUnits="userSpaceOnUse"><stop offset=".219" class="wcectbccf"/><stop offset="1" class="b3jcjo1jv"/></radialGradient><radialGradient id="ia8MWVb" cx="0" cy="0" r="1" gradientTransform="matrix(0 .39063 -.60919 0 12.772 5.608)" gradientUnits="userSpaceOnUse"><stop offset=".155" class="ie_w39bfj"/><stop offset="1" class="dx40lk_kc"/></radialGradient><radialGradient id="iCgiomd" cx="0" cy="0" r="1" gradientTransform="matrix(1.53488 -.43168 .9251 3.28923 11.716 3.326)" gradientUnits="userSpaceOnUse"><stop class="k_urnmdao"/><stop offset="1" class="w7r1zi1yh"/></radialGradient><radialGradient id="iSQs5Rd" cx="0" cy="0" r="1" gradientTransform="matrix(1.53488 -.43168 .9251 3.28923 11.716 3.326)" gradientUnits="userSpaceOnUse"><stop class="tzf255bgc"/><stop offset="1" class="ctuud_14h"/></radialGradient><radialGradient id="iahLKjl" cx="0" cy="0" r="1" gradientTransform="matrix(.72656 -.21094 .10296 .35463 14.537 5.452)" gradientUnits="userSpaceOnUse"><stop offset=".17" class="i8aj4_5_r"/><stop offset="1" class="u2yjj3mld"/></radialGradient><radialGradient id="i0hiUpd" cx="0" cy="0" r="1" gradientTransform="matrix(.22596 1.17975 -1.22934 .23546 14.569 5.151)" gradientUnits="userSpaceOnUse"><stop offset=".556" class="chiqx4b_a"/><stop offset="1" class="vmk6x9_kg"/><stop offset="1" class="hq1ekobkc"/></radialGradient><radialGradient id="ifqYMqQ" cx="0" cy="0" r="1" gradientTransform="matrix(2.45369 2.93958 -5.96661 4.98038 16.953 18.038)" gradientUnits="userSpaceOnUse"><stop offset=".434" class="oiy_54b9a"/><stop offset="1" class="rm4aiz5dn"/></radialGradient><radialGradient id="i0vVaLx" cx="0" cy="0" r="1" gradientTransform="matrix(.89062 .65625 -3.9414 5.34905 16.637 19.054)" gradientUnits="userSpaceOnUse"><stop offset=".043" class="v5lz4sb9o"/><stop offset="1" class="m_uy2vb_d"/></radialGradient><radialGradient id="icwFmpc" cx="0" cy="0" r="1" gradientTransform="matrix(3.25 -5.14063 1.35402 .85604 15.856 20.898)" gradientUnits="userSpaceOnUse"><stop offset=".07" class="mngz2ebss"/><stop offset="1" class="ttsumpbek"/></radialGradient><radialGradient id="iZllrhd" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.42188 -1.38588 0 16.668 16.194)" gradientUnits="userSpaceOnUse"><stop class="f3j6dkfip"/><stop offset="1" class="fxoxl0blj"/></radialGradient><radialGradient id="iaFjZcd" cx="0" cy="0" r="1" gradientTransform="matrix(.14063 -.17968 .6458 .50543 11.973 28.108)" gradientUnits="userSpaceOnUse"><stop class="ryq0o3qru"/><stop offset="1" class="yfqxgqb1h"/></radialGradient><radialGradient id="iGSnOGg" cx="0" cy="0" r="1" gradientTransform="matrix(6.375 -1.8125 4.67455 16.4415 12.293 19.241)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="ex23x-brg"/><stop offset="1" class="ux4w7lb6c"/></radialGradient><radialGradient id="igghbnd" cx="0" cy="0" r="1" gradientTransform="matrix(-.09375 -1.53125 2.45635 -.15039 10.84 29.46)" gradientUnits="userSpaceOnUse"><stop class="cl2mlwbhs"/><stop offset="1" class="yvuyjoqpy"/></radialGradient><radialGradient id="iycJEBd" cx="0" cy="0" r="1" gradientTransform="matrix(1.0625 -.21875 .15137 .73521 7.73 28.522)" gradientUnits="userSpaceOnUse"><stop class="m3n9jy0fh"/><stop offset="1" class="hdzwkybza"/></radialGradient><radialGradient id="ix5lz9d" cx="0" cy="0" r="1" gradientTransform="rotate(-70.942 26.754 6.636)scale(1.81842 .89694)" gradientUnits="userSpaceOnUse"><stop offset=".08" class="a541b3bqx"/><stop offset="1" class="zc8ie-1dg"/></radialGradient><radialGradient id="iAfs6BU" cx="0" cy="0" r="1" gradientTransform="rotate(-132.875 17.852 8.36)scale(1.99789 1.10527)" gradientUnits="userSpaceOnUse"><stop class="xh_da2q2q"/><stop offset="1" class="stwbr2bhy"/></radialGradient><radialGradient id="iJXHvke" cx="0" cy="0" r="1" gradientTransform="matrix(1.0625 -.07813 .1783 2.42485 7.694 17.124)" gradientUnits="userSpaceOnUse"><stop class="lfdq75b0a"/><stop offset="1" class="ekb-q1ght"/></radialGradient><radialGradient id="iAuMjRL" cx="0" cy="0" r="1" gradientTransform="rotate(130.815 3.34 9.163)scale(2.27101 1.05465)" gradientUnits="userSpaceOnUse"><stop class="poq1tcc_c"/><stop offset="1" class="ezhbzwb_v"/></radialGradient><radialGradient id="i7nvgLd" cx="0" cy="0" r="1" gradientTransform="matrix(-.09377 -4.95122 1.33998 -.02538 16.564 16.194)" gradientUnits="userSpaceOnUse"><stop class="dkjt4cbcx"/><stop offset="1" class="w9ku-ifwq"/></radialGradient><radialGradient id="iCu47me" cx="0" cy="0" r="1" gradientTransform="matrix(3.65186 0 0 15.6875 14.689 14.306)" gradientUnits="userSpaceOnUse"><stop offset=".436" class="p0p0ijbbx"/><stop offset=".967" class="dvcrl_y_s"/></radialGradient><radialGradient id="iXBp5Ca" cx="0" cy="0" r="1" gradientTransform="matrix(-4.78125 .78125 -1.79108 -10.96143 18.064 15.118)" gradientUnits="userSpaceOnUse"><stop offset=".781" class="jx6m9tune"/><stop offset=".931" class="g41565bda"/></radialGradient><radialGradient id="i7qrlKd" cx="0" cy="0" r="1" gradientTransform="matrix(.51562 1.34375 -3.67742 1.4111 14.626 8.274)" gradientUnits="userSpaceOnUse"><stop offset=".297" class="mwuao6bkl"/><stop offset="1" class="jw-yqmb7v"/></radialGradient><radialGradient id="iLjNrXc" cx="0" cy="0" r="1" gradientTransform="matrix(-.67188 .9433 -1.66927 -1.18897 16.439 8.612)" gradientUnits="userSpaceOnUse"><stop class="aflh_2rif"/><stop offset="1" class="ujjvz6nrm"/></radialGradient><radialGradient id="inRLYEN" cx="0" cy="0" r="1" gradientTransform="rotate(90 1.452 19.341)scale(.90625)" gradientUnits="userSpaceOnUse"><stop offset=".256" class="qf2lyobnm"/><stop offset="1" class="l21zq2bsp"/></radialGradient><radialGradient id="i9wCq7b" cx="0" cy="0" r="1" gradientTransform="matrix(1.0907 .20313 -.42058 2.25834 14.88 10.352)" gradientUnits="userSpaceOnUse"><stop offset=".12" class="xot8u71lw"/><stop offset="1" class="jjp3z2beb"/></radialGradient><radialGradient id="ia1iyoc" cx="0" cy="0" r="1" gradientTransform="matrix(1.90625 1.84375 -1.04604 1.0815 17.939 10.087)" gradientUnits="userSpaceOnUse"><stop offset=".204" class="lz70c3nqo"/><stop offset="1" class="pt5v4qb1w"/></radialGradient><radialGradient id="ix37qji" cx="0" cy="0" r="1" gradientTransform="matrix(.8373 -.05636 .04467 .6636 8.005 16.594)" gradientUnits="userSpaceOnUse"><stop class="jq9e5d-ak"/><stop offset="1" class="uf4c4wb_q"/></radialGradient><radialGradient id="izUgOBB" cx="0" cy="0" r="1" gradientTransform="matrix(-.3295 .27291 -.22275 -.26894 8.961 16.543)" gradientUnits="userSpaceOnUse"><stop class="y8ctrfbhv"/><stop offset="1" class="tf8v38baz"/></radialGradient><radialGradient id="iwqUy0u" cx="0" cy="0" r="1" gradientTransform="matrix(.27344 0 0 .53125 12.477 5.636)" gradientUnits="userSpaceOnUse"><stop offset=".895" class="l0aricxam"/><stop offset="1" class="n9r91ylyy"/></radialGradient><radialGradient id="iu2jm3P" cx="0" cy="0" r="1" gradientTransform="matrix(.25 0 0 .54102 12.309 5.657)" gradientUnits="userSpaceOnUse"><stop class="gv3iwdbvq"/><stop offset=".813" class="ubyl24bdb"/></radialGradient><linearGradient id="iwLbnLe" x1="14.528" x2="11.665" y1="6.304" y2="6.476" gradientUnits="userSpaceOnUse"><stop class="dxjajos_o"/><stop offset="1" class="gu4uskbqq"/></linearGradient><linearGradient id="iUPp3oc" x1="14.483" x2="14.631" y1="5.521" y2="5.532" gradientUnits="userSpaceOnUse"><stop class="o01zddb6n"/><stop offset="1" class="h5b83fbqu"/></linearGradient><linearGradient id="iDSp5id" x1="17.973" x2="20.201" y1="22.898" y2="20.954" gradientUnits="userSpaceOnUse"><stop offset=".211" class="pat1zf4-w"/><stop offset="1" class="wtea7v6lu"/></linearGradient><linearGradient id="iML24Wb" x1="15.746" x2="15.746" y1="16.085" y2="16.429" gradientUnits="userSpaceOnUse"><stop offset=".136" class="x5p6yzbmf"/><stop offset="1" class="cnh3p8b3x"/></linearGradient><linearGradient id="iPYUKxe" x1="10.278" x2="10.364" y1="29.632" y2="29.319" gradientUnits="userSpaceOnUse"><stop class="l138bfbcs"/><stop offset="1" class="oxce79bcz"/></linearGradient><linearGradient id="iQSzi3h" x1="12.246" x2="11.668" y1="30.007" y2="29.788" gradientUnits="userSpaceOnUse"><stop offset=".064" class="lhdz7oxfj"/><stop offset="1" class="csaq2_bel"/></linearGradient><linearGradient id="iujHcGe" x1="20.856" x2="21.45" y1="27.991" y2="28.163" gradientUnits="userSpaceOnUse"><stop class="oxg1n1wjw"/><stop offset="1" class="y0g_czb9f"/></linearGradient><linearGradient id="ioMwqdd" x1="22.981" x2="22.801" y1="28.065" y2="27.917" gradientUnits="userSpaceOnUse"><stop class="p6qc3nb-j"/><stop offset="0" class="ezcqmvbni"/><stop offset="1" class="stwbr2bhy"/></linearGradient><linearGradient id="iLQKQcd" x1="12.7" x2="13.575" y1="12.851" y2="10.46" gradientUnits="userSpaceOnUse"><stop class="t55apucyo"/><stop offset=".787" class="biw5o_cgj"/></linearGradient><linearGradient id="iSsiqfe" x1="16.731" x2="17.84" y1="9.132" y2="12.585" gradientUnits="userSpaceOnUse"><stop offset=".118" class="u1dukib7n"/><stop offset="1" class="mk0srdu2z"/></linearGradient><linearGradient id="iZvH4HK" x1="12.302" x2="12.488" y1="5.267" y2="5.328" gradientUnits="userSpaceOnUse"><stop class="vc--wpv5i"/><stop offset="1" class="stui2mbih"/></linearGradient><linearGradient id="iX2l1Hf" x1="12.075" x2="16.7" y1="27.429" y2="17.288" gradientUnits="userSpaceOnUse"><stop class="v9kimlbms"/><stop offset="1" class="g24ahctiy"/></linearGradient><linearGradient id="ie0wx9b" x1="22.219" x2="17.908" y1="25.338" y2="19.966" gradientUnits="userSpaceOnUse"><stop class="ckhjb_bgt"/><stop offset="1" class="rnrhdzckq"/></linearGradient><filter id="iGkHlob" width="4.443" height="5.249" x="11.465" y="3.363" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2" dy="-.2"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.815686 0 0 0 0 0.596078 0 0 0 0 0.580392 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_110"/></filter><filter id="iZ0s8dc" width="6.813" height="7.403" x="11.104" y="1.701" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.4" dy=".4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.972549 0 0 0 0 0.737255 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_110"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.956863 0 0 0 0 0.788235 0 0 0 0 0.631373 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_110" result="effect2_innerShadow_4002_110"/></filter><filter id="iCAmdob" width="6.813" height="7.403" x="11.104" y="1.701" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.4" dy=".4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.290196 0 0 0 0 0.266667 0 0 0 0 0.27451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_110"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0901961 0 0 0 0 0.0392157 0 0 0 0 0.133333 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_110" result="effect2_innerShadow_4002_110"/></filter><filter id="inhJ1bc" width="8.674" height="14.771" x="16.188" y="15.476" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".75" dy="-.75"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.439216 0 0 0 0 0.388235 0 0 0 0 0.486275 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_110"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.537255 0 0 0 0 0.423529 0 0 0 0 0.635294 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_110" result="effect2_innerShadow_4002_110"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy=".25"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.529412 0 0 0 0 0.490196 0 0 0 0 0.537255 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_4002_110" result="effect3_innerShadow_4002_110"/></filter><filter id="il2ikXc" width="10.972" height="14.104" x="7.882" y="15.994" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy="-.2"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.619608 0 0 0 0 0.592157 0 0 0 0 0.611765 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_110"/></filter><filter id="i46k6bN" width="8.438" height="7.859" x="6.785" y="10.624" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-1"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.843137 0 0 0 0 0.541176 0 0 0 0 0.486275 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_110"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.764706 0 0 0 0 0.517647 0 0 0 0 0.529412 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_110" result="effect2_innerShadow_4002_110"/></filter><filter id="iZqVnie" width="5.442" height="5.875" x="14.28" y="8.468" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_110" stdDeviation=".375"/></filter><filter id="ivKGqsb" width="7.59" height="10.511" x="15.741" y="9.157" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.909804 0 0 0 0 0.678431 0 0 0 0 0.639216 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_110"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.4" dy=".4"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.980392 0 0 0 0 0.807843 0 0 0 0 0.713726 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_110" result="effect2_innerShadow_4002_110"/></filter><filter id="i9XL0na" width="6.084" height="9.069" x="17.076" y="9.902" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_110" stdDeviation=".3"/></filter><filter id="i6td11d" width="4.758" height="4.525" x="14.879" y="8.654" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.15"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.392157 0 0 0 0 0.254902 0 0 0 0 0.639216 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_110"/></filter><filter id="iMdttjb" width="1.013" height=".568" x="12.227" y="4.307" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0705882 0 0 0 0 0.0588235 0 0 0 0 0.054902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_110"/></filter><filter id="i0Mw4Lx" width="6.844" height="12.891" x="10.856" y="16.116" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_110" stdDeviation=".5"/></filter><filter id="iglXwsd" width="6.45" height="8.475" x="16.804" y="18.044" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_110" stdDeviation=".375"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:woman-walking-light" /></template>
<style>
.a1xwrybbh {
  fill: var(--svg-color--2c2828, #2C2828);
  fill-rule: evenodd;
  d: path("M12.712 4.624a.8.8 0 0 0-.216-.015a.15.15 0 0 1-.038-.298a1 1 0 0 1 .313.02c.128.025.278.076.409.172a.15.15 0 0 1-.179.242a.7.7 0 0 0-.289-.12");
}

.a541b3bqx {
  stop-color: var(--svg-color--515279, #515279);
}

.aflh_2rif {
  stop-color: var(--svg-color--281a4b, #281A4B);
}

.b3jcjo1jv {
  stop-color: var(--svg-color--ffcdb7, #FFCDB7);
  stop-opacity: 0;
}

.bd0zhzbvo {
  d: path("m14.386 6.325l.2-1.439a.727.727 0 0 1-.2 1.44");
}

.biuc-6bfh {
  stop-color: var(--svg-color--eeb298, #EEB298);
  stop-opacity: 0;
}

.biw5o_cgj {
  stop-color: var(--svg-color--816fa6, #816FA6);
}

.bw39i08st {
  d: path("m12.61 5.657l.004-.072c0-.186-.08-.336-.176-.336c-.097 0-.176.15-.176.336q0 .038.004.072z");
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

.ctuud_14h {
  stop-color: var(--svg-color--534b49, #534B49);
  stop-opacity: 0;
}

.d08kwlbtn {
  fill: var(--svg-color--86004c, #86004C);
  fill-rule: evenodd;
  d: path("M12.945 6.77a.125.125 0 0 1-.002.178c-.238.233-.582.293-.692.304a.125.125 0 0 1-.025-.248c.093-.01.366-.062.542-.235a.125.125 0 0 1 .177.002");
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

.dx40lk_kc {
  stop-color: var(--svg-color--fabfa4, #FABFA4);
  stop-opacity: 0;
}

.dxjajos_o {
  stop-color: var(--svg-color--f0b5a2, #F0B5A2);
}

.ekb-q1ght {
  stop-color: var(--svg-color--ffd3b9, #FFD3B9);
  stop-opacity: 0;
}

.ex23x-brg {
  stop-color: var(--svg-color--8c8388, #8C8388);
  stop-opacity: 0;
}

.ezcqmvbni {
  stop-color: var(--svg-color--443a80, #443A80);
}

.ezhbzwb_v {
  stop-color: var(--svg-color--f9c0a6, #F9C0A6);
  stop-opacity: 0;
}

.f3j6dkfip {
  stop-color: var(--svg-color--99919a, #99919A);
}

.fdoftxbqs {
  fill: var(--svg-color--725ca6, #725CA6);
  d: path("M15.524 8.612c.89 0 1.137.215 1.434.407l1.023 2.597c.3 1.4.364 3.636.36 4.578h-4.766c-.258-.656-.678-2.675-.516-4.578c.164-1.93 1.207-2.902 2.465-3.004");
}

.ft5dv1b6b {
  fill: none;
}

.fwkhvmb2c {
  d: path("m23.035 25.668l-1.638.678l.022.02l-.107.355c-.217.713-.536 1.764-.62 2.27c-.077.462.145.768.35.953c.094.083.235.064.319-.03l2.688-2.995a.25.25 0 0 0-.02-.353l-.985-.887z");
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

.gu4uskbqq {
  stop-color: var(--svg-color--fac1a8, #FAC1A8);
}

.gv3iwdbvq {
  stop-color: var(--svg-color--666361, #666361);
}

.h5b83fbqu {
  stop-color: var(--svg-color--f4bca5, #F4BCA5);
  stop-opacity: 0;
}

.hdzwkybza {
  stop-color: var(--svg-color--63617e, #63617E);
  stop-opacity: 0;
}

.hjg1-_xep {
  d: path("m8.657 16.026l.496.052c.21.022.374.192.388.403a.38.38 0 0 1-.077.266c-.264.33-.524.366-.721.408c-.22.047-.676-.191-.59-.691a.53.53 0 0 1 .504-.438");
}

.hq1ekobkc {
  stop-color: var(--svg-color--e7a792, #E7A792);
}

.hymklqb8k {
  stop-color: var(--svg-color--ffd4b7, #FFD4B7);
}

.i7ywxfd5f {
  d: path("M13.215 10.515c.281-.713.774-1.224.985-1.391l-.04 4.469l-1.785-.836c.278-.524.489-1.352.84-2.242");
}

.i8aj4_5_r {
  stop-color: var(--svg-color--fac7b1, #FAC7B1);
}

.ie_w39bfj {
  stop-color: var(--svg-color--fabfa4, #FABFA4);
}

.ik_2dacqf {
  fill: var(--svg-color--442e79, #442E79);
  d: path("M15.236 10.985c-.31-.248-.178-.39-.178-.818c0-.749.013-.95.761-.95c.338 0 .646.124.883.327c.95.692 1.79 1.592 2.27 2.135l-2.04 1.914a58 58 0 0 1-1.696-2.608");
}

.iv0p50s_n {
  stop-color: var(--svg-color--f0aa89, #F0AA89);
  stop-opacity: 0;
}

.iz9008bnp {
  stop-color: var(--svg-color--eab1a3, #EAB1A3);
}

.jge_lpuyc {
  stroke: var(--svg-color--ffd0bb, #FFD0BB);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M17.876 10.702c.97.906 3.157 3.219 4.485 7.469");
}

.jjp3z2beb {
  stop-color: var(--svg-color--8974b4, #8974B4);
  stop-opacity: 0;
}

.jq9e5d-ak {
  stop-color: var(--svg-color--ffccb3, #FFCCB3);
}

.jw-yqmb7v {
  stop-color: var(--svg-color--6f5797, #6F5797);
  stop-opacity: 0;
}

.jx6m9tune {
  stop-color: var(--svg-color--8272a4, #8272A4);
  stop-opacity: 0;
}

.k_urnmdao {
  stop-color: var(--svg-color--ffecb8, #FFECB8);
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

.lfdq75b0a {
  stop-color: var(--svg-color--ffd3b9, #FFD3B9);
}

.lhdz7oxfj {
  stop-color: var(--svg-color--444571, #444571);
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

.mwuao6bkl {
  stop-color: var(--svg-color--4d395c, #4D395C);
}

.myi01vbpi {
  fill: var(--svg-color--ffe0af, #FFE0AF);
  d: path("M11.573 3.517c-.171-.41.017-.844.113-.993c.367-.672 1.129-.716 1.567-.523c.516.226.67.347 1.504.11c.837-.239 1.867-.13 2.406.84c.54.968-.047 2.058.086 2.651c.133.594.513.653.653 1.34c.117.953-.473 1.575-.997 1.715c-.523.14-1.601 0-1.953-.875c-.575-1.431-.184-2.11-.309-2.828c-.125-.719-.554-.922-1.336-.766c-.92.184-1.505-.126-1.734-.671");
}

.n9r91ylyy {
  stop-color: var(--svg-color--824d44, #824D44);
}

.o01zddb6n {
  stop-color: var(--svg-color--f4b9a2, #F4B9A2);
}

.oiy_54b9a {
  stop-color: var(--svg-color--887e8b, #887E8B);
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

.p6qc3nb-j {
  stop-color: var(--svg-color--492d85, #492D85);
}

.p7b9ddycf {
  d: path("M12.817 18.577c.383-1.05.716-2.029.773-2.383h4.742c.1 1.375-.144 1.712-.773 2.422c-.693.782-2.172 2.43-2.54 2.895c-.35.35-.5.789-.554.98l-2.262 7.43a.25.25 0 0 1-.315.166l-3.737-1.183c-.195-.061-.326-.265-.244-.452c.107-.245.333-.5.886-.656c.663-.188 1.943-.284 2.516-.336c.214-1.766.66-5.431.734-5.969c.094-.672.227-1.414.774-2.914");
}

.pat1zf4-w {
  stop-color: var(--svg-color--8b8290, #8B8290);
}

.pdtjsyxpv {
  d: path("M11.693 4.863c.039-.8.298-1.187.42-1.3h3.733l.062 3.164c-.866 2.121-3.511 2.212-3.906 1.445s-.354-2.381-.309-3.309");
}

.pj7iwwbcq {
  fill: var(--svg-color--f0b6a6, #F0B6A6);
  fill-rule: evenodd;
  d: path("M21.837 19.238a.614.614 0 0 1-.776-.407c-1.215-3.921-3.166-6.29-4.542-7.545c-.438-.4-.516-1.082-.128-1.53c.346-.401.944-.472 1.348-.13c1.626 1.381 3.91 3.976 5.316 8.605a.59.59 0 0 1-.382.73z");
}

.poq1tcc_c {
  stop-color: var(--svg-color--f9c0a6, #F9C0A6);
}

.pt5v4qb1w {
  stop-color: var(--svg-color--9075ca, #9075CA);
  stop-opacity: 0;
}

.pxvqh6bla {
  stop-color: var(--svg-color--bb816f, #BB816F);
}

.qf2lyobnm {
  stop-color: var(--svg-color--e8a99a, #E8A99A);
}

.qyyjdihbk {
  d: path("M11.47 5.827c.155-.147.236-.366.257-.457h.18v1.125c-.215.137-.522.115-.614-.09c-.078-.176-.02-.394.176-.578");
}

.rbatabzoa {
  d: path("M15.524 8.612c.89 0 1.137.215 1.434.407l1.023 2.597c.3 1.4.364 3.636.36 4.578h-4.766c-.258-.656-.678-2.675-.516-4.578c.164-1.93 1.207-2.902 2.465-3.004");
}

.rgs3hja9j {
  fill: var(--svg-color--8c8393, #8C8393);
  d: path("M12.817 18.577c.383-1.05.716-2.029.773-2.383h4.742c.1 1.375-.144 1.712-.773 2.422c-.693.782-2.172 2.43-2.54 2.895c-.35.35-.5.789-.554.98l-2.262 7.43a.25.25 0 0 1-.315.166l-3.737-1.183c-.195-.061-.326-.265-.244-.452c.107-.245.333-.5.886-.656c.663-.188 1.943-.284 2.516-.336c.214-1.766.66-5.431.734-5.969c.094-.672.227-1.414.774-2.914");
}

.rimyswhxd {
  d: path("M15.388 11.218a1.355 1.355 0 1 1 1.729-2.088c.951.692 1.79 1.592 2.27 2.135l-2.039 1.914c-.308-.32-1.382-1.393-1.96-1.961");
}

.rm4aiz5dn {
  stop-color: var(--svg-color--887e8b, #887E8B);
  stop-opacity: 0;
}

.rnrhdzckq {
  stop-color: var(--svg-color--a39fa7, #A39FA7);
  stop-opacity: 0;
}

.rq9c-melg {
  fill: var(--svg-color--fff, #fff);
  d: path("M12.2 5.657h.988c0-.391-.221-.709-.494-.709s-.494.318-.494.71");
}

.ryq0o3qru {
  stop-color: var(--svg-color--a19da6, #A19DA6);
}

.s2f2c_bct {
  stop-color: var(--svg-color--ffc4a7, #FFC4A7);
}

.sbtry_g-h {
  fill: var(--svg-color--e4aa95, #E4AA95);
  fill-rule: evenodd;
  d: path("M9.169 18.406a.85.85 0 0 1-1.13-.433l-.19-.427a.755.755 0 0 1 .383-.992c1.533-.704 4.023-2.149 4.983-5.93l2.008.524c-1.185 4.668-4.29 6.44-6.054 7.258");
}

.sgc3fpsca {
  fill-rule: evenodd;
  d: path("M9.169 18.406a.85.85 0 0 1-1.13-.433l-.19-.427a.755.755 0 0 1 .383-.992c1.533-.704 4.023-2.149 4.983-5.93l2.008.524c-1.185 4.668-4.29 6.44-6.054 7.258");
}

.stui2mbih {
  stop-color: var(--svg-color--fff, #fff);
  stop-opacity: 0;
}

.stwbr2bhy {
  stop-color: var(--svg-color--46437b, #46437B);
  stop-opacity: 0;
}

.szm--fb2k {
  d: path("m19.028 21.142l3.476 4.428l-.514.199l-3.484-3.708a3 3 0 0 1-.761-1.493l-.19-1l.751-.774l.544 1.993q.053.196.178.355");
}

.t_a45vbzn {
  fill: var(--svg-color--45437a, #45437A);
  d: path("m23.035 25.668l-1.638.678l.022.02l-.107.355c-.217.713-.536 1.764-.62 2.27c-.077.462.145.768.35.953c.094.083.235.064.319-.03l2.688-2.995a.25.25 0 0 0-.02-.353l-.985-.887z");
}

.t55apucyo {
  stop-color: var(--svg-color--725d9d, #725D9D);
}

.tf8v38baz {
  stop-color: var(--svg-color--e6a89b, #E6A89B);
  stop-opacity: 0;
}

.tkltjqapj {
  d: path("m13.2 21.194l-1.344 6.5l.36.313l1.468-6.531L16.7 17.6l-.703-.485z");
}

.ttsumpbek {
  stop-color: var(--svg-color--897998, #897998);
  stop-opacity: 0;
}

.tzf255bgc {
  stop-color: var(--svg-color--534b49, #534B49);
}

.u_490kbtp {
  d: path("M12.805 5.657v-.004c0-.32-.137-.58-.307-.58s-.306.26-.306.58v.004z");
}

.u1dukib7n {
  stop-color: var(--svg-color--8265b5, #8265B5);
}

.u2yjj3mld {
  stop-color: var(--svg-color--ecb39e, #ECB39E);
}

.ubyl24bdb {
  stop-color: var(--svg-color--565352, #565352);
}

.uf4c4wb_q {
  stop-color: var(--svg-color--e6a792, #E6A792);
}

.ujjvz6nrm {
  stop-color: var(--svg-color--483368, #483368);
  stop-opacity: 0;
}

.ux4w7lb6c {
  stop-color: var(--svg-color--8c8388, #8C8388);
}

.v5j3hrbgo {
  fill: var(--svg-color--2f2c2d, #2F2C2D);
  d: path("M13.205 5.146c-.132-.131-.35-.161-.442-.16l.303.467c.147-.008.302-.143.139-.307");
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

.vmk6x9_kg {
  stop-color: var(--svg-color--dd9a7e, #DD9A7E);
}

.vp_qxubew {
  d: path("m12.594 28.636l-.391 1.285a.25.25 0 0 1-.315.166l-3.737-1.183c-.195-.062-.326-.265-.244-.452c.107-.245.333-.5.886-.656c.591-.167 1.673-.262 2.306-.318l.21-.018v-.002z");
}

.vtnhsob1e {
  d: path("M11.573 3.517c-.171-.41.017-.844.113-.993c.367-.672 1.129-.716 1.567-.523c.516.226.67.347 1.504.11c.837-.239 1.867-.13 2.406.84c.54.968-.047 2.058.086 2.651c.133.594.513.653.653 1.34c.117.953-.473 1.575-.997 1.715c-.523.14-1.601 0-1.953-.875c-.575-1.431-.184-2.11-.309-2.828c-.125-.719-.554-.922-1.336-.766c-.92.184-1.505-.126-1.734-.671");
}

.w7r1zi1yh {
  stop-color: var(--svg-color--ffecb8, #FFECB8);
  stop-opacity: 0;
}

.w9ku-ifwq {
  stop-color: var(--svg-color--7966a4, #7966A4);
  stop-opacity: 0;
}

.wcectbccf {
  stop-color: var(--svg-color--ffcdb7, #FFCDB7);
}

.wtea7v6lu {
  stop-color: var(--svg-color--9f9c9f, #9F9C9F);
}

.x_2kr5bze {
  d: path("m19.169 19.96l-.891-3.734h-1.781c-.052.614-.152 2.215-.29 3.515s.492 2.032.766 2.313l4.446 4.312c-.198.662-.627 2.025-.727 2.625c-.077.462.145.768.35.953c.094.083.235.064.319-.03l2.687-2.995a.25.25 0 0 0-.018-.353l-.986-.887c-1.042-1.365-3.191-4.194-3.454-4.594c-.18-.276-.39-.917-.421-1.125");
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

.y8ctrfbhv {
  stop-color: var(--svg-color--edb3a0, #EDB3A0);
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

.zc8ie-1dg {
  stop-color: var(--svg-color--515279, #515279);
  stop-opacity: 0;
}

.zkj259b3a {
  stop-color: var(--svg-color--f0aa89, #F0AA89);
}

.zttnlvbeg {
  fill: var(--svg-color--241823, #241823);
  d: path("M11.573 3.517c-.171-.41.017-.844.113-.993c.367-.672 1.129-.716 1.567-.523c.516.226.67.347 1.504.11c.837-.239 1.867-.13 2.406.84c.54.968-.047 2.058.086 2.651c.133.594.513.653.653 1.34c.117.953-.473 1.575-.997 1.715c-.523.14-1.601 0-1.953-.875c-.575-1.431-.184-2.11-.309-2.828c-.125-.719-.554-.922-1.336-.766c-.92.184-1.505-.126-1.734-.671");
}

</style>
