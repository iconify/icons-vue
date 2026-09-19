<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iPyDnqc)"><path class="gj3zww6vu"/><path fill="url(#igor3Gb)" class="uba0w767q"/></g><path fill="url(#iIGioBb)" class="k11z14bzp"/><path fill="url(#i24w8Cd)" class="k11z14bzp"/><path fill="url(#iMvt7ze)" class="nx7otbuhy"/><path fill="url(#iQbkTHd)" class="nx7otbuhy"/><path fill="url(#i6bDAZc)" class="rcaxln_tj"/><path fill="url(#iNxtrnd)" class="rcaxln_tj"/><path fill="url(#ikdOtqe)" class="rcaxln_tj"/><path fill="url(#i91Rooe)" class="rcaxln_tj"/><path fill="url(#iiMOPSG)" class="dz22vydpm"/><path fill="url(#iJLLXdb)" class="dz22vydpm"/><path fill="url(#iByWW2b)" class="dz22vydpm"/><path fill="url(#inT6Foe)" class="dz22vydpm"/><path fill="url(#ixVT4Wb)" class="dz22vydpm"/><path fill="url(#ilB0Wzc)" class="dz22vydpm"/><path fill="url(#iKDccHc)" class="xae-7spdj"/><path fill="url(#iS84Bnu)" class="m-wch-t_n"/><path fill="url(#ix3fokc)" class="d_l0xgbwf"/><path fill="url(#iMNKWHd)" class="q0gcp3bpu"/><path fill="url(#iW300Cb)" class="q0gcp3bpu"/><path fill="url(#iGjwQCd)" class="q0gcp3bpu"/><path fill="url(#ikOF6xd)" class="qnami1-cw"/><path fill="url(#iWk20LR)" class="qnami1-cw"/><path fill="url(#iB0qGAe)" class="jqw16nonk"/><path fill="url(#iFvug5c)" class="jqw16nonk"/><path fill="url(#iF5C5le)" class="jqw16nonk"/><path fill="url(#i4e3klc)" class="jqw16nonk"/><g filter="url(#iKzeJpc)"><path fill="url(#iLiq6Dd)" class="knolhud8e"/><path fill="url(#iJmncce)" class="knolhud8e"/><path fill="url(#ig45bRd)" class="knolhud8e"/></g><path fill="url(#iFRjnrb)" class="i17r3cb_z"/><path fill="url(#i8PtfSb)" class="i17r3cb_z"/><path fill="url(#iRQsDTc)" class="i17r3cb_z"/><g filter="url(#i88bEyc)"><path fill="url(#iqQ3BRc)" class="sxc5dabme"/></g><g filter="url(#ij8sGac)"><circle fill="url(#iaTK3Db)" class="qh_sysofq"/></g><g filter="url(#iGvLMDc)"><circle fill="url(#iOUZFae)" class="plgpmnbcq"/></g><g filter="url(#iI3Fj7c)"><path fill="url(#ic9lpth)" class="w2g6prbzi"/><path fill="url(#iC35bTd)" class="w2g6prbzi"/><path fill="url(#iK4ZIpc)" class="w2g6prbzi"/><path fill="url(#iEFUEtd)" class="w2g6prbzi"/><path fill="url(#igWxpNc)" class="w2g6prbzi"/></g><g filter="url(#iZXawkQ)"><path stroke="url(#i3marjd)" class="gw5hcg17q"/></g><g filter="url(#i9sRVob)"><path stroke="url(#i0hW5Fb)" class="bsvhxursv"/></g><g filter="url(#igTJbQe)"><path stroke="url(#iy2BjcV)" class="vmrtso9qd"/></g><g filter="url(#iY2tUui)"><circle fill="url(#iidUzge)" class="hre2qfboa"/></g><circle fill="url(#iti6aed)" class="hre2qfboa"/><g filter="url(#i3aAjOe)"><circle fill="url(#iBAhQSZ)" class="ax7pcvbpy"/></g><g filter="url(#iKGUg8u)"><circle fill="url(#itlyKOP)" class="n4m-kxv1v"/><circle fill="url(#iHVCg7l)" class="n4m-kxv1v"/></g><g filter="url(#isHJjqd)"><circle class="b2oqkkb1l"/><circle fill="url(#i9DFeVZ)" class="nyj1sbbug"/><circle fill="url(#ir2pXhO)" class="nyj1sbbug"/></g><g filter="url(#iPIwZSb)"><path fill="url(#iA3KpPt)" class="qol164g5k"/><path fill="url(#i1Pc7bd)" class="qol164g5k"/><path fill="url(#iOKkese)" class="qol164g5k"/></g><path fill="url(#iZ1mDpe)" class="wgn_rvbma"/><path fill="url(#iRMAPmR)" class="wgn_rvbma"/><path fill="url(#ibT6CPe)" class="wgn_rvbma"/><path fill="url(#icfvQLe)" class="wgn_rvbma"/><g filter="url(#i6XWsXd)"><path fill="url(#ibCZzse)" class="a7lil8crc"/></g><g filter="url(#ib0ZOrb)"><path class="jq2gabc_s"/><path fill="url(#ildNVHc)" class="bx_706lpj"/><path fill="url(#iwm24Ub)" class="bx_706lpj"/><path fill="url(#iOrmwdd)" class="bx_706lpj"/><path fill="url(#iChgPod)" class="bx_706lpj"/></g><g filter="url(#idZn73b)"><path class="i5-87ib3k"/></g><g filter="url(#ijfEicb)"><path class="elah571hr"/><path fill="url(#iGCEgBb)" class="kimybvkmf"/><path fill="url(#iTYUIkW)" class="kimybvkmf"/><path fill="url(#iE2tb4c)" class="kimybvkmf"/><path fill="url(#ibPd1kY)" class="kimybvkmf"/></g><path fill="url(#isjmPvc)" class="kimybvkmf"/><path fill="url(#ijeu7Ge)" class="do752sbjh"/><path fill="url(#iqzdySw)" class="do752sbjh"/><path fill="url(#ihAqlIc)" class="do752sbjh"/><path stroke="url(#iNgdnoc)" class="qqbkbjb6w"/><g filter="url(#inaV4wF)"><path class="l9hbmrwjw"/><path fill="url(#ikBDN6d)" class="k8ge5dlro"/></g><g filter="url(#iM3VRZb)"><path class="irp9u6dgr"/><path fill="url(#il0zKoe)" class="cb83gypuf"/></g><path class="qz389ycjy"/><path fill="url(#ioqSB1e)" class="vwbl2bazu"/><path class="p3ajftwoy"/><g filter="url(#iqQKlJe)"><path class="lm-qrljex"/><path fill="url(#i3vsOge)" class="opvnr7b5e"/></g><g filter="url(#ijCXTud)"><path fill="url(#iVGbSuy)" class="g2n8qcc6u"/></g><path class="zrzq9bc8v"/><path fill="url(#i3shHGe)" class="cpu5ihbur"/><path class="pujp6dbuf"/><g filter="url(#iLSsW1b)"><path fill="url(#iFE8PEc)" class="pizp6ebil"/></g><g filter="url(#iqJOb5p)"><ellipse transform="rotate(-27.914 12.686 11.443)" class="sh___bchx"/><ellipse fill="url(#iK0m8ld)" transform="rotate(-27.914 12.686 11.443)" class="ih6ylj_bo"/></g><g filter="url(#iljuWHb)"><path stroke="url(#imurRpd)" class="b9f983ucc"/></g><g filter="url(#inNTDZN)"><path stroke="url(#ixnWhre)" class="k6qg2pirw"/></g><g filter="url(#iZprAYc)"><path stroke="url(#iJRrSkc)" class="z62f_abmw"/></g><defs><radialGradient id="iIGioBb" cx="0" cy="0" r="1" gradientTransform="matrix(3.125 1 -2.08207 6.50646 3.708 25.86)" gradientUnits="userSpaceOnUse"><stop offset=".176" class="li28y9bsf"/><stop offset="1" class="o1jwunhtj"/></radialGradient><radialGradient id="iMvt7ze" cx="0" cy="0" r="1" gradientTransform="rotate(110.288 4.581 19.67)scale(5.49596 3.74438)" gradientUnits="userSpaceOnUse"><stop class="oe2xm9ikp"/><stop offset="1" class="d6d59o0ou"/></radialGradient><radialGradient id="ikdOtqe" cx="0" cy="0" r="1" gradientTransform="matrix(-2.71872 5.59376 -.25587 -.12436 24.239 18.141)" gradientUnits="userSpaceOnUse"><stop class="m4vk7-mbl"/><stop offset="1" class="esw1hmivn"/></radialGradient><radialGradient id="iJLLXdb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.55616 -6.67822 .6506 -.1516 13.25 28.761)" gradientUnits="userSpaceOnUse"><stop class="o4j1rvu5g"/><stop offset="1" class="yp-hr1bpr"/></radialGradient><radialGradient id="ilB0Wzc" cx="0" cy="0" r="1" gradientTransform="matrix(-2.17874 .81494 -1.02635 -2.74392 12.187 18.027)" gradientUnits="userSpaceOnUse"><stop offset=".178" class="k910dfb4a"/><stop offset="1" class="vm-pj7b0c"/></radialGradient><radialGradient id="iMNKWHd" cx="0" cy="0" r="1" gradientTransform="matrix(0 9.50857 -5.52096 0 15.105 20.5)" gradientUnits="userSpaceOnUse"><stop offset=".092" class="cn088_52m"/><stop offset=".838" class="nym90gb4n"/></radialGradient><radialGradient id="iW300Cb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -7.08205 11.2731 0 15.106 24.451)" gradientUnits="userSpaceOnUse"><stop offset=".717" class="ayb1dwuvg"/><stop offset=".937" class="z6xoafb2r"/></radialGradient><radialGradient id="ikOF6xd" cx="0" cy="0" r="1" gradientTransform="matrix(-2.1394 1.4599 -1.43346 -2.10066 28.718 21.77)" gradientUnits="userSpaceOnUse"><stop offset=".464" class="v0ox3l-0u"/><stop offset="1" class="x78tqlban"/></radialGradient><radialGradient id="iWk20LR" cx="0" cy="0" r="1" gradientTransform="matrix(.84335 -.64209 .49204 .64628 28.086 21.608)" gradientUnits="userSpaceOnUse"><stop offset=".132" class="ruv4dbc7o"/><stop offset="1" class="meeoi68df"/></radialGradient><radialGradient id="iFvug5c" cx="0" cy="0" r="1" gradientTransform="rotate(148.849 11.265 12.204)scale(4.17157)" gradientUnits="userSpaceOnUse"><stop offset=".838" class="wc1l7vbis"/><stop offset="1" class="oa317xagd"/></radialGradient><radialGradient id="iF5C5le" cx="0" cy="0" r="1" gradientTransform="matrix(1.26514 1.24827 -2.90348 2.94272 23.842 15.457)" gradientUnits="userSpaceOnUse"><stop class="ky_indbcd"/><stop offset="1" class="s_ufbeclz"/></radialGradient><radialGradient id="i4e3klc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.37479 2.10625 0 26.912 16.814)" gradientUnits="userSpaceOnUse"><stop class="qkb33eb6n"/><stop offset="1" class="q-0s8ibrs"/></radialGradient><radialGradient id="iJmncce" cx="0" cy="0" r="1" gradientTransform="matrix(0 .4408 -2.66861 0 27.506 17.205)" gradientUnits="userSpaceOnUse"><stop class="zxhnj4bqq"/><stop offset="1" class="hf-5q38gm"/></radialGradient><radialGradient id="iqQ3BRc" cx="0" cy="0" r="1" gradientTransform="matrix(-.4998 .66245 -.66245 -.4998 25.981 21.077)" gradientUnits="userSpaceOnUse"><stop class="dg3rcdvoo"/><stop offset="1" class="r0tyikbvd"/></radialGradient><radialGradient id="iaTK3Db" cx="0" cy="0" r="1" gradientTransform="matrix(-1.12692 -1.56257 1.8364 -1.3244 16.412 20.197)" gradientUnits="userSpaceOnUse"><stop class="c41784n4d"/><stop offset="1" class="r5_3rkp5l"/></radialGradient><radialGradient id="iOUZFae" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.5843 -1.90116 0 15.15 18.687)" gradientUnits="userSpaceOnUse"><stop class="nj4ic69jx"/><stop offset="1" class="nf6el5bab"/></radialGradient><radialGradient id="iC35bTd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .8787 -1.6371 0 26.073 23.615)" gradientUnits="userSpaceOnUse"><stop offset=".106" class="njj87ojhb"/><stop offset="1" class="d1vocvbes"/></radialGradient><radialGradient id="iK4ZIpc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .94192 -1.75486 0 26.073 25.034)" gradientUnits="userSpaceOnUse"><stop offset=".109" class="njj87ojhb"/><stop offset="1" class="d1vocvbes"/></radialGradient><radialGradient id="iEFUEtd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .78779 -1.4677 0 26.073 26.404)" gradientUnits="userSpaceOnUse"><stop offset=".109" class="njj87ojhb"/><stop offset="1" class="d1vocvbes"/></radialGradient><radialGradient id="igWxpNc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .87616 -2.08784 0 26.073 27.885)" gradientUnits="userSpaceOnUse"><stop offset=".186" class="njj87ojhb"/><stop offset="1" class="d1vocvbes"/></radialGradient><radialGradient id="iidUzge" cx="0" cy="0" r="1" gradientTransform="matrix(1.75472 0 0 3.07077 8.724 12.22)" gradientUnits="userSpaceOnUse"><stop offset=".351" class="n91c-gs8j"/><stop offset="1" class="qo7u-3bcf"/></radialGradient><radialGradient id="iti6aed" cx="0" cy="0" r="1" gradientTransform="rotate(-124.98 8.814 4.239)scale(1.6566)" gradientUnits="userSpaceOnUse"><stop offset=".34" class="ev4-2pfvs"/><stop offset="1" class="w_j-6pbpp"/></radialGradient><radialGradient id="iHVCg7l" cx="0" cy="0" r="1" gradientTransform="matrix(.82663 -.60192 .68701 .9435 20.278 11.956)" gradientUnits="userSpaceOnUse"><stop offset=".543" class="cu-ecjbbc"/><stop offset="1" class="a1ftncccj"/></radialGradient><radialGradient id="i9DFeVZ" cx="0" cy="0" r="1" gradientTransform="matrix(.8212 -1.5104 .88405 .48065 19.864 13.042)" gradientUnits="userSpaceOnUse"><stop offset=".755" class="d66ufbbtl"/><stop offset=".916" class="f7hwkw-sq"/></radialGradient><radialGradient id="ir2pXhO" cx="0" cy="0" r="1" gradientTransform="rotate(44.707 -4.906 30.313)scale(.3648 .47028)" gradientUnits="userSpaceOnUse"><stop class="suj-pjbhk"/><stop offset="1" class="dg9o8ubcl"/></radialGradient><radialGradient id="i1Pc7bd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.30697 1.60858 0 17.487 10.95)" gradientUnits="userSpaceOnUse"><stop class="e6v6vrbif"/><stop offset="1" class="qmnjff_ag"/></radialGradient><radialGradient id="iOKkese" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.37399 1.70868 0 12.929 11.084)" gradientUnits="userSpaceOnUse"><stop class="c02-eqbxv"/><stop offset="1" class="mmmkqcbgq"/></radialGradient><radialGradient id="ibT6CPe" cx="0" cy="0" r="1" gradientTransform="matrix(0 7.93632 -22.2788 0 15.013 10.688)" gradientUnits="userSpaceOnUse"><stop offset=".656" class="wf8xbnbxu"/><stop offset="1" class="krgam5jwq"/></radialGradient><radialGradient id="ildNVHc" cx="0" cy="0" r="1" gradientTransform="rotate(-74.899 15.04 -8.663)scale(3.06211 1.13553)" gradientUnits="userSpaceOnUse"><stop class="ki2rd4v4k"/><stop offset="1" class="tp9jx5j2y"/></radialGradient><radialGradient id="iwm24Ub" cx="0" cy="0" r="1" gradientTransform="rotate(5.258 -60.285 197.483)scale(3.84067 2.0651)" gradientUnits="userSpaceOnUse"><stop offset=".392" class="je_aabb8l"/><stop offset="1" class="ivhsfvmdg"/></radialGradient><radialGradient id="iOrmwdd" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.67903 -2.60035 0 15.14 3.62)" gradientUnits="userSpaceOnUse"><stop class="n7o-m0b5s"/><stop offset="1" class="xp-9f0bqu"/></radialGradient><radialGradient id="iChgPod" cx="0" cy="0" r="1" gradientTransform="matrix(3.07368 -2.25248 3.5289 4.81545 8.693 10.438)" gradientUnits="userSpaceOnUse"><stop class="ux7-g74jy"/><stop offset="1" class="dd8hfetks"/></radialGradient><radialGradient id="ibPd1kY" cx="0" cy="0" r="1" gradientTransform="matrix(0 .19688 -.63254 0 15.468 13.827)" gradientUnits="userSpaceOnUse"><stop class="mifq-tdon"/><stop offset="1" class="n-ko-_w7d"/></radialGradient><radialGradient id="ijeu7Ge" cx="0" cy="0" r="1" gradientTransform="matrix(-2.9117 6.52447 -8.23836 -3.67657 14.666 7)" gradientUnits="userSpaceOnUse"><stop class="jy25td8rp"/><stop offset="1" class="xftsofb3t"/></radialGradient><radialGradient id="iqzdySw" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.29688 1.23651 0 13.133 11.468)" gradientUnits="userSpaceOnUse"><stop offset=".545" class="hkf1_jbsj"/><stop offset="1" class="wrhkd7bsy"/></radialGradient><radialGradient id="ihAqlIc" cx="0" cy="0" r="1" gradientTransform="rotate(-92.851 13.11 .087)scale(6.59612 25.5871)" gradientUnits="userSpaceOnUse"><stop offset=".942" class="rsiltfr7x"/><stop offset=".985" class="d1yjj5b4a"/></radialGradient><radialGradient id="ikBDN6d" cx="0" cy="0" r="1" gradientTransform="matrix(.10418 -.60322 1.78457 .30822 17.584 10.137)" gradientUnits="userSpaceOnUse"><stop class="fr4wpbo2m"/><stop offset="1" class="xo-sv8bhm"/></radialGradient><radialGradient id="il0zKoe" cx="0" cy="0" r="1" gradientTransform="rotate(-80.2 12.237 -2.316)scale(.61215 1.81109)" gradientUnits="userSpaceOnUse"><stop class="fr4wpbo2m"/><stop offset="1" class="xo-sv8bhm"/></radialGradient><radialGradient id="ioqSB1e" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81106 -1.29009 0 17.32 11.539)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="i3vsOge" cx="0" cy="0" r="1" gradientTransform="matrix(-.23184 -.29876 .41132 -.3192 17.091 11.623)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="i3shHGe" cx="0" cy="0" r="1" gradientTransform="matrix(0 .8111 -1.29015 0 12.957 11.539)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="iK0m8ld" cx="0" cy="0" r="1" gradientTransform="rotate(-90.897 12.123 -.358)scale(.49399 .59379)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><linearGradient id="igor3Gb" x1="16.902" x2="15.504" y1="26.381" y2="26.079" gradientUnits="userSpaceOnUse"><stop class="k6k-6oblx"/><stop offset="1" class="l5x5or5jn"/></linearGradient><linearGradient id="i24w8Cd" x1="7.199" x2="6.027" y1="26.181" y2="26.181" gradientUnits="userSpaceOnUse"><stop class="xfetrrneo"/><stop offset="1" class="n0fg5jb7h"/></linearGradient><linearGradient id="iQbkTHd" x1="23.127" x2="23.77" y1="26.266" y2="26.235" gradientUnits="userSpaceOnUse"><stop offset=".478" class="g2cjljmej"/><stop offset="1" class="h5gp5h3ar"/></linearGradient><linearGradient id="i6bDAZc" x1="22.77" x2="18.395" y1="16.251" y2="28.761" gradientUnits="userSpaceOnUse"><stop class="c08ew-b0i"/><stop offset="1" class="exuz4sbao"/></linearGradient><linearGradient id="iNxtrnd" x1="16.824" x2="17.53" y1="26.752" y2="26.847" gradientUnits="userSpaceOnUse"><stop class="q5z4iwf2u"/><stop offset="1" class="t7ud1ab5b"/></linearGradient><linearGradient id="i91Rooe" x1="20.787" x2="20.787" y1="16.251" y2="17.35" gradientUnits="userSpaceOnUse"><stop offset=".457" class="tffk3lifv"/><stop offset="1" class="e4yz8gz4u"/></linearGradient><linearGradient id="iiMOPSG" x1="7.895" x2="11.895" y1="17.891" y2="29.141" gradientUnits="userSpaceOnUse"><stop class="m3gjwjbhl"/><stop offset="1" class="c9zswtx-n"/></linearGradient><linearGradient id="iByWW2b" x1="8.365" x2="9.063" y1="15.997" y2="19.562" gradientUnits="userSpaceOnUse"><stop class="s434a46or"/><stop offset="1" class="qrv_44bpu"/></linearGradient><linearGradient id="inT6Foe" x1="7.895" x2="8.309" y1="22.829" y2="22.626" gradientUnits="userSpaceOnUse"><stop class="bwk0n7bpz"/><stop offset="1" class="oinrtsbml"/></linearGradient><linearGradient id="ixVT4Wb" x1="13.739" x2="13.328" y1="28.457" y2="28.543" gradientUnits="userSpaceOnUse"><stop class="ifhx39w3y"/><stop offset="1" class="tmbtljdgb"/></linearGradient><linearGradient id="iKDccHc" x1="23.395" x2="21.614" y1="26.298" y2="26.298" gradientUnits="userSpaceOnUse"><stop class="tsgwb3b4a"/><stop offset="1" class="nvk1b4bey"/></linearGradient><linearGradient id="iS84Bnu" x1="8.114" x2="10.395" y1="28.11" y2="26.954" gradientUnits="userSpaceOnUse"><stop class="h1snaz72e"/><stop offset="1" class="kvxpklbcz"/></linearGradient><linearGradient id="ix3fokc" x1="15.111" x2="15.111" y1="17.652" y2="28.756" gradientUnits="userSpaceOnUse"><stop offset=".006" class="kt__1405u"/><stop offset="1" class="h_j9u0wvt"/></linearGradient><linearGradient id="iGjwQCd" x1="17.886" x2="15.925" y1="22.341" y2="22.013" gradientUnits="userSpaceOnUse"><stop offset=".196" class="xco_-7b_j"/><stop offset=".671" class="ru3ag_b2y"/></linearGradient><linearGradient id="iB0qGAe" x1="25.739" x2="25.739" y1="15.948" y2="20.004" gradientUnits="userSpaceOnUse"><stop offset=".313" class="wprwrdbxj"/><stop offset=".562" class="ax-d4eb4u"/></linearGradient><linearGradient id="iLiq6Dd" x1="25.934" x2="25.792" y1="16.884" y2="18.087" gradientUnits="userSpaceOnUse"><stop offset=".12" class="qcwm1i13v"/><stop offset="1" class="s0eee-boz"/></linearGradient><linearGradient id="ig45bRd" x1="23.236" x2="23.363" y1="16.82" y2="17.257" gradientUnits="userSpaceOnUse"><stop class="wtu393bab"/><stop offset="1" class="ce_wr9jxr"/></linearGradient><linearGradient id="iFRjnrb" x1="26.936" x2="24.649" y1="21.391" y2="21.391" gradientUnits="userSpaceOnUse"><stop class="j-x55pbxn"/><stop offset="1" class="zg05wl6cw"/></linearGradient><linearGradient id="i8PtfSb" x1="24.466" x2="24.847" y1="21.233" y2="21.205" gradientUnits="userSpaceOnUse"><stop class="fs7-dablt"/><stop offset="1" class="zg97ljbvw"/></linearGradient><linearGradient id="iRQsDTc" x1="27.084" x2="26.822" y1="21.105" y2="21.081" gradientUnits="userSpaceOnUse"><stop class="qna0z9q7a"/><stop offset="1" class="toldersuv"/></linearGradient><linearGradient id="ic9lpth" x1="27.996" x2="23.127" y1="26.638" y2="26.638" gradientUnits="userSpaceOnUse"><stop offset=".146" class="fd7w0ysog"/><stop offset=".861" class="wtwh9i50b"/></linearGradient><linearGradient id="i3marjd" x1="23.742" x2="25.663" y1="24.435" y2="24.435" gradientUnits="userSpaceOnUse"><stop class="l731pf7zh"/><stop offset="1" class="ucdgelbmi"/></linearGradient><linearGradient id="i0hW5Fb" x1="23.742" x2="25.663" y1="25.877" y2="25.877" gradientUnits="userSpaceOnUse"><stop class="l731pf7zh"/><stop offset="1" class="ucdgelbmi"/></linearGradient><linearGradient id="iy2BjcV" x1="23.742" x2="25.663" y1="27.307" y2="27.307" gradientUnits="userSpaceOnUse"><stop class="l731pf7zh"/><stop offset="1" class="ucdgelbmi"/></linearGradient><linearGradient id="iBAhQSZ" x1="10.393" x2="9.753" y1="12.5" y2="12.5" gradientUnits="userSpaceOnUse"><stop class="vo9agqbnp"/><stop offset="1" class="fwwugibmc"/></linearGradient><linearGradient id="itlyKOP" x1="20.992" x2="20.174" y1="11.129" y2="13.665" gradientUnits="userSpaceOnUse"><stop class="ix2ytv1nc"/><stop offset="1" class="sla6kib8v"/></linearGradient><linearGradient id="iA3KpPt" x1="19.176" x2="11.54" y1="12.61" y2="13.748" gradientUnits="userSpaceOnUse"><stop class="f43nfdclv"/><stop offset="1" class="ixdockwro"/></linearGradient><linearGradient id="iZ1mDpe" x1="9.745" x2="11.627" y1="15.306" y2="15.239" gradientUnits="userSpaceOnUse"><stop class="xaj4s_mqh"/><stop offset="1" class="nzdq87b8k"/></linearGradient><linearGradient id="iRMAPmR" x1="20.061" x2="18.949" y1="14.465" y2="14.368" gradientUnits="userSpaceOnUse"><stop class="mxfqo-b2y"/><stop offset="1" class="z8_150olp"/></linearGradient><linearGradient id="icfvQLe" x1="15.169" x2="15.169" y1="16.576" y2="18.624" gradientUnits="userSpaceOnUse"><stop offset=".847" class="ei129vbgu"/><stop offset="1" class="yivi8fb5p"/></linearGradient><linearGradient id="ibCZzse" x1="14.609" x2="22.753" y1="9.626" y2="6.71" gradientUnits="userSpaceOnUse"><stop class="m26ledckw"/><stop offset="1" class="yudgedput"/></linearGradient><linearGradient id="iGCEgBb" x1="14.277" x2="15.215" y1="13.27" y2="13.27" gradientUnits="userSpaceOnUse"><stop class="brzpz-p3w"/><stop offset="1" class="qxphtrj0e"/></linearGradient><linearGradient id="iTYUIkW" x1="16.079" x2="15.054" y1="13.592" y2="13.577" gradientUnits="userSpaceOnUse"><stop class="hcuo1obkg"/><stop offset="1" class="soj01hbui"/></linearGradient><linearGradient id="iE2tb4c" x1="15.335" x2="15.335" y1="14.334" y2="13.761" gradientUnits="userSpaceOnUse"><stop class="xk94moblk"/><stop offset="1" class="v1vf9kb3x"/></linearGradient><linearGradient id="isjmPvc" x1="15.267" x2="15.267" y1="14.376" y2="14.209" gradientUnits="userSpaceOnUse"><stop class="kpt7nxbeg"/><stop offset="1" class="c70lx944e"/></linearGradient><linearGradient id="iNgdnoc" x1="14.104" x2="14.539" y1="15.949" y2="15.262" gradientUnits="userSpaceOnUse"><stop class="ssfga94sp"/><stop offset=".663" class="t-wcrfbaw"/></linearGradient><linearGradient id="iVGbSuy" x1="18.097" x2="17.784" y1="11.593" y2="11.786" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iFE8PEc" x1="13.7" x2="13.387" y1="11.593" y2="11.786" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="imurRpd" x1="18.113" x2="17.693" y1="9.453" y2="8.595" gradientUnits="userSpaceOnUse"><stop class="bac636b7w"/><stop offset="1" class="eqzjb1bwj"/></linearGradient><linearGradient id="ixnWhre" x1="12.809" x2="11.62" y1="9.326" y2="8.827" gradientUnits="userSpaceOnUse"><stop class="bac636b7w"/><stop offset="1" class="eqzjb1bwj"/></linearGradient><linearGradient id="iJRrSkc" x1="10.479" x2="10.479" y1="7.311" y2="9.468" gradientUnits="userSpaceOnUse"><stop offset=".228" class="zw2ljvb-t"/><stop offset="1" class="ohs50t_5m"/></linearGradient><filter id="iPyDnqc" width="5.513" height="4.74" x="12.848" y="24.011" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.976471 0 0 0 0 0.780392 0 0 0 0 0.866667 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2320"/></filter><filter id="iKzeJpc" width="6.102" height="1.228" x="22.791" y="16.721" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.05"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.647059 0 0 0 0 0.47451 0 0 0 0 0.54902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2320"/></filter><filter id="i88bEyc" width="1.075" height="1.075" x="25.198" y="20.855" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy="-.05"/><feGaussianBlur stdDeviation=".025"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.694118 0 0 0 0 0.560784 0 0 0 0 0.764706 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2320"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.05" dy=".05"/><feGaussianBlur stdDeviation=".025"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.917647 0 0 0 0 0.87451 0 0 0 0 0.976471 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2320" result="effect2_innerShadow_4002_2320"/></filter><filter id="ij8sGac" width="5.967" height="5.967" x="12.166" y="14.918" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2320" stdDeviation=".125"/></filter><filter id="iGvLMDc" width="5.813" height="5.813" x="12.243" y="15.105" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2320" stdDeviation=".25"/></filter><filter id="iI3Fj7c" width="5.369" height="6.076" x="23.127" y="22.686" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.15"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.454902 0 0 0 0 0.313726 0 0 0 0 0.266667 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2320"/></filter><filter id="iZXawkQ" width="2.319" height=".3" x="23.592" y="24.207" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2320" stdDeviation=".05"/></filter><filter id="i9sRVob" width="2.319" height=".3" x="23.592" y="25.648" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2320" stdDeviation=".05"/></filter><filter id="igTJbQe" width="2.319" height=".3" x="23.592" y="27.079" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2320" stdDeviation=".05"/></filter><filter id="iY2tUui" width="3.539" height="3.339" x="8.724" y="10.552" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.619608 0 0 0 0 0.470588 0 0 0 0 0.407843 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2320"/></filter><filter id="i3aAjOe" width="2.99" height="2.99" x="8.898" y="10.726" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2320" stdDeviation=".25"/></filter><filter id="iKGUg8u" width="3.589" height="3.589" x="18.237" y="10.302" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.584314 0 0 0 0 0.368627 0 0 0 0 0.470588 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2320"/></filter><filter id="isHJjqd" width="2.99" height="2.99" x="18.411" y="10.726" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2320" stdDeviation=".25"/></filter><filter id="iPIwZSb" width="10.373" height="12.177" x="9.983" y="6.597" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".15"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.305882 0 0 0 0 0.2 0 0 0 0 0.172549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2320"/></filter><filter id="i6XWsXd" width="8.246" height="7.066" x="13.311" y="4.597" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2320" stdDeviation="1"/></filter><filter id="ib0ZOrb" width="12.601" height="8.543" x="8.841" y="3.12" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.207843 0 0 0 0 0.109804 0 0 0 0 0.109804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2320"/></filter><filter id="idZn73b" width="3.26" height="4.181" x="13.272" y="11.066" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2320" stdDeviation=".375"/></filter><filter id="ijfEicb" width="2.377" height="3.181" x="13.953" y="11.403" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2320" stdDeviation=".125"/></filter><filter id="inaV4wF" width="2.979" height="1.873" x="16.323" y="8.572" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.254902 0 0 0 0 0.156863 0 0 0 0 0.152941 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2320"/></filter><filter id="iM3VRZb" width="2.98" height="1.873" x="11.175" y="8.572" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.254902 0 0 0 0 0.156863 0 0 0 0 0.152941 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2320"/></filter><filter id="iqQKlJe" width=".787" height=".696" x="16.585" y="11.099" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2320" stdDeviation=".05"/></filter><filter id="ijCXTud" width=".891" height=".913" x="17.425" y="11.174" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2320" stdDeviation=".1"/></filter><filter id="iLSsW1b" width=".986" height="1.04" x="12.984" y="11.111" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2320" stdDeviation=".1"/></filter><filter id="iqJOb5p" width=".913" height=".704" x="12.229" y="11.091" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2320" stdDeviation=".05"/></filter><filter id="iljuWHb" width="3.099" height="1.681" x="16.176" y="8.698" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2320" stdDeviation=".25"/></filter><filter id="inNTDZN" width="3.177" height="1.738" x="10.957" y="8.762" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2320" stdDeviation=".25"/></filter><filter id="iZprAYc" width="1.008" height="2.269" x="9.975" y="7.035" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2320" stdDeviation=".125"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:man-singer-medium" /></template>
<style>
.a1ftncccj {
  stop-color: var(--svg-color--8f6459, #8F6459);
  stop-opacity: 0;
}

.a7lil8crc {
  d: path("m19.104 6.597l-3.077 1.026a1.047 1.047 0 0 0 .47 2.031l3.06-.41z");
}

.ax-d4eb4u {
  stop-color: var(--svg-color--562d79, #562D79);
}

.ax7pcvbpy {
  cx: 10.393px;
  cy: 12.221px;
  r: 0.995px;
}

.ayb1dwuvg {
  stop-color: var(--svg-color--704239, #704239);
  stop-opacity: 0;
}

.b2oqkkb1l {
  cx: 19.906px;
  cy: 12.221px;
  r: 0.995px;
  fill: var(--svg-color--a57c70, #A57C70);
}

.b9f983ucc {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M16.801 9.357c.43-.076 1.269-.054 1.85.398");
}

.bac636b7w {
  stop-color: var(--svg-color--5b4545, #5B4545);
}

.brzpz-p3w {
  stop-color: var(--svg-color--8b6455, #8B6455);
}

.bsvhxursv {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M23.742 25.799h2.02");
}

.bwk0n7bpz {
  stop-color: var(--svg-color--3e8ed5, #3E8ED5);
}

.bx_706lpj {
  d: path("m19.96 5.744l.428.213c.751.373 1.18 1.227 1.02 2.133l-.59 3.04c-.053.314-.26.525-.572.533h-.018s.053-.906.107-1.44c.043-.433-.032-.565-.43-.96c-.214-.213-.375-.533-.375-.853v-.853c0-.267-.214-.48-.429-.533c-.643-.16-1.984-.427-3.915-.427s-3.272.267-3.915.427a.52.52 0 0 0-.43.533v.853c0 .32-.107.64-.375.853l-.161.16c-.214.16-.322.48-.322.747c.054.587.107 1.44.107 1.44l-.049-.002a.63.63 0 0 1-.594-.531l-.59-3.04c-.107-.853.322-1.707 1.073-2.08l.429-.213c.268-.16.536-.374.804-.587l.966-1.013c.59-.534 1.448-.693 2.199-.32a2.94 2.94 0 0 0 1.662 0c.805-.267 1.717-.054 2.36.533l.805.8c.214.267.482.427.804.587");
}

.c02-eqbxv {
  stop-color: var(--svg-color--8f5d65, #8F5D65);
}

.c08ew-b0i {
  stop-color: var(--svg-color--2ca9dd, #2CA9DD);
}

.c41784n4d {
  stop-color: var(--svg-color--ae8074, #AE8074);
}

.c70lx944e {
  stop-color: var(--svg-color--8e5263, #8E5263);
  stop-opacity: 0;
}

.c9zswtx-n {
  stop-color: var(--svg-color--3073d6, #3073D6);
}

.cb83gypuf {
  d: path("M11.368 9.502V9.5h.001l.002-.002l.005-.004l.011-.01l.037-.027q.044-.033.118-.08c.1-.062.241-.14.42-.21a2.83 2.83 0 0 1 1.493-.159a.534.534 0 0 1-.167 1.054a1.77 1.77 0 0 0-.934.097a1.5 1.5 0 0 0-.308.165a.534.534 0 0 1-.678-.823");
}

.ce_wr9jxr {
  stop-color: var(--svg-color--b19a83, #B19A83);
  stop-opacity: 0;
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cn088_52m {
  stop-color: var(--svg-color--b17f71, #B17F71);
}

.cpu5ihbur {
  d: path("M12.955 11.062a.892.892 0 0 0-.86 1.127h1.724a1 1 0 0 0 .032-.235a.9.9 0 0 0-.896-.892");
}

.cu-ecjbbc {
  stop-color: var(--svg-color--8f6459, #8F6459);
}

.d_l0xgbwf {
  d: path("M15.118 17.651c-1.16 0-2.3.17-3.38.49l1.1 5.87c.72.28 1.5.44 2.32.44c.77 0 1.51-.14 2.19-.38l1.11-5.92c-1.05-.33-2.18-.5-3.34-.5");
}

.d1vocvbes {
  stop-color: var(--svg-color--c99e80, #C99E80);
  stop-opacity: 0;
}

.d1yjj5b4a {
  stop-color: var(--svg-color--a90f5e, #A90F5E);
}

.d66ufbbtl {
  stop-color: var(--svg-color--8a5d55, #8A5D55);
  stop-opacity: 0;
}

.d6d59o0ou {
  stop-color: var(--svg-color--4d396f, #4D396F);
}

.dd8hfetks {
  stop-color: var(--svg-color--4e3c3a, #4E3C3A);
  stop-opacity: 0;
}

.dg3rcdvoo {
  stop-color: var(--svg-color--d2bfe7, #D2BFE7);
}

.dg9o8ubcl {
  stop-color: var(--svg-color--895f52, #895F52);
  stop-opacity: 0;
}

.do752sbjh {
  d: path("M15.099 6.597c-.901.004-1.67.066-2.298.146l-2.163 6.367h1.81l-.508 2.687l3.687-5.132h-1.883z");
}

.dz22vydpm {
  d: path("M5.405 16.773h6.086l2.248 11.988h-2.79l-5.88-11.528c-.086-.125-.07-.46.336-.46");
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.e4yz8gz4u {
  stop-color: var(--svg-color--2ea1dc, #2EA1DC);
  stop-opacity: 0;
}

.e6v6vrbif {
  stop-color: var(--svg-color--ab7773, #AB7773);
}

.ei129vbgu {
  stop-color: var(--svg-color--9c598c, #9C598C);
  stop-opacity: 0.046;
}

.elah571hr {
  fill: var(--svg-color--b7877d, #B7877D);
  d: path("m14.759 11.936l-.532 1.7a.54.54 0 0 0 .52.698h.787a.54.54 0 0 0 .52-.699l-.53-1.7c-.115-.376-.646-.376-.765 0");
}

.eqzjb1bwj {
  stop-color: var(--svg-color--5b4545, #5B4545);
  stop-opacity: 0;
}

.esw1hmivn {
  stop-color: var(--svg-color--2796d4, #2796D4);
  stop-opacity: 0;
}

.ev4-2pfvs {
  stop-color: var(--svg-color--834e63, #834E63);
}

.exuz4sbao {
  stop-color: var(--svg-color--3069c9, #3069C9);
}

.f43nfdclv {
  stop-color: var(--svg-color--c69980, #C69980);
}

.f7hwkw-sq {
  stop-color: var(--svg-color--8a5d55, #8A5D55);
}

.fd7w0ysog {
  stop-color: var(--svg-color--c89a81, #C89A81);
}

.fr4wpbo2m {
  stop-color: var(--svg-color--422235, #422235);
}

.fs7-dablt {
  stop-color: var(--svg-color--a0768f, #A0768F);
}

.ft5dv1b6b {
  fill: none;
}

.fwwugibmc {
  stop-color: var(--svg-color--6e464d, #6E464D);
}

.g2cjljmej {
  stop-color: var(--svg-color--604e83, #604E83);
}

.g2n8qcc6u {
  d: path("M18.116 11.837a.84.84 0 0 0-.231-.463l-.26.285l.117.228z");
}

.gj3zww6vu {
  fill: var(--svg-color--e7c1f2, #E7C1F2);
  d: path("M12.848 24.011v4.74h5.313l-.803-4.69c-.68.25-1.42.38-2.19.38c-.81.01-1.6-.15-2.32-.43");
}

.gw5hcg17q {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M23.742 24.357h2.02");
}

.h_j9u0wvt {
  stop-color: var(--svg-color--e6e6e6, #E6E6E6);
}

.h1snaz72e {
  stop-color: var(--svg-color--665395, #665395);
}

.h5gp5h3ar {
  stop-color: var(--svg-color--604e83, #604E83);
  stop-opacity: 0;
}

.hcuo1obkg {
  stop-color: var(--svg-color--cda186, #CDA186);
}

.hf-5q38gm {
  stop-color: var(--svg-color--c1bcc8, #C1BCC8);
  stop-opacity: 0;
}

.hkf1_jbsj {
  stop-color: var(--svg-color--be2252, #BE2252);
}

.hre2qfboa {
  cx: 10.393px;
  cy: 12.221px;
  r: 1.669px;
}

.i17r3cb_z {
  d: path("M25.726 26.591a.784.784 0 0 1-.782-.71l-.67-6.429l2.975.01l-.731 6.429a.8.8 0 0 1-.792.7");
}

.i5-87ib3k {
  fill: var(--svg-color--87565c, #87565C);
  d: path("m14.866 12.099l-.82 1.7c-.102.349.142.698.487.698h.738c.345 0 .59-.355.487-.699l-.498-1.7c-.107-.376-.283-.376-.394 0");
}

.ifhx39w3y {
  stop-color: var(--svg-color--3469bc, #3469BC);
}

.ih6ylj_bo {
  cx: 12.686px;
  cy: 11.443px;
  rx: 0.389px;
  ry: 0.197px;
}

.irp9u6dgr {
  fill: var(--svg-color--4c3230, #4C3230);
  d: path("M11.368 9.502V9.5h.001l.002-.002l.005-.004l.011-.01l.037-.027q.044-.033.118-.08c.1-.062.241-.14.42-.21a2.83 2.83 0 0 1 1.493-.159a.534.534 0 0 1-.167 1.054a1.77 1.77 0 0 0-.934.097a1.5 1.5 0 0 0-.308.165a.534.534 0 0 1-.678-.823");
}

.ivhsfvmdg {
  stop-color: var(--svg-color--644949, #644949);
  stop-opacity: 0;
}

.ix2ytv1nc {
  stop-color: var(--svg-color--cca68c, #CCA68C);
}

.ixdockwro {
  stop-color: var(--svg-color--916762, #916762);
}

.j-x55pbxn {
  stop-color: var(--svg-color--d9cbea, #D9CBEA);
}

.je_aabb8l {
  stop-color: var(--svg-color--644949, #644949);
}

.jq2gabc_s {
  fill: var(--svg-color--4f3332, #4F3332);
  d: path("m19.96 5.744l.428.213c.751.373 1.18 1.227 1.02 2.133l-.59 3.04c-.053.314-.26.525-.572.533h-.018s.053-.906.107-1.44c.043-.433-.032-.565-.43-.96c-.214-.213-.375-.533-.375-.853v-.853c0-.267-.214-.48-.429-.533c-.643-.16-1.984-.427-3.915-.427s-3.272.267-3.915.427a.52.52 0 0 0-.43.533v.853c0 .32-.107.64-.375.853l-.161.16c-.214.16-.322.48-.322.747c.054.587.107 1.44.107 1.44l-.049-.002a.63.63 0 0 1-.594-.531l-.59-3.04c-.107-.853.322-1.707 1.073-2.08l.429-.213c.268-.16.536-.374.804-.587l.966-1.013c.59-.534 1.448-.693 2.199-.32a2.94 2.94 0 0 0 1.662 0c.805-.267 1.717-.054 2.36.533l.805.8c.214.267.482.427.804.587");
}

.jqw16nonk {
  d: path("M25.766 19.95a2.498 2.498 0 1 0 0-4.996a2.498 2.498 0 0 0 0 4.996");
}

.jy25td8rp {
  stop-color: var(--svg-color--e82d86, #E82D86);
}

.k11z14bzp {
  d: path("M7.078 28.751v-7.93a11.75 11.75 0 0 0-3.18 5.04l-.03.09c-.29.91-.51 1.85-.66 2.8z");
}

.k6k-6oblx {
  stop-color: var(--svg-color--c296bf, #C296BF);
}

.k6qg2pirw {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M11.582 9.875c.327-.29 1.042-.594 1.927-.452");
}

.k8ge5dlro {
  d: path("M18.86 9.501h-.001l-.002-.002l-.004-.004l-.012-.01a1.4 1.4 0 0 0-.155-.107c-.1-.062-.241-.14-.42-.21a2.83 2.83 0 0 0-1.492-.159a.534.534 0 1 0 .166 1.054c.398-.062.716.01.934.097a1.5 1.5 0 0 1 .308.165a.534.534 0 0 0 .678-.824");
}

.k910dfb4a {
  stop-color: var(--svg-color--2c649b, #2C649B);
}

.ki2rd4v4k {
  stop-color: var(--svg-color--554042, #554042);
}

.kimybvkmf {
  d: path("m14.759 11.936l-.532 1.7a.54.54 0 0 0 .52.698h.787a.54.54 0 0 0 .52-.699l-.53-1.7c-.115-.376-.646-.376-.765 0");
}

.knolhud8e {
  d: path("m28.214 16.792l-4.844-.02a.57.57 0 0 0-.579.578c0 .325.254.58.579.58l4.844.02a.57.57 0 0 0 .579-.58a.585.585 0 0 0-.58-.578");
}

.kpt7nxbeg {
  stop-color: var(--svg-color--8e5263, #8E5263);
}

.krgam5jwq {
  stop-color: var(--svg-color--96587d, #96587D);
}

.kt__1405u {
  stop-color: var(--svg-color--ccc, #CCC);
}

.kvxpklbcz {
  stop-color: var(--svg-color--5d4c7d, #5D4C7D);
}

.ky_indbcd {
  stop-color: var(--svg-color--7b5e40, #7B5E40);
}

.l5x5or5jn {
  stop-color: var(--svg-color--e7c1f5, #E7C1F5);
  stop-opacity: 0;
}

.l731pf7zh {
  stop-color: var(--svg-color--835646, #835646);
}

.l7c47o-wr {
  stop-color: var(--svg-color--664944, #664944);
}

.l9hbmrwjw {
  fill: var(--svg-color--4c3230, #4C3230);
  d: path("M18.86 9.501h-.001l-.002-.002l-.004-.004l-.012-.01a1.4 1.4 0 0 0-.155-.107c-.1-.062-.241-.14-.42-.21a2.83 2.83 0 0 0-1.492-.159a.534.534 0 1 0 .166 1.054c.398-.062.716.01.934.097a1.5 1.5 0 0 1 .308.165a.534.534 0 0 0 .678-.824");
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.li28y9bsf {
  stop-color: var(--svg-color--675890, #675890);
}

.lm-qrljex {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M17.256 11.25c.064.086-.07.19-.22.302c-.152.113-.264.193-.327.108c-.064-.085.007-.246.158-.359s.325-.135.389-.05");
}

.m-wch-t_n {
  d: path("M7.078 28.751h3.87l-3.87-7.596z");
}

.m26ledckw {
  stop-color: var(--svg-color--c89f8b, #C89F8B);
}

.m3gjwjbhl {
  stop-color: var(--svg-color--258ec6, #258EC6);
}

.m4vk7-mbl {
  stop-color: var(--svg-color--40a8ea, #40A8EA);
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.meeoi68df {
  stop-color: var(--svg-color--cba68e, #CBA68E);
  stop-opacity: 0;
}

.mifq-tdon {
  stop-color: var(--svg-color--c39787, #C39787);
}

.mmmkqcbgq {
  stop-color: var(--svg-color--8f5d65, #8F5D65);
  stop-opacity: 0;
}

.mxfqo-b2y {
  stop-color: var(--svg-color--c1987f, #C1987F);
}

.n-ko-_w7d {
  stop-color: var(--svg-color--c39787, #C39787);
  stop-opacity: 0;
}

.n0fg5jb7h {
  stop-color: var(--svg-color--504665, #504665);
  stop-opacity: 0;
}

.n4m-kxv1v {
  cx: 19.906px;
  cy: 12.221px;
  r: 1.669px;
}

.n7o-m0b5s {
  stop-color: var(--svg-color--624c49, #624C49);
}

.n91c-gs8j {
  stop-color: var(--svg-color--865d5f, #865D5F);
}

.nf6el5bab {
  stop-color: var(--svg-color--a06665, #A06665);
}

.nj4ic69jx {
  stop-color: var(--svg-color--975567, #975567);
}

.njj87ojhb {
  stop-color: var(--svg-color--c2998b, #C2998B);
}

.nvk1b4bey {
  stop-color: var(--svg-color--5f4b8a, #5F4B8A);
}

.nx7otbuhy {
  d: path("M27.017 28.751c-.14-.96-.36-1.91-.65-2.84a11.77 11.77 0 0 0-3.24-5.13v7.97z");
}

.nyj1sbbug {
  cx: 19.906px;
  cy: 12.221px;
  r: 0.995px;
}

.nym90gb4n {
  stop-color: var(--svg-color--7a4845, #7A4845);
}

.nzdq87b8k {
  stop-color: var(--svg-color--9b7569, #9B7569);
  stop-opacity: 0;
}

.o1jwunhtj {
  stop-color: var(--svg-color--58497e, #58497E);
}

.o4j1rvu5g {
  stop-color: var(--svg-color--3778d0, #3778D0);
}

.oa317xagd {
  stop-color: var(--svg-color--673d45, #673D45);
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.oe2xm9ikp {
  stop-color: var(--svg-color--746b8d, #746B8D);
}

.ohs50t_5m {
  stop-color: var(--svg-color--4a3236, #4A3236);
  stop-opacity: 0;
}

.oinrtsbml {
  stop-color: var(--svg-color--2a85ce, #2A85CE);
  stop-opacity: 0;
}

.opvnr7b5e {
  d: path("M17.256 11.25c.064.086-.07.19-.22.302c-.152.113-.264.193-.327.108c-.064-.085.007-.246.158-.359s.325-.135.389-.05");
}

.p3ajftwoy {
  fill: var(--svg-color--000, #000);
  d: path("M16.81 11.954c0-.284.228-.51.512-.51a.51.51 0 0 1 .454.745h-.905a.46.46 0 0 1-.06-.235");
}

.pizp6ebil {
  d: path("M13.77 11.85c0-.289-.234-.481-.298-.54l-.288.28l.177.36z");
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.plgpmnbcq {
  cx: 15.15px;
  cy: 18.011px;
  r: 2.406px;
}

.pujp6dbuf {
  fill: var(--svg-color--000, #000);
  d: path("M13.466 11.954a.51.51 0 0 0-.511-.51a.51.51 0 0 0-.454.746h.904a.5.5 0 0 0 .06-.236");
}

.q-0s8ibrs {
  stop-color: var(--svg-color--7d718c, #7D718C);
  stop-opacity: 0;
}

.q0gcp3bpu {
  d: path("M15.118 16.564c-1.16 0-2.487.209-3.567.58l1.29 6.873c.72.325 1.497.434 2.317.434c.77 0 1.51-.073 2.19-.352l1.313-6.955c-1.05-.383-2.384-.58-3.544-.58");
}

.q5z4iwf2u {
  stop-color: var(--svg-color--3466b9, #3466B9);
}

.qcwm1i13v {
  stop-color: var(--svg-color--bfbac7, #BFBAC7);
}

.qh_sysofq {
  cx: 15.149px;
  cy: 17.902px;
  r: 2.734px;
}

.qkb33eb6n {
  stop-color: var(--svg-color--7d718c, #7D718C);
}

.qmnjff_ag {
  stop-color: var(--svg-color--ab7773, #AB7773);
  stop-opacity: 0;
}

.qna0z9q7a {
  stop-color: var(--svg-color--cbc6d6, #CBC6D6);
}

.qnami1-cw {
  d: path("M27.277 21.076c.59 0 1.07.48 1.07 1.07v2.45h-2.14v-2.45c0-.59.48-1.07 1.07-1.07");
}

.qo7u-3bcf {
  stop-color: var(--svg-color--76594a, #76594A);
}

.qol164g5k {
  d: path("m10.041 11.608l.05.002s-.054-.853-.108-1.44c0-.267.107-.587.322-.747l.16-.16c.269-.213.376-.533.376-.853v-.853a.52.52 0 0 1 .43-.533c.643-.16 1.984-.427 3.915-.427c1.93 0 3.271.267 3.915.427c.215.053.43.266.43.533v.853c0 .32.16.64.375.853c.502.352.47.546.429.96c-.054.534-.108 1.44-.108 1.44h.018l-.265 3.958c-.16 1.77-1.552 3.003-3.21 3.003h-3.21c-1.713 0-3.05-1.233-3.21-3.003z");
}

.qqbkbjb6w {
  fill: var(--svg-color--88024e, #88024E);
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M13.779 14.978a.2.2 0 0 0-.242.041a.19.19 0 0 0-.02.24c.343.52.942.868 1.624.868s1.28-.347 1.624-.868a.19.19 0 0 0-.02-.242a.2.2 0 0 0-.242-.04a2.94 2.94 0 0 1-1.362.323c-.5 0-.969-.117-1.362-.322Z");
}

.qrv_44bpu {
  stop-color: var(--svg-color--2987cc, #2987CC);
  stop-opacity: 0;
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.qxphtrj0e {
  stop-color: var(--svg-color--8b6455, #8B6455);
  stop-opacity: 0;
}

.qz389ycjy {
  fill: var(--svg-color--fff, #fff);
  d: path("M17.528 10.79c.653 0 1.205.45 1.355 1.059a.274.274 0 0 1-.268.34h-2.23a.23.23 0 0 1-.227-.271c.125-.64.69-1.127 1.37-1.127");
}

.r0tyikbvd {
  stop-color: var(--svg-color--c0a6d9, #C0A6D9);
}

.r5_3rkp5l {
  stop-color: var(--svg-color--ae8074, #AE8074);
  stop-opacity: 0;
}

.rcaxln_tj {
  d: path("M24.313 16.765h-5.58L16.459 28.76h3.149l5.325-11.016a.685.685 0 0 0-.62-.98");
}

.rsiltfr7x {
  stop-color: var(--svg-color--a90f5e, #A90F5E);
  stop-opacity: 0;
}

.ru3ag_b2y {
  stop-color: var(--svg-color--ac7b6e, #AC7B6E);
  stop-opacity: 0;
}

.ruv4dbc7o {
  stop-color: var(--svg-color--cba68e, #CBA68E);
}

.s_ufbeclz {
  stop-color: var(--svg-color--463358, #463358);
  stop-opacity: 0;
}

.s0eee-boz {
  stop-color: var(--svg-color--aa7bd1, #AA7BD1);
}

.s434a46or {
  stop-color: var(--svg-color--3a90be, #3A90BE);
}

.sh___bchx {
  cx: 12.686px;
  cy: 11.443px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.389px;
  ry: 0.197px;
}

.sla6kib8v {
  stop-color: var(--svg-color--ae7f75, #AE7F75);
}

.soj01hbui {
  stop-color: var(--svg-color--cda186, #CDA186);
  stop-opacity: 0;
}

.ssfga94sp {
  stop-color: var(--svg-color--a87d7b, #A87D7B);
}

.suj-pjbhk {
  stop-color: var(--svg-color--895f52, #895F52);
}

.sxc5dabme {
  d: path("M25.736 21.88a.487.487 0 1 0 0-.975a.487.487 0 0 0 0 .974");
}

.t-wcrfbaw {
  stop-color: var(--svg-color--a87d7b, #A87D7B);
  stop-opacity: 0;
}

.t7ud1ab5b {
  stop-color: var(--svg-color--3073cd, #3073CD);
  stop-opacity: 0;
}

.tffk3lifv {
  stop-color: var(--svg-color--3ca6cf, #3CA6CF);
}

.tmbtljdgb {
  stop-color: var(--svg-color--2e7fd1, #2E7FD1);
  stop-opacity: 0;
}

.toldersuv {
  stop-color: var(--svg-color--d3c3e5, #D3C3E5);
  stop-opacity: 0;
}

.tp9jx5j2y {
  stop-color: var(--svg-color--554042, #554042);
  stop-opacity: 0;
}

.tsgwb3b4a {
  stop-color: var(--svg-color--7c739f, #7C739F);
}

.uba0w767q {
  d: path("M12.848 24.011v4.74h5.313l-.803-4.69c-.68.25-1.42.38-2.19.38c-.81.01-1.6-.15-2.32-.43");
}

.ucdgelbmi {
  stop-color: var(--svg-color--835646, #835646);
  stop-opacity: 0;
}

.ux7-g74jy {
  stop-color: var(--svg-color--4e3c3a, #4E3C3A);
}

.v0ox3l-0u {
  stop-color: var(--svg-color--a27f66, #A27F66);
}

.v1vf9kb3x {
  stop-color: var(--svg-color--9c6073, #9C6073);
  stop-opacity: 0;
}

.vm-pj7b0c {
  stop-color: var(--svg-color--288acb, #288ACB);
  stop-opacity: 0;
}

.vmrtso9qd {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M23.742 27.229h2.02");
}

.vo9agqbnp {
  stop-color: var(--svg-color--694448, #694448);
}

.vwbl2bazu {
  d: path("M17.322 11.062a.892.892 0 0 1 .86 1.127h-1.724a.896.896 0 0 1 .864-1.127");
}

.w_j-6pbpp {
  stop-color: var(--svg-color--834e63, #834E63);
  stop-opacity: 0;
}

.w2g6prbzi {
  d: path("M23.127 23.638c0-.44.366-.802.817-.802h3.054c.745 0 1.349.589 1.349 1.315v3.514c0 .606-.504 1.097-1.124 1.097h-3.28a.81.81 0 0 1-.816-.803c0-.314.187-.589.458-.72a.8.8 0 0 1-.458-.72c0-.314.187-.59.458-.72a.8.8 0 0 1-.458-.72c0-.315.187-.59.458-.72a.8.8 0 0 1-.458-.72");
}

.wc1l7vbis {
  stop-color: var(--svg-color--473558, #473558);
  stop-opacity: 0;
}

.wf8xbnbxu {
  stop-color: var(--svg-color--a66f7c, #A66F7C);
  stop-opacity: 0;
}

.wgn_rvbma {
  d: path("M9.983 10.17c0-.267.107-.587.322-.747l.16-.16c.269-.213.376-.533.376-.853v-.853a.52.52 0 0 1 .43-.533c.643-.16 1.984-.427 3.915-.427c1.93 0 3.271.267 3.915.427c.215.053.43.266.43.533v.853c0 .32.16.64.375.853c.502.352.47.546.429.96c-.054.534-.108 1.44-.108 1.44h.018l-.265 3.958c-.16 1.77-1.552 3.003-3.21 3.003h-3.21c-1.713 0-3.05-1.233-3.21-3.003c-.14-1.816-.201-3.638-.367-5.451");
}

.wprwrdbxj {
  stop-color: var(--svg-color--453357, #453357);
}

.wrhkd7bsy {
  stop-color: var(--svg-color--be2252, #BE2252);
  stop-opacity: 0;
}

.wtu393bab {
  stop-color: var(--svg-color--b19a83, #B19A83);
}

.wtwh9i50b {
  stop-color: var(--svg-color--94616d, #94616D);
}

.x78tqlban {
  stop-color: var(--svg-color--6f4745, #6F4745);
}

.xae-7spdj {
  d: path("M23.128 28.751v-7.267l-3.52 7.267z");
}

.xaj4s_mqh {
  stop-color: var(--svg-color--9b7569, #9B7569);
}

.xco_-7b_j {
  stop-color: var(--svg-color--814c4b, #814C4B);
}

.xfetrrneo {
  stop-color: var(--svg-color--504665, #504665);
}

.xftsofb3t {
  stop-color: var(--svg-color--d42552, #D42552);
}

.xk94moblk {
  stop-color: var(--svg-color--9c6073, #9C6073);
}

.xo-sv8bhm {
  stop-color: var(--svg-color--422235, #422235);
  stop-opacity: 0;
}

.xp-9f0bqu {
  stop-color: var(--svg-color--624c49, #624C49);
  stop-opacity: 0;
}

.yivi8fb5p {
  stop-color: var(--svg-color--9c598c, #9C598C);
}

.yp-hr1bpr {
  stop-color: var(--svg-color--3778d0, #3778D0);
  stop-opacity: 0;
}

.yudgedput {
  stop-color: var(--svg-color--c89f8b, #C89F8B);
  stop-opacity: 0;
}

.z62f_abmw {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M10.608 7.41v.897c-.007.149-.07.481-.258.622");
}

.z6xoafb2r {
  stop-color: var(--svg-color--704239, #704239);
}

.z8_150olp {
  stop-color: var(--svg-color--c1987f, #C1987F);
  stop-opacity: 0;
}

.zg05wl6cw {
  stop-color: var(--svg-color--a78bc1, #A78BC1);
}

.zg97ljbvw {
  stop-color: var(--svg-color--ad93c6, #AD93C6);
  stop-opacity: 0;
}

.zrzq9bc8v {
  fill: var(--svg-color--fff, #fff);
  d: path("M12.748 10.79c-.653 0-1.204.45-1.355 1.059c-.044.174.09.34.268.34h2.23a.23.23 0 0 0 .228-.271a1.4 1.4 0 0 0-1.371-1.128");
}

.zw2ljvb-t {
  stop-color: var(--svg-color--4a3236, #4A3236);
}

.zxhnj4bqq {
  stop-color: var(--svg-color--eae5f7, #EAE5F7);
}

</style>
