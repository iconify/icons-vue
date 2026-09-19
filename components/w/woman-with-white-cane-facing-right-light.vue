<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#i6f5pLb)"><path clip-rule="evenodd" class="n7vpf3uhv"/><path fill="url(#iScvuce)" clip-rule="evenodd" class="hdrw_q19a"/><path fill="url(#i7AimMb)" clip-rule="evenodd" class="hdrw_q19a"/></g><path class="spmxexb0c"/><g filter="url(#in1rqsd)"><path stroke="url(#ibMWDnd)" class="exc3v1b0k"/></g><g filter="url(#iY3YyWW)"><path fill="url(#iB5PCEr)" clip-rule="evenodd" class="kczqywbmk"/></g><path fill="url(#iLR5FNe)" class="qat-h_3-d"/><path fill="url(#ilWQc7b)" class="qat-h_3-d"/><g filter="url(#ioI58Pd)"><circle fill="url(#iUctc4d)" transform="matrix(-1 0 0 1 28.377 28.248)" class="ghq9gsa-q"/><circle fill="url(#iETpATd)" transform="matrix(-1 0 0 1 28.377 28.248)" class="ghq9gsa-q"/><circle fill="url(#iPmd0rd)" transform="matrix(-1 0 0 1 28.377 28.248)" class="ghq9gsa-q"/></g><g filter="url(#i7QmHae)"><path fill="url(#iKRJ9ue)" class="q_2gpqbnn"/><path fill="url(#iSzj9ae)" class="q_2gpqbnn"/></g><g filter="url(#iM9Lxcb)"><rect transform="scale(-1 1)rotate(-7.657 106.798 156.208)" class="zel2068zd"/></g><path fill="url(#iQrawbb)" class="ejf7kubhl"/><path fill="url(#iGmRzpd)" transform="scale(-1 1)rotate(-4.337 82.026 183.698)" class="z8jy9-b3h"/><path fill="url(#i7HS5Kd)" class="dhl3fvzyq"/><path fill="url(#istyCxe)" class="dhl3fvzyq"/><g filter="url(#iYBa8ke)"><path fill="url(#iMGVPHc)" class="kapwmk5on"/><path fill="url(#iVDOKwc)" class="kapwmk5on"/><path fill="url(#iFcWxrc)" class="kapwmk5on"/><path fill="url(#iIdc6Ad)" class="kapwmk5on"/></g><g filter="url(#iK3aoee)"><path class="y3s89cb0p"/><path fill="url(#iOkzWud)" class="p37dkg_gm"/></g><g filter="url(#iR9Hgmw)"><path class="ncq810t9m"/><path fill="url(#iPkYdUc)" class="p37dkg_gm"/></g><path fill="url(#iqbCCib)" class="t9domgbao"/><path fill="url(#iOux0gd)" class="t9domgbao"/><path fill="url(#iK0I3cb)" class="t9domgbao"/><g filter="url(#iBg17oe)"><path fill="url(#iro18fV)" class="difn51jsi"/><path fill="url(#ivoVCGu)" class="difn51jsi"/><path fill="url(#iExqujb)" class="difn51jsi"/></g><g filter="url(#ilvDuhc)"><path class="s57b1sjgv"/><path fill="url(#iwWZyJN)" class="fuk4r0b9y"/><path fill="url(#iBKljzd)" class="fuk4r0b9y"/><path fill="url(#iNRrf7J)" class="fuk4r0b9y"/><path fill="url(#i4g3nsK)" class="fuk4r0b9y"/><path fill="url(#iQFz4TW)" class="fuk4r0b9y"/></g><path fill="url(#iTE5Ome)" class="c3llg3bbh"/><path fill="url(#ixAGnJc)" class="c3llg3bbh"/><path fill="url(#iaH5dwc)" class="c3llg3bbh"/><path fill="url(#i956Bxc)" class="c3llg3bbh"/><path fill="url(#iZBwaKA)" class="c3llg3bbh"/><path class="q1zx8nb7h"/><path fill="url(#imCWhEe)" class="ptvv_ciwp"/><path fill="url(#iFBNoNc)" class="ptvv_ciwp"/><path fill="url(#iU8DXVc)" class="ptvv_ciwp"/><path class="z8tduhbjs"/><path class="z38gl_n6u"/><path fill="url(#idHLpab)" class="wqcho7c9g"/><path fill="url(#ifP2Fvn)" class="wqcho7c9g"/><path fill="url(#ilYM9Rd)" class="wqcho7c9g"/><path fill="url(#iHVA9Fb)" class="wqcho7c9g"/><path fill="url(#iGxx55b)" class="wqcho7c9g"/><circle fill="url(#iBmeYYs)" transform="matrix(-1 0 0 1 7.459 17.491)" class="am9uocbqt"/><g filter="url(#iBdhPae)"><path class="jycraqbfi"/></g><g filter="url(#iKHejfI)"><path clip-rule="evenodd" class="agjvu2bqx"/></g><g filter="url(#iE6Rhid)"><path class="i-ycqsnid"/></g><g filter="url(#igAbATy)"><path fill="url(#ibwslKF)" class="vr_1bpgok"/><path fill="url(#iJV0Dnd)" class="vr_1bpgok"/><path fill="url(#iFxHSeb)" class="vr_1bpgok"/></g><path clip-rule="evenodd" class="b_7lymb9p"/><g filter="url(#iQ1NLHd)"><path clip-rule="evenodd" class="d-rnr-izw"/></g><path class="e6rkvj0nk"/><path fill="url(#iqpdOSb)" class="a3z451bhu"/><path fill="url(#iNkYHPd)" class="nj9f_kb0e"/><ellipse fill="url(#ipECBte)" transform="scale(-1 1)rotate(24.61 -19.66 -32.9)" class="m1l7k9jve"/><g filter="url(#iRhqlNd)"><path fill="url(#iKhibHb)" class="x2k51tb9n"/></g><g filter="url(#idAWnjS)"><path fill="url(#iGGWPmQ)" class="jdqaa4tpp"/></g><defs><radialGradient id="iScvuce" cx="0" cy="0" r="1" gradientTransform="matrix(2.34375 2.75 -.60904 .51907 15.45 12.521)" gradientUnits="userSpaceOnUse"><stop class="p8cjc8bgx"/><stop offset="1" class="o7s7rsbjo"/></radialGradient><radialGradient id="i7AimMb" cx="0" cy="0" r="1" gradientTransform="rotate(176.424 9.283 8.45)scale(1.50293 1.62478)" gradientUnits="userSpaceOnUse"><stop class="ppddtcccf"/><stop offset="1" class="ircb6-b3r"/></radialGradient><radialGradient id="iUctc4d" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.57031 -1.46069 0 .84 .234)" gradientUnits="userSpaceOnUse"><stop offset=".238" class="ygdc80fko"/><stop offset="1" class="a5_lx-bnb"/></radialGradient><radialGradient id="iETpATd" cx="0" cy="0" r="1" gradientTransform="rotate(-14.821 2.856 -4.348)scale(.48867)" gradientUnits="userSpaceOnUse"><stop class="tl0sw7mkk"/><stop offset="1" class="xu259ab4x"/></radialGradient><radialGradient id="iPmd0rd" cx="0" cy="0" r="1" gradientTransform="matrix(.50415 0 0 .66877 0 .727)" gradientUnits="userSpaceOnUse"><stop class="hyb__5ivb"/><stop offset="1" class="wfraawh3t"/></radialGradient><radialGradient id="iGmRzpd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.30831 .72148 -1.24915 -2.26517 1.33 1.557)" gradientUnits="userSpaceOnUse"><stop class="pxvqh6bla"/><stop offset=".912" class="iz9008bnp"/></radialGradient><radialGradient id="i7HS5Kd" cx="0" cy="0" r="1" gradientTransform="rotate(151.587 7.537 5.241)scale(.54183 .76481)" gradientUnits="userSpaceOnUse"><stop offset=".101" class="hymklqb8k"/><stop offset=".684" class="s2f2c_bct"/></radialGradient><radialGradient id="istyCxe" cx="0" cy="0" r="1" gradientTransform="matrix(.12006 -.29152 .4375 .18018 16.255 6.582)" gradientUnits="userSpaceOnUse"><stop class="zkj259b3a"/><stop offset="1" class="iv0p50s_n"/></radialGradient><radialGradient id="iVDOKwc" cx="0" cy="0" r="1" gradientTransform="matrix(.84375 -.04687 .05715 1.0287 12.998 5.561)" gradientUnits="userSpaceOnUse"><stop offset=".156" class="l7mbhnbzh"/><stop offset="1" class="biuc-6bfh"/></radialGradient><radialGradient id="iFcWxrc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -5.1875 2.01562 0 15.895 6.749)" gradientUnits="userSpaceOnUse"><stop offset=".219" class="wcectbccf"/><stop offset="1" class="b3jcjo1jv"/></radialGradient><radialGradient id="iIdc6Ad" cx="0" cy="0" r="1" gradientTransform="matrix(0 .39063 -.60919 0 15.066 5.608)" gradientUnits="userSpaceOnUse"><stop offset=".155" class="ie_w39bfj"/><stop offset="1" class="dx40lk_kc"/></radialGradient><radialGradient id="iOkzWud" cx="0" cy="0" r="1" gradientTransform="matrix(-1.53488 -.4317 .92512 -3.28923 16.122 3.326)" gradientUnits="userSpaceOnUse"><stop class="k_urnmdao"/><stop offset="1" class="w7r1zi1yh"/></radialGradient><radialGradient id="iPkYdUc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.53488 -.4317 .92512 -3.28923 16.122 3.326)" gradientUnits="userSpaceOnUse"><stop class="tzf255bgc"/><stop offset="1" class="ctuud_14h"/></radialGradient><radialGradient id="iqbCCib" cx="0" cy="0" r="1" gradientTransform="rotate(-163.812 7.038 1.78)scale(.75656 .36927)" gradientUnits="userSpaceOnUse"><stop offset=".17" class="i8aj4_5_r"/><stop offset="1" class="u2yjj3mld"/></radialGradient><radialGradient id="iOux0gd" cx="0" cy="0" r="1" gradientTransform="rotate(100.843 4.506 8.06)scale(1.20119 1.25169)" gradientUnits="userSpaceOnUse"><stop offset=".556" class="chiqx4b_a"/><stop offset="1" class="vmk6x9_kg"/><stop offset="1" class="hq1ekobkc"/></radialGradient><radialGradient id="ivoVCGu" cx="0" cy="0" r="1" gradientTransform="matrix(-2.45369 2.93958 -5.96661 -4.98038 10.886 18.039)" gradientUnits="userSpaceOnUse"><stop offset=".434" class="oiy_54b9a"/><stop offset="1" class="rm4aiz5dn"/></radialGradient><radialGradient id="iExqujb" cx="0" cy="0" r="1" gradientTransform="rotate(143.616 2.47 11.367)scale(1.10629 6.64432)" gradientUnits="userSpaceOnUse"><stop offset=".043" class="v5lz4sb9o"/><stop offset="1" class="m_uy2vb_d"/></radialGradient><radialGradient id="iwWZyJN" cx="0" cy="0" r="1" gradientTransform="rotate(-122.302 11.747 7.148)scale(6.08182 1.60193)" gradientUnits="userSpaceOnUse"><stop offset=".07" class="mngz2ebss"/><stop offset="1" class="ttsumpbek"/></radialGradient><radialGradient id="iBKljzd" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.42188 -1.38588 0 11.17 16.194)" gradientUnits="userSpaceOnUse"><stop class="f3j6dkfip"/><stop offset="1" class="fxoxl0blj"/></radialGradient><radialGradient id="i4g3nsK" cx="0" cy="0" r="1" gradientTransform="matrix(-.14062 -.17969 .6458 -.50541 15.865 28.108)" gradientUnits="userSpaceOnUse"><stop class="ryq0o3qru"/><stop offset="1" class="yfqxgqb1h"/></radialGradient><radialGradient id="iQFz4TW" cx="0" cy="0" r="1" gradientTransform="matrix(-6.375 -1.81248 4.6745 -16.4415 15.545 19.241)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="ex23x-brg"/><stop offset="1" class="ux4w7lb6c"/></radialGradient><radialGradient id="iTE5Ome" cx="0" cy="0" r="1" gradientTransform="matrix(.09374 -1.53125 2.45635 .15037 16.998 29.46)" gradientUnits="userSpaceOnUse"><stop class="cl2mlwbhs"/><stop offset="1" class="yvuyjoqpy"/></radialGradient><radialGradient id="ixAGnJc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.0625 -.21876 .15137 -.73521 20.107 28.522)" gradientUnits="userSpaceOnUse"><stop class="m3n9jy0fh"/><stop offset="1" class="hdzwkybza"/></radialGradient><radialGradient id="iaH5dwc" cx="0" cy="0" r="1" gradientTransform="matrix(-.59376 -1.71875 .84778 -.29287 16.092 29.757)" gradientUnits="userSpaceOnUse"><stop offset=".08" class="a541b3bqx"/><stop offset="1" class="zc8ie-1dg"/></radialGradient><radialGradient id="iU8DXVc" cx="0" cy="0" r="1" gradientTransform="rotate(-47.125 33.09 9.018)scale(1.99789 1.10527)" gradientUnits="userSpaceOnUse"><stop class="xh_da2q2q"/><stop offset="1" class="stwbr2bhy"/></radialGradient><radialGradient id="idHLpab" cx="0" cy="0" r="1" gradientTransform="rotate(-88.915 13.89 2.352)scale(4.95211 1.34022)" gradientUnits="userSpaceOnUse"><stop class="dkjt4cbcx"/><stop offset="1" class="w9ku-ifwq"/></radialGradient><radialGradient id="ifP2Fvn" cx="0" cy="0" r="1" gradientTransform="matrix(-3.65186 0 0 -15.6875 13.15 14.306)" gradientUnits="userSpaceOnUse"><stop offset=".436" class="p0p0ijbbx"/><stop offset=".967" class="dvcrl_y_s"/></radialGradient><radialGradient id="ilYM9Rd" cx="0" cy="0" r="1" gradientTransform="matrix(4.78125 .78125 -1.79108 10.96143 9.775 15.118)" gradientUnits="userSpaceOnUse"><stop offset=".781" class="jx6m9tune"/><stop offset=".931" class="g41565bda"/></radialGradient><radialGradient id="iHVA9Fb" cx="0" cy="0" r="1" gradientTransform="matrix(-.51563 1.34375 -3.67742 -1.41111 13.212 8.274)" gradientUnits="userSpaceOnUse"><stop offset=".297" class="mwuao6bkl"/><stop offset="1" class="jw-yqmb7v"/></radialGradient><radialGradient id="iGxx55b" cx="0" cy="0" r="1" gradientTransform="matrix(.67188 .9433 -1.66928 1.18896 11.4 8.612)" gradientUnits="userSpaceOnUse"><stop class="aflh_2rif"/><stop offset="1" class="ujjvz6nrm"/></radialGradient><radialGradient id="iBmeYYs" cx="0" cy="0" r="1" gradientTransform="rotate(90 .008 .406)scale(.90625)" gradientUnits="userSpaceOnUse"><stop offset=".256" class="qf2lyobnm"/><stop offset="1" class="l21zq2bsp"/></radialGradient><radialGradient id="iJV0Dnd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.0907 .20313 -.4206 -2.25834 12.959 10.352)" gradientUnits="userSpaceOnUse"><stop offset=".12" class="xot8u71lw"/><stop offset="1" class="jjp3z2beb"/></radialGradient><radialGradient id="iFxHSeb" cx="0" cy="0" r="1" gradientTransform="rotate(135.955 2.91 7.046)scale(2.65202 1.5046)" gradientUnits="userSpaceOnUse"><stop offset=".204" class="lz70c3nqo"/><stop offset="1" class="pt5v4qb1w"/></radialGradient><radialGradient id="iqpdOSb" cx="0" cy="0" r="1" gradientTransform="matrix(-.27344 0 0 -.53125 15.361 5.636)" gradientUnits="userSpaceOnUse"><stop offset=".895" class="l0aricxam"/><stop offset="1" class="n9r91ylyy"/></radialGradient><radialGradient id="iNkYHPd" cx="0" cy="0" r="1" gradientTransform="matrix(-.25 0 0 -.54102 15.53 5.657)" gradientUnits="userSpaceOnUse"><stop class="gv3iwdbvq"/><stop offset=".813" class="ubyl24bdb"/></radialGradient><linearGradient id="ibMWDnd" x1="17.662" x2="19.545" y1="15.545" y2="17.584" gradientUnits="userSpaceOnUse"><stop class="o52vxyscb"/><stop offset="1" class="u-867gbtx"/></linearGradient><linearGradient id="iB5PCEr" x1="23.107" x2="21.857" y1="21.834" y2="22.771" gradientUnits="userSpaceOnUse"><stop class="n6l6ilaec"/><stop offset="1" class="vjqn9lx3p"/></linearGradient><linearGradient id="iLR5FNe" x1="26.771" x2="25.037" y1="28.678" y2="26.334" gradientUnits="userSpaceOnUse"><stop class="uug2ubxhk"/><stop offset="1" class="deyia0bkx"/></linearGradient><linearGradient id="ilWQc7b" x1="26.716" x2="26.358" y1="27.115" y2="27.365" gradientUnits="userSpaceOnUse"><stop class="p8mdyfi9b"/><stop offset="1" class="g6zbvk7ui"/></linearGradient><linearGradient id="iKRJ9ue" x1="18.248" x2="19.998" y1="16.381" y2="18.678" gradientUnits="userSpaceOnUse"><stop class="ly5_jc0cc"/><stop offset="1" class="sxo3xwbvl"/></linearGradient><linearGradient id="iSzj9ae" x1="18.138" x2="18.662" y1="16.443" y2="17.209" gradientUnits="userSpaceOnUse"><stop offset=".098" class="iykv72k7v"/><stop offset="1" class="qg5pcsysc"/></linearGradient><linearGradient id="iQrawbb" x1="15.127" x2="14.252" y1="12.872" y2="10.481" gradientUnits="userSpaceOnUse"><stop class="t55apucyo"/><stop offset=".787" class="biw5o_cgj"/></linearGradient><linearGradient id="iMGVPHc" x1="13.31" x2="16.173" y1="6.304" y2="6.476" gradientUnits="userSpaceOnUse"><stop class="dxjajos_o"/><stop offset="1" class="gu4uskbqq"/></linearGradient><linearGradient id="iK0I3cb" x1="13.355" x2="13.207" y1="5.521" y2="5.532" gradientUnits="userSpaceOnUse"><stop class="o01zddb6n"/><stop offset="1" class="h5b83fbqu"/></linearGradient><linearGradient id="iro18fV" x1="9.865" x2="7.637" y1="22.898" y2="20.954" gradientUnits="userSpaceOnUse"><stop offset=".211" class="pat1zf4-w"/><stop offset="1" class="wtea7v6lu"/></linearGradient><linearGradient id="iNRrf7J" x1="12.092" x2="12.092" y1="16.085" y2="16.429" gradientUnits="userSpaceOnUse"><stop offset=".136" class="x5p6yzbmf"/><stop offset="1" class="cnh3p8b3x"/></linearGradient><linearGradient id="i956Bxc" x1="17.561" x2="17.475" y1="29.632" y2="29.319" gradientUnits="userSpaceOnUse"><stop class="l138bfbcs"/><stop offset="1" class="oxce79bcz"/></linearGradient><linearGradient id="iZBwaKA" x1="15.592" x2="16.17" y1="30.007" y2="29.788" gradientUnits="userSpaceOnUse"><stop offset=".064" class="lhdz7oxfj"/><stop offset="1" class="csaq2_bel"/></linearGradient><linearGradient id="imCWhEe" x1="6.982" x2="6.389" y1="27.991" y2="28.163" gradientUnits="userSpaceOnUse"><stop class="oxg1n1wjw"/><stop offset="1" class="y0g_czb9f"/></linearGradient><linearGradient id="iFBNoNc" x1="4.857" x2="5.037" y1="28.065" y2="27.917" gradientUnits="userSpaceOnUse"><stop class="p6qc3nb-j"/><stop offset="0" class="ezcqmvbni"/><stop offset="1" class="stwbr2bhy"/></linearGradient><linearGradient id="ibwslKF" x1="11.107" x2="9.998" y1="9.132" y2="12.585" gradientUnits="userSpaceOnUse"><stop offset=".118" class="u1dukib7n"/><stop offset="1" class="mk0srdu2z"/></linearGradient><linearGradient id="ipECBte" x1="-.007" x2=".179" y1=".05" y2=".11" gradientUnits="userSpaceOnUse"><stop class="vc--wpv5i"/><stop offset="1" class="stui2mbih"/></linearGradient><linearGradient id="iKhibHb" x1="15.764" x2="11.139" y1="27.429" y2="17.288" gradientUnits="userSpaceOnUse"><stop class="v9kimlbms"/><stop offset="1" class="g24ahctiy"/></linearGradient><linearGradient id="iGGWPmQ" x1="5.619" x2="9.93" y1="25.338" y2="19.966" gradientUnits="userSpaceOnUse"><stop class="ckhjb_bgt"/><stop offset="1" class="rnrhdzckq"/></linearGradient><filter id="i6f5pLb" width="7.179" height="6.928" x="12.684" y="10.901" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.5" dy="-.75"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.760784 0 0 0 0 0.501961 0 0 0 0 0.513726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_3403"/></filter><filter id="in1rqsd" width="2.607" height="2.722" x="17.055" y="15.172" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_2_3403" stdDeviation=".05"/></filter><filter id="iY3YyWW" width="8.674" height="11.796" x="19.138" y="17.504" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.741176 0 0 0 0 0.647059 0 0 0 0 0.811765 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_3403"/></filter><filter id="ioI58Pd" width="1.68" height="1.68" x="26.697" y="28.248" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.835294 0 0 0 0 0.819608 0 0 0 0 0.835294 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_3403"/></filter><filter id="i7QmHae" width="2.726" height="3.079" x="17.73" y="15.94" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.211765 0 0 0 0 0.133333 0 0 0 0 0.27451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_3403"/></filter><filter id="iM9Lxcb" width="1.093" height="1.661" x="18.717" y="15.565" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.15"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.858824 0 0 0 0 0.639216 0 0 0 0 0.592157 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_3403"/></filter><filter id="iYBa8ke" width="4.443" height="5.249" x="11.73" y="3.363" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2" dy="-.2"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.815686 0 0 0 0 0.596078 0 0 0 0 0.580392 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_3403"/></filter><filter id="iK3aoee" width="6.813" height="7.403" x="9.522" y="1.701" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.4" dy=".4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.972549 0 0 0 0 0.737255 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_3403"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.956863 0 0 0 0 0.788235 0 0 0 0 0.631373 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_2_3403" result="effect2_innerShadow_2_3403"/></filter><filter id="iR9Hgmw" width="6.813" height="7.403" x="9.522" y="1.701" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.4" dy=".4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.290196 0 0 0 0 0.266667 0 0 0 0 0.27451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_3403"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0901961 0 0 0 0 0.0392157 0 0 0 0 0.133333 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_2_3403" result="effect2_innerShadow_2_3403"/></filter><filter id="iBg17oe" width="8.674" height="14.771" x="3.726" y="15.476" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".75" dy="-.75"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.439216 0 0 0 0 0.388235 0 0 0 0 0.486275 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_3403"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.537255 0 0 0 0 0.423529 0 0 0 0 0.635294 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_2_3403" result="effect2_innerShadow_2_3403"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy=".25"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.529412 0 0 0 0 0.490196 0 0 0 0 0.537255 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_2_3403" result="effect3_innerShadow_2_3403"/></filter><filter id="ilvDuhc" width="10.972" height="14.104" x="9.484" y="15.994" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy="-.2"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.619608 0 0 0 0 0.592157 0 0 0 0 0.611765 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_3403"/></filter><filter id="iBdhPae" width="5.442" height="5.875" x="8.117" y="8.468" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_2_3403" stdDeviation=".375"/></filter><filter id="iKHejfI" width="7.59" height="10.511" x="4.358" y="9.157" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.909804 0 0 0 0 0.678431 0 0 0 0 0.639216 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_3403"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.4" dy=".4"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.980392 0 0 0 0 0.807843 0 0 0 0 0.713726 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_2_3403" result="effect2_innerShadow_2_3403"/></filter><filter id="iE6Rhid" width="6.084" height="9.069" x="4.678" y="9.902" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_2_3403" stdDeviation=".3"/></filter><filter id="igAbATy" width="4.758" height="4.525" x="8.451" y="8.654" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.15"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.392157 0 0 0 0 0.254902 0 0 0 0 0.639216 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_3403"/></filter><filter id="iQ1NLHd" width="1.013" height=".568" x="14.498" y="4.307" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0705882 0 0 0 0 0.0588235 0 0 0 0 0.054902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_3403"/></filter><filter id="iRhqlNd" width="6.844" height="12.891" x="10.139" y="16.116" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_2_3403" stdDeviation=".5"/></filter><filter id="idAWnjS" width="6.45" height="8.475" x="4.584" y="18.044" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_2_3403" stdDeviation=".375"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:woman-with-white-cane-facing-right-light" /></template>
<style>
.a3z451bhu {
  d: path("M15.033 5.657v-.004c0-.32.138-.58.307-.58c.17 0 .306.26.306.58v.004z");
}

