<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iOr1wQM)"><path clip-rule="evenodd" class="a2cki4zdz"/><path fill="url(#iH78xyQ)" clip-rule="evenodd" class="v4o_zqb9x"/><path fill="url(#it26bvc)" clip-rule="evenodd" class="v4o_zqb9x"/></g><path class="pgj01zbaf"/><g filter="url(#iGtu0Up)"><path stroke="url(#i7e5vze)" class="t2hu-p3oq"/></g><g filter="url(#iYTkvHe)"><path fill="url(#iTksytq)" clip-rule="evenodd" class="e2--ewbsp"/></g><path fill="url(#iksjITb)" class="pz752f3kh"/><path fill="url(#iB1Ax7d)" class="pz752f3kh"/><g filter="url(#iUTjoIe)"><circle fill="url(#iUctc4d)" transform="matrix(-1 0 0 1 28.42 28.227)" class="ghq9gsa-q"/><circle fill="url(#iETpATd)" transform="matrix(-1 0 0 1 28.42 28.227)" class="ghq9gsa-q"/><circle fill="url(#iPmd0rd)" transform="matrix(-1 0 0 1 28.42 28.227)" class="ghq9gsa-q"/></g><g filter="url(#iz9Zi6c)"><path fill="url(#iNsGSSd)" class="p2xgfbccg"/><path fill="url(#iLFDc3d)" class="p2xgfbccg"/></g><g filter="url(#iMbgzZb)"><rect transform="scale(-1 1)rotate(-7.657 106.617 156.519)" class="zel2068zd"/></g><path fill="url(#is5lFnb)" class="wy2-a_orr"/><path fill="url(#iJ3oyJd)" transform="scale(-1 1)rotate(-4.337 81.565 185.296)" class="z8jy9-b3h"/><path fill="url(#iJVUGUb)" transform="scale(-1 1)rotate(-4.337 81.565 185.296)" class="z8jy9-b3h"/><path fill="url(#ianRafN)" transform="scale(-1 1)rotate(-4.337 81.565 185.296)" class="z8jy9-b3h"/><path fill="url(#idJYsAd)" class="klx8rkb4d"/><path fill="url(#iHJh3xe)" class="klx8rkb4d"/><g filter="url(#isSvpoc)"><path fill="url(#ipwPTEe)" class="a6sqesncg"/><path fill="url(#i9DB0Vd)" class="a6sqesncg"/><path fill="url(#iq4qYce)" class="a6sqesncg"/><path fill="url(#i129U6d)" class="a6sqesncg"/></g><g filter="url(#ilf6Nke)"><path fill="url(#iasBbid)" class="y6kadwb9i"/><path fill="url(#iIw1afc)" class="y6kadwb9i"/><path fill="url(#i6vOpQX)" class="y6kadwb9i"/></g><path fill="url(#i4p3tVd)" class="d5_1ldb3r"/><path fill="url(#iGDc4ie)" class="d5_1ldb3r"/><path fill="url(#ih4wdeC)" class="d5_1ldb3r"/><g filter="url(#ilSKDxV)"><path fill="url(#iNjgzAc)" class="b6g2rcc6c"/><path fill="url(#iuSrGXd)" class="b6g2rcc6c"/><path fill="url(#igP5ITb)" class="b6g2rcc6c"/></g><g filter="url(#iKAcPtb)"><path class="ug8yaobdd"/><path fill="url(#ihOQtWb)" class="b7qanra0c"/><path fill="url(#itEVBzR)" class="b7qanra0c"/><path fill="url(#iwC7vXy)" class="b7qanra0c"/><path fill="url(#iglvYSc)" class="b7qanra0c"/><path fill="url(#iKnj5ib)" class="b7qanra0c"/></g><path fill="url(#iXD7Gbc)" class="wj9bins_h"/><path fill="url(#ic0EDTb)" class="wj9bins_h"/><path fill="url(#iiSnBmb)" class="wj9bins_h"/><path fill="url(#istDPNe)" class="wj9bins_h"/><path fill="url(#iG8uImb)" class="wj9bins_h"/><path class="hfq020b1u"/><path fill="url(#iLKdrZi)" class="j657_qdha"/><path fill="url(#iJzdUvc)" class="j657_qdha"/><path fill="url(#i0DhLrd)" class="j657_qdha"/><path class="oxj7i12ho"/><path fill="url(#idz5xYQ)" class="p-v_uzerw"/><path fill="url(#iYUOPfK)" class="p-v_uzerw"/><path fill="url(#izbYpqd)" class="p-v_uzerw"/><path fill="url(#i7Ofyye)" class="p-v_uzerw"/><path fill="url(#ief8Ewd)" class="p-v_uzerw"/><circle fill="url(#iBmeYYs)" transform="matrix(-1 0 0 1 7.416 17.433)" class="am9uocbqt"/><g filter="url(#igm0jfb)"><path class="j5__uftpu"/></g><g filter="url(#iyTG8ab)"><path clip-rule="evenodd" class="eh--cpbup"/></g><g filter="url(#iYu8JDd)"><path class="h8sm7gtis"/></g><g filter="url(#iAOHIUc)"><path fill="url(#ij72sTd)" class="an-n8n3gl"/><path fill="url(#iTxQAmc)" class="an-n8n3gl"/><path fill="url(#iuXMmVb)" class="an-n8n3gl"/></g><path fill="url(#iZjeeOc)" class="an-n8n3gl"/><path clip-rule="evenodd" class="z9lslngvi"/><path class="h-296qkmg"/><path fill="url(#i7ekZvc)" class="a8xggvz5s"/><path fill="url(#iEsNE0v)" class="a2e8hqb_h"/><ellipse fill="url(#ipECBte)" transform="scale(-1 1)rotate(24.61 -19.506 -32.831)" class="m1l7k9jve"/><g filter="url(#ikN4JyH)"><path fill="url(#icmehIe)" class="h-e-fl1js"/></g><g filter="url(#il7FDed)"><path fill="url(#iXNFi4c)" class="w3m-iu1cc"/></g><g filter="url(#i6piaWf)"><path clip-rule="evenodd" class="dcpr1zb6b"/></g><defs><radialGradient id="iH78xyQ" cx="0" cy="0" r="1" gradientTransform="matrix(2.34375 2.75 -.60904 .51907 15.494 12.5)" gradientUnits="userSpaceOnUse"><stop class="p8cjc8bgx"/><stop offset="1" class="o7s7rsbjo"/></radialGradient><radialGradient id="it26bvc" cx="0" cy="0" r="1" gradientTransform="rotate(176.424 9.305 8.439)scale(1.50293 1.62478)" gradientUnits="userSpaceOnUse"><stop class="ppddtcccf"/><stop offset="1" class="ircb6-b3r"/></radialGradient><radialGradient id="iUctc4d" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.57031 -1.46069 0 .84 .234)" gradientUnits="userSpaceOnUse"><stop offset=".238" class="ygdc80fko"/><stop offset="1" class="a5_lx-bnb"/></radialGradient><radialGradient id="iETpATd" cx="0" cy="0" r="1" gradientTransform="rotate(-14.821 2.856 -4.348)scale(.48867)" gradientUnits="userSpaceOnUse"><stop class="tl0sw7mkk"/><stop offset="1" class="xu259ab4x"/></radialGradient><radialGradient id="iPmd0rd" cx="0" cy="0" r="1" gradientTransform="matrix(.50415 0 0 .66877 0 .727)" gradientUnits="userSpaceOnUse"><stop class="hyb__5ivb"/><stop offset="1" class="wfraawh3t"/></radialGradient><radialGradient id="iJ3oyJd" cx="0" cy="0" r="1" gradientTransform="matrix(-.05152 -2.21336 1.59858 -.0372 1.708 2.01)" gradientUnits="userSpaceOnUse"><stop offset=".116" class="x_jc9nbct"/><stop offset="1" class="ixo4mj6aq"/></radialGradient><radialGradient id="iJVUGUb" cx="0" cy="0" r="1" gradientTransform="matrix(-.53617 .66448 -.89991 -.72614 2.062 .438)" gradientUnits="userSpaceOnUse"><stop class="wlb8cfb3m"/><stop offset="1" class="wjsp4yb7h"/></radialGradient><radialGradient id="ianRafN" cx="0" cy="0" r="1" gradientTransform="matrix(.01105 -.86884 .23985 .00305 .214 2.413)" gradientUnits="userSpaceOnUse"><stop class="e7fhnutoo"/><stop offset="1" class="rq75l3itm"/></radialGradient><radialGradient id="idJYsAd" cx="0" cy="0" r="1" gradientTransform="rotate(151.587 7.523 5.206)scale(.54183 .76481)" gradientUnits="userSpaceOnUse"><stop offset=".101" class="hymklqb8k"/><stop offset=".684" class="s2f2c_bct"/></radialGradient><radialGradient id="iHJh3xe" cx="0" cy="0" r="1" gradientTransform="matrix(.12006 -.29152 .4375 .18018 16.212 6.523)" gradientUnits="userSpaceOnUse"><stop class="zkj259b3a"/><stop offset="1" class="iv0p50s_n"/></radialGradient><radialGradient id="i9DB0Vd" cx="0" cy="0" r="1" gradientTransform="matrix(.84375 -.04687 .05715 1.0287 12.955 5.503)" gradientUnits="userSpaceOnUse"><stop offset=".156" class="l7mbhnbzh"/><stop offset="1" class="biuc-6bfh"/></radialGradient><radialGradient id="iq4qYce" cx="0" cy="0" r="1" gradientTransform="matrix(0 -5.1875 2.01562 0 15.852 6.69)" gradientUnits="userSpaceOnUse"><stop offset=".219" class="wcectbccf"/><stop offset="1" class="b3jcjo1jv"/></radialGradient><radialGradient id="i129U6d" cx="0" cy="0" r="1" gradientTransform="matrix(0 .39063 -.60919 0 15.024 5.55)" gradientUnits="userSpaceOnUse"><stop offset=".155" class="ie_w39bfj"/><stop offset="1" class="dx40lk_kc"/></radialGradient><radialGradient id="iasBbid" cx="0" cy="0" r="1" gradientTransform="matrix(3.4375 3.125 -3.54355 3.8979 11.08 2.841)" gradientUnits="userSpaceOnUse"><stop offset=".363" class="sd2k4tbbl"/><stop offset="1" class="n3xu87-4f"/></radialGradient><radialGradient id="iIw1afc" cx="0" cy="0" r="1" gradientTransform="matrix(-.39452 2.68273 -1.18513 -.17428 11.187 3.59)" gradientUnits="userSpaceOnUse"><stop offset=".106" class="qvi3m-3ib"/><stop offset="1" class="sx_wpgngv"/></radialGradient><radialGradient id="i6vOpQX" cx="0" cy="0" r="1" gradientTransform="matrix(-1.5 -.09374 .18396 -2.94358 16.377 3.456)" gradientUnits="userSpaceOnUse"><stop offset=".218" class="ehlb6fbrs"/><stop offset="1" class="xv-sacbws"/></radialGradient><radialGradient id="i4p3tVd" cx="0" cy="0" r="1" gradientTransform="rotate(-163.812 6.973 1.756)scale(.75656 .36927)" gradientUnits="userSpaceOnUse"><stop offset=".17" class="i8aj4_5_r"/><stop offset="1" class="u2yjj3mld"/></radialGradient><radialGradient id="iGDc4ie" cx="0" cy="0" r="1" gradientTransform="rotate(100.843 4.472 7.977)scale(1.20119 1.25169)" gradientUnits="userSpaceOnUse"><stop offset=".556" class="chiqx4b_a"/><stop offset="1" class="vmk6x9_kg"/><stop offset="1" class="hq1ekobkc"/></radialGradient><radialGradient id="iuSrGXd" cx="0" cy="0" r="1" gradientTransform="matrix(-2.45369 2.93958 -5.96661 -4.98038 10.842 17.98)" gradientUnits="userSpaceOnUse"><stop offset=".434" class="oiy_54b9a"/><stop offset="1" class="rm4aiz5dn"/></radialGradient><radialGradient id="igP5ITb" cx="0" cy="0" r="1" gradientTransform="rotate(143.616 2.458 11.331)scale(1.10629 6.64432)" gradientUnits="userSpaceOnUse"><stop offset=".043" class="v5lz4sb9o"/><stop offset="1" class="m_uy2vb_d"/></radialGradient><radialGradient id="ihOQtWb" cx="0" cy="0" r="1" gradientTransform="rotate(-122.302 11.71 7.13)scale(6.08182 1.60193)" gradientUnits="userSpaceOnUse"><stop offset=".07" class="mngz2ebss"/><stop offset="1" class="ttsumpbek"/></radialGradient><radialGradient id="itEVBzR" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.42188 -1.38588 0 11.127 16.136)" gradientUnits="userSpaceOnUse"><stop class="f3j6dkfip"/><stop offset="1" class="fxoxl0blj"/></radialGradient><radialGradient id="iglvYSc" cx="0" cy="0" r="1" gradientTransform="matrix(-.14062 -.17969 .6458 -.50541 15.822 28.05)" gradientUnits="userSpaceOnUse"><stop class="ryq0o3qru"/><stop offset="1" class="yfqxgqb1h"/></radialGradient><radialGradient id="iKnj5ib" cx="0" cy="0" r="1" gradientTransform="matrix(-6.375 -1.81248 4.6745 -16.4415 15.502 19.183)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="ex23x-brg"/><stop offset="1" class="ux4w7lb6c"/></radialGradient><radialGradient id="iXD7Gbc" cx="0" cy="0" r="1" gradientTransform="matrix(.09374 -1.53125 2.45635 .15037 16.956 29.401)" gradientUnits="userSpaceOnUse"><stop class="cl2mlwbhs"/><stop offset="1" class="yvuyjoqpy"/></radialGradient><radialGradient id="ic0EDTb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.0625 -.21876 .15137 -.73521 20.065 28.464)" gradientUnits="userSpaceOnUse"><stop class="m3n9jy0fh"/><stop offset="1" class="hdzwkybza"/></radialGradient><radialGradient id="iiSnBmb" cx="0" cy="0" r="1" gradientTransform="matrix(-.59376 -1.71875 .84778 -.29287 16.049 29.698)" gradientUnits="userSpaceOnUse"><stop offset=".08" class="a541b3bqx"/><stop offset="1" class="zc8ie-1dg"/></radialGradient><radialGradient id="i0DhLrd" cx="0" cy="0" r="1" gradientTransform="rotate(-47.125 33.002 9.038)scale(1.99789 1.10527)" gradientUnits="userSpaceOnUse"><stop class="xh_da2q2q"/><stop offset="1" class="stwbr2bhy"/></radialGradient><radialGradient id="idz5xYQ" cx="0" cy="0" r="1" gradientTransform="matrix(1.5625 -.54688 .76306 2.18017 11.924 9.669)" gradientUnits="userSpaceOnUse"><stop offset=".266" class="anxjqssms"/><stop offset="1" class="p0binz11r"/></radialGradient><radialGradient id="iYUOPfK" cx="0" cy="0" r="1" gradientTransform="rotate(-88.915 13.838 2.345)scale(4.95211 1.34022)" gradientUnits="userSpaceOnUse"><stop class="ba65pd9sy"/><stop offset="1" class="c0n24ybhp"/></radialGradient><radialGradient id="izbYpqd" cx="0" cy="0" r="1" gradientTransform="matrix(-3.65186 0 0 -15.6875 13.106 14.247)" gradientUnits="userSpaceOnUse"><stop offset=".436" class="l7vpqwwuy"/><stop offset="1" class="r5z1pjbbo"/></radialGradient><radialGradient id="i7Ofyye" cx="0" cy="0" r="1" gradientTransform="matrix(4.78125 .78125 -1.79108 10.96143 9.731 15.06)" gradientUnits="userSpaceOnUse"><stop offset=".781" class="gxh5rg5pu"/><stop offset=".931" class="x45bnccdq"/></radialGradient><radialGradient id="iBmeYYs" cx="0" cy="0" r="1" gradientTransform="rotate(90 .008 .406)scale(.90625)" gradientUnits="userSpaceOnUse"><stop offset=".256" class="qf2lyobnm"/><stop offset="1" class="l21zq2bsp"/></radialGradient><radialGradient id="iTxQAmc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.0907 .20313 -.4206 -2.25834 12.916 10.294)" gradientUnits="userSpaceOnUse"><stop offset=".12" class="c7e6m9b-c"/><stop offset="1" class="kqn0y5w2b"/></radialGradient><radialGradient id="iuXMmVb" cx="0" cy="0" r="1" gradientTransform="matrix(2.15625 -2.3125 .88732 .82737 8.83 11.638)" gradientUnits="userSpaceOnUse"><stop class="mpu3do46a"/><stop offset="1" class="ftb4gxmwr"/></radialGradient><radialGradient id="iZjeeOc" cx="0" cy="0" r="1" gradientTransform="rotate(112.307 3.194 8.48)scale(1.23495 2.7533)" gradientUnits="userSpaceOnUse"><stop offset=".126" class="jogzo_66p"/><stop offset="1" class="hir3rg47y"/></radialGradient><radialGradient id="i7ekZvc" cx="0" cy="0" r="1" gradientTransform="matrix(-.27344 0 0 -.53125 15.319 5.577)" gradientUnits="userSpaceOnUse"><stop offset=".895" class="l0aricxam"/><stop offset="1" class="n9r91ylyy"/></radialGradient><radialGradient id="iEsNE0v" cx="0" cy="0" r="1" gradientTransform="matrix(-.25 0 0 -.54102 15.486 5.599)" gradientUnits="userSpaceOnUse"><stop class="gv3iwdbvq"/><stop offset=".813" class="ubyl24bdb"/></radialGradient><linearGradient id="i7e5vze" x1="17.705" x2="19.587" y1="15.523" y2="17.563" gradientUnits="userSpaceOnUse"><stop class="o52vxyscb"/><stop offset="1" class="u-867gbtx"/></linearGradient><linearGradient id="iTksytq" x1="23.15" x2="21.9" y1="21.812" y2="22.75" gradientUnits="userSpaceOnUse"><stop class="n6l6ilaec"/><stop offset="1" class="vjqn9lx3p"/></linearGradient><linearGradient id="iksjITb" x1="26.814" x2="25.08" y1="28.656" y2="26.312" gradientUnits="userSpaceOnUse"><stop class="uug2ubxhk"/><stop offset="1" class="deyia0bkx"/></linearGradient><linearGradient id="iB1Ax7d" x1="26.759" x2="26.401" y1="27.094" y2="27.344" gradientUnits="userSpaceOnUse"><stop class="p8mdyfi9b"/><stop offset="1" class="g6zbvk7ui"/></linearGradient><linearGradient id="iNsGSSd" x1="18.291" x2="20.041" y1="16.359" y2="18.656" gradientUnits="userSpaceOnUse"><stop class="ly5_jc0cc"/><stop offset="1" class="sxo3xwbvl"/></linearGradient><linearGradient id="iLFDc3d" x1="18.181" x2="18.705" y1="16.422" y2="17.188" gradientUnits="userSpaceOnUse"><stop offset=".098" class="iykv72k7v"/><stop offset="1" class="qg5pcsysc"/></linearGradient><linearGradient id="is5lFnb" x1="14.529" x2="15.115" y1="12.833" y2="12.122" gradientUnits="userSpaceOnUse"><stop class="f8fpq6bgz"/><stop offset="1" class="w48m3830t"/></linearGradient><linearGradient id="ipwPTEe" x1="13.268" x2="16.13" y1="6.245" y2="6.417" gradientUnits="userSpaceOnUse"><stop class="dxjajos_o"/><stop offset="1" class="gu4uskbqq"/></linearGradient><linearGradient id="ih4wdeC" x1="13.234" x2="13.086" y1="5.455" y2="5.466" gradientUnits="userSpaceOnUse"><stop class="o01zddb6n"/><stop offset="1" class="h5b83fbqu"/></linearGradient><linearGradient id="iNjgzAc" x1="9.822" x2="7.594" y1="22.839" y2="20.895" gradientUnits="userSpaceOnUse"><stop offset=".211" class="pat1zf4-w"/><stop offset="1" class="wtea7v6lu"/></linearGradient><linearGradient id="iwC7vXy" x1="12.049" x2="12.049" y1="16.026" y2="16.37" gradientUnits="userSpaceOnUse"><stop offset=".136" class="x5p6yzbmf"/><stop offset="1" class="cnh3p8b3x"/></linearGradient><linearGradient id="istDPNe" x1="17.518" x2="17.432" y1="29.573" y2="29.261" gradientUnits="userSpaceOnUse"><stop class="l138bfbcs"/><stop offset="1" class="oxce79bcz"/></linearGradient><linearGradient id="iG8uImb" x1="15.549" x2="16.127" y1="29.948" y2="29.73" gradientUnits="userSpaceOnUse"><stop offset=".064" class="lhdz7oxfj"/><stop offset="1" class="csaq2_bel"/></linearGradient><linearGradient id="iLKdrZi" x1="6.94" x2="6.346" y1="27.933" y2="28.105" gradientUnits="userSpaceOnUse"><stop class="oxg1n1wjw"/><stop offset="1" class="y0g_czb9f"/></linearGradient><linearGradient id="iJzdUvc" x1="4.815" x2="4.994" y1="28.007" y2="27.859" gradientUnits="userSpaceOnUse"><stop class="p6qc3nb-j"/><stop offset="0" class="ezcqmvbni"/><stop offset="1" class="stwbr2bhy"/></linearGradient><linearGradient id="ief8Ewd" x1="11.736" x2="11.736" y1="16.169" y2="15.989" gradientUnits="userSpaceOnUse"><stop class="znpkhwbgq"/><stop offset="1" class="z629lk5yz"/></linearGradient><linearGradient id="ij72sTd" x1="11.065" x2="9.955" y1="9.073" y2="12.526" gradientUnits="userSpaceOnUse"><stop offset=".118" class="bds_ezblb"/><stop offset="1" class="y3zdm1aic"/></linearGradient><linearGradient id="ipECBte" x1="-.007" x2=".179" y1=".05" y2=".11" gradientUnits="userSpaceOnUse"><stop class="vc--wpv5i"/><stop offset="1" class="stui2mbih"/></linearGradient><linearGradient id="icmehIe" x1="15.721" x2="11.096" y1="27.37" y2="17.23" gradientUnits="userSpaceOnUse"><stop class="v9kimlbms"/><stop offset="1" class="g24ahctiy"/></linearGradient><linearGradient id="iXNFi4c" x1="5.576" x2="9.887" y1="25.279" y2="19.907" gradientUnits="userSpaceOnUse"><stop class="ckhjb_bgt"/><stop offset="1" class="rnrhdzckq"/></linearGradient><filter id="iOr1wQM" width="7.179" height="6.928" x="12.727" y="10.879" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.5" dy="-.75"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.760784 0 0 0 0 0.501961 0 0 0 0 0.513726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_3438"/></filter><filter id="iGtu0Up" width="2.607" height="2.722" x="17.098" y="15.151" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_2_3438" stdDeviation=".05"/></filter><filter id="iYTkvHe" width="8.674" height="11.796" x="19.181" y="17.483" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.741176 0 0 0 0 0.647059 0 0 0 0 0.811765 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_3438"/></filter><filter id="iUTjoIe" width="1.68" height="1.68" x="26.74" y="28.227" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.835294 0 0 0 0 0.819608 0 0 0 0 0.835294 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_3438"/></filter><filter id="iz9Zi6c" width="2.726" height="3.079" x="17.772" y="15.918" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.211765 0 0 0 0 0.133333 0 0 0 0 0.27451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_3438"/></filter><filter id="iMbgzZb" width="1.093" height="1.661" x="18.761" y="15.543" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.15"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.858824 0 0 0 0 0.639216 0 0 0 0 0.592157 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_3438"/></filter><filter id="isSvpoc" width="4.443" height="5.249" x="11.687" y="3.304" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2" dy="-.2"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.815686 0 0 0 0 0.596078 0 0 0 0 0.580392 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_3438"/></filter><filter id="ilf6Nke" width="6.391" height="5.479" x="10.272" y="1.66" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.3" dy=".3"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.282353 0 0 0 0 0.262745 0 0 0 0 0.270588 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_3438"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.3"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0980392 0 0 0 0 0.054902 0 0 0 0 0.0705882 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_2_3438" result="effect2_innerShadow_2_3438"/></filter><filter id="ilSKDxV" width="8.674" height="14.771" x="3.683" y="15.417" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".75" dy="-.75"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.439216 0 0 0 0 0.388235 0 0 0 0 0.486275 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_3438"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.537255 0 0 0 0 0.423529 0 0 0 0 0.635294 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_2_3438" result="effect2_innerShadow_2_3438"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy=".25"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.529412 0 0 0 0 0.490196 0 0 0 0 0.537255 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_2_3438" result="effect3_innerShadow_2_3438"/></filter><filter id="iKAcPtb" width="10.972" height="14.104" x="9.441" y="15.936" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy="-.2"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.619608 0 0 0 0 0.592157 0 0 0 0 0.611765 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_3438"/></filter><filter id="igm0jfb" width="5.586" height="5.875" x="7.949" y="8.255" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_2_3438" stdDeviation=".375"/></filter><filter id="iyTG8ab" width="7.59" height="10.511" x="4.314" y="9.099" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.909804 0 0 0 0 0.678431 0 0 0 0 0.639216 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_3438"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.4" dy=".4"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.980392 0 0 0 0 0.807843 0 0 0 0 0.713726 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_2_3438" result="effect2_innerShadow_2_3438"/></filter><filter id="iYu8JDd" width="6.084" height="9.069" x="4.724" y="9.844" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_2_3438" stdDeviation=".3"/></filter><filter id="iAOHIUc" width="4.758" height="4.525" x="8.408" y="8.595" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.15"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.160784 0 0 0 0 0.47451 0 0 0 0 0.866667 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_3438"/></filter><filter id="ikN4JyH" width="6.844" height="12.891" x="10.096" y="16.058" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_2_3438" stdDeviation=".5"/></filter><filter id="il7FDed" width="6.45" height="8.475" x="4.541" y="17.986" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_2_3438" stdDeviation=".375"/></filter><filter id="i6piaWf" width="1.117" height=".649" x="14.409" y="4.231" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0705882 0 0 0 0 0.0588235 0 0 0 0 0.054902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_2_3438"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:man-with-white-cane-facing-right-light" /></template>
<style>
.a2cki4zdz {
  fill: var(--svg-color--e4aa95, #E4AA95);
  fill-rule: evenodd;
  d: path("M13.818 11.735a1.05 1.05 0 0 0-.485 1.404c1.832 3.77 4.235 4.912 5.72 4.627a1.05 1.05 0 0 0-.396-2.063s-.026.004-.082 0a1.2 1.2 0 0 1-.24-.044a2.7 2.7 0 0 1-.803-.404c-.65-.457-1.494-1.354-2.31-3.034a1.05 1.05 0 0 0-1.404-.486");
}

.a2e8hqb_h {
  d: path("m15.186 5.599l-.004-.073c0-.185.079-.336.175-.336c.098 0 .176.15.176.336l-.004.073z");
}

.a5_lx-bnb {
  stop-color: var(--svg-color--ccaae9, #CCAAE9);
}

.a541b3bqx {
  stop-color: var(--svg-color--515279, #515279);
}

.a6sqesncg {
  d: path("M16.102 4.805c-.038-.801-.298-1.188-.42-1.3H11.95l-.063 3.163c.867 2.122 3.512 2.213 3.907 1.445c.395-.767.353-2.38.308-3.308");
}

.a8xggvz5s {
  d: path("M14.99 5.599v-.004c0-.32.138-.58.307-.58c.17 0 .307.26.307.58v.004z");
}

.am9uocbqt {
  cx: 0.551px;
  cy: 0.551px;
  r: 0.551px;
}

.an-n8n3gl {
  d: path("M12.407 11.16a1.355 1.355 0 1 0-1.729-2.088c-.95.691-1.79 1.591-2.27 2.134l2.04 1.914c.307-.32 1.381-1.392 1.959-1.96");
}

.anxjqssms {
  stop-color: var(--svg-color--3d98c9, #3D98C9);
}

.b3jcjo1jv {
  stop-color: var(--svg-color--ffcdb7, #FFCDB7);
  stop-opacity: 0;
}

.b6g2rcc6c {
  d: path("m8.627 19.901l.89-3.734h1.781c.053.615.152 2.216.29 3.516s-.492 2.03-.766 2.312l-4.445 4.313c.197.661.627 2.025.727 2.625c.076.461-.146.768-.352.952c-.093.083-.234.064-.318-.029l-2.687-2.995a.25.25 0 0 1 .019-.353l.986-.888c1.041-1.364 3.19-4.194 3.453-4.594c.181-.276.39-.916.422-1.125");
}

.b7qanra0c {
  d: path("M14.979 18.519c-.383-1.051-.716-2.03-.774-2.383H9.463c-.1 1.375.144 1.712.774 2.422c.692.78 2.171 2.43 2.538 2.894c.35.35.5.79.555.98l2.262 7.43a.25.25 0 0 0 .315.166l3.738-1.182c.194-.062.325-.266.243-.453c-.107-.245-.332-.499-.886-.656c-.662-.187-1.943-.284-2.515-.336c-.214-1.765-.66-5.43-.735-5.968c-.094-.672-.227-1.414-.773-2.914");
}

.ba65pd9sy {
  stop-color: var(--svg-color--407bbe, #407BBE);
}

.bds_ezblb {
  stop-color: var(--svg-color--2e83d0, #2E83D0);
}

.biuc-6bfh {
  stop-color: var(--svg-color--eeb298, #EEB298);
  stop-opacity: 0;
}

.c0n24ybhp {
  stop-color: var(--svg-color--407bbe, #407BBE);
  stop-opacity: 0;
}

.c7e6m9b-c {
  stop-color: var(--svg-color--5696dc, #5696DC);
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

.d5_1ldb3r {
  d: path("m13.331 6.26l-.2-1.44a.727.727 0 0 0 .2 1.44");
}

.dcpr1zb6b {
  fill: var(--svg-color--2c2828, #2C2828);
  fill-rule: evenodd;
  d: path("M14.826 4.742c.147-.106.363-.111.5-.111a.2.2 0 0 0 0-.4h-.01c-.128 0-.463 0-.723.186a.2.2 0 1 0 .233.325");
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

.e2--ewbsp {
  fill-rule: evenodd;
  d: path("M19.366 17.769a.45.45 0 0 0-.1.628l7.774 10.696a.45.45 0 1 0 .728-.53l-7.773-10.695a.45.45 0 0 0-.629-.1");
}

.e7fhnutoo {
  stop-color: var(--svg-color--eba, #EBA);
}

.eh--cpbup {
  fill: var(--svg-color--f0b6a6, #F0B6A6);
  fill-rule: evenodd;
  d: path("M5.959 19.18a.614.614 0 0 0 .776-.407c1.215-3.922 3.165-6.29 4.541-7.545c.438-.4.516-1.082.128-1.53c-.346-.402-.944-.473-1.348-.13c-1.626 1.38-3.91 3.976-5.316 8.605a.59.59 0 0 0 .382.729z");
}

.ehlb6fbrs {
  stop-color: var(--svg-color--544b49, #544B49);
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

.f8fpq6bgz {
  stop-color: var(--svg-color--3981ca, #3981CA);
}

.ft5dv1b6b {
  fill: none;
}

.ftb4gxmwr {
  stop-color: var(--svg-color--4d95e1, #4D95E1);
  stop-opacity: 0;
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

.gu4uskbqq {
  stop-color: var(--svg-color--fac1a8, #FAC1A8);
}

.gv3iwdbvq {
  stop-color: var(--svg-color--666361, #666361);
}

.gxh5rg5pu {
  stop-color: var(--svg-color--588fc4, #588FC4);
  stop-opacity: 0;
}

.h-296qkmg {
  fill: var(--svg-color--fff, #fff);
  d: path("M15.596 5.599h-.989c0-.392.222-.71.495-.71s.494.318.494.71");
}

.h-e-fl1js {
  d: path("m14.596 21.136l1.344 6.5l-.36.312l-1.469-6.531l-3.015-3.875l.703-.484z");
}

.h5b83fbqu {
  stop-color: var(--svg-color--f4bca5, #F4BCA5);
  stop-opacity: 0;
}

.h8sm7gtis {
  stroke: var(--svg-color--ffd0bb, #FFD0BB);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M10.008 10.644c-.968.906-3.156 3.218-4.484 7.468");
}

.hdzwkybza {
  stop-color: var(--svg-color--63617e, #63617E);
  stop-opacity: 0;
}

.hfq020b1u {
  fill: var(--svg-color--45437a, #45437A);
  d: path("m4.76 25.61l1.638.677l-.021.02q.046.157.107.356c.216.712.535 1.763.62 2.27c.077.462-.145.768-.351.952c-.094.084-.235.064-.319-.029l-2.687-2.995a.25.25 0 0 1 .019-.353l.986-.888z");
}

.hir3rg47y {
  stop-color: var(--svg-color--4080be, #4080BE);
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

.ixo4mj6aq {
  stop-color: var(--svg-color--d9a799, #D9A799);
}

.iykv72k7v {
  stop-color: var(--svg-color--62516b, #62516B);
}

.j5__uftpu {
  fill: var(--svg-color--1049ac, #1049AC);
  d: path("M12.323 11.231c.31-.248.462-.638.462-1.066c0-.749-.185-1.16-.934-1.16a1.35 1.35 0 0 0-.883.327c-.95.691-1.789 1.59-2.27 2.134l2.04 1.914c.288-.383 1.069-1.446 1.585-2.149");
}

.j657_qdha {
  d: path("m4.76 25.61l1.638.677l-.021.02q.046.157.107.356c.216.712.535 1.763.62 2.27c.077.462-.145.768-.351.952c-.094.084-.235.064-.319-.029l-2.687-2.995a.25.25 0 0 1 .019-.353l.986-.888z");
}

.jogzo_66p {
  stop-color: var(--svg-color--5b789d, #5B789D);
}

.klx8rkb4d {
  d: path("M16.326 5.769a1 1 0 0 1-.258-.457h-.18v1.125c.215.136.523.115.614-.09c.078-.176.02-.395-.176-.578");
}

.kqn0y5w2b {
  stop-color: var(--svg-color--5696dc, #5696DC);
  stop-opacity: 0;
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

.l7vpqwwuy {
  stop-color: var(--svg-color--4475a6, #4475A6);
  stop-opacity: 0;
}

.lhdz7oxfj {
  stop-color: var(--svg-color--444571, #444571);
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

.mngz2ebss {
  stop-color: var(--svg-color--897998, #897998);
}

.mpu3do46a {
  stop-color: var(--svg-color--4d95e1, #4D95E1);
}

.n3xu87-4f {
  stop-color: var(--svg-color--1d0d23, #1D0D23);
}

.n6l6ilaec {
  stop-color: var(--svg-color--d4c6dc, #D4C6DC);
}

.n9r91ylyy {
  stop-color: var(--svg-color--824d44, #824D44);
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

.oxj7i12ho {
  fill: var(--svg-color--397ec9, #397EC9);
  d: path("M12.271 8.554c-.89 0-1.137.215-1.433.406l-1.024 2.598c-.3 1.4-.364 3.635-.36 4.578h4.747c.258-.656.697-2.675.535-4.578c-.164-1.93-1.207-2.903-2.465-3.004");
}

.p-v_uzerw {
  d: path("M12.271 8.554c-.89 0-1.137.215-1.433.406l-1.024 2.598c-.3 1.4-.364 3.635-.36 4.578h4.747c.258-.656.697-2.675.535-4.578c-.164-1.93-1.207-2.903-2.465-3.004");
}

.p0binz11r {
  stop-color: var(--svg-color--3d98c9, #3D98C9);
  stop-opacity: 0;
}

.p2xgfbccg {
  d: path("M18.952 16.001a.2.2 0 0 0-.28-.045l-.817.59a.2.2 0 0 0-.045.28l1.51 2.089a.2.2 0 0 0 .279.045l.817-.59a.2.2 0 0 0 .045-.28z");
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

.pgj01zbaf {
  stroke: var(--svg-color--33241a, #33241A);
  stroke-width: var(--svg-stroke-width--0-35px, 0.35px);
  d: path("M19.545 15.976a1.21 1.21 0 1 0-.101 1.24");
}

.ppddtcccf {
  stop-color: var(--svg-color--d29b87, #D29B87);
}

.pz752f3kh {
  d: path("m24.948 26.214l2.092 2.879a.45.45 0 1 0 .728-.53l-2.092-2.878z");
}

.qf2lyobnm {
  stop-color: var(--svg-color--e8a99a, #E8A99A);
}

.qg5pcsysc {
  stop-color: var(--svg-color--483a55, #483A55);
  stop-opacity: 0;
}

.qvi3m-3ib {
  stop-color: var(--svg-color--464143, #464143);
}

.r5z1pjbbo {
  stop-color: var(--svg-color--4475a6, #4475A6);
}

.rm4aiz5dn {
  stop-color: var(--svg-color--887e8b, #887E8B);
  stop-opacity: 0;
}

.rnrhdzckq {
  stop-color: var(--svg-color--a39fa7, #A39FA7);
  stop-opacity: 0;
}

.rq75l3itm {
  stop-color: var(--svg-color--eba, #EBA);
  stop-opacity: 0;
}

.ryq0o3qru {
  stop-color: var(--svg-color--a19da6, #A19DA6);
}

.s2f2c_bct {
  stop-color: var(--svg-color--ffc4a7, #FFC4A7);
}

.sd2k4tbbl {
  stop-color: var(--svg-color--251a23, #251A23);
}

.stui2mbih {
  stop-color: var(--svg-color--fff, #fff);
  stop-opacity: 0;
}

.stwbr2bhy {
  stop-color: var(--svg-color--46437b, #46437B);
  stop-opacity: 0;
}

.sx_wpgngv {
  stop-color: var(--svg-color--464143, #464143);
  stop-opacity: 0;
}

.sxo3xwbvl {
  stop-color: var(--svg-color--3f3647, #3F3647);
}

.t2hu-p3oq {
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M19.56 16.006a1.211 1.211 0 1 0-.118 1.212");
}

.tl0sw7mkk {
  stop-color: var(--svg-color--e9d9f5, #E9D9F5);
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

.ubyl24bdb {
  stop-color: var(--svg-color--565352, #565352);
}

.ug8yaobdd {
  fill: var(--svg-color--8c8393, #8C8393);
  d: path("M14.979 18.519c-.383-1.051-.716-2.03-.774-2.383H9.463c-.1 1.375.144 1.712.774 2.422c.692.78 2.171 2.43 2.538 2.894c.35.35.5.79.555.98l2.262 7.43a.25.25 0 0 0 .315.166l3.738-1.182c.194-.062.325-.266.243-.453c-.107-.245-.332-.499-.886-.656c-.662-.187-1.943-.284-2.515-.336c-.214-1.765-.66-5.43-.735-5.968c-.094-.672-.227-1.414-.773-2.914");
}

.uug2ubxhk {
  stop-color: var(--svg-color--e82b8e, #E82B8E);
}

.ux4w7lb6c {
  stop-color: var(--svg-color--8c8388, #8C8388);
}

.v4o_zqb9x {
  fill-rule: evenodd;
  d: path("M13.818 11.735a1.05 1.05 0 0 0-.485 1.404c1.832 3.77 4.235 4.912 5.72 4.627a1.05 1.05 0 0 0-.396-2.063s-.026.004-.082 0a1.2 1.2 0 0 1-.24-.044a2.7 2.7 0 0 1-.803-.404c-.65-.457-1.494-1.354-2.31-3.034a1.05 1.05 0 0 0-1.404-.486");
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

.w3m-iu1cc {
  d: path("m8.767 21.084l-3.476 4.428l.514.199l3.485-3.708a3 3 0 0 0 .76-1.494l.19-1l-.75-.773l-.544 1.993a1 1 0 0 1-.179.355");
}

.w48m3830t {
  stop-color: var(--svg-color--4e98d7, #4E98D7);
}

.wcectbccf {
  stop-color: var(--svg-color--ffcdb7, #FFCDB7);
}

.wfraawh3t {
  stop-color: var(--svg-color--e4d4ea, #E4D4EA);
  stop-opacity: 0;
}

.wj9bins_h {
  d: path("m15.201 28.577l.391 1.286a.25.25 0 0 0 .315.165l3.738-1.182c.194-.062.325-.266.243-.453c-.107-.244-.332-.499-.886-.656c-.59-.167-1.672-.261-2.306-.317l-.21-.019V27.4z");
}

.wjsp4yb7h {
  stop-color: var(--svg-color--cda28c, #CDA28C);
  stop-opacity: 0;
}

.wlb8cfb3m {
  stop-color: var(--svg-color--cda28c, #CDA28C);
}

.wtea7v6lu {
  stop-color: var(--svg-color--9f9c9f, #9F9C9F);
}

.wy2-a_orr {
  d: path("M14.654 10.456c-.281-.712-.841-1.208-1.052-1.374l.107 4.452l1.785-.836c-.278-.523-.489-1.351-.84-2.242");
}

.x_jc9nbct {
  stop-color: var(--svg-color--e9c1ad, #E9C1AD);
}

.x45bnccdq {
  stop-color: var(--svg-color--588fc4, #588FC4);
}

.x5p6yzbmf {
  stop-color: var(--svg-color--817076, #817076);
}

.xh_da2q2q {
  stop-color: var(--svg-color--60618d, #60618D);
}

.xu259ab4x {
  stop-color: var(--svg-color--e9d9f5, #E9D9F5);
  stop-opacity: 0;
}

.xv-sacbws {
  stop-color: var(--svg-color--544b49, #544B49);
  stop-opacity: 0;
}

.y0g_czb9f {
  stop-color: var(--svg-color--5a577e, #5A577E);
  stop-opacity: 0;
}

.y3zdm1aic {
  stop-color: var(--svg-color--3384e0, #3384E0);
}

.y6kadwb9i {
  d: path("M15.463 4.052c.656 0 .969-.371 1-.836c0-.656-.501-.796-.695-.816c-.219-.024-.305-.047-.61-.262a.9.9 0 0 0-.91-.098c-.148.07-.476.106-.71.035c-.391-.117-.696-.113-.997.118c-.209.16-.363.16-.613.16c-.344 0-.636.154-.856.32c-.657.497-.582 2.207-.257 3.168c.31.92.777 1.027 1.168.992c.47-.042.59-.398.66-.695c.056-.238.2-.99.265-1.238c.136-.062.432-.086.532-.473c.1-.388.492-.432.757-.406c.162.015.61.03 1.266.03");
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

.z629lk5yz {
  stop-color: var(--svg-color--417ab5, #417AB5);
  stop-opacity: 0;
}

.z8jy9-b3h {
  d: path("M0 0h1.946v3.44H0z");
}

.z9lslngvi {
  fill: var(--svg-color--86004c, #86004C);
  fill-rule: evenodd;
  d: path("M14.85 6.712a.125.125 0 0 0 .002.177c.238.234.582.293.692.305a.125.125 0 1 0 .025-.249c-.093-.01-.366-.062-.542-.234a.125.125 0 0 0-.177.001");
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

.znpkhwbgq {
  stop-color: var(--svg-color--445b8b, #445B8B);
}

</style>
