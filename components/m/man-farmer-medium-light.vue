<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iePr34b)" class="en3cqcc2r"/><path fill="url(#iQ7Xxfe)" class="t7_hkjbap"/><path fill="url(#iYirTgO)" class="t7_hkjbap"/><g filter="url(#ig4BfAV)"><path fill="url(#i9F1CId)" class="efez_2bmy"/><path fill="url(#izguYke)" class="efez_2bmy"/></g><path class="v_qusm7gm"/><path fill="url(#iOzyFad)" class="qmyxitbhu"/><path fill="url(#i78VrFc)" class="z1ud-kpwi"/><path fill="url(#izGfO9b)" class="z1ud-kpwi"/><path fill="url(#iRutGzb)" class="kky8tzcjx"/><path fill="url(#iaRdLfc)" class="kky8tzcjx"/><g filter="url(#ial5I3A)"><path fill="url(#iK4HyMc)" class="q5oqcih4w"/><path fill="url(#ihEhn2d)" class="q5oqcih4w"/><path fill="url(#iGDyIKc)" class="q5oqcih4w"/></g><path fill="url(#i4ja36c)" class="q5oqcih4w"/><path fill="url(#i9GCd4G)" class="q5oqcih4w"/><path fill="url(#iFBh55c)" class="seszgebct"/><path fill="url(#iOIbUde)" class="b0fcggb5v"/><path fill="url(#immCZLx)" class="b0fcggb5v"/><g filter="url(#iCVHYBc)"><path class="jm4hqf2zy"/><path fill="url(#iAJxrEb)" class="s6evr8b9t"/></g><g filter="url(#iLUbhJd)"><path fill="url(#iXUheWb)" class="dvymziplf"/></g><path fill="url(#i7akEKe)" class="or173xb1f"/><path fill="url(#iplIIZd)" class="or173xb1f"/><g filter="url(#ixtQPPb)"><path fill="url(#i4NNL0d)" class="c0ces0ufe"/></g><path fill="url(#irjmldb)" class="z7v4f46_s"/><path fill="url(#i9ZO14d)" class="kw34xudqh"/><path fill="url(#iEofhic)" class="lioq9m7hi"/><path fill="url(#ie6NYbe)" class="lioq9m7hi"/><path fill="url(#iWiZHUM)" class="lioq9m7hi"/><path fill="url(#iN7XaFc)" class="lioq9m7hi"/><path fill="url(#iwcZZdd)" class="lioq9m7hi"/><g filter="url(#im6AlCd)"><path class="ygr1mqboi"/></g><g filter="url(#i5cxrfi)"><path fill="url(#ivDgabc)" class="lam2cnohl"/></g><g filter="url(#iwMCiwd)"><path fill="url(#iXcNRVb)" class="nkojhbbwr"/></g><path fill="url(#isjBsLe)" class="nkojhbbwr"/><path fill="url(#ihiap7d)" class="nkojhbbwr"/><path fill="url(#irDVSDb)" class="nkojhbbwr"/><path fill="url(#i3Xq1oe)" class="nkojhbbwr"/><path fill="url(#iUn2jAc)" class="nkojhbbwr"/><g filter="url(#iu00ihd)"><path class="c75mxbchy"/></g><g filter="url(#iFVyNjb)"><path fill="url(#iCf1OAd)" class="aoi-30bis"/><path fill="url(#iRIiOoe)" class="aoi-30bis"/><path fill="url(#iLwVPwF)" class="aoi-30bis"/><path fill="url(#iGhaIbQ)" class="aoi-30bis"/></g><g filter="url(#iEyVjCc)"><path stroke="url(#i32zuCj)" class="i51qo2bmb"/></g><path class="k150n8bho"/><path fill="url(#idkMYtd)" class="sn76xowoz"/><path fill="url(#i1FGM5w)" class="sn76xowoz"/><path fill="url(#iKeEkmd)" class="rqjejjbyp"/><path fill="url(#imdDcCe)" class="rqjejjbyp"/><path fill="url(#iyWdt0d)" class="racw9ccri"/><path fill="url(#iED5kQd)" class="racw9ccri"/><path fill="url(#i8JFE7b)" class="racw9ccri"/><g filter="url(#ixxrVjb)"><path class="urrq_mbar"/></g><path class="nmo9kfdje"/><path fill="url(#idKoF8L)" class="ehp0m0b6n"/><path class="tidl_lzwa"/><g filter="url(#iDxYCHe)"><path class="i-6b1qbmn"/><path fill="url(#iZui0FM)" class="pjyridg8y"/></g><g filter="url(#i2d9bbc)"><path fill="url(#iEh3Ync)" class="ogazzbbkt"/></g><path class="tyd3-kmwr"/><path fill="url(#iGPIeBc)" class="bhtc49btl"/><path class="e4o45ibyi"/><g filter="url(#ikvdJue)"><path fill="url(#iXEaXJd)" class="o2pamybnw"/></g><g filter="url(#iZ1z8Fb)"><ellipse transform="rotate(-27.914 13.51 9.892)" class="hiy36ccjt"/><ellipse fill="url(#igNjrdp)" transform="rotate(-27.914 13.51 9.892)" class="d89qw3dmr"/></g><g filter="url(#i7c6vTb)"><path fill="url(#ihrNxsc)" class="idanqg1oa"/><path fill="url(#iQCR8Oc)" class="idanqg1oa"/><path fill="url(#ibIcReb)" class="idanqg1oa"/><path fill="url(#iCVbpsb)" class="idanqg1oa"/><path fill="url(#iT0u5kb)" class="idanqg1oa"/></g><g filter="url(#iL5yHVd)"><path stroke="url(#ipWKtFb)" class="d5bh__bgt"/></g><g filter="url(#ixsMuiq)"><path stroke="url(#iHcqtpe)" class="sog6_lbfk"/></g><g filter="url(#iRMlbVx)"><path stroke="url(#i2TZIKB)" class="l5sb_gbjb"/></g><g filter="url(#iBS1oTd)"><path clip-rule="evenodd" class="w7xati8xm"/></g><g filter="url(#ix0UAsl)"><path clip-rule="evenodd" class="cn_4wnbjs"/></g><g filter="url(#iOrh1Cc)"><path class="dym4kjb3u"/></g><g filter="url(#izHxPwZ)"><path class="f278--bqq"/></g><defs><radialGradient id="iePr34b" cx="0" cy="0" r="1" gradientTransform="matrix(-4.28126 -2.7131 2.52682 -3.98732 19.818 3.98)" gradientUnits="userSpaceOnUse"><stop class="lgo9yub8v"/><stop offset="1" class="ltcbfxk7p"/></radialGradient><radialGradient id="iQ7Xxfe" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.15625 8.40625 0 19.693 5.142)" gradientUnits="userSpaceOnUse"><stop class="ya4lejb1r"/><stop offset="1" class="r9exlwbyv"/></radialGradient><radialGradient id="izguYke" cx="0" cy="0" r="1" gradientTransform="rotate(-115.388 9.617 3.926)scale(4.08169 6.42739)" gradientUnits="userSpaceOnUse"><stop class="yc_s6bd2r"/><stop offset="1" class="e2_jykbzy"/></radialGradient><radialGradient id="iOzyFad" cx="0" cy="0" r="1" gradientTransform="matrix(0 7.16424 -8.99366 0 15.93 16.305)" gradientUnits="userSpaceOnUse"><stop offset=".53" class="oolzzy49q"/><stop offset="1" class="kc6n1tb_x"/></radialGradient><radialGradient id="izGfO9b" cx="0" cy="0" r="1" gradientTransform="matrix(2.6875 .4375 -2.13811 13.1341 3.787 25.267)" gradientUnits="userSpaceOnUse"><stop class="d6r03hc-n"/><stop offset="1" class="h29l8x_8c"/></radialGradient><radialGradient id="iaRdLfc" cx="0" cy="0" r="1" gradientTransform="matrix(.79488 -.01787 .1758 7.81887 22.96 24.73)" gradientUnits="userSpaceOnUse"><stop offset=".249" class="dz1f1dx9q"/><stop offset="1" class="a2gn4iuzk"/></radialGradient><radialGradient id="iK4HyMc" cx="0" cy="0" r="1" gradientTransform="matrix(0 5.49005 -3.73669 0 16 16.173)" gradientUnits="userSpaceOnUse"><stop offset=".232" class="w6969eyte"/><stop offset="1" class="nb487cbvy"/></radialGradient><radialGradient id="iGDyIKc" cx="0" cy="0" r="1" gradientTransform="matrix(-2.27543 1.55452 -.96733 -1.41593 15.145 19.571)" gradientUnits="userSpaceOnUse"><stop class="zif_-obqz"/><stop offset="1" class="j3eudux9e"/></radialGradient><radialGradient id="i9GCd4G" cx="0" cy="0" r="1" gradientTransform="matrix(0 3.28924 -4.48731 0 15.393 15.989)" gradientUnits="userSpaceOnUse"><stop offset=".344" class="rs3k7gc8p"/><stop offset=".987" class="zm4f_vbug"/></radialGradient><radialGradient id="iFBh55c" cx="0" cy="0" r="1" gradientTransform="matrix(0 -4.58005 5.35185 0 15.92 19.671)" gradientUnits="userSpaceOnUse"><stop offset=".027" class="h7qlxhb-a"/><stop offset=".737" class="wly33_qqy"/></radialGradient><radialGradient id="iOIbUde" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.87968 -1.90863 0 15.93 16.81)" gradientUnits="userSpaceOnUse"><stop offset=".298" class="ztiay3bsr"/><stop offset="1" class="d4abicb0m"/></radialGradient><radialGradient id="immCZLx" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.77385 -2.8552 0 15.93 14.864)" gradientUnits="userSpaceOnUse"><stop offset=".637" class="xcfgjsbuv"/><stop offset="1" class="h3ackr9-s"/></radialGradient><radialGradient id="iAJxrEb" cx="0" cy="0" r="1" gradientTransform="matrix(-.99999 -1.375 1.3434 -.977 11.38 12.123)" gradientUnits="userSpaceOnUse"><stop class="wc81wbc4w"/><stop offset="1" class="r1r_vbb7o"/></radialGradient><radialGradient id="iXUheWb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.46687 0 0 -2.17002 11.25 10.797)" gradientUnits="userSpaceOnUse"><stop offset=".149" class="yyk4p6yip"/><stop offset="1" class="e3i87pb5c"/></radialGradient><radialGradient id="iplIIZd" cx="0" cy="0" r="1" gradientTransform="rotate(-51.009 23.384 -16.112)scale(1.68866)" gradientUnits="userSpaceOnUse"><stop class="vl2cjyt3c"/><stop offset="1" class="bx_7xxbew"/></radialGradient><radialGradient id="i4NNL0d" cx="0" cy="0" r="1" gradientTransform="rotate(91.606 5.34 15.514)scale(1.11515)" gradientUnits="userSpaceOnUse"><stop class="bg0uvkbxl"/><stop offset=".912" class="npel8zblz"/></radialGradient><radialGradient id="irjmldb" cx="0" cy="0" r="1" gradientTransform="matrix(1.03903 -.98438 2.30833 2.4365 20.398 8.47)" gradientUnits="userSpaceOnUse"><stop offset=".269" class="kgaoz61he"/><stop offset=".879" class="loauufbpn"/></radialGradient><radialGradient id="i9ZO14d" cx="0" cy="0" r="1" gradientTransform="matrix(-1.1641 -.71876 .94072 -1.52358 11.602 8.798)" gradientUnits="userSpaceOnUse"><stop offset=".521" class="gqwm2cb_f"/><stop offset=".957" class="psirj8b2v"/></radialGradient><radialGradient id="ie6NYbe" cx="0" cy="0" r="1" gradientTransform="rotate(154.069 9.529 11.795)scale(3.78757 11.2112)" gradientUnits="userSpaceOnUse"><stop class="ium6abcxp"/><stop offset="1" class="h7lqrlw1r"/></radialGradient><radialGradient id="iwcZZdd" cx="0" cy="0" r="1" gradientTransform="matrix(2.5033 -1.90624 3.00378 3.94459 8.94 18.829)" gradientUnits="userSpaceOnUse"><stop class="g3ev-1bmq"/><stop offset="1" class="hdbb6nacd"/></radialGradient><radialGradient id="iXcNRVb" cx="0" cy="0" r="1" gradientTransform="matrix(-5.9544 1.19435 -2.01845 -10.06296 19.451 10.4)" gradientUnits="userSpaceOnUse"><stop offset=".248" class="am4t6ybzs"/><stop offset="1" class="vq-o0hb7c"/></radialGradient><radialGradient id="isjBsLe" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.13592 1.13266 0 14.095 9.673)" gradientUnits="userSpaceOnUse"><stop offset=".179" class="os_-_lbel"/><stop offset="1" class="hayka3bfc"/></radialGradient><radialGradient id="ihiap7d" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.04388 1.15848 0 18.427 9.477)" gradientUnits="userSpaceOnUse"><stop offset=".313" class="lprbii0_n"/><stop offset="1" class="sfz3e3bnu"/></radialGradient><radialGradient id="irDVSDb" cx="0" cy="0" r="1" gradientTransform="matrix(0 9.30493 -11.6557 0 16 8.478)" gradientUnits="userSpaceOnUse"><stop offset=".625" class="wt2vnwxrd"/><stop offset=".972" class="wypzjlw3a"/></radialGradient><radialGradient id="i3Xq1oe" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.35663 5.77264 0 15.813 17.571)" gradientUnits="userSpaceOnUse"><stop class="cx55tqblk"/><stop offset="1" class="sun7-kw7r"/></radialGradient><radialGradient id="iUn2jAc" cx="0" cy="0" r="1" gradientTransform="rotate(137.827 8.073 6.851)scale(3.58407 2.1419)" gradientUnits="userSpaceOnUse"><stop offset=".121" class="x_13atamu"/><stop offset="1" class="kzlhtpbbg"/></radialGradient><radialGradient id="idkMYtd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.99943 1.36453 -1.33986 -1.96328 28.12 23.788)" gradientUnits="userSpaceOnUse"><stop offset=".464" class="a05f1abog"/><stop offset="1" class="u70m8cc1d"/></radialGradient><radialGradient id="i1FGM5w" cx="0" cy="0" r="1" gradientTransform="matrix(.78818 -.60013 .4599 .60401 27.529 23.637)" gradientUnits="userSpaceOnUse"><stop offset=".132" class="hcxzg0b5c"/><stop offset="1" class="eqicngbxg"/></radialGradient><radialGradient id="imdDcCe" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.85126 .74829 0 26.113 24.79)" gradientUnits="userSpaceOnUse"><stop class="j2-8_acvh"/><stop offset="1" class="x6aj7b3cp"/></radialGradient><radialGradient id="iyWdt0d" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.82813 1.14062 0 26.137 21.61)" gradientUnits="userSpaceOnUse"><stop class="ag_y78bhq"/><stop offset="1" class="r_2nh8m3w"/></radialGradient><radialGradient id="iED5kQd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.14844 2.01125 0 25.638 21.993)" gradientUnits="userSpaceOnUse"><stop offset=".76" class="isjnp_l6m"/><stop offset="1" class="y9bk_9fsc"/></radialGradient><radialGradient id="idKoF8L" cx="0" cy="0" r="1" gradientTransform="matrix(0 .82316 -1.30932 0 18.214 9.99)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="bbyb_mbsk"/></radialGradient><radialGradient id="iZui0FM" cx="0" cy="0" r="1" gradientTransform="matrix(-.2353 -.30322 .41746 -.32395 17.982 10.075)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iGPIeBc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .8232 -1.30939 0 13.786 9.99)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="bbyb_mbsk"/></radialGradient><radialGradient id="igNjrdp" cx="0" cy="0" r="1" gradientTransform="matrix(-.00785 -.5013 .60257 -.00943 13.495 10.212)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iQCR8Oc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .8017 -1.35439 0 25.892 25.304)" gradientUnits="userSpaceOnUse"><stop offset=".106" class="yhi4l7bah"/><stop offset="1" class="sbugs4b_s"/></radialGradient><radialGradient id="ibIcReb" cx="0" cy="0" r="1" gradientTransform="matrix(0 .85938 -1.45182 0 25.892 26.599)" gradientUnits="userSpaceOnUse"><stop offset=".109" class="yhi4l7bah"/><stop offset="1" class="sbugs4b_s"/></radialGradient><radialGradient id="iCVbpsb" cx="0" cy="0" r="1" gradientTransform="matrix(0 .71875 -1.21425 0 25.892 27.849)" gradientUnits="userSpaceOnUse"><stop offset=".109" class="yhi4l7bah"/><stop offset="1" class="sbugs4b_s"/></radialGradient><radialGradient id="iT0u5kb" cx="0" cy="0" r="1" gradientTransform="matrix(0 .79938 -1.7273 0 25.892 29.2)" gradientUnits="userSpaceOnUse"><stop offset=".186" class="yhi4l7bah"/><stop offset="1" class="sbugs4b_s"/></radialGradient><linearGradient id="iYirTgO" x1="15.92" x2="15.92" y1="4.03" y2="4.083" gradientUnits="userSpaceOnUse"><stop class="xjz9wom2l"/><stop offset="1" class="pqe0dnzfz"/></linearGradient><linearGradient id="i9F1CId" x1="16" x2="16" y1="4.829" y2="14.86" gradientUnits="userSpaceOnUse"><stop class="dg7qenbli"/><stop offset="1" class="ws4hjpl0o"/></linearGradient><linearGradient id="i78VrFc" x1="8.94" x2="5.35" y1="28.454" y2="28.454" gradientUnits="userSpaceOnUse"><stop class="es32odbdd"/><stop offset="1" class="wevrdub6o"/></linearGradient><linearGradient id="iRutGzb" x1="26.503" x2="22.96" y1="22.884" y2="29.19" gradientUnits="userSpaceOnUse"><stop class="kcb1h97-p"/><stop offset="1" class="c6jm60b1r"/></linearGradient><linearGradient id="ihEhn2d" x1="20" x2="19.066" y1="18.517" y2="18.517" gradientUnits="userSpaceOnUse"><stop class="lzh17ac1w"/><stop offset="1" class="yrr42qhfr"/></linearGradient><linearGradient id="i4ja36c" x1="12" x2="12.334" y1="18.517" y2="18.517" gradientUnits="userSpaceOnUse"><stop offset=".143" class="pescu9bef"/><stop offset="1" class="fl69hubql"/></linearGradient><linearGradient id="i7akEKe" x1="21.926" x2="20.82" y1="9.779" y2="12.28" gradientUnits="userSpaceOnUse"><stop class="xfxz_xbmx"/><stop offset="1" class="cegy3obbl"/></linearGradient><linearGradient id="iEofhic" x1="17.162" x2="15.95" y1="29.142" y2="22.017" gradientUnits="userSpaceOnUse"><stop class="h3q0cq17v"/><stop offset="1" class="zykvaibcy"/></linearGradient><linearGradient id="iWiZHUM" x1="23.014" x2="22.787" y1="29.673" y2="29.673" gradientUnits="userSpaceOnUse"><stop class="w-ul8jbeq"/><stop offset="1" class="vtbjbdc7x"/></linearGradient><linearGradient id="iN7XaFc" x1="8.94" x2="9.064" y1="29.673" y2="29.673" gradientUnits="userSpaceOnUse"><stop class="w-ul8jbeq"/><stop offset="1" class="vtbjbdc7x"/></linearGradient><linearGradient id="ivDgabc" x1="13.787" x2="20.318" y1="28.36" y2="28.36" gradientUnits="userSpaceOnUse"><stop class="ym_13nbvu"/><stop offset="1" class="kehse99iu"/></linearGradient><linearGradient id="iCf1OAd" x1="16" x2="16.852" y1="11.763" y2="11.763" gradientUnits="userSpaceOnUse"><stop class="f6og14bdq"/><stop offset="1" class="hk633lr2o"/></linearGradient><linearGradient id="iRIiOoe" x1="14.931" x2="16.001" y1="11.618" y2="11.681" gradientUnits="userSpaceOnUse"><stop class="z_vmdubsa"/><stop offset=".203" class="umam-bfga"/><stop offset="1" class="oanih0n0r"/></linearGradient><linearGradient id="iLwVPwF" x1="16" x2="16" y1="12.133" y2="12.925" gradientUnits="userSpaceOnUse"><stop class="y-mxywbmo"/><stop offset=".845" class="ed0uty_4k"/></linearGradient><linearGradient id="iGhaIbQ" x1="16" x2="16" y1="10.045" y2="10.434" gradientUnits="userSpaceOnUse"><stop class="f6ma3ccql"/><stop offset="1" class="donh02dkd"/></linearGradient><linearGradient id="i32zuCj" x1="14.658" x2="15.011" y1="14.24" y2="13.334" gradientUnits="userSpaceOnUse"><stop class="hq16hab0i"/><stop offset="1" class="iokwoek-x"/></linearGradient><linearGradient id="iKeEkmd" x1="25.61" x2="25.61" y1="21.61" y2="24.79" gradientUnits="userSpaceOnUse"><stop class="rl_kfsb7q"/><stop offset=".997" class="va-kb9bvg"/></linearGradient><linearGradient id="i8JFE7b" x1="25.638" x2="25.638" y1="22.314" y2="21.72" gradientUnits="userSpaceOnUse"><stop class="lmnxagbed"/><stop offset="1" class="ztn8dybrr"/></linearGradient><linearGradient id="iEh3Ync" x1="19.003" x2="18.685" y1="10.044" y2="10.24" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iXEaXJd" x1="14.541" x2="14.223" y1="10.044" y2="10.24" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="ihrNxsc" x1="27.483" x2="23.454" y1="28.062" y2="28.062" gradientUnits="userSpaceOnUse"><stop offset=".146" class="hqh-1rbea"/><stop offset=".861" class="nfkkf0b1d"/></linearGradient><linearGradient id="ipWKtFb" x1="23.975" x2="25.684" y1="26.056" y2="26.056" gradientUnits="userSpaceOnUse"><stop class="uxfooubcv"/><stop offset="1" class="ldqge0b0v"/></linearGradient><linearGradient id="iHcqtpe" x1="23.896" x2="25.606" y1="27.36" y2="27.36" gradientUnits="userSpaceOnUse"><stop class="uxfooubcv"/><stop offset="1" class="ldqge0b0v"/></linearGradient><linearGradient id="i2TZIKB" x1="23.975" x2="25.684" y1="28.665" y2="28.665" gradientUnits="userSpaceOnUse"><stop class="uxfooubcv"/><stop offset="1" class="ldqge0b0v"/></linearGradient><filter id="ig4BfAV" width="20.537" height="10.328" x="5.481" y="4.829" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".5"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.478431 0 0 0 0 0.384314 0 0 0 0 0.368627 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1812"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.5" dy=".25"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.388235 0 0 0 0 0.243137 0 0 0 0 0.25098 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1812" result="effect2_innerShadow_4002_1812"/></filter><filter id="ial5I3A" width="8" height="6.44" x="12" y="15.27" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".175"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.109804 0 0 0 0 0.47451 0 0 0 0 0.333333 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1812"/></filter><filter id="iCVHYBc" width="3.44" height="3.34" x="9.36" y="8.94" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.807843 0 0 0 0 0.592157 0 0 0 0 0.501961 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1812"/></filter><filter id="iLUbhJd" width="2.64" height="2.64" x="9.71" y="9.29" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1812" stdDeviation=".1"/></filter><filter id="ixtQPPb" width="2.827" height="2.827" x="19.407" y="9.196" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.796078 0 0 0 0 0.576471 0 0 0 0 0.435294 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1812"/><feGaussianBlur result="effect2_foregroundBlur_4002_1812" stdDeviation=".125"/></filter><filter id="im6AlCd" width="8.45" height="4.612" x="11.73" y="25.58" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1812" stdDeviation=".125"/></filter><filter id="i5cxrfi" width="8.05" height="4.28" x="11.88" y="25.83" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.258824 0 0 0 0 0.67451 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1812"/></filter><filter id="iwMCiwd" width="10.66" height="10.004" x="10.92" y="7.002" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.85098 0 0 0 0 0.623529 0 0 0 0 0.517647 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1812"/></filter><filter id="iu00ihd" width="3.871" height="4.695" x="13.872" y="9.27" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1812" stdDeviation=".5"/></filter><filter id="iFVyNjb" width="2.071" height="2.895" x="14.965" y="9.945" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1812" stdDeviation=".05"/></filter><filter id="iEyVjCc" width="3.833" height="1.572" x="14.023" y="13.128" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1812" stdDeviation=".05"/></filter><filter id="ixxrVjb" width="7.625" height="9.853" x="21.853" y="10.664" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.4"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.529412 0 0 0 0 0.470588 0 0 0 0 0.588235 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1812"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.3" dy=".5"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.784314 0 0 0 0 0.776471 0 0 0 0 0.796078 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1812" result="effect2_innerShadow_4002_1812"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".1"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.517647 0 0 0 0 0.517647 0 0 0 0 0.545098 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_4002_1812" result="effect3_innerShadow_4002_1812"/></filter><filter id="iDxYCHe" width=".795" height=".703" x="17.47" y="9.545" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1812" stdDeviation=".05"/></filter><filter id="i2d9bbc" width=".898" height=".921" x="18.324" y="9.622" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1812" stdDeviation=".1"/></filter><filter id="ikvdJue" width=".995" height="1.05" x="13.816" y="9.558" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1812" stdDeviation=".1"/></filter><filter id="iZ1z8Fb" width=".923" height=".712" x="13.049" y="9.536" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1812" stdDeviation=".05"/></filter><filter id="i7c6vTb" width="4.468" height="5.556" x="23.454" y="24.444" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.15"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.658824 0 0 0 0 0.443137 0 0 0 0 0.411765 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1812"/></filter><filter id="iL5yHVd" width="2.097" height=".3" x="23.825" y="25.828" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1812" stdDeviation=".05"/></filter><filter id="ixsMuiq" width="2.097" height=".3" x="23.747" y="27.132" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1812" stdDeviation=".05"/></filter><filter id="iRMlbVx" width="2.097" height=".3" x="23.825" y="28.437" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1812" stdDeviation=".05"/></filter><filter id="iBS1oTd" width="2.573" height="1.468" x="12.133" y="7.336" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.466667 0 0 0 0 0.266667 0 0 0 0 0.168627 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1812"/></filter><filter id="ix0UAsl" width="2.573" height="1.468" x="17.293" y="7.336" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.466667 0 0 0 0 0.266667 0 0 0 0 0.168627 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1812"/></filter><filter id="iOrh1Cc" width="2.123" height=".868" x="17.56" y="7.594" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1812" stdDeviation=".075"/></filter><filter id="izHxPwZ" width="2.123" height=".868" x="12.3" y="7.594" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1812" stdDeviation=".075"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:man-farmer-medium-light" /></template>
<style>
.a05f1abog {
  stop-color: var(--svg-color--deaf8e, #DEAF8E);
}

.a2gn4iuzk {
  stop-color: var(--svg-color--28a96b, #28A96B);
  stop-opacity: 0;
}

.ag_y78bhq {
  stop-color: var(--svg-color--c7c1cc, #C7C1CC);
}

.am4t6ybzs {
  stop-color: var(--svg-color--f9c29a, #F9C29A);
}

.aoi-30bis {
  d: path("m15.62 10.33l-.53 1.71c-.11.35.15.7.52.7h.78c.37 0 .63-.35.52-.7l-.52-1.71a.403.403 0 0 0-.77 0");
}

.b0fcggb5v {
  d: path("M15.93 18.69c-1.14 0-2.06-.92-2.06-2.06v-2.56c0-1.14.92-2.06 2.06-2.06s2.06.92 2.06 2.06v2.56a2.07 2.07 0 0 1-2.06 2.06");
}

.bbyb_mbsk {
  stop-color: var(--svg-color--664842, #664842);
}

.bg0uvkbxl {
  stop-color: var(--svg-color--dba889, #DBA889);
}

.bhtc49btl {
  d: path("M13.784 9.505a.906.906 0 0 0-.873 1.145h1.75a1 1 0 0 0 .033-.24a.91.91 0 0 0-.91-.905");
}

.bx_7xxbew {
  stop-color: var(--svg-color--cc9981, #CC9981);
  stop-opacity: 0;
}

.c0ces0ufe {
  d: path("M20.82 11.773a1.163 1.163 0 1 0 0-2.327a1.163 1.163 0 0 0 0 2.327");
}

.c6jm60b1r {
  stop-color: var(--svg-color--368d6e, #368D6E);
}

.c75mxbchy {
  fill: var(--svg-color--c48377, #C48377);
  d: path("m15.427 10.555l-.53 1.71c-.11.35.15.7.52.7h.78c.37 0 .63-.35.52-.7l-.52-1.71a.403.403 0 0 0-.77 0");
}

.cegy3obbl {
  stop-color: var(--svg-color--d9a385, #D9A385);
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cn_4wnbjs {
  fill: var(--svg-color--875425, #875425);
  fill-rule: evenodd;
  d: path("M19.15 8.688a.425.425 0 0 0 .587-.615c-.493.51 0 0 0 0h-.001l-.002-.002l-.004-.004l-.01-.01a1 1 0 0 0-.144-.113a2.3 2.3 0 0 0-.403-.228a2.85 2.85 0 0 0-1.505-.207a.425.425 0 0 0 .1.844c.477-.057.831.039 1.06.14a1.5 1.5 0 0 1 .312.187z");
}

.cx55tqblk {
  stop-color: var(--svg-color--a27678, #A27678);
}

.d4abicb0m {
  stop-color: var(--svg-color--b48574, #B48574);
}

.d5bh__bgt {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M23.975 25.978h1.796");
}

.d6r03hc-n {
  stop-color: var(--svg-color--63c890, #63C890);
}

.d89qw3dmr {
  cx: 13.511px;
  cy: 9.892px;
  rx: 0.395px;
  ry: 0.2px;
}

.dg7qenbli {
  stop-color: var(--svg-color--6b3d41, #6B3D41);
}

.donh02dkd {
  stop-color: var(--svg-color--e0a78c, #E0A78C);
  stop-opacity: 0;
}

.dvymziplf {
  d: path("M11.03 11.73a1.12 1.12 0 1 0 0-2.24a1.12 1.12 0 0 0 0 2.24");
}

.dym4kjb3u {
  stroke: var(--svg-color--98643d, #98643D);
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-miterlimit: 10;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M19.483 8.262s-.6-.581-1.723-.448");
}

.dz1f1dx9q {
  stop-color: var(--svg-color--28a96b, #28A96B);
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.e2_jykbzy {
  stop-color: var(--svg-color--6e4f4b, #6E4F4B);
  stop-opacity: 0;
}

.e3i87pb5c {
  stop-color: var(--svg-color--bd826e, #BD826E);
}

.e4o45ibyi {
  fill: var(--svg-color--000, #000);
  d: path("M14.303 10.41a.516.516 0 0 0-.519-.518a.516.516 0 0 0-.461.758h.918a.5.5 0 0 0 .062-.24");
}

.ed0uty_4k {
  stop-color: var(--svg-color--cb8685, #CB8685);
}

.efez_2bmy {
  d: path("M11.564 4.83c-.85.03-2.678.228-4.102 1.335c-1.238.963-1.477 2.117-1.477 3.086v.477c-.093 1.78 1.446 4.93 6.883 4.93h6.264c5.437 0 6.976-3.15 6.883-4.93V9.25c0-.969-.24-2.123-1.477-3.086c-1.423-1.107-3.252-1.305-4.101-1.336z");
}

.ehp0m0b6n {
  d: path("M18.216 9.506a.905.905 0 0 1 .872 1.144H17.34a.91.91 0 0 1 .877-1.144");
}

.en3cqcc2r {
  d: path("M21.92 5.93h-12l.18-.36a6.549 6.549 0 0 1 11.65.03z");
}

.eqicngbxg {
  stop-color: var(--svg-color--e6bea1, #E6BEA1);
  stop-opacity: 0;
}

.es32odbdd {
  stop-color: var(--svg-color--399965, #399965);
}

.f278--bqq {
  stroke: var(--svg-color--98643d, #98643D);
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-miterlimit: 10;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M12.5 8.262s.6-.581 1.723-.448");
}

.f6ma3ccql {
  stop-color: var(--svg-color--e0a78c, #E0A78C);
}

.f6og14bdq {
  stop-color: var(--svg-color--e1aa8c, #E1AA8C);
}

.fl69hubql {
  stop-color: var(--svg-color--6a9e7e, #6A9E7E);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.g3ev-1bmq {
  stop-color: var(--svg-color--3da0db, #3DA0DB);
}

.gqwm2cb_f {
  stop-color: var(--svg-color--cfa180, #CFA180);
}

.h29l8x_8c {
  stop-color: var(--svg-color--63c890, #63C890);
  stop-opacity: 0;
}

.h3ackr9-s {
  stop-color: var(--svg-color--805333, #805333);
}

.h3q0cq17v {
  stop-color: var(--svg-color--3560c5, #3560C5);
}

.h7lqrlw1r {
  stop-color: var(--svg-color--47b2f6, #47B2F6);
  stop-opacity: 0;
}

.h7qlxhb-a {
  stop-color: var(--svg-color--e9cee6, #E9CEE6);
}

.hayka3bfc {
  stop-color: var(--svg-color--c4887c, #C4887C);
  stop-opacity: 0;
}

.hcxzg0b5c {
  stop-color: var(--svg-color--e6bea1, #E6BEA1);
}

.hdbb6nacd {
  stop-color: var(--svg-color--3aa1e0, #3AA1E0);
  stop-opacity: 0;
}

.hiy36ccjt {
  cx: 13.511px;
  cy: 9.892px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.395px;
  ry: 0.2px;
}

.hk633lr2o {
  stop-color: var(--svg-color--fecaa8, #FECAA8);
}

.hq16hab0i {
  stop-color: var(--svg-color--cf9a8c, #CF9A8C);
}

.hqh-1rbea {
  stop-color: var(--svg-color--f3c29f, #F3C29F);
}

.i-6b1qbmn {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M18.15 9.697c.064.086-.071.191-.224.306s-.267.195-.332.109c-.064-.086.008-.25.16-.364c.154-.114.33-.137.395-.051");
}

.i51qo2bmb {
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M14.484 13.306c-.199-.106-.392.12-.276.3v.001a2.07 2.07 0 0 0 1.732.943a2.07 2.07 0 0 0 1.732-.943a.2.2 0 0 0-.024-.255a.21.21 0 0 0-.25-.047h-.002a3.1 3.1 0 0 1-1.456.355a3.1 3.1 0 0 1-1.456-.354Z");
}

.idanqg1oa {
  d: path("M23.455 25.325c0-.4.325-.732.726-.732h2.391a1.2 1.2 0 0 1 1.2 1.2V29a1 1 0 0 1-1 1h-2.591a.731.731 0 0 1-.32-1.39a.735.735 0 0 1 0-1.313a.735.735 0 0 1 0-1.315a.74.74 0 0 1-.407-.657");
}

.iokwoek-x {
  stop-color: var(--svg-color--cf9a8c, #CF9A8C);
  stop-opacity: 0;
}

.isjnp_l6m {
  stop-color: var(--svg-color--85808c, #85808C);
  stop-opacity: 0;
}

.ium6abcxp {
  stop-color: var(--svg-color--47b2f6, #47B2F6);
}

.j2-8_acvh {
  stop-color: var(--svg-color--88625f, #88625F);
}

.j3eudux9e {
  stop-color: var(--svg-color--519473, #519473);
  stop-opacity: 0;
}

.jm4hqf2zy {
  fill: var(--svg-color--c08675, #C08675);
  d: path("M11.03 12.28a1.67 1.67 0 1 0 0-3.34a1.67 1.67 0 0 0 0 3.34");
}

.k150n8bho {
  fill: var(--svg-color--89004f, #89004F);
  d: path("M15.94 13.71c-.54 0-1.05-.13-1.48-.36c-.15-.08-.3.09-.21.23c.36.55.98.92 1.69.92s1.33-.37 1.69-.92c.09-.14-.07-.3-.21-.23c-.43.23-.94.36-1.48.36");
}

.kc6n1tb_x {
  stop-color: var(--svg-color--399967, #399967);
  stop-opacity: 0;
}

.kcb1h97-p {
  stop-color: var(--svg-color--63d591, #63D591);
}

.kehse99iu {
  stop-color: var(--svg-color--389dff, #389DFF);
}

.kgaoz61he {
  stop-color: var(--svg-color--edc48e, #EDC48E);
}

.kky8tzcjx {
  d: path("M22.96 30V18.03h.006a10.95 10.95 0 0 1 3.994 8.47V30z");
}

.kw34xudqh {
  d: path("M10.508 7.74c.418-.64 1.996-.738 2.566-.738l-1.726 3.18h-.53c-.177 0-.35-.076-.433-.23c-.285-.529-.438-1.467.123-2.212");
}

.kzlhtpbbg {
  stop-color: var(--svg-color--d9ab96, #D9AB96);
  stop-opacity: 0;
}

.l5sb_gbjb {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M23.975 28.587h1.796");
}

.lam2cnohl {
  d: path("M19.42 25.83h-6.94c-.28 0-.5.22-.5.5v3.68h7.95v-3.68a.517.517 0 0 0-.51-.5");
}

.ldqge0b0v {
  stop-color: var(--svg-color--c08666, #C08666);
  stop-opacity: 0;
}

.lgo9yub8v {
  stop-color: var(--svg-color--7f5f58, #7F5F58);
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lioq9m7hi {
  d: path("M22.96 18.06c-.63-.53-1.33-.99-2.07-1.36v5.9c0 .23-.18.41-.41.41h-9.07c-.23 0-.41-.18-.41-.41v-5.92c-.74.37-1.43.82-2.06 1.35V30h14.02z");
}

.lmnxagbed {
  stop-color: var(--svg-color--89829d, #89829D);
}

.loauufbpn {
  stop-color: var(--svg-color--eccda5, #ECCDA5);
}

.lprbii0_n {
  stop-color: var(--svg-color--e1a58a, #E1A58A);
}

.ltcbfxk7p {
  stop-color: var(--svg-color--644841, #644841);
}

.lzh17ac1w {
  stop-color: var(--svg-color--5aa37a, #5AA37A);
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.nb487cbvy {
  stop-color: var(--svg-color--3d8f6c, #3D8F6C);
}

.nfkkf0b1d {
  stop-color: var(--svg-color--c4907c, #C4907C);
}

.nkojhbbwr {
  d: path("M19.082 7.002h-6.168c-1.127 0-2.086 1.008-1.987 2.125l.184 4.942c.168 1.71 1.532 2.937 3.193 2.937h3.394c1.661 0 3.026-1.226 3.194-2.937l.187-5.04c.04-1.078-.91-2.027-1.997-2.027");
}

.nmo9kfdje {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.426 9.23c.663 0 1.222.457 1.375 1.074a.278.278 0 0 1-.272.346h-2.264a.234.234 0 0 1-.23-.276c.127-.65.7-1.144 1.391-1.144");
}

.npel8zblz {
  stop-color: var(--svg-color--d6a080, #D6A080);
}

.o2pamybnw {
  d: path("M14.611 10.305c0-.293-.238-.488-.302-.547l-.292.283l.18.367z");
}

.oanih0n0r {
  stop-color: var(--svg-color--d29879, #D29879);
  stop-opacity: 0;
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.ogazzbbkt {
  d: path("M19.022 10.292a.85.85 0 0 0-.234-.47l-.264.29l.119.231z");
}

.oolzzy49q {
  stop-color: var(--svg-color--399967, #399967);
}

.or173xb1f {
  d: path("M20.82 12.28a1.67 1.67 0 1 0 0-3.34a1.67 1.67 0 0 0 0 3.34");
}

.os_-_lbel {
  stop-color: var(--svg-color--c4887c, #C4887C);
}

.pescu9bef {
  stop-color: var(--svg-color--6a9e7e, #6A9E7E);
}

.pjyridg8y {
  d: path("M18.15 9.697c.064.086-.071.191-.224.306s-.267.195-.332.109c-.064-.086.008-.25.16-.364c.154-.114.33-.137.395-.051");
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pqe0dnzfz {
  stop-color: var(--svg-color--4e2d3a, #4E2D3A);
  stop-opacity: 0;
}

.psirj8b2v {
  stop-color: var(--svg-color--e8ba93, #E8BA93);
}

.q5oqcih4w {
  d: path("M12.964 21.493L16 19.37l2.987 2.084c.421.324 1.013.465 1.013-.354v-4.81c-1.24-.48-2.59-.77-4-.77s-2.76.24-4 .72v4.69c0 .954.594.823.964.563");
}

.qmyxitbhu {
  d: path("M15.93 15.52c-6.07 0-10.99 4.91-10.99 10.98V30h21.98v-3.5c0-6.07-4.92-10.98-10.99-10.98");
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.r_2nh8m3w {
  stop-color: var(--svg-color--a099a8, #A099A8);
}

.r1r_vbb7o {
  stop-color: var(--svg-color--bf8271, #BF8271);
  stop-opacity: 0;
}

.r9exlwbyv {
  stop-color: var(--svg-color--4f3b60, #4F3B60);
}

.racw9ccri {
  d: path("M24.877 20.009H26.4v1.734a.25.25 0 0 1-.25.25h-1.023a.25.25 0 0 1-.25-.25z");
}

.rl_kfsb7q {
  stop-color: var(--svg-color--784853, #784853);
}

.rqjejjbyp {
  d: path("M26.113 21.79h-1v3h1z");
}

.rs3k7gc8p {
  stop-color: var(--svg-color--2a5923, #2A5923);
}

.s6evr8b9t {
  d: path("M11.03 12.28a1.67 1.67 0 1 0 0-3.34a1.67 1.67 0 0 0 0 3.34");
}

.sbugs4b_s {
  stop-color: var(--svg-color--f2c49e, #F2C49E);
  stop-opacity: 0;
}

.seszgebct {
  d: path("m16.85 19.71l-.65.58c-.16.14-.39.14-.55 0l-.65-.58a3.45 3.45 0 0 1-1.14-2.55v-3.09c0-1.14.92-2.06 2.06-2.06s2.06.92 2.06 2.06v3.09c0 .97-.41 1.9-1.13 2.55");
}

.sfz3e3bnu {
  stop-color: var(--svg-color--e1a58a, #E1A58A);
  stop-opacity: 0;
}

.sn76xowoz {
  d: path("M26.772 23.14c.55 0 1 .45 1 1v2.29h-2v-2.29c0-.55.44-1 1-1");
}

.sog6_lbfk {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M23.897 27.282h1.796");
}

.sun7-kw7r {
  stop-color: var(--svg-color--a27678, #A27678);
  stop-opacity: 0;
}

.t7_hkjbap {
  d: path("m10.1 5.57l-.18.36h12l-.17-.33c-.3-.59-.68-1.11-1.12-1.57h-9.42c-.43.45-.81.97-1.11 1.54");
}

.tidl_lzwa {
  fill: var(--svg-color--000, #000);
  d: path("M17.697 10.41c0-.287.23-.518.519-.518a.516.516 0 0 1 .46.758h-.917a.47.47 0 0 1-.062-.24");
}

.tyd3-kmwr {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.574 9.23c-.662 0-1.222.457-1.375 1.074a.278.278 0 0 0 .272.346h2.264c.144 0 .26-.132.23-.276a1.42 1.42 0 0 0-1.39-1.144");
}

.u70m8cc1d {
  stop-color: var(--svg-color--b27959, #B27959);
}

.umam-bfga {
  stop-color: var(--svg-color--d29879, #D29879);
}

.urrq_mbar {
  fill: var(--svg-color--c4b9cc, #C4B9CC);
  d: path("M22.755 11.064a.6.6 0 0 0-.602.601v6.852a1.5 1.5 0 0 0 1.5 1.5h4.125a1.5 1.5 0 0 0 1.5-1.5v-6.852a.601.601 0 1 0-1.203 0v4.45a.879.879 0 0 1-1.758 0v-4.45a.602.602 0 0 0-1.203 0v4.45a.879.879 0 0 1-1.757 0v-4.45a.6.6 0 0 0-.602-.601");
}

.uxfooubcv {
  stop-color: var(--svg-color--ae7759, #AE7759);
}

.v_qusm7gm {
  fill: var(--svg-color--45bb85, #45BB85);
  d: path("M15.93 15.52c-6.07 0-10.99 4.91-10.99 10.98V30h21.98v-3.5c0-6.07-4.92-10.98-10.99-10.98");
}

.va-kb9bvg {
  stop-color: var(--svg-color--7d5248, #7D5248);
}

.vl2cjyt3c {
  stop-color: var(--svg-color--cc9981, #CC9981);
}

.vq-o0hb7c {
  stop-color: var(--svg-color--ca947d, #CA947D);
}

.vtbjbdc7x {
  stop-color: var(--svg-color--356ebb, #356EBB);
  stop-opacity: 0;
}

.w-ul8jbeq {
  stop-color: var(--svg-color--356ebb, #356EBB);
}

.w6969eyte {
  stop-color: var(--svg-color--387c46, #387C46);
}

.w7xati8xm {
  fill: var(--svg-color--875425, #875425);
  fill-rule: evenodd;
  d: path("M12.85 8.688a.425.425 0 0 1-.587-.615l.296.306l-.296-.306h.001l.002-.002l.004-.004l.01-.01a1 1 0 0 1 .144-.113a2.3 2.3 0 0 1 .403-.228a2.85 2.85 0 0 1 1.505-.207a.425.425 0 0 1-.1.844a2 2 0 0 0-1.06.14a1.5 1.5 0 0 0-.312.187z");
}

.wc81wbc4w {
  stop-color: var(--svg-color--bf8271, #BF8271);
}

.wevrdub6o {
  stop-color: var(--svg-color--5cc585, #5CC585);
}

.wly33_qqy {
  stop-color: var(--svg-color--9c8f92, #9C8F92);
}

.ws4hjpl0o {
  stop-color: var(--svg-color--7c5653, #7C5653);
}

.wt2vnwxrd {
  stop-color: var(--svg-color--bd8384, #BD8384);
  stop-opacity: 0;
}

.wypzjlw3a {
  stop-color: var(--svg-color--a07575, #A07575);
}

.x_13atamu {
  stop-color: var(--svg-color--d9ab96, #D9AB96);
}

.x6aj7b3cp {
  stop-color: var(--svg-color--88625f, #88625F);
  stop-opacity: 0;
}

.xcfgjsbuv {
  stop-color: var(--svg-color--805333, #805333);
  stop-opacity: 0;
}

.xfxz_xbmx {
  stop-color: var(--svg-color--dcaf93, #DCAF93);
}

.xjz9wom2l {
  stop-color: var(--svg-color--4e2d3a, #4E2D3A);
}

.y-mxywbmo {
  stop-color: var(--svg-color--cb8685, #CB8685);
  stop-opacity: 0;
}

.y9bk_9fsc {
  stop-color: var(--svg-color--85808c, #85808C);
}

.ya4lejb1r {
  stop-color: var(--svg-color--6e5980, #6E5980);
}

.yc_s6bd2r {
  stop-color: var(--svg-color--6e4f4b, #6E4F4B);
}

.ygr1mqboi {
  fill: var(--svg-color--3661c6, #3661C6);
  d: path("M19.42 25.83h-6.94a.49.49 0 0 0-.5.492v3.62h7.95v-3.62a.513.513 0 0 0-.51-.492");
}

.yhi4l7bah {
  stop-color: var(--svg-color--f8c8ad, #F8C8AD);
}

.ym_13nbvu {
  stop-color: var(--svg-color--3ca9ff, #3CA9FF);
}

.yrr42qhfr {
  stop-color: var(--svg-color--5aa37a, #5AA37A);
  stop-opacity: 0;
}

.yyk4p6yip {
  stop-color: var(--svg-color--b67862, #B67862);
}

.z_vmdubsa {
  stop-color: var(--svg-color--d29879, #D29879);
  stop-opacity: 0.915;
}

.z1ud-kpwi {
  d: path("M8.94 30V18.03h-.006A10.95 10.95 0 0 0 4.94 26.5V30z");
}

.z7v4f46_s {
  d: path("M21.492 7.74c-.418-.64-1.996-.738-2.566-.738l1.726 3.18h.53c.177 0 .35-.076.433-.23c.286-.529.438-1.467-.123-2.212");
}

.zif_-obqz {
  stop-color: var(--svg-color--519473, #519473);
}

.zm4f_vbug {
  stop-color: var(--svg-color--2a5923, #2A5923);
  stop-opacity: 0;
}

.ztiay3bsr {
  stop-color: var(--svg-color--aa7876, #AA7876);
}

.ztn8dybrr {
  stop-color: var(--svg-color--89829d, #89829D);
  stop-opacity: 0;
}

.zykvaibcy {
  stop-color: var(--svg-color--329fea, #329FEA);
}

</style>
