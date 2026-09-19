<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#i07y7fb)"><path class="s-46tsbaj"/><path fill="url(#iVOIuJb)" class="qz8nx3iur"/></g><path fill="url(#i07X1ie)" class="qlkjxkk-g"/><path fill="url(#i4Nl9le)" class="qlkjxkk-g"/><path fill="url(#iM2JTLe)" class="j7_9c6bse"/><path fill="url(#iehQjMe)" class="j7_9c6bse"/><path fill="url(#iQ0NSod)" class="snv-ysb0t"/><path fill="url(#iG0CGgc)" class="snv-ysb0t"/><path fill="url(#iwtHj3b)" class="snv-ysb0t"/><path fill="url(#ivubtui)" class="snv-ysb0t"/><path fill="url(#i1rfvSb)" class="j998t3bor"/><path fill="url(#i8MotOe)" class="j998t3bor"/><path fill="url(#i8Qro1b)" class="j998t3bor"/><path fill="url(#i4WTvKe)" class="j998t3bor"/><path fill="url(#izIgdLb)" class="j998t3bor"/><path fill="url(#iGL4l5c)" class="j998t3bor"/><path fill="url(#ilieiYc)" class="yw0gpqv1k"/><path fill="url(#ioOqPFe)" class="r57exrbov"/><path fill="url(#i2RAssb)" class="x597vdeso"/><path fill="url(#i1Rc7sg)" class="qb_yaybod"/><path fill="url(#i7JKwFc)" class="qb_yaybod"/><path fill="url(#ici3KLb)" class="qb_yaybod"/><path fill="url(#ivd4JLe)" class="hx9qd6bzz"/><path fill="url(#iWQiM2P)" class="hx9qd6bzz"/><path fill="url(#iIPlQnd)" class="dh58orbia"/><path fill="url(#iS8BdYX)" class="dh58orbia"/><path fill="url(#ir8Vklb)" class="dh58orbia"/><path fill="url(#iCO6KNc)" class="dh58orbia"/><g filter="url(#i7Wvd3d)"><path fill="url(#iISzOte)" class="cwb5s4b7a"/><path fill="url(#iqCZQQc)" class="cwb5s4b7a"/><path fill="url(#iPhs8tc)" class="cwb5s4b7a"/></g><path fill="url(#iDa2hhb)" class="dm_fr_bzn"/><path fill="url(#iULB3pp)" class="dm_fr_bzn"/><path fill="url(#ilGrvtf)" class="dm_fr_bzn"/><g filter="url(#idZPNlb)"><path fill="url(#iZvPCGd)" class="zwdhe_emk"/></g><g filter="url(#iBATW9D)"><circle fill="url(#ifCvIac)" class="ismqbeb_x"/></g><g filter="url(#izBjjmA)"><circle fill="url(#iAbjTed)" class="kzoru-n_t"/></g><g filter="url(#iIQBWye)"><path fill="url(#i6q3R3d)" class="k0-4bl52g"/><path fill="url(#iWcBtPG)" class="k0-4bl52g"/><path fill="url(#iLo8Fab)" class="k0-4bl52g"/><path fill="url(#iVc1Xeb)" class="k0-4bl52g"/><path fill="url(#i0FCnKc)" class="k0-4bl52g"/></g><g filter="url(#iqZDYwj)"><path stroke="url(#io3Ohjd)" class="l6cdgjewt"/></g><g filter="url(#ijVno3b)"><path stroke="url(#ikgTf9R)" class="jh-gxaboi"/></g><g filter="url(#igD61Cd)"><path stroke="url(#im1gSKd)" class="wk26a8quy"/></g><g filter="url(#iRwUhSb)"><circle fill="url(#ieJu5od)" class="jex_nzasb"/></g><g filter="url(#iGfURwb)"><circle fill="url(#iyR5uvb)" class="iwvyjac9s"/></g><g filter="url(#iZttqOc)"><circle fill="url(#irzakLb)" class="bmf769bla"/><circle fill="url(#isVKkdd)" class="bmf769bla"/></g><g filter="url(#ik7CLUc)"><circle class="brais2b2y"/><circle fill="url(#imilBdd)" class="nukn2xbgy"/><circle fill="url(#ikkHwCH)" class="nukn2xbgy"/></g><g filter="url(#iw4EK0c)"><path fill="url(#ijSGxjD)" class="t76r9385w"/><path fill="url(#iZmC1Ib)" class="t76r9385w"/><path fill="url(#ixIhAhd)" class="t76r9385w"/></g><path fill="url(#i459gnd)" class="dgh2pqmbc"/><path fill="url(#ioCjqCc)" class="dgh2pqmbc"/><path fill="url(#iRRU6de)" class="dgh2pqmbc"/><path fill="url(#iwocrQy)" class="dgh2pqmbc"/><g filter="url(#ijEZyIc)"><path fill="url(#i6wlk7b)" class="oyinlcb4d"/></g><g filter="url(#icgHt3C)"><path class="gsqz31bqc"/><path fill="url(#idaAEqb)" class="poz6z3j1n"/><path fill="url(#il6QICz)" class="poz6z3j1n"/><path fill="url(#iXRnm8c)" class="poz6z3j1n"/><path fill="url(#iP9D7qb)" class="poz6z3j1n"/></g><g filter="url(#is2dORp)"><path class="cw-5m3czo"/></g><g filter="url(#i4wMgFe)"><path class="f26frdvjg"/><path fill="url(#ik4Sz3d)" class="pgk0gl3fj"/><path fill="url(#i4Irrud)" class="pgk0gl3fj"/><path fill="url(#iUfcJyd)" class="pgk0gl3fj"/><path fill="url(#ibKFs0b)" class="pgk0gl3fj"/></g><path fill="url(#icFbXKc)" class="pgk0gl3fj"/><path fill="url(#ikr4Vqd)" class="ixdvrhbqy"/><path fill="url(#iiQiLKe)" class="ixdvrhbqy"/><path fill="url(#iCSFBje)" class="ixdvrhbqy"/><path stroke="url(#iQhTUkb)" class="gropwub8q"/><g filter="url(#i24sHle)"><path class="nwu_01b8i"/><path fill="url(#iU8g7md)" class="x3aoszbvg"/></g><g filter="url(#iMWbI7b)"><path class="zpgf_ubnq"/><path fill="url(#iLpqOeb)" class="mz4-2hb0a"/></g><path class="zrb0fp9et"/><path fill="url(#iKpdjQd)" class="l7mxo_90g"/><path class="uiz90ac4g"/><g filter="url(#iqRencc)"><path class="x5gh4ztgw"/><path fill="url(#iUy7MTd)" class="at15ufb2l"/></g><g filter="url(#iOtcSxe)"><path fill="url(#iN8C4pb)" class="vgl8lzbns"/></g><path class="dny8vkwgo"/><path fill="url(#iqUPHtc)" class="lbdc1tbho"/><path class="hrygmabaw"/><g filter="url(#icOGmYu)"><path fill="url(#iqKiXtr)" class="jrtw48bvk"/></g><g filter="url(#ist2Hjc)"><ellipse transform="rotate(-27.914 12.683 11.737)" class="f5tpcv3mf"/><ellipse fill="url(#iMc7eWc)" transform="rotate(-27.914 12.683 11.737)" class="h79m0ob2w"/></g><g filter="url(#i3ntzqc)"><path stroke="url(#ivLJ7Ge)" class="aw-w3h_1b"/></g><g filter="url(#ilYzKBb)"><path stroke="url(#iohdpgb)" class="nwvq8zb0a"/></g><g filter="url(#iNatjNd)"><path stroke="url(#ifsaTib)" class="sgsz0chto"/></g><defs><radialGradient id="i07X1ie" cx="0" cy="0" r="1" gradientTransform="matrix(3.125 1 -2.08207 6.50646 3.708 25.849)" gradientUnits="userSpaceOnUse"><stop offset=".176" class="li28y9bsf"/><stop offset="1" class="o1jwunhtj"/></radialGradient><radialGradient id="iM2JTLe" cx="0" cy="0" r="1" gradientTransform="rotate(110.288 4.585 19.664)scale(5.49596 3.74438)" gradientUnits="userSpaceOnUse"><stop class="oe2xm9ikp"/><stop offset="1" class="d6d59o0ou"/></radialGradient><radialGradient id="iwtHj3b" cx="0" cy="0" r="1" gradientTransform="matrix(-2.71872 5.59376 -.25587 -.12436 24.239 18.13)" gradientUnits="userSpaceOnUse"><stop class="m4vk7-mbl"/><stop offset="1" class="esw1hmivn"/></radialGradient><radialGradient id="i8MotOe" cx="0" cy="0" r="1" gradientTransform="matrix(-1.55616 -6.67822 .6506 -.1516 13.25 28.75)" gradientUnits="userSpaceOnUse"><stop class="o4j1rvu5g"/><stop offset="1" class="yp-hr1bpr"/></radialGradient><radialGradient id="iGL4l5c" cx="0" cy="0" r="1" gradientTransform="matrix(-2.17874 .81494 -1.02635 -2.74392 12.187 18.016)" gradientUnits="userSpaceOnUse"><stop offset=".178" class="k910dfb4a"/><stop offset="1" class="vm-pj7b0c"/></radialGradient><radialGradient id="i1Rc7sg" cx="0" cy="0" r="1" gradientTransform="matrix(0 9.50857 -5.52096 0 15.105 20.5)" gradientUnits="userSpaceOnUse"><stop offset=".092" class="yartpqble"/><stop offset=".838" class="adq2qn0ak"/></radialGradient><radialGradient id="i7JKwFc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -7.08205 11.2731 0 15.106 24.44)" gradientUnits="userSpaceOnUse"><stop offset=".717" class="a80gjybst"/><stop offset=".937" class="vkxv1sb2j"/></radialGradient><radialGradient id="ivd4JLe" cx="0" cy="0" r="1" gradientTransform="rotate(140.588 10.275 15.96)scale(2.28848 2.24827)" gradientUnits="userSpaceOnUse"><stop offset=".354" class="b5vuh20co"/><stop offset="1" class="hrswh-pmg"/></radialGradient><radialGradient id="iWQiM2P" cx="0" cy="0" r="1" gradientTransform="matrix(.84335 -.64209 .3353 .44041 28.086 21.597)" gradientUnits="userSpaceOnUse"><stop offset=".132" class="wyf8ygbxi"/><stop offset="1" class="i6hs9gb9s"/></radialGradient><radialGradient id="iS8BdYX" cx="0" cy="0" r="1" gradientTransform="rotate(148.849 11.267 12.198)scale(4.17157)" gradientUnits="userSpaceOnUse"><stop offset=".838" class="wc1l7vbis"/><stop offset="1" class="oa317xagd"/></radialGradient><radialGradient id="ir8Vklb" cx="0" cy="0" r="1" gradientTransform="matrix(1.26514 1.24827 -2.90348 2.94272 23.842 15.446)" gradientUnits="userSpaceOnUse"><stop class="ky_indbcd"/><stop offset="1" class="s_ufbeclz"/></radialGradient><radialGradient id="iCO6KNc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.37479 2.10625 0 26.912 16.803)" gradientUnits="userSpaceOnUse"><stop class="qkb33eb6n"/><stop offset="1" class="q-0s8ibrs"/></radialGradient><radialGradient id="iqCZQQc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .4408 -2.66861 0 27.506 17.195)" gradientUnits="userSpaceOnUse"><stop class="zxhnj4bqq"/><stop offset="1" class="hf-5q38gm"/></radialGradient><radialGradient id="iZvPCGd" cx="0" cy="0" r="1" gradientTransform="matrix(-.4998 .66245 -.66245 -.4998 25.981 21.066)" gradientUnits="userSpaceOnUse"><stop class="dg3rcdvoo"/><stop offset="1" class="r0tyikbvd"/></radialGradient><radialGradient id="ifCvIac" cx="0" cy="0" r="1" gradientTransform="matrix(-1.12692 -1.56257 1.8364 -1.3244 16.412 20.186)" gradientUnits="userSpaceOnUse"><stop class="wbedg6bqs"/><stop offset="1" class="mu9g4n4za"/></radialGradient><radialGradient id="iAbjTed" cx="0" cy="0" r="1" gradientTransform="matrix(1.23422 2.24153 -2.68983 1.48106 14.83 18)" gradientUnits="userSpaceOnUse"><stop class="lp720zbph"/><stop offset="1" class="v7c966wuf"/></radialGradient><radialGradient id="iWcBtPG" cx="0" cy="0" r="1" gradientTransform="matrix(0 .8787 -1.6371 0 26.073 23.604)" gradientUnits="userSpaceOnUse"><stop offset=".106" class="r0i0_6b9f"/><stop offset="1" class="dcb4tlblp"/></radialGradient><radialGradient id="iLo8Fab" cx="0" cy="0" r="1" gradientTransform="matrix(0 .94192 -1.75486 0 26.073 25.023)" gradientUnits="userSpaceOnUse"><stop offset=".109" class="r0i0_6b9f"/><stop offset="1" class="dcb4tlblp"/></radialGradient><radialGradient id="iVc1Xeb" cx="0" cy="0" r="1" gradientTransform="matrix(0 .78779 -1.4677 0 26.073 26.393)" gradientUnits="userSpaceOnUse"><stop offset=".109" class="r0i0_6b9f"/><stop offset="1" class="dcb4tlblp"/></radialGradient><radialGradient id="i0FCnKc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .87616 -2.08784 0 26.073 27.874)" gradientUnits="userSpaceOnUse"><stop offset=".186" class="r0i0_6b9f"/><stop offset="1" class="dcb4tlblp"/></radialGradient><radialGradient id="ieJu5od" cx="0" cy="0" r="1" gradientTransform="matrix(1.75652 0 0 3.07393 8.717 12.515)" gradientUnits="userSpaceOnUse"><stop offset=".351" class="gsgzrwbpm"/><stop offset="1" class="nhrtbwabt"/></radialGradient><radialGradient id="isVKkdd" cx="0" cy="0" r="1" gradientTransform="matrix(.82748 -.60254 .68772 .94447 20.283 12.25)" gradientUnits="userSpaceOnUse"><stop offset=".543" class="ywu0pr7ii"/><stop offset="1" class="pw1h71b2a"/></radialGradient><radialGradient id="imilBdd" cx="0" cy="0" r="1" gradientTransform="matrix(.82204 -1.51196 .88496 .48114 19.87 13.338)" gradientUnits="userSpaceOnUse"><stop offset=".755" class="evklql54e"/><stop offset=".916" class="ppo67rb9b"/></radialGradient><radialGradient id="ikkHwCH" cx="0" cy="0" r="1" gradientTransform="matrix(.25953 .2569 -.33118 .33457 19.911 12.516)" gradientUnits="userSpaceOnUse"><stop class="o45oetbxg"/><stop offset="1" class="mfyy4ibhn"/></radialGradient><radialGradient id="iZmC1Ib" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.30832 1.61023 0 17.489 11.243)" gradientUnits="userSpaceOnUse"><stop class="q3kvcibxc"/><stop offset="1" class="kz100sbcz"/></radialGradient><radialGradient id="ixIhAhd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.37541 1.71044 0 12.927 11.377)" gradientUnits="userSpaceOnUse"><stop class="z_g0j449a"/><stop offset="1" class="s5xtkwbhw"/></radialGradient><radialGradient id="iRRU6de" cx="0" cy="0" r="1" gradientTransform="matrix(0 8.18536 -11.1112 0 14.839 10.74)" gradientUnits="userSpaceOnUse"><stop offset=".649" class="ovqiuzbzv"/><stop offset="1" class="keo8ftw6s"/></radialGradient><radialGradient id="iwocrQy" cx="0" cy="0" r="1" gradientTransform="matrix(3.14588 -.82304 .52131 1.9926 10.95 19.748)" gradientUnits="userSpaceOnUse"><stop class="m13zyzbuk"/><stop offset="1" class="kzk-_ccou"/></radialGradient><radialGradient id="idaAEqb" cx="0" cy="0" r="1" gradientTransform="matrix(.79857 -2.95942 1.42495 .3845 19.49 8.406)" gradientUnits="userSpaceOnUse"><stop offset=".372" class="v4bc9u3un"/><stop offset="1" class="o90gcpqxu"/></radialGradient><radialGradient id="il6QICz" cx="0" cy="0" r="1" gradientTransform="matrix(3.82845 .35231 -.18944 2.05853 17.846 6.643)" gradientUnits="userSpaceOnUse"><stop offset=".32" class="tti32obdt"/><stop offset="1" class="cpvxurbrw"/></radialGradient><radialGradient id="iXRnm8c" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.68076 -2.60303 0 15.14 3.906)" gradientUnits="userSpaceOnUse"><stop class="vpyj0s_ar"/><stop offset="1" class="lkn2u3bae"/></radialGradient><radialGradient id="iP9D7qb" cx="0" cy="0" r="1" gradientTransform="matrix(3.07685 -2.2548 3.53253 4.82042 8.686 10.73)" gradientUnits="userSpaceOnUse"><stop class="zk3m83b4g"/><stop offset="1" class="gey-evbzc"/></radialGradient><radialGradient id="ibKFs0b" cx="0" cy="0" r="1" gradientTransform="matrix(0 .19709 -.6332 0 15.468 14.124)" gradientUnits="userSpaceOnUse"><stop class="w-44tpbkk"/><stop offset="1" class="d52rddbnb"/></radialGradient><radialGradient id="ikr4Vqd" cx="0" cy="0" r="1" gradientTransform="matrix(-2.9117 6.52447 -8.23836 -3.67657 14.666 6.988)" gradientUnits="userSpaceOnUse"><stop class="jy25td8rp"/><stop offset="1" class="xftsofb3t"/></radialGradient><radialGradient id="iiQiLKe" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.29688 1.23651 0 13.133 11.457)" gradientUnits="userSpaceOnUse"><stop offset=".545" class="hkf1_jbsj"/><stop offset="1" class="wrhkd7bsy"/></radialGradient><radialGradient id="iCSFBje" cx="0" cy="0" r="1" gradientTransform="matrix(-.48435 -4.44988 9.95838 -1.08394 13.518 11.337)" gradientUnits="userSpaceOnUse"><stop offset=".926" class="a2lyv2bbk"/><stop offset=".986" class="uqdbzpbmu"/></radialGradient><radialGradient id="iU8g7md" cx="0" cy="0" r="1" gradientTransform="matrix(.1043 -.60384 1.78641 .30854 17.586 10.43)" gradientUnits="userSpaceOnUse"><stop class="ne4llzbvb"/><stop offset="1" class="vgfjqtbdb"/></radialGradient><radialGradient id="iLpqOeb" cx="0" cy="0" r="1" gradientTransform="rotate(-80.2 12.41 -2.168)scale(.61278 1.81296)" gradientUnits="userSpaceOnUse"><stop class="ne4llzbvb"/><stop offset="1" class="vgfjqtbdb"/></radialGradient><radialGradient id="iKpdjQd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .8119 -1.29142 0 17.322 11.833)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="iUy7MTd" cx="0" cy="0" r="1" gradientTransform="matrix(-.23208 -.29907 .41175 -.31952 17.093 11.918)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iqUPHtc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81194 -1.29148 0 12.954 11.833)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="iMc7eWc" cx="0" cy="0" r="1" gradientTransform="rotate(-90.897 12.266 -.21)scale(.4945 .5944)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><linearGradient id="iVOIuJb" x1="16.902" x2="15.504" y1="26.37" y2="26.068" gradientUnits="userSpaceOnUse"><stop class="k6k-6oblx"/><stop offset="1" class="l5x5or5jn"/></linearGradient><linearGradient id="i4Nl9le" x1="7.199" x2="6.027" y1="26.17" y2="26.17" gradientUnits="userSpaceOnUse"><stop class="xfetrrneo"/><stop offset="1" class="n0fg5jb7h"/></linearGradient><linearGradient id="iehQjMe" x1="23.127" x2="23.77" y1="26.255" y2="26.224" gradientUnits="userSpaceOnUse"><stop offset=".478" class="g2cjljmej"/><stop offset="1" class="h5gp5h3ar"/></linearGradient><linearGradient id="iQ0NSod" x1="22.77" x2="18.395" y1="16.24" y2="28.75" gradientUnits="userSpaceOnUse"><stop class="c08ew-b0i"/><stop offset="1" class="exuz4sbao"/></linearGradient><linearGradient id="iG0CGgc" x1="16.824" x2="17.53" y1="26.741" y2="26.836" gradientUnits="userSpaceOnUse"><stop class="q5z4iwf2u"/><stop offset="1" class="t7ud1ab5b"/></linearGradient><linearGradient id="ivubtui" x1="20.787" x2="20.787" y1="16.241" y2="17.339" gradientUnits="userSpaceOnUse"><stop offset=".457" class="tffk3lifv"/><stop offset="1" class="e4yz8gz4u"/></linearGradient><linearGradient id="i1rfvSb" x1="7.895" x2="11.895" y1="17.88" y2="29.13" gradientUnits="userSpaceOnUse"><stop class="m3gjwjbhl"/><stop offset="1" class="c9zswtx-n"/></linearGradient><linearGradient id="i8Qro1b" x1="8.365" x2="9.063" y1="15.986" y2="19.551" gradientUnits="userSpaceOnUse"><stop class="s434a46or"/><stop offset="1" class="qrv_44bpu"/></linearGradient><linearGradient id="i4WTvKe" x1="7.895" x2="8.309" y1="22.818" y2="22.615" gradientUnits="userSpaceOnUse"><stop class="bwk0n7bpz"/><stop offset="1" class="oinrtsbml"/></linearGradient><linearGradient id="izIgdLb" x1="13.739" x2="13.328" y1="28.446" y2="28.532" gradientUnits="userSpaceOnUse"><stop class="ifhx39w3y"/><stop offset="1" class="tmbtljdgb"/></linearGradient><linearGradient id="ilieiYc" x1="23.395" x2="21.614" y1="26.287" y2="26.287" gradientUnits="userSpaceOnUse"><stop class="tsgwb3b4a"/><stop offset="1" class="nvk1b4bey"/></linearGradient><linearGradient id="ioOqPFe" x1="8.114" x2="10.395" y1="28.099" y2="26.943" gradientUnits="userSpaceOnUse"><stop class="h1snaz72e"/><stop offset="1" class="kvxpklbcz"/></linearGradient><linearGradient id="i2RAssb" x1="15.111" x2="15.111" y1="17.64" y2="28.744" gradientUnits="userSpaceOnUse"><stop offset=".006" class="kt__1405u"/><stop offset="1" class="h_j9u0wvt"/></linearGradient><linearGradient id="ici3KLb" x1="17.905" x2="16.316" y1="22.348" y2="22.055" gradientUnits="userSpaceOnUse"><stop class="u4y0gibbb"/><stop offset="1" class="g49m20bpi"/></linearGradient><linearGradient id="iIPlQnd" x1="25.739" x2="25.739" y1="15.937" y2="19.993" gradientUnits="userSpaceOnUse"><stop offset=".313" class="wprwrdbxj"/><stop offset=".562" class="ax-d4eb4u"/></linearGradient><linearGradient id="iISzOte" x1="25.934" x2="25.792" y1="16.873" y2="18.076" gradientUnits="userSpaceOnUse"><stop offset=".12" class="qcwm1i13v"/><stop offset="1" class="s0eee-boz"/></linearGradient><linearGradient id="iPhs8tc" x1="23.236" x2="23.363" y1="16.81" y2="17.246" gradientUnits="userSpaceOnUse"><stop class="wtu393bab"/><stop offset="1" class="ce_wr9jxr"/></linearGradient><linearGradient id="iDa2hhb" x1="26.936" x2="24.649" y1="21.38" y2="21.38" gradientUnits="userSpaceOnUse"><stop class="j-x55pbxn"/><stop offset="1" class="zg05wl6cw"/></linearGradient><linearGradient id="iULB3pp" x1="24.466" x2="24.847" y1="21.222" y2="21.194" gradientUnits="userSpaceOnUse"><stop class="fs7-dablt"/><stop offset="1" class="zg97ljbvw"/></linearGradient><linearGradient id="ilGrvtf" x1="27.084" x2="26.822" y1="21.093" y2="21.07" gradientUnits="userSpaceOnUse"><stop class="qna0z9q7a"/><stop offset="1" class="toldersuv"/></linearGradient><linearGradient id="i6q3R3d" x1="27.996" x2="23.127" y1="26.627" y2="26.627" gradientUnits="userSpaceOnUse"><stop offset=".146" class="pxu01k21v"/><stop offset=".861" class="mrmriqoyy"/></linearGradient><linearGradient id="io3Ohjd" x1="23.742" x2="25.663" y1="24.424" y2="24.424" gradientUnits="userSpaceOnUse"><stop class="lf8a5e78i"/><stop offset="1" class="ar7lpj8pp"/></linearGradient><linearGradient id="ikgTf9R" x1="23.742" x2="25.663" y1="25.866" y2="25.866" gradientUnits="userSpaceOnUse"><stop class="lf8a5e78i"/><stop offset="1" class="ar7lpj8pp"/></linearGradient><linearGradient id="im1gSKd" x1="23.742" x2="25.663" y1="27.296" y2="27.296" gradientUnits="userSpaceOnUse"><stop class="lf8a5e78i"/><stop offset="1" class="ar7lpj8pp"/></linearGradient><linearGradient id="iyR5uvb" x1="10.388" x2="9.747" y1="12.794" y2="12.794" gradientUnits="userSpaceOnUse"><stop class="jrtbzwbyo"/><stop offset="1" class="xh6agdcni"/></linearGradient><linearGradient id="irzakLb" x1="20.998" x2="20.179" y1="11.423" y2="13.961" gradientUnits="userSpaceOnUse"><stop class="z3o7w4-ew"/><stop offset="1" class="uddso4bed"/></linearGradient><linearGradient id="ijSGxjD" x1="19.18" x2="11.536" y1="12.905" y2="14.044" gradientUnits="userSpaceOnUse"><stop class="ah-u2v6vh"/><stop offset="1" class="hp2sktbkw"/></linearGradient><linearGradient id="i459gnd" x1="9.74" x2="11.623" y1="15.604" y2="15.537" gradientUnits="userSpaceOnUse"><stop class="wgn2-qn3r"/><stop offset="1" class="cyilnmbju"/></linearGradient><linearGradient id="ioCjqCc" x1="20.01" x2="18.953" y1="14.765" y2="14.665" gradientUnits="userSpaceOnUse"><stop class="y91wuhb_y"/><stop offset="1" class="dfnybco8z"/></linearGradient><linearGradient id="i6wlk7b" x1="14.608" x2="22.76" y1="9.918" y2="6.999" gradientUnits="userSpaceOnUse"><stop offset=".109" class="fxywcj73h"/><stop offset="1" class="c0g7wdubv"/></linearGradient><linearGradient id="ik4Sz3d" x1="14.276" x2="15.215" y1="13.565" y2="13.565" gradientUnits="userSpaceOnUse"><stop class="tye5yqhfq"/><stop offset="1" class="rb8odhbtu"/></linearGradient><linearGradient id="i4Irrud" x1="16.08" x2="15.053" y1="13.888" y2="13.873" gradientUnits="userSpaceOnUse"><stop class="w6mxzsbgv"/><stop offset="1" class="ylom6naui"/></linearGradient><linearGradient id="iUfcJyd" x1="15.335" x2="15.335" y1="14.631" y2="14.057" gradientUnits="userSpaceOnUse"><stop class="hlulkvo5l"/><stop offset="1" class="y_z4ite8v"/></linearGradient><linearGradient id="icFbXKc" x1="15.267" x2="15.267" y1="14.673" y2="14.505" gradientUnits="userSpaceOnUse"><stop class="ahyqmxbmp"/><stop offset="1" class="g67mx8b1h"/></linearGradient><linearGradient id="iQhTUkb" x1="14.103" x2="14.538" y1="16.247" y2="15.559" gradientUnits="userSpaceOnUse"><stop class="lwz87437z"/><stop offset=".663" class="c7jfumw-i"/></linearGradient><linearGradient id="iN8C4pb" x1="18.1" x2="17.786" y1="11.887" y2="12.08" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iqKiXtr" x1="13.699" x2="13.385" y1="11.887" y2="12.08" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="ivLJ7Ge" x1="18.116" x2="17.695" y1="9.745" y2="8.885" gradientUnits="userSpaceOnUse"><stop class="v9-6-sbuc"/><stop offset="1" class="q8x82vmoe"/></linearGradient><linearGradient id="iohdpgb" x1="12.806" x2="11.616" y1="9.617" y2="9.118" gradientUnits="userSpaceOnUse"><stop class="v9-6-sbuc"/><stop offset="1" class="q8x82vmoe"/></linearGradient><linearGradient id="ifsaTib" x1="10.474" x2="10.474" y1="7.601" y2="9.76" gradientUnits="userSpaceOnUse"><stop offset=".228" class="tkijdf1cs"/><stop offset="1" class="wg8zzjbli"/></linearGradient><filter id="i07y7fb" width="5.513" height="4.74" x="12.848" y="24" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.976471 0 0 0 0 0.780392 0 0 0 0 0.866667 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2317"/></filter><filter id="i7Wvd3d" width="6.102" height="1.228" x="22.791" y="16.711" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.05"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.647059 0 0 0 0 0.47451 0 0 0 0 0.54902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2317"/></filter><filter id="idZPNlb" width="1.075" height="1.075" x="25.198" y="20.844" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy="-.05"/><feGaussianBlur stdDeviation=".025"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.694118 0 0 0 0 0.560784 0 0 0 0 0.764706 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2317"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.05" dy=".05"/><feGaussianBlur stdDeviation=".025"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.917647 0 0 0 0 0.87451 0 0 0 0 0.976471 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2317" result="effect2_innerShadow_4002_2317"/></filter><filter id="iBATW9D" width="5.967" height="5.967" x="12.166" y="14.907" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2317" stdDeviation=".125"/></filter><filter id="izBjjmA" width="5.813" height="5.813" x="12.243" y="15.094" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2317" stdDeviation=".25"/></filter><filter id="iIQBWye" width="5.369" height="6.076" x="23.127" y="22.675" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.15"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.341176 0 0 0 0 0.211765 0 0 0 0 0.219608 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2317"/></filter><filter id="iqZDYwj" width="2.319" height=".3" x="23.592" y="24.196" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2317" stdDeviation=".05"/></filter><filter id="ijVno3b" width="2.319" height=".3" x="23.592" y="25.637" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2317" stdDeviation=".05"/></filter><filter id="igD61Cd" width="2.319" height=".3" x="23.592" y="27.068" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2317" stdDeviation=".05"/></filter><filter id="iRwUhSb" width="3.542" height="3.342" x="8.717" y="10.844" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.517647 0 0 0 0 0.384314 0 0 0 0 0.34902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2317"/></filter><filter id="iGfURwb" width="2.992" height="2.992" x="8.892" y="11.02" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2317" stdDeviation=".25"/></filter><filter id="iZttqOc" width="3.592" height="3.592" x="18.24" y="10.594" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.482353 0 0 0 0 0.278431 0 0 0 0 0.372549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2317"/></filter><filter id="ik7CLUc" width="2.992" height="2.992" x="18.415" y="11.02" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2317" stdDeviation=".25"/></filter><filter id="iw4EK0c" width="10.383" height="12.139" x="9.978" y="6.886" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.254902 0 0 0 0 0.137255 0 0 0 0 0.113725 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2317"/></filter><filter id="ijEZyIc" width="8.25" height="7.07" x="13.311" y="4.886" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2317" stdDeviation="1"/></filter><filter id="icgHt3C" width="12.614" height="8.551" x="8.834" y="3.406" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0392157 0 0 0 0 0.00784314 0 0 0 0 0.0196078 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2317"/></filter><filter id="is2dORp" width="3.262" height="4.184" x="13.271" y="11.36" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2317" stdDeviation=".375"/></filter><filter id="i4wMgFe" width="2.379" height="3.184" x="13.951" y="11.697" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2317" stdDeviation=".125"/></filter><filter id="i24sHle" width="2.982" height="1.874" x="16.324" y="8.864" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.156863 0 0 0 0 0.0784314 0 0 0 0 0.109804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2317"/></filter><filter id="iMWbI7b" width="2.982" height="1.874" x="11.171" y="8.864" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.156863 0 0 0 0 0.0784314 0 0 0 0 0.109804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2317"/></filter><filter id="iqRencc" width=".787" height=".697" x="16.587" y="11.392" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2317" stdDeviation=".05"/></filter><filter id="iOtcSxe" width=".892" height=".914" x="17.428" y="11.468" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2317" stdDeviation=".1"/></filter><filter id="icOGmYu" width=".987" height="1.041" x="12.982" y="11.405" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2317" stdDeviation=".1"/></filter><filter id="ist2Hjc" width=".914" height=".705" x="12.226" y="11.384" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2317" stdDeviation=".05"/></filter><filter id="i3ntzqc" width="2.601" height="1.182" x="16.428" y="9.24" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2317" stdDeviation=".125"/></filter><filter id="ilYzKBb" width="2.679" height="1.239" x="11.203" y="9.303" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2317" stdDeviation=".125"/></filter><filter id="iNatjNd" width="1.008" height="2.271" x="9.97" y="7.325" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2317" stdDeviation=".125"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:man-singer-medium-dark" /></template>
<style>
.a2lyv2bbk {
  stop-color: var(--svg-color--a90f60, #A90F60);
  stop-opacity: 0;
}

.a80gjybst {
  stop-color: var(--svg-color--562e2e, #562E2E);
  stop-opacity: 0;
}

.adq2qn0ak {
  stop-color: var(--svg-color--593031, #593031);
}

.ah-u2v6vh {
  stop-color: var(--svg-color--9b6c5e, #9B6C5E);
}

.ahyqmxbmp {
  stop-color: var(--svg-color--743b4a, #743B4A);
}

.ar7lpj8pp {
  stop-color: var(--svg-color--7a4b42, #7A4B42);
  stop-opacity: 0;
}

.at15ufb2l {
  d: path("M17.258 11.544c.064.085-.07.189-.22.302c-.152.113-.264.193-.328.107c-.063-.085.008-.245.159-.358c.151-.114.325-.136.389-.051");
}

.aw-w3h_1b {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M16.803 9.648c.43-.075 1.27-.054 1.851.398");
}

.ax-d4eb4u {
  stop-color: var(--svg-color--562d79, #562D79);
}

.b5vuh20co {
  stop-color: var(--svg-color--8b655b, #8B655B);
}

.bmf769bla {
  cx: 19.911px;
  cy: 12.515px;
  r: 1.671px;
}

.brais2b2y {
  cx: 19.911px;
  cy: 12.515px;
  r: 0.996px;
  fill: var(--svg-color--7a5654, #7A5654);
}

.bwk0n7bpz {
  stop-color: var(--svg-color--3e8ed5, #3E8ED5);
}

.c08ew-b0i {
  stop-color: var(--svg-color--2ca9dd, #2CA9DD);
}

.c0g7wdubv {
  stop-color: var(--svg-color--a27b71, #A27B71);
  stop-opacity: 0;
}

.c7jfumw-i {
  stop-color: var(--svg-color--865e63, #865E63);
  stop-opacity: 0;
}

.c9zswtx-n {
  stop-color: var(--svg-color--3073d6, #3073D6);
}

.ce_wr9jxr {
  stop-color: var(--svg-color--b19a83, #B19A83);
  stop-opacity: 0;
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cpvxurbrw {
  stop-color: var(--svg-color--46383d, #46383D);
  stop-opacity: 0;
}

.cw-5m3czo {
  fill: var(--svg-color--71404a, #71404A);
  d: path("m14.865 12.393l-.821 1.701c-.102.35.143.7.489.7h.738c.346 0 .59-.355.488-.7l-.499-1.701c-.107-.377-.283-.377-.395 0");
}

.cwb5s4b7a {
  d: path("m28.214 16.781l-4.844-.02a.57.57 0 0 0-.579.579c0 .325.254.578.579.578l4.844.02a.57.57 0 0 0 .579-.578a.585.585 0 0 0-.58-.579");
}

.cyilnmbju {
  stop-color: var(--svg-color--84615a, #84615A);
  stop-opacity: 0;
}

.d52rddbnb {
  stop-color: var(--svg-color--976f6a, #976F6A);
  stop-opacity: 0;
}

.d6d59o0ou {
  stop-color: var(--svg-color--4d396f, #4D396F);
}

.dcb4tlblp {
  stop-color: var(--svg-color--986e66, #986E66);
  stop-opacity: 0;
}

.dfnybco8z {
  stop-color: var(--svg-color--966d5f, #966D5F);
  stop-opacity: 0;
}

.dg3rcdvoo {
  stop-color: var(--svg-color--d2bfe7, #D2BFE7);
}

.dgh2pqmbc {
  d: path("M9.978 10.463c0-.267.107-.588.322-.748l.161-.16c.268-.214.376-.534.376-.854v-.854a.52.52 0 0 1 .43-.534c.644-.16 1.986-.427 3.919-.427s3.275.267 3.92.427c.214.053.429.267.429.534V8.7c0 .32.16.64.375.854c.503.352.472.546.43.96a46 46 0 0 0-.107 1.442h.018l-.266 3.962c-.161 1.771-1.553 3.006-3.214 3.006h-3.213c-1.714 0-3.053-1.235-3.214-3.006c-.14-1.818-.2-3.641-.366-5.456");
}

.dh58orbia {
  d: path("M25.766 19.94a2.498 2.498 0 1 0 0-4.997a2.498 2.498 0 0 0 0 4.996");
}

.dm_fr_bzn {
  d: path("M25.726 26.58a.784.784 0 0 1-.782-.71l-.67-6.429l2.975.01l-.731 6.429a.8.8 0 0 1-.792.7");
}

.dny8vkwgo {
  fill: var(--svg-color--fff, #fff);
  d: path("M12.746 11.084c-.654 0-1.206.45-1.357 1.06a.274.274 0 0 0 .269.34h2.232a.23.23 0 0 0 .228-.272a1.4 1.4 0 0 0-1.373-1.128");
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.e4yz8gz4u {
  stop-color: var(--svg-color--2ea1dc, #2EA1DC);
  stop-opacity: 0;
}

.esw1hmivn {
  stop-color: var(--svg-color--2796d4, #2796D4);
  stop-opacity: 0;
}

.evklql54e {
  stop-color: var(--svg-color--73443e, #73443E);
  stop-opacity: 0;
}

.exuz4sbao {
  stop-color: var(--svg-color--3069c9, #3069C9);
}

.f26frdvjg {
  fill: var(--svg-color--8c5f5e, #8C5F5E);
  d: path("m14.758 12.23l-.532 1.701a.54.54 0 0 0 .521.7h.787a.54.54 0 0 0 .521-.7l-.532-1.701c-.114-.377-.646-.377-.765 0");
}

.f5tpcv3mf {
  cx: 12.683px;
  cy: 11.737px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.39px;
  ry: 0.197px;
}

.fs7-dablt {
  stop-color: var(--svg-color--a0768f, #A0768F);
}

.ft5dv1b6b {
  fill: none;
}

.fxywcj73h {
  stop-color: var(--svg-color--a47f73, #A47F73);
}

.g2cjljmej {
  stop-color: var(--svg-color--604e83, #604E83);
}

.g49m20bpi {
  stop-color: var(--svg-color--825b56, #825B56);
  stop-opacity: 0;
}

.g67mx8b1h {
  stop-color: var(--svg-color--743b4a, #743B4A);
  stop-opacity: 0;
}

.gey-evbzc {
  stop-color: var(--svg-color--453938, #453938);
  stop-opacity: 0;
}

.gropwub8q {
  fill: var(--svg-color--88014f, #88014F);
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M13.777 15.275c.394.205.864.323 1.364.323c.505 0 .97-.118 1.363-.323a.204.204 0 0 1 .242.04a.19.19 0 0 1 .02.241m-2.989-.28l2.948.253m-2.948-.254a.2.2 0 0 0-.242.042a.19.19 0 0 0-.02.24m.262-.282l-.22.254m3.21.027l-.042-.027m.042.027l-.042-.027m.042.027a1.95 1.95 0 0 1-1.626.87a1.95 1.95 0 0 1-1.626-.87m3.21-.027c-.335.508-.919.846-1.584.846s-1.25-.338-1.585-.846m-.041.028l.041-.028m-.041.028l.041-.028");
}

.gsgzrwbpm {
  stop-color: var(--svg-color--664249, #664249);
}

.gsqz31bqc {
  fill: var(--svg-color--27151c, #27151C);
  d: path("m19.964 6.031l.43.214c.751.373 1.18 1.228 1.02 2.135l-.59 3.043c-.053.314-.261.526-.573.534h-.018s.053-.908.107-1.442c.044-.433-.032-.565-.43-.96c-.214-.214-.375-.534-.375-.855v-.854c0-.267-.215-.48-.43-.534c-.644-.16-1.986-.427-3.92-.427c-1.932 0-3.274.267-3.919.427a.52.52 0 0 0-.43.534V8.7c0 .32-.107.641-.375.855l-.161.16c-.215.16-.322.48-.322.747c.053.587.107 1.441.107 1.441l-.049-.001a.634.634 0 0 1-.595-.532l-.59-3.043c-.108-.854.321-1.709 1.073-2.082l.43-.214c.268-.16.537-.373.805-.587l.966-1.014c.591-.534 1.45-.694 2.202-.32c.537.16 1.127.16 1.664 0c.806-.268 1.718-.054 2.363.533l.805.801c.215.267.483.427.805.587");
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

.h79m0ob2w {
  cx: 12.683px;
  cy: 11.737px;
  rx: 0.39px;
  ry: 0.197px;
}

.hf-5q38gm {
  stop-color: var(--svg-color--c1bcc8, #C1BCC8);
  stop-opacity: 0;
}

.hkf1_jbsj {
  stop-color: var(--svg-color--be2252, #BE2252);
}

.hlulkvo5l {
  stop-color: var(--svg-color--7c4559, #7C4559);
}

.hp2sktbkw {
  stop-color: var(--svg-color--744d4a, #744D4A);
}

.hrswh-pmg {
  stop-color: var(--svg-color--673a32, #673A32);
}

.hrygmabaw {
  fill: var(--svg-color--000, #000);
  d: path("M13.464 12.248a.51.51 0 0 0-.512-.511a.51.51 0 0 0-.454.747h.905a.5.5 0 0 0 .061-.236");
}

.hx9qd6bzz {
  d: path("M27.277 21.065c.59 0 1.07.48 1.07 1.07v2.45h-2.14v-2.45c0-.59.48-1.07 1.07-1.07");
}

.i6hs9gb9s {
  stop-color: var(--svg-color--997c73, #997C73);
  stop-opacity: 0;
}

.ifhx39w3y {
  stop-color: var(--svg-color--3469bc, #3469BC);
}

.ismqbeb_x {
  cx: 15.149px;
  cy: 17.891px;
  r: 2.734px;
}

.iwvyjac9s {
  cx: 10.388px;
  cy: 12.515px;
  r: 0.996px;
}

.ixdvrhbqy {
  d: path("M14.999 6.886a19 19 0 0 0-2.304.16l-2.057 6.052h1.81l-.508 2.688l3.687-5.133h-1.883z");
}

.j-x55pbxn {
  stop-color: var(--svg-color--d9cbea, #D9CBEA);
}

.j7_9c6bse {
  d: path("M27.017 28.74c-.14-.96-.36-1.91-.65-2.84a11.77 11.77 0 0 0-3.24-5.13v7.97z");
}

.j998t3bor {
  d: path("M5.405 16.762h6.086l2.248 11.988h-2.79l-5.88-11.528c-.086-.125-.07-.46.336-.46");
}

.jex_nzasb {
  cx: 10.388px;
  cy: 12.515px;
  r: 1.671px;
}

.jh-gxaboi {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M23.742 25.788h2.02");
}

.jrtbzwbyo {
  stop-color: var(--svg-color--553038, #553038);
}

.jrtw48bvk {
  d: path("M13.768 12.144c0-.289-.234-.481-.298-.54l-.288.28l.177.361z");
}

.jy25td8rp {
  stop-color: var(--svg-color--e82d86, #E82D86);
}

.k0-4bl52g {
  d: path("M23.127 23.627c0-.44.366-.802.817-.802h3.054c.745 0 1.349.589 1.349 1.315v3.514c0 .605-.504 1.096-1.124 1.096h-3.28a.81.81 0 0 1-.816-.802c0-.314.187-.589.458-.72a.8.8 0 0 1-.458-.72c0-.315.187-.59.458-.72a.8.8 0 0 1-.458-.72c0-.315.187-.59.458-.72a.8.8 0 0 1-.458-.721");
}

.k6k-6oblx {
  stop-color: var(--svg-color--c296bf, #C296BF);
}

.k910dfb4a {
  stop-color: var(--svg-color--2c649b, #2C649B);
}

.keo8ftw6s {
  stop-color: var(--svg-color--74405b, #74405B);
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

.kz100sbcz {
  stop-color: var(--svg-color--855354, #855354);
  stop-opacity: 0;
}

.kzk-_ccou {
  stop-color: var(--svg-color--8b6a6b, #8B6A6B);
  stop-opacity: 0;
}

.kzoru-n_t {
  cx: 15.15px;
  cy: 18px;
  r: 2.406px;
}

.l5x5or5jn {
  stop-color: var(--svg-color--e7c1f5, #E7C1F5);
  stop-opacity: 0;
}

.l6cdgjewt {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M23.742 24.346h2.02");
}

.l7c47o-wr {
  stop-color: var(--svg-color--664944, #664944);
}

.l7mxo_90g {
  d: path("M17.324 11.356a.893.893 0 0 1 .86 1.128H16.46a.897.897 0 0 1 .865-1.129");
}

.lbdc1tbho {
  d: path("M12.953 11.356a.893.893 0 0 0-.861 1.128h1.725a1 1 0 0 0 .033-.235a.9.9 0 0 0-.897-.894");
}

.lf8a5e78i {
  stop-color: var(--svg-color--664139, #664139);
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.li28y9bsf {
  stop-color: var(--svg-color--675890, #675890);
}

.lkn2u3bae {
  stop-color: var(--svg-color--3e3034, #3E3034);
  stop-opacity: 0;
}

.lp720zbph {
  stop-color: var(--svg-color--73394c, #73394C);
}

.lwz87437z {
  stop-color: var(--svg-color--865e63, #865E63);
}

.m13zyzbuk {
  stop-color: var(--svg-color--8b6a6b, #8B6A6B);
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

.mfyy4ibhn {
  stop-color: var(--svg-color--6c443e, #6C443E);
  stop-opacity: 0;
}

.mrmriqoyy {
  stop-color: var(--svg-color--744950, #744950);
}

.mu9g4n4za {
  stop-color: var(--svg-color--84605d, #84605D);
  stop-opacity: 0;
}

.mz4-2hb0a {
  d: path("m11.364 9.793l.002-.002l.005-.003l.012-.01l.036-.027q.044-.033.119-.08c.1-.063.24-.14.42-.211a2.84 2.84 0 0 1 1.494-.159a.534.534 0 0 1-.167 1.056a1.77 1.77 0 0 0-.934.096a1.5 1.5 0 0 0-.309.166a.534.534 0 0 1-.68-.825");
}

.n0fg5jb7h {
  stop-color: var(--svg-color--504665, #504665);
  stop-opacity: 0;
}

.ne4llzbvb {
  stop-color: var(--svg-color--301a2d, #301A2D);
}

.nhrtbwabt {
  stop-color: var(--svg-color--613641, #613641);
}

.nukn2xbgy {
  cx: 19.911px;
  cy: 12.515px;
  r: 0.996px;
}

.nvk1b4bey {
  stop-color: var(--svg-color--5f4b8a, #5F4B8A);
}

.nwu_01b8i {
  fill: var(--svg-color--352827, #352827);
  d: path("m18.864 9.793l-.002-.001l-.001-.002l-.005-.003l-.012-.01a2 2 0 0 0-.155-.107a2.6 2.6 0 0 0-.42-.211a2.84 2.84 0 0 0-1.494-.159a.534.534 0 1 0 .167 1.056c.398-.063.717.01.934.096a1.5 1.5 0 0 1 .3.16l.009.006a.534.534 0 0 0 .679-.825");
}

.nwvq8zb0a {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M11.578 10.167c.328-.29 1.043-.594 1.93-.453");
}

.o1jwunhtj {
  stop-color: var(--svg-color--58497e, #58497E);
}

.o45oetbxg {
  stop-color: var(--svg-color--6c443e, #6C443E);
}

.o4j1rvu5g {
  stop-color: var(--svg-color--3778d0, #3778D0);
}

.o90gcpqxu {
  stop-color: var(--svg-color--3d3437, #3D3437);
  stop-opacity: 0;
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

.oinrtsbml {
  stop-color: var(--svg-color--2a85ce, #2A85CE);
  stop-opacity: 0;
}

.ovqiuzbzv {
  stop-color: var(--svg-color--865362, #865362);
  stop-opacity: 0;
}

.oyinlcb4d {
  d: path("m19.108 6.886l-3.08 1.027a1.048 1.048 0 0 0 .47 2.033l3.063-.41z");
}

.pgk0gl3fj {
  d: path("m14.758 12.23l-.532 1.701a.54.54 0 0 0 .521.7h.787a.54.54 0 0 0 .521-.7l-.532-1.701c-.114-.377-.646-.377-.765 0");
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.poz6z3j1n {
  d: path("m19.964 6.031l.43.214c.751.373 1.18 1.228 1.02 2.135l-.59 3.043c-.053.314-.261.526-.573.534h-.018s.053-.908.107-1.442c.044-.433-.032-.565-.43-.96c-.214-.214-.375-.534-.375-.855v-.854c0-.267-.215-.48-.43-.534c-.644-.16-1.986-.427-3.92-.427c-1.932 0-3.274.267-3.919.427a.52.52 0 0 0-.43.534V8.7c0 .32-.107.641-.375.855l-.161.16c-.215.16-.322.48-.322.747c.053.587.107 1.441.107 1.441l-.049-.001a.634.634 0 0 1-.595-.532l-.59-3.043c-.108-.854.321-1.709 1.073-2.082l.43-.214c.268-.16.537-.373.805-.587l.966-1.014c.591-.534 1.45-.694 2.202-.32c.537.16 1.127.16 1.664 0c.806-.268 1.718-.054 2.363.533l.805.801c.215.267.483.427.805.587");
}

.ppo67rb9b {
  stop-color: var(--svg-color--73443e, #73443E);
}

.pw1h71b2a {
  stop-color: var(--svg-color--7c524c, #7C524C);
  stop-opacity: 0;
}

.pxu01k21v {
  stop-color: var(--svg-color--976c5f, #976C5F);
}

.q-0s8ibrs {
  stop-color: var(--svg-color--7d718c, #7D718C);
  stop-opacity: 0;
}

.q3kvcibxc {
  stop-color: var(--svg-color--855354, #855354);
}

.q5z4iwf2u {
  stop-color: var(--svg-color--3466b9, #3466B9);
}

.q8x82vmoe {
  stop-color: var(--svg-color--483e3e, #483E3E);
  stop-opacity: 0;
}

.qb_yaybod {
  d: path("M15.118 16.553c-1.16 0-2.487.209-3.567.58l1.29 6.873c.72.325 1.497.434 2.317.434c.77 0 1.51-.073 2.19-.352l1.313-6.955c-1.05-.383-2.384-.58-3.544-.58");
}

.qcwm1i13v {
  stop-color: var(--svg-color--bfbac7, #BFBAC7);
}

.qkb33eb6n {
  stop-color: var(--svg-color--7d718c, #7D718C);
}

.qlkjxkk-g {
  d: path("M7.078 28.74v-7.93a11.75 11.75 0 0 0-3.18 5.04l-.03.09c-.29.91-.51 1.85-.66 2.8z");
}

.qna0z9q7a {
  stop-color: var(--svg-color--cbc6d6, #CBC6D6);
}

.qrv_44bpu {
  stop-color: var(--svg-color--2987cc, #2987CC);
  stop-opacity: 0;
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.qz8nx3iur {
  d: path("M12.848 24v4.74h5.313l-.803-4.69c-.68.25-1.42.38-2.19.38c-.81.01-1.6-.15-2.32-.43");
}

.r0i0_6b9f {
  stop-color: var(--svg-color--947068, #947068);
}

.r0tyikbvd {
  stop-color: var(--svg-color--c0a6d9, #C0A6D9);
}

.r57exrbov {
  d: path("M7.078 28.74h3.87l-3.87-7.595z");
}

.rb8odhbtu {
  stop-color: var(--svg-color--754e46, #754E46);
  stop-opacity: 0;
}

.s_ufbeclz {
  stop-color: var(--svg-color--463358, #463358);
  stop-opacity: 0;
}

.s-46tsbaj {
  fill: var(--svg-color--e7c1f2, #E7C1F2);
  d: path("M12.848 24v4.74h5.313l-.803-4.69c-.68.25-1.42.38-2.19.38c-.81.01-1.6-.15-2.32-.43");
}

.s0eee-boz {
  stop-color: var(--svg-color--aa7bd1, #AA7BD1);
}

.s434a46or {
  stop-color: var(--svg-color--3a90be, #3A90BE);
}

.s5xtkwbhw {
  stop-color: var(--svg-color--6f414d, #6F414D);
  stop-opacity: 0;
}

.sgsz0chto {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M10.604 7.7v.898c-.008.149-.07.482-.259.623");
}

.snv-ysb0t {
  d: path("M24.313 16.754h-5.58L16.459 28.75h3.149l5.325-11.016a.685.685 0 0 0-.62-.98");
}

.t76r9385w {
  d: path("m10.036 11.902l.05.002s-.055-.854-.108-1.441c0-.267.107-.588.322-.748l.161-.16c.268-.214.376-.534.376-.854v-.854a.52.52 0 0 1 .43-.534c.644-.16 1.986-.427 3.919-.427s3.275.267 3.92.427c.214.053.429.267.429.534V8.7c0 .32.16.64.375.854c.503.352.472.546.43.96a46 46 0 0 0-.107 1.442h.018l-.266 3.962c-.161 1.771-1.553 3.006-3.214 3.006h-3.213c-1.714 0-3.053-1.235-3.214-3.006z");
}

.t7ud1ab5b {
  stop-color: var(--svg-color--3073cd, #3073CD);
  stop-opacity: 0;
}

.tffk3lifv {
  stop-color: var(--svg-color--3ca6cf, #3CA6CF);
}

.tkijdf1cs {
  stop-color: var(--svg-color--32272d, #32272D);
}

.tmbtljdgb {
  stop-color: var(--svg-color--2e7fd1, #2E7FD1);
  stop-opacity: 0;
}

.toldersuv {
  stop-color: var(--svg-color--d3c3e5, #D3C3E5);
  stop-opacity: 0;
}

.tsgwb3b4a {
  stop-color: var(--svg-color--7c739f, #7C739F);
}

.tti32obdt {
  stop-color: var(--svg-color--46383d, #46383D);
}

.tye5yqhfq {
  stop-color: var(--svg-color--754e46, #754E46);
}

.u4y0gibbb {
  stop-color: var(--svg-color--5e302e, #5E302E);
}

.uddso4bed {
  stop-color: var(--svg-color--855a5b, #855A5B);
}

.uiz90ac4g {
  fill: var(--svg-color--000, #000);
  d: path("M16.812 12.248a.51.51 0 0 1 .512-.511a.51.51 0 0 1 .454.747h-.905a.46.46 0 0 1-.06-.236");
}

.uqdbzpbmu {
  stop-color: var(--svg-color--a90f60, #A90F60);
}

.v4bc9u3un {
  stop-color: var(--svg-color--3d3437, #3D3437);
}

.v7c966wuf {
  stop-color: var(--svg-color--754744, #754744);
}

.v9-6-sbuc {
  stop-color: var(--svg-color--483e3e, #483E3E);
}

.vgfjqtbdb {
  stop-color: var(--svg-color--301a2d, #301A2D);
  stop-opacity: 0;
}

.vgl8lzbns {
  d: path("M18.12 12.131a.84.84 0 0 0-.232-.463l-.26.285l.117.229z");
}

.vkxv1sb2j {
  stop-color: var(--svg-color--54302a, #54302A);
}

.vm-pj7b0c {
  stop-color: var(--svg-color--288acb, #288ACB);
  stop-opacity: 0;
}

.vpyj0s_ar {
  stop-color: var(--svg-color--3e3034, #3E3034);
}

.w-44tpbkk {
  stop-color: var(--svg-color--976f6a, #976F6A);
}

.w6mxzsbgv {
  stop-color: var(--svg-color--9d766b, #9D766B);
}

.wbedg6bqs {
  stop-color: var(--svg-color--84605d, #84605D);
}

.wc1l7vbis {
  stop-color: var(--svg-color--473558, #473558);
  stop-opacity: 0;
}

.wg8zzjbli {
  stop-color: var(--svg-color--32272d, #32272D);
  stop-opacity: 0;
}

.wgn2-qn3r {
  stop-color: var(--svg-color--84615a, #84615A);
}

.wk26a8quy {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M23.742 27.218h2.02");
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

.wyf8ygbxi {
  stop-color: var(--svg-color--997c73, #997C73);
}

.x3aoszbvg {
  d: path("m18.864 9.793l-.002-.001l-.001-.002l-.005-.003l-.012-.01a2 2 0 0 0-.155-.107a2.6 2.6 0 0 0-.42-.211a2.84 2.84 0 0 0-1.494-.159a.534.534 0 1 0 .167 1.056c.398-.063.717.01.934.096a1.5 1.5 0 0 1 .3.16l.009.006a.534.534 0 0 0 .679-.825");
}

.x597vdeso {
  d: path("M15.118 17.64c-1.16 0-2.3.17-3.38.49l1.1 5.87c.72.28 1.5.44 2.32.44c.77 0 1.51-.14 2.19-.38l1.11-5.92c-1.05-.33-2.18-.5-3.34-.5");
}

.x5gh4ztgw {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M17.258 11.544c.064.085-.07.189-.22.302c-.152.113-.264.193-.328.107c-.063-.085.008-.245.159-.358c.151-.114.325-.136.389-.051");
}

.xfetrrneo {
  stop-color: var(--svg-color--504665, #504665);
}

.xftsofb3t {
  stop-color: var(--svg-color--d42552, #D42552);
}

.xh6agdcni {
  stop-color: var(--svg-color--59323c, #59323C);
}

.y_z4ite8v {
  stop-color: var(--svg-color--7c4559, #7C4559);
  stop-opacity: 0;
}

.y91wuhb_y {
  stop-color: var(--svg-color--966d5f, #966D5F);
}

.yartpqble {
  stop-color: var(--svg-color--865b56, #865B56);
}

.ylom6naui {
  stop-color: var(--svg-color--9d766b, #9D766B);
  stop-opacity: 0;
}

.yp-hr1bpr {
  stop-color: var(--svg-color--3778d0, #3778D0);
  stop-opacity: 0;
}

.yw0gpqv1k {
  d: path("M23.128 28.74v-7.267l-3.52 7.267z");
}

.ywu0pr7ii {
  stop-color: var(--svg-color--7c524c, #7C524C);
}

.z_g0j449a {
  stop-color: var(--svg-color--6f414d, #6F414D);
}

.z3o7w4-ew {
  stop-color: var(--svg-color--96776b, #96776B);
}

.zg05wl6cw {
  stop-color: var(--svg-color--a78bc1, #A78BC1);
}

.zg97ljbvw {
  stop-color: var(--svg-color--ad93c6, #AD93C6);
  stop-opacity: 0;
}

.zk3m83b4g {
  stop-color: var(--svg-color--453938, #453938);
}

.zpgf_ubnq {
  fill: var(--svg-color--352827, #352827);
  d: path("m11.364 9.793l.002-.002l.005-.003l.012-.01l.036-.027q.044-.033.119-.08c.1-.063.24-.14.42-.211a2.84 2.84 0 0 1 1.494-.159a.534.534 0 0 1-.167 1.056a1.77 1.77 0 0 0-.934.096a1.5 1.5 0 0 0-.309.166a.534.534 0 0 1-.68-.825");
}

.zrb0fp9et {
  fill: var(--svg-color--fff, #fff);
  d: path("M17.53 11.084c.654 0 1.206.45 1.357 1.059a.274.274 0 0 1-.268.341h-2.233a.23.23 0 0 1-.227-.272a1.4 1.4 0 0 1 1.372-1.128");
}

.zwdhe_emk {
  d: path("M25.736 21.868a.487.487 0 1 0 0-.974a.487.487 0 0 0 0 .974");
}

.zxhnj4bqq {
  stop-color: var(--svg-color--eae5f7, #EAE5F7);
}

</style>