.a5_lx-bnb {
  stop-color: var(--svg-color--ccaae9, #CCAAE9);
}

.a541b3bqx {
  stop-color: var(--svg-color--515279, #515279);
}

.aflh_2rif {
  stop-color: var(--svg-color--281a4b, #281A4B);
}

.agjvu2bqx {
  fill: var(--svg-color--f0b6a6, #F0B6A6);
  fill-rule: evenodd;
  d: path("M6.002 19.238a.614.614 0 0 0 .776-.407c1.215-3.922 3.165-6.29 4.541-7.545c.438-.4.516-1.082.128-1.53c-.346-.401-.944-.472-1.348-.13c-1.626 1.38-3.91 3.976-5.316 8.605a.59.59 0 0 0 .382.73z");
}

.am9uocbqt {
  cx: 0.551px;
  cy: 0.551px;
  r: 0.551px;
}

.b_7lymb9p {
  fill: var(--svg-color--86004c, #86004C);
  fill-rule: evenodd;
  d: path("M14.893 6.77a.125.125 0 0 0 .002.178c.238.233.582.293.692.304a.125.125 0 0 0 .025-.248c-.093-.01-.366-.062-.542-.235a.125.125 0 0 0-.177.002");
}

.b3jcjo1jv {
  stop-color: var(--svg-color--ffcdb7, #FFCDB7);
  stop-opacity: 0;
}

.biuc-6bfh {
  stop-color: var(--svg-color--eeb298, #EEB298);
  stop-opacity: 0;
}

.biw5o_cgj {
  stop-color: var(--svg-color--816fa6, #816FA6);
}

.c3llg3bbh {
  d: path("m15.244 28.636l.391 1.285a.25.25 0 0 0 .315.166l3.737-1.183c.195-.062.326-.265.244-.452c-.107-.245-.332-.5-.886-.656c-.59-.167-1.672-.262-2.306-.318l-.21-.018v-.002z");
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

.d-rnr-izw {
  fill: var(--svg-color--2c2828, #2C2828);
  fill-rule: evenodd;
  d: path("M15.126 4.625a.8.8 0 0 1 .217-.016a.15.15 0 0 0 .037-.298a1 1 0 0 0-.313.02a1 1 0 0 0-.408.173a.15.15 0 0 0 .178.24c.085-.062.19-.1.29-.12");
}

.deyia0bkx {
  stop-color: var(--svg-color--f3386a, #F3386A);
}

.dhl3fvzyq {
  d: path("M16.37 5.827a1 1 0 0 1-.259-.457h-.18v1.125c.215.137.523.115.614-.09c.078-.176.02-.394-.176-.578");
}

.difn51jsi {
  d: path("m8.67 19.96l.89-3.734h1.781c.053.614.152 2.215.29 3.515s-.492 2.032-.766 2.313L6.42 26.366c.198.662.627 2.025.727 2.625c.077.462-.145.768-.351.953c-.094.083-.235.064-.319-.03L3.79 26.92a.25.25 0 0 1 .019-.353l.986-.887c1.041-1.365 3.19-4.194 3.453-4.594c.181-.276.39-.917.422-1.125");
}

.dkjt4cbcx {
  stop-color: var(--svg-color--7966a4, #7966A4);
}

.dvcrl_y_s {
  stop-color: var(--svg-color--6c5d89, #6C5D89);
}

.dx40lk_kc {
  stop-color: var(--svg-color--fabfa4, #FABFA4);
  stop-opacity: 0;
}

.dxjajos_o {
  stop-color: var(--svg-color--f0b5a2, #F0B5A2);
}

.e6rkvj0nk {
  fill: var(--svg-color--fff, #fff);
  d: path("M15.639 5.657h-.989c0-.391.222-.709.495-.709c.272 0 .494.318.494.71");
}

.ejf7kubhl {
  d: path("M14.61 10.536c-.28-.712-.773-1.224-.983-1.39l.038 4.468l1.786-.836c-.278-.523-.489-1.351-.84-2.242");
}

.ex23x-brg {
  stop-color: var(--svg-color--8c8388, #8C8388);
  stop-opacity: 0;
}

.exc3v1b0k {
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M19.517 16.028a1.211 1.211 0 1 0-.117 1.212");
}

.ezcqmvbni {
  stop-color: var(--svg-color--443a80, #443A80);
}

.f3j6dkfip {
  stop-color: var(--svg-color--99919a, #99919A);
}

.ft5dv1b6b {
  fill: none;
}

.fuk4r0b9y {
  d: path("M15.022 18.577c-.384-1.05-.717-2.029-.774-2.383H9.506c-.1 1.375.144 1.712.773 2.422c.693.782 2.172 2.43 2.54 2.895c.35.35.5.789.554.98l2.262 7.43a.25.25 0 0 0 .315.166l3.737-1.183c.195-.061.326-.265.244-.452c-.107-.245-.332-.5-.886-.656c-.663-.188-1.943-.284-2.516-.336c-.213-1.766-.66-5.431-.734-5.969c-.094-.672-.227-1.414-.774-2.914");
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

.ghq9gsa-q {
  cx: 0.84px;
  cy: 0.84px;
  r: 0.84px;
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

.hdrw_q19a {
  fill-rule: evenodd;
  d: path("M13.775 11.757a1.05 1.05 0 0 0-.485 1.403c1.832 3.77 4.235 4.912 5.72 4.627a1.05 1.05 0 0 0-.396-2.062s-.026.004-.082 0a1.2 1.2 0 0 1-.24-.044a2.7 2.7 0 0 1-.803-.404c-.65-.457-1.494-1.354-2.31-3.035a1.05 1.05 0 0 0-1.404-.485");
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

.i-ycqsnid {
  stroke: var(--svg-color--ffd0bb, #FFD0BB);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M9.962 10.702c-.969.906-3.156 3.219-4.484 7.469");
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

.iykv72k7v {
  stop-color: var(--svg-color--62516b, #62516B);
}

.iz9008bnp {
  stop-color: var(--svg-color--eab1a3, #EAB1A3);
}

.jdqaa4tpp {
  d: path("M8.81 21.142L5.334 25.57l.514.199l3.485-3.708a3 3 0 0 0 .76-1.494l.19-1l-.75-.773l-.544 1.993a1 1 0 0 1-.179.355");
}

.jjp3z2beb {
  stop-color: var(--svg-color--8974b4, #8974B4);
  stop-opacity: 0;
}

.jw-yqmb7v {
  stop-color: var(--svg-color--6f5797, #6F5797);
  stop-opacity: 0;
}

.jx6m9tune {
  stop-color: var(--svg-color--8272a4, #8272A4);
  stop-opacity: 0;
}

.jycraqbfi {
  fill: var(--svg-color--442e79, #442E79);
  d: path("M12.603 10.985c.31-.248.178-.39.178-.818c0-.749-.013-.95-.762-.95a1.35 1.35 0 0 0-.883.327c-.95.692-1.789 1.592-2.27 2.135l2.04 1.914a58 58 0 0 0 1.697-2.608");
}

.k_urnmdao {
  stop-color: var(--svg-color--ffecb8, #FFECB8);
}

.kapwmk5on {
  d: path("M16.145 4.863c-.038-.8-.298-1.187-.42-1.3h-3.732l-.063 3.164c.867 2.121 3.512 2.212 3.906 1.445c.396-.768.354-2.381.31-3.309");
}

.kczqywbmk {
  fill-rule: evenodd;
  d: path("M19.323 17.79a.45.45 0 0 0-.1.629l7.774 10.695a.45.45 0 1 0 .728-.53L19.952 17.89a.45.45 0 0 0-.629-.1");
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

.mwuao6bkl {
  stop-color: var(--svg-color--4d395c, #4D395C);
}

.n6l6ilaec {
  stop-color: var(--svg-color--d4c6dc, #D4C6DC);
}

.n7vpf3uhv {
  fill: var(--svg-color--e4aa95, #E4AA95);
  fill-rule: evenodd;
  d: path("M13.775 11.757a1.05 1.05 0 0 0-.485 1.403c1.832 3.77 4.235 4.912 5.72 4.627a1.05 1.05 0 0 0-.396-2.062s-.026.004-.082 0a1.2 1.2 0 0 1-.24-.044a2.7 2.7 0 0 1-.803-.404c-.65-.457-1.494-1.354-2.31-3.035a1.05 1.05 0 0 0-1.404-.485");
}

.n9r91ylyy {
  stop-color: var(--svg-color--824d44, #824D44);
}

.ncq810t9m {
  fill: var(--svg-color--241823, #241823);
  d: path("M16.265 3.516c.172-.41-.017-.843-.113-.992c-.367-.672-1.128-.716-1.567-.523c-.516.226-.67.347-1.504.11c-.836-.24-1.867-.13-2.406.839s.047 2.059-.086 2.652c-.133.594-.512.653-.652 1.34c-.118.953.472 1.574.996 1.715c.523.14 1.601 0 1.953-.875c.575-1.432.184-2.11.309-2.828c.125-.719.555-.922 1.336-.766c.92.184 1.505-.126 1.734-.672");
}

.nj9f_kb0e {
  d: path("m15.229 5.657l-.004-.072c0-.186.078-.336.175-.336c.098 0 .176.15.176.336l-.004.072z");
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

.p37dkg_gm {
  d: path("M16.265 3.516c.172-.41-.017-.843-.113-.992c-.367-.672-1.128-.716-1.567-.523c-.516.226-.67.347-1.504.11c-.836-.24-1.867-.13-2.406.839s.047 2.059-.086 2.652c-.133.594-.512.653-.652 1.34c-.118.953.472 1.574.996 1.715c.523.14 1.601 0 1.953-.875c.575-1.432.184-2.11.309-2.828c.125-.719.555-.922 1.336-.766c.92.184 1.505-.126 1.734-.672");
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

.ppddtcccf {
  stop-color: var(--svg-color--d29b87, #D29B87);
}

.pt5v4qb1w {
  stop-color: var(--svg-color--9075ca, #9075CA);
  stop-opacity: 0;
}

.ptvv_ciwp {
  d: path("m4.803 25.668l1.638.677l-.022.021l.108.355c.216.713.535 1.763.62 2.27c.076.462-.146.768-.352.952c-.093.084-.234.064-.318-.029L3.79 26.92a.25.25 0 0 1 .018-.353l.986-.887z");
}

.pxvqh6bla {
  stop-color: var(--svg-color--bb816f, #BB816F);
}

.q_2gpqbnn {
  d: path("M18.909 16.023a.2.2 0 0 0-.28-.045l-.817.59a.2.2 0 0 0-.045.28l1.51 2.088a.2.2 0 0 0 .279.045l.817-.59a.2.2 0 0 0 .045-.28z");
}

.q1zx8nb7h {
  fill: var(--svg-color--45437a, #45437A);
  d: path("m4.803 25.668l1.638.677l-.022.021l.108.355c.216.713.535 1.763.62 2.27c.076.462-.146.768-.352.952c-.093.084-.234.064-.318-.029L3.79 26.92a.25.25 0 0 1 .018-.353l.986-.887z");
}

.qat-h_3-d {
  d: path("m24.905 26.235l2.092 2.879a.45.45 0 1 0 .728-.53l-2.092-2.878z");
}

.qf2lyobnm {
  stop-color: var(--svg-color--e8a99a, #E8A99A);
}

.qg5pcsysc {
  stop-color: var(--svg-color--483a55, #483A55);
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

.s2f2c_bct {
  stop-color: var(--svg-color--ffc4a7, #FFC4A7);
}

.s57b1sjgv {
  fill: var(--svg-color--8c8393, #8C8393);
  d: path("M15.022 18.577c-.384-1.05-.717-2.029-.774-2.383H9.506c-.1 1.375.144 1.712.773 2.422c.693.782 2.172 2.43 2.54 2.895c.35.35.5.789.554.98l2.262 7.43a.25.25 0 0 0 .315.166l3.737-1.183c.195-.061.326-.265.244-.452c-.107-.245-.332-.5-.886-.656c-.663-.188-1.943-.284-2.516-.336c-.213-1.766-.66-5.431-.734-5.969c-.094-.672-.227-1.414-.774-2.914");
}

.spmxexb0c {
  stroke: var(--svg-color--33241a, #33241A);
  stroke-width: var(--svg-stroke-width--0-35px, 0.35px);
  d: path("M19.502 15.998a1.21 1.21 0 1 0-.101 1.24");
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

.t55apucyo {
  stop-color: var(--svg-color--725d9d, #725D9D);
}

.t9domgbao {
  d: path("m13.452 6.325l-.2-1.44a.727.727 0 0 0 .2 1.44");
}

.tl0sw7mkk {
  stop-color: var(--svg-color--e9d9f5, #E9D9F5);
}

.ttsumpbek {
  stop-color: var(--svg-color--897998, #897998);
  stop-opacity: 0;
}

.tzf255bgc {
  stop-color: var(--svg-color--534b49, #534B49);
}

.u-867gbtx {
  stop-color: var(--svg-color--443d44, #443D44);
  stop-opacity: 0;
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

.ujjvz6nrm {
  stop-color: var(--svg-color--483368, #483368);
  stop-opacity: 0;
}

.uug2ubxhk {
  stop-color: var(--svg-color--e82b8e, #E82B8E);
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

.vjqn9lx3p {
  stop-color: var(--svg-color--cdb4e3, #CDB4E3);
}

.vmk6x9_kg {
  stop-color: var(--svg-color--dd9a7e, #DD9A7E);
}

.vr_1bpgok {
  d: path("M12.45 11.218a1.355 1.355 0 1 0-1.73-2.088c-.95.692-1.79 1.592-2.27 2.135l2.04 1.914a154 154 0 0 1 1.959-1.961");
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

.wfraawh3t {
  stop-color: var(--svg-color--e4d4ea, #E4D4EA);
  stop-opacity: 0;
}

.wqcho7c9g {
  d: path("M12.314 8.612c-.89 0-1.136.215-1.433.407l-1.024 2.597c-.3 1.4-.364 3.636-.359 4.578h4.766c.258-.656.677-2.675.515-4.578c-.164-1.93-1.207-2.902-2.465-3.004");
}

.wtea7v6lu {
  stop-color: var(--svg-color--9f9c9f, #9F9C9F);
}

.x2k51tb9n {
  d: path("m14.639 21.194l1.343 6.5l-.359.313l-1.469-6.531L11.14 17.6l.703-.485z");
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

.xu259ab4x {
  stop-color: var(--svg-color--e9d9f5, #E9D9F5);
  stop-opacity: 0;
}

.y0g_czb9f {
  stop-color: var(--svg-color--5a577e, #5A577E);
  stop-opacity: 0;
}

.y3s89cb0p {
  fill: var(--svg-color--ffe0af, #FFE0AF);
  d: path("M16.265 3.516c.172-.41-.017-.843-.113-.992c-.367-.672-1.128-.716-1.567-.523c-.516.226-.67.347-1.504.11c-.836-.24-1.867-.13-2.406.839s.047 2.059-.086 2.652c-.133.594-.512.653-.652 1.34c-.118.953.472 1.574.996 1.715c.523.14 1.601 0 1.953-.875c.575-1.432.184-2.11.309-2.828c.125-.719.555-.922 1.336-.766c.92.184 1.505-.126 1.734-.672");
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

.z38gl_n6u {
  fill: var(--svg-color--725ca6, #725CA6);
  d: path("M12.314 8.612c-.89 0-1.136.215-1.433.407l-1.024 2.597c-.3 1.4-.364 3.636-.359 4.578h4.766c.258-.656.677-2.675.515-4.578c-.164-1.93-1.207-2.902-2.465-3.004");
}

.z8jy9-b3h {
  d: path("M0 0h1.946v3.44H0z");
}

.z8tduhbjs {
  fill: var(--svg-color--2f2c2d, #2F2C2D);
  d: path("M14.634 5.146c.13-.131.349-.161.441-.16l-.302.467c-.148-.008-.303-.143-.14-.307");
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

</style>
