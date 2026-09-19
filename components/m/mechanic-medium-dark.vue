<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#im0wb4T)" class="m1i1rlbvk"/><g filter="url(#iHB2K8b)"><path class="u7j5qywzc"/></g><path class="m3se_ob2r"/><path fill="url(#i4RHwye)" class="zqss5obsp"/><path fill="url(#i86fP2c)" class="zqss5obsp"/><path fill="url(#iGxIi3d)" class="zqss5obsp"/><path class="llp516bpm"/><path fill="url(#ioCT77d)" class="xn6dhjjio"/><path fill="url(#if8dKTc)" class="xn6dhjjio"/><path fill="url(#i77Ytid)" class="xn6dhjjio"/><path fill="url(#i8Zzivd)" class="kvfq7h_0m"/><path fill="url(#iE5Ofte)" class="kvfq7h_0m"/><path fill="url(#iE6iQae)" class="kvfq7h_0m"/><path fill="url(#i1B5pTu)" class="biuac8r4x"/><path fill="url(#iJIw8ya)" class="biuac8r4x"/><path fill="url(#iwZFu8W)" class="dvr2s59yl"/><path fill="url(#iP7E3xc)" class="dvr2s59yl"/><path fill="url(#idlbkMe)" class="sp6_o9bxd"/><path fill="url(#iIvEVud)" class="sp6_o9bxd"/><path fill="url(#iXRw9pd)" class="sp6_o9bxd"/><path fill="url(#iz9xh1o)" class="sp6_o9bxd"/><path fill="url(#ixge7fe)" class="sp6_o9bxd"/><g filter="url(#iuaEXte)"><path fill="url(#i1uMIud)" class="lwc2zdrqr"/></g><g filter="url(#iysqGsc)"><path fill="url(#iPXFJHe)" class="momee7bch"/></g><g filter="url(#iXJBFZb)"><path class="hv4xcjbfa"/></g><g filter="url(#iTodnEe)"><path class="vcv8c754j"/><path fill="url(#iU8Jczd)" class="u1e8ikbzb"/><path fill="url(#ibXRrGc)" class="u1e8ikbzb"/><path fill="url(#i9sxEsb)" class="u1e8ikbzb"/></g><g filter="url(#iqZGnDd)"><path class="z5g21op2e"/></g><g filter="url(#iSek3Bd)"><path fill="url(#iBVZlGV)" class="pimvl5kot"/><path fill="url(#i5oGPfb)" class="pimvl5kot"/><path fill="url(#ioQSTVd)" class="pimvl5kot"/><path fill="url(#iqH81bx)" class="pimvl5kot"/><path fill="url(#i4TNoOd)" class="pimvl5kot"/></g><g filter="url(#i6jrj8d)"><path stroke="url(#icCtmNd)" class="cjq4b16bn"/></g><g filter="url(#i8AX0gV)"><path stroke="url(#i8rhfrd)" class="luyfkt2yj"/></g><g filter="url(#iEL8kVy)"><path stroke="url(#ic9kcre)" class="eqaszhbhb"/></g><path fill="url(#ijuJNhe)" class="an9lfrbqg"/><path fill="url(#iNf0NTb)" class="kpgj139iy"/><path fill="url(#iLm9Wib)" class="d1nqo1ozq"/><path fill="url(#iVYRS4b)" class="gbm0j7buv"/><g filter="url(#i5GM9HU)"><path fill="url(#iggfluc)" class="q8910qc9y"/><path fill="url(#ii4KVPd)" class="q8910qc9y"/></g><path fill="url(#ignW0sb)" class="q8910qc9y"/><path fill="url(#iDHlVad)" class="q8910qc9y"/><path fill="url(#iTg1Bne)" class="q8910qc9y"/><path fill="url(#ix5nY8c)" class="q8910qc9y"/><path fill="url(#i21jUjc)" class="q8910qc9y"/><path fill="url(#iIMd45c)" class="q8910qc9y"/><path fill="url(#iPqkbgb)" class="q8910qc9y"/><path fill="url(#inTmV8c)" class="q8910qc9y"/><g filter="url(#ienaCmj)"><path class="k48h9jq7n"/></g><g filter="url(#i0IESgc)"><path class="bl8avbcrx"/><path fill="url(#ivsM9Qb)" class="pl8yez_4c"/><path fill="url(#i1s0Vjz)" class="pl8yez_4c"/><path fill="url(#iq93zdb)" class="pl8yez_4c"/><path fill="url(#iH4duxe)" class="pl8yez_4c"/><path fill="url(#iuwo1Ic)" class="pl8yez_4c"/></g><g filter="url(#iMLAZsM)"><path stroke="url(#iB1E5Xc)" class="bnz0cu8sy"/></g><path fill="url(#iKIv8zb)" class="nmn3kcc9t"/><g filter="url(#i0oRrAc)"><path class="l0m9-xrem"/></g><g filter="url(#iM5CvAd)"><path class="g7fwrrnhw"/></g><path class="z2i69vhci"/><path fill="url(#ieh8BZc)" class="a6zw9sbfb"/><path class="t4zox_b8l"/><g filter="url(#iwGxZSd)"><path class="jsu2z0bfz"/><path fill="url(#i5Zd0MZ)" class="w63ac8ldj"/></g><g filter="url(#iqrBYCb)"><path fill="url(#iieRoec)" class="hhwr7-ozw"/></g><path class="g1lr41sok"/><path fill="url(#ioPdWie)" class="a1bm_7bxi"/><path class="i9dyq3bii"/><g filter="url(#iDbkqlA)"><path fill="url(#ibjYmcP)" class="y7cstgbaj"/></g><g filter="url(#ifWH1Vc)"><ellipse transform="rotate(-27.914 13.2 9.668)" class="xwhv343ph"/><ellipse fill="url(#iKFv6Pe)" transform="rotate(-27.914 13.2 9.668)" class="x8h5m09gp"/></g><path fill="url(#ilKFOye)" class="lxinqpbky"/><path fill="url(#isVxKKe)" class="lxinqpbky"/><path fill="url(#iSjrD7o)" class="lxinqpbky"/><path fill="url(#iq8sbgG)" class="lxinqpbky"/><path fill="url(#ihqDS2c)" class="yga9n3beu"/><path fill="url(#iAmVdXH)" class="yga9n3beu"/><g filter="url(#idJwV5c)"><path fill="url(#iyakJQd)" class="u3w_lm5rg"/></g><g filter="url(#iUKIlKc)"><path fill="url(#iWnsyse)" class="lu6dbhl8o"/></g><g filter="url(#iD4UPub)"><path class="ogijq9bup"/></g><g filter="url(#iWBaVve)"><path class="e60pjifpz"/></g><g filter="url(#iSLuPPb)"><path fill="url(#i0vaKQd)" class="s2-xryl0i"/></g><g filter="url(#iYbajWd)"><path fill="url(#iIvrIye)" class="psv7auxid"/></g><defs><radialGradient id="iGxIi3d" cx="0" cy="0" r="1" gradientTransform="rotate(131.119 3.397 11.463)scale(2.81867 4.68292)" gradientUnits="userSpaceOnUse"><stop offset=".203" class="qunsngokg"/><stop offset="1" class="zsyglhsdv"/></radialGradient><radialGradient id="i77Ytid" cx="0" cy="0" r="1" gradientTransform="rotate(123.951 4.148 12.705)scale(2.98327 2.1547)" gradientUnits="userSpaceOnUse"><stop class="f7vxzf2re"/><stop offset="1" class="bjz-35bmd"/></radialGradient><radialGradient id="i8Zzivd" cx="0" cy="0" r="1" gradientTransform="matrix(2.70871 0 0 14.0625 6.066 30)" gradientUnits="userSpaceOnUse"><stop class="g21-8bc8z"/><stop offset="1" class="uhp0yeb2h"/></radialGradient><radialGradient id="iE5Ofte" cx="0" cy="0" r="1" gradientTransform="matrix(-2.2813 6.68749 -5.49369 -1.87406 9.223 17.781)" gradientUnits="userSpaceOnUse"><stop class="ghamttb0q"/><stop offset="1" class="z1an05bwi"/></radialGradient><radialGradient id="iE6iQae" cx="0" cy="0" r="1" gradientTransform="matrix(0 -13.2187 2.59375 0 9.223 30.438)" gradientUnits="userSpaceOnUse"><stop offset=".168" class="z8optlbcz"/><stop offset="1" class="gmjyv1b7b"/></radialGradient><radialGradient id="iJIw8ya" cx="0" cy="0" r="1" gradientTransform="matrix(0 7.3125 -1.98 0 24.755 21.938)" gradientUnits="userSpaceOnUse"><stop offset=".329" class="cbe6sn2ns"/><stop offset="1" class="gvyr5190s"/></radialGradient><radialGradient id="iwZFu8W" cx="0" cy="0" r="1" gradientTransform="rotate(140.585 9.368 16.757)scale(2.13884 2.10129)" gradientUnits="userSpaceOnUse"><stop offset=".464" class="kieesbm_x"/><stop offset="1" class="w58utkb1j"/></radialGradient><radialGradient id="iP7E3xc" cx="0" cy="0" r="1" gradientTransform="matrix(.78818 -.60013 .3134 .41161 27.001 23.598)" gradientUnits="userSpaceOnUse"><stop offset=".132" class="hmj-ymbzq"/><stop offset="1" class="ekxsm__ep"/></radialGradient><radialGradient id="idlbkMe" cx="0" cy="0" r="1" gradientTransform="matrix(0 -12.1153 44.4939 0 15.79 29.983)" gradientUnits="userSpaceOnUse"><stop offset=".077" class="s8-qpgb5g"/><stop offset="1" class="o5bua8boy"/></radialGradient><radialGradient id="iIvEVud" cx="0" cy="0" r="1" gradientTransform="matrix(0 -8.875 5.37793 0 22.464 32.545)" gradientUnits="userSpaceOnUse"><stop class="zwo8xvbzg"/><stop offset="1" class="c-tzwtb6q"/></radialGradient><radialGradient id="ixge7fe" cx="0" cy="0" r="1" gradientTransform="matrix(-3.59908 3.3973 -1.77851 -1.88415 10.554 15.318)" gradientUnits="userSpaceOnUse"><stop class="hfyjss5uq"/><stop offset="1" class="y9jato2vd"/></radialGradient><radialGradient id="ibXRrGc" cx="0" cy="0" r="1" gradientTransform="matrix(1.26563 -2.32812 2.70524 1.47064 23.707 20.906)" gradientUnits="userSpaceOnUse"><stop class="tdvgs2sbs"/><stop offset="1" class="tz6f6rbmx"/></radialGradient><radialGradient id="i9sxEsb" cx="0" cy="0" r="1" gradientTransform="rotate(53.424 -5.116 34.838)scale(2.25697 2.46612)" gradientUnits="userSpaceOnUse"><stop class="sf2388bnl"/><stop offset="1" class="ganm9fbbs"/></radialGradient><radialGradient id="i5oGPfb" cx="0" cy="0" r="1" gradientTransform="matrix(0 .8017 -1.35439 0 25.364 25.305)" gradientUnits="userSpaceOnUse"><stop offset=".106" class="r0i0_6b9f"/><stop offset="1" class="dcb4tlblp"/></radialGradient><radialGradient id="ioQSTVd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .85938 -1.45182 0 25.364 26.6)" gradientUnits="userSpaceOnUse"><stop offset=".109" class="r0i0_6b9f"/><stop offset="1" class="dcb4tlblp"/></radialGradient><radialGradient id="iqH81bx" cx="0" cy="0" r="1" gradientTransform="matrix(0 .71875 -1.21425 0 25.364 27.85)" gradientUnits="userSpaceOnUse"><stop offset=".109" class="r0i0_6b9f"/><stop offset="1" class="dcb4tlblp"/></radialGradient><radialGradient id="i4TNoOd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .79938 -1.7273 0 25.364 29.2)" gradientUnits="userSpaceOnUse"><stop offset=".186" class="r0i0_6b9f"/><stop offset="1" class="dcb4tlblp"/></radialGradient><radialGradient id="iLm9Wib" cx="0" cy="0" r="1" gradientTransform="matrix(.76433 2.06149 -2.44889 .90797 20.557 11.662)" gradientUnits="userSpaceOnUse"><stop offset=".215" class="rra4r9bnq"/><stop offset="1" class="pft2s7y0a"/></radialGradient><radialGradient id="iVYRS4b" cx="0" cy="0" r="1" gradientTransform="rotate(17.447 -34.87 37.11)scale(1.57981 4.87383)" gradientUnits="userSpaceOnUse"><stop class="gg1n47rtb"/><stop offset=".746" class="q53v6mhsp"/></radialGradient><radialGradient id="iggfluc" cx="0" cy="0" r="1" gradientTransform="matrix(-5.37627 0 0 -9.44013 18.596 10.7)" gradientUnits="userSpaceOnUse"><stop class="e4t6-lb6y"/><stop offset="1" class="hhi9hubjb"/><stop offset="1" class="hhi9hubjb"/></radialGradient><radialGradient id="ii4KVPd" cx="0" cy="0" r="1" gradientTransform="rotate(121.348 7.524 7.922)scale(3.44585 2.85461)" gradientUnits="userSpaceOnUse"><stop offset=".078" class="fajfg00jo"/><stop offset="1" class="wpa_x2uhd"/></radialGradient><radialGradient id="iDHlVad" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.1722 1.46143 0 18.225 9.36)" gradientUnits="userSpaceOnUse"><stop offset=".325" class="o847wybrn"/><stop offset="1" class="z-0dlhbai"/></radialGradient><radialGradient id="iTg1Bne" cx="0" cy="0" r="1" gradientTransform="rotate(-89.793 11.392 -1.991)scale(1.11702 1.22465)" gradientUnits="userSpaceOnUse"><stop offset=".378" class="pxeuj6buu"/><stop offset="1" class="lg98p_5je"/></radialGradient><radialGradient id="ix5nY8c" cx="0" cy="0" r="1" gradientTransform="matrix(-8.73718 .54755 -1.38845 -22.15514 19.238 11.71)" gradientUnits="userSpaceOnUse"><stop offset=".836" class="sim-rnb6d"/><stop offset="1" class="vx5g9qbgu"/></radialGradient><radialGradient id="i21jUjc" cx="0" cy="0" r="1" gradientTransform="matrix(3.4819 -2.97705 .87838 1.02734 8.724 7.911)" gradientUnits="userSpaceOnUse"><stop offset=".539" class="sf65_-b_u"/><stop offset="1" class="n9ebefe8q"/></radialGradient><radialGradient id="iIMd45c" cx="0" cy="0" r="1" gradientTransform="matrix(-.24132 2.54931 -1.02654 -.09717 21.41 7.723)" gradientUnits="userSpaceOnUse"><stop offset=".245" class="p54kb3bjj"/><stop offset="1" class="rm9y2hb6m"/></radialGradient><radialGradient id="iPqkbgb" cx="0" cy="0" r="1" gradientTransform="matrix(0 9.57877 -12.8698 0 15.756 8.049)" gradientUnits="userSpaceOnUse"><stop offset=".657" class="qoe9pbqhg"/><stop offset=".987" class="t4yt-y83y"/></radialGradient><radialGradient id="inTmV8c" cx="0" cy="0" r="1" gradientTransform="matrix(0 3.75296 -11.3113 0 15.756 6.55)" gradientUnits="userSpaceOnUse"><stop offset=".22" class="uo14aq7gq"/><stop offset="1" class="lxdipdb-v"/></radialGradient><radialGradient id="i1s0Vjz" cx="0" cy="0" r="1" gradientTransform="matrix(0 .24917 -.78312 0 16.18 12.09)" gradientUnits="userSpaceOnUse"><stop class="eqmylox_y"/><stop offset="1" class="sicchzd0u"/></radialGradient><radialGradient id="iH4duxe" cx="0" cy="0" r="1" gradientTransform="rotate(155.369 6.894 7.533)scale(1.70817 2.74517)" gradientUnits="userSpaceOnUse"><stop offset=".714" class="cjboikbop"/><stop offset="1" class="l6ffphqdg"/></radialGradient><radialGradient id="iKIv8zb" cx="0" cy="0" r="1" gradientTransform="matrix(2.2273 -1.095 4.40549 8.96103 15.204 14.4)" gradientUnits="userSpaceOnUse"><stop offset=".562" class="etju2kb3q"/><stop offset="1" class="iazz9lb4s"/></radialGradient><radialGradient id="ieh8BZc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .82817 -1.3173 0 17.932 9.766)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="bbyb_mbsk"/></radialGradient><radialGradient id="i5Zd0MZ" cx="0" cy="0" r="1" gradientTransform="matrix(-.23674 -.30507 .42 -.32593 17.7 9.852)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="ioPdWie" cx="0" cy="0" r="1" gradientTransform="matrix(0 .82822 -1.31737 0 13.477 9.766)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="bbyb_mbsk"/></radialGradient><radialGradient id="iKFv6Pe" cx="0" cy="0" r="1" gradientTransform="matrix(-.0079 -.50435 .60625 -.0095 13.185 9.99)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="isVxKKe" cx="0" cy="0" r="1" gradientTransform="matrix(.6416 2.28987 -2.18472 .61214 20.418 9.78)" gradientUnits="userSpaceOnUse"><stop offset=".856" class="xron-kbnx"/><stop offset="1" class="bzyp_ibbo"/></radialGradient><radialGradient id="iSjrD7o" cx="0" cy="0" r="1" gradientTransform="matrix(.80415 -1.10356 .925 .67403 20.786 10.336)" gradientUnits="userSpaceOnUse"><stop offset=".664" class="w_o-5kbak"/><stop offset="1" class="mb4bnzbbk"/></radialGradient><radialGradient id="iq8sbgG" cx="0" cy="0" r="1" gradientTransform="matrix(.5992 -1.58263 2.1146 .8006 20.903 10.512)" gradientUnits="userSpaceOnUse"><stop offset=".803" class="sxoyafbbn"/><stop offset="1" class="tri7bg95c"/></radialGradient><radialGradient id="iAmVdXH" cx="0" cy="0" r="1" gradientTransform="matrix(-1.6927 0 0 -1.88734 10.687 10.437)" gradientUnits="userSpaceOnUse"><stop offset=".778" class="srn41o2oz"/><stop offset="1" class="dfc36bbxx"/></radialGradient><radialGradient id="iyakJQd" cx="0" cy="0" r="1" gradientTransform="matrix(-.93552 .16058 -.16465 -.9592 10.737 10.437)" gradientUnits="userSpaceOnUse"><stop class="m_eaw6bxg"/><stop offset="1" class="nk_trfbso"/></radialGradient><radialGradient id="i0vaKQd" cx="0" cy="0" r="1" gradientTransform="rotate(-158.919 10.694 2.553)scale(8.7748 8.41903)" gradientUnits="userSpaceOnUse"><stop offset=".207" class="iodgi0b6i"/><stop offset="1" class="xh-hzrtoi"/></radialGradient><radialGradient id="iIvrIye" cx="0" cy="0" r="1" gradientTransform="rotate(139.529 8.817 5.504)scale(8.95518 9.18704)" gradientUnits="userSpaceOnUse"><stop class="pvjcf1omm"/><stop offset=".682" class="o2y-twbma"/><stop offset="1" class="x2409oaqt"/></radialGradient><linearGradient id="im0wb4T" x1="12.035" x2="21.723" y1="23.156" y2="18.344" gradientUnits="userSpaceOnUse"><stop class="d__di5b1k"/><stop offset="1" class="ldn_ouzqy"/></linearGradient><linearGradient id="i4RHwye" x1="14.633" x2="13.974" y1="19.957" y2="19.239" gradientUnits="userSpaceOnUse"><stop class="ptx8-dg4d"/><stop offset="1" class="m1cydckkt"/></linearGradient><linearGradient id="i86fP2c" x1="11.699" x2="12.504" y1="18.875" y2="18.875" gradientUnits="userSpaceOnUse"><stop class="a969r93lb"/><stop offset="1" class="zsyglhsdv"/></linearGradient><linearGradient id="ioCT77d" x1="19.938" x2="18.313" y1="19.527" y2="19.527" gradientUnits="userSpaceOnUse"><stop class="z9cu3vbra"/><stop offset="1" class="ul2cu2h0c"/></linearGradient><linearGradient id="if8dKTc" x1="17" x2="17.938" y1="20.105" y2="19.027" gradientUnits="userSpaceOnUse"><stop class="h5mxx_cud"/><stop offset="1" class="c5x-f3bwv"/></linearGradient><linearGradient id="i1B5pTu" x1="23.473" x2="23.473" y1="29.782" y2="23.532" gradientUnits="userSpaceOnUse"><stop class="unsdl8pjp"/><stop offset="1" class="r0l64jbzx"/></linearGradient><linearGradient id="iXRw9pd" x1="8.441" x2="9.059" y1="29.973" y2="29.953" gradientUnits="userSpaceOnUse"><stop offset=".203" class="t2xb9pb8a"/><stop offset="1" class="oh9185bnq"/></linearGradient><linearGradient id="iz9xh1o" x1="23.232" x2="22.627" y1="30" y2="30" gradientUnits="userSpaceOnUse"><stop class="hwgxlbc5v"/><stop offset="1" class="z4q6dwvkw"/></linearGradient><linearGradient id="i1uMIud" x1="12.43" x2="12.43" y1="23.95" y2="27.53" gradientUnits="userSpaceOnUse"><stop class="qcmtsylcx"/><stop offset="1" class="o7pw9mb8f"/></linearGradient><linearGradient id="iPXFJHe" x1="12.43" x2="12.43" y1="24.45" y2="27.03" gradientUnits="userSpaceOnUse"><stop class="d337rwvie"/><stop offset=".752" class="n5xzb8_yo"/></linearGradient><linearGradient id="iU8Jczd" x1="25.191" x2="23.16" y1="21.906" y2="21.906" gradientUnits="userSpaceOnUse"><stop class="oj6on8fvq"/><stop offset="1" class="fxowcsv6r"/></linearGradient><linearGradient id="iBVZlGV" x1="26.955" x2="22.927" y1="28.063" y2="28.063" gradientUnits="userSpaceOnUse"><stop offset=".146" class="pxu01k21v"/><stop offset=".861" class="fusa66-jk"/></linearGradient><linearGradient id="icCtmNd" x1="23.503" x2="25.212" y1="26.07" y2="26.07" gradientUnits="userSpaceOnUse"><stop class="lf8a5e78i"/><stop offset="1" class="ar7lpj8pp"/></linearGradient><linearGradient id="i8rhfrd" x1="23.425" x2="25.134" y1="27.375" y2="27.375" gradientUnits="userSpaceOnUse"><stop class="lf8a5e78i"/><stop offset="1" class="ar7lpj8pp"/></linearGradient><linearGradient id="ic9kcre" x1="23.503" x2="25.212" y1="28.68" y2="28.68" gradientUnits="userSpaceOnUse"><stop class="lf8a5e78i"/><stop offset="1" class="ar7lpj8pp"/></linearGradient><linearGradient id="ijuJNhe" x1="10.427" x2="10.427" y1="7.621" y2="9.757" gradientUnits="userSpaceOnUse"><stop class="qi731gbjb"/><stop offset="1" class="zmama0ttw"/></linearGradient><linearGradient id="iNf0NTb" x1="20.983" x2="20.983" y1="7.446" y2="9.041" gradientUnits="userSpaceOnUse"><stop class="ty8nzq04x"/><stop offset="1" class="uf4kgmbxa"/></linearGradient><linearGradient id="ignW0sb" x1="21.012" x2="18.411" y1="12.421" y2="12.421" gradientUnits="userSpaceOnUse"><stop class="agilw2byy"/><stop offset="1" class="h3kh2yb2k"/></linearGradient><linearGradient id="ivsM9Qb" x1="16.561" x2="15.705" y1="11.39" y2="11.425" gradientUnits="userSpaceOnUse"><stop offset=".36" class="eqmylox_y"/><stop offset="1" class="sicchzd0u"/></linearGradient><linearGradient id="iq93zdb" x1="15.705" x2="15.705" y1="12.553" y2="12.078" gradientUnits="userSpaceOnUse"><stop class="qsncw6btn"/><stop offset="1" class="v7xhdx32s"/></linearGradient><linearGradient id="iuwo1Ic" x1="15.705" x2="15.705" y1="9.72" y2="10.748" gradientUnits="userSpaceOnUse"><stop class="arngw003p"/><stop offset="1" class="enihb_bho"/></linearGradient><linearGradient id="iB1E5Xc" x1="14.478" x2="14.803" y1="14.156" y2="13.304" gradientUnits="userSpaceOnUse"><stop class="t_m5csgaz"/><stop offset="1" class="ln8xouyxx"/></linearGradient><linearGradient id="iieRoec" x1="18.726" x2="18.406" y1="9.821" y2="10.018" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="ibjYmcP" x1="14.237" x2="13.917" y1="9.821" y2="10.018" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="ilKFOye" x1="22.275" x2="21.043" y1="9.848" y2="12.07" gradientUnits="userSpaceOnUse"><stop class="pkjt6qfem"/><stop offset="1" class="qw3t0fbxr"/></linearGradient><linearGradient id="ihqDS2c" x1="9.734" x2="11.222" y1="10.569" y2="10.439" gradientUnits="userSpaceOnUse"><stop class="lsjj5yb-k"/><stop offset="1" class="ac3zxpbrp"/></linearGradient><linearGradient id="iWnsyse" x1="21.253" x2="21.253" y1="9.462" y2="11.405" gradientUnits="userSpaceOnUse"><stop class="x9ttejxmc"/><stop offset="1" class="nal-rljch"/></linearGradient><filter id="iHB2K8b" width="9.938" height="8.021" x="10.364" y="15" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1950" stdDeviation=".5"/></filter><filter id="iuaEXte" width="5.33" height="3.88" x="9.765" y="23.9" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".1"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.188235 0 0 0 0 0.384314 0 0 0 0 0.823529 0 0 0 1 0"/><feBlend in2="BackgroundImageFix" result="effect1_dropShadow_4002_1950"/><feBlend in="SourceGraphic" in2="effect1_dropShadow_4002_1950" result="shape"/></filter><filter id="iysqGsc" width="4.03" height="2.58" x="10.415" y="24.45" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.882353 0 0 0 0 0.807843 0 0 0 0 0.929412 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1950"/></filter><filter id="iXJBFZb" width="3.922" height="2.04" x="13.799" y="16.636" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.368627 0 0 0 0 0.192157 0 0 0 0 0.180392 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1950"/></filter><filter id="iTodnEe" width="5.15" height="12.15" x="22.255" y="16.85" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.15"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.490196 0 0 0 0 0.384314 0 0 0 0 0.611765 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1950"/></filter><filter id="iqZGnDd" width="2.08" height="4.962" x="24.105" y="21.001" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1950" stdDeviation=".325"/></filter><filter id="iSek3Bd" width="4.468" height="5.556" x="22.927" y="24.444" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.15"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.341176 0 0 0 0 0.211765 0 0 0 0 0.219608 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1950"/></filter><filter id="i6jrj8d" width="2.097" height=".3" x="23.353" y="25.842" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1950" stdDeviation=".05"/></filter><filter id="i8AX0gV" width="2.097" height=".3" x="23.275" y="27.147" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1950" stdDeviation=".05"/></filter><filter id="iEL8kVy" width="2.097" height=".3" x="23.353" y="28.451" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1950" stdDeviation=".05"/></filter><filter id="i5GM9HU" width="11.511" height="12.798" x="10.501" y="4.402" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1"/><feGaussianBlur stdDeviation=".7"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.494118 0 0 0 0 0.352941 0 0 0 0 0.32549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1950"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".2"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.396078 0 0 0 0 0.215686 0 0 0 0 0.215686 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1950" result="effect2_innerShadow_4002_1950"/></filter><filter id="ienaCmj" width="3.916" height="4.96" x="13.535" y="8.859" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1950" stdDeviation=".5"/></filter><filter id="i0IESgc" width="2.316" height="3.36" x="14.547" y="9.46" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1950" stdDeviation=".1"/></filter><filter id="iMLAZsM" width="3.785" height="1.595" x="13.812" y="13.054" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1950" stdDeviation=".05"/></filter><filter id="i0oRrAc" width="2.385" height="1.211" x="17.327" y="7.215" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0588235 0 0 0 0 0.054902 0 0 0 0 0.0588235 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1950"/></filter><filter id="iM5CvAd" width="2.385" height="1.196" x="11.961" y="7.222" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0588235 0 0 0 0 0.054902 0 0 0 0 0.0588235 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1950"/></filter><filter id="iwGxZSd" width=".799" height=".707" x="17.185" y="9.319" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1950" stdDeviation=".05"/></filter><filter id="iqrBYCb" width=".901" height=".924" x="18.044" y="9.398" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1950" stdDeviation=".1"/></filter><filter id="iDbkqlA" width=".999" height="1.054" x="13.509" y="9.333" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1950" stdDeviation=".1"/></filter><filter id="ifWH1Vc" width=".928" height=".715" x="12.737" y="9.31" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1950" stdDeviation=".05"/></filter><filter id="idJwV5c" width="1.346" height="2.418" x="9.552" y="9.229" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1950" stdDeviation=".125"/></filter><filter id="iUKIlKc" width="1.966" height="2.943" x="20.27" y="8.962" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1950" stdDeviation=".25"/></filter><filter id="iD4UPub" width="2.44" height="1.169" x="11.886" y="7.302" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1950" stdDeviation=".125"/></filter><filter id="iWBaVve" width="2.44" height="1.178" x="17.275" y="7.254" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1950" stdDeviation=".125"/></filter><filter id="iSLuPPb" width="11.17" height="3.114" x="10.155" y="5.342" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.254902 0 0 0 0 0.560784 0 0 0 0 0.972549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1950"/></filter><filter id="iYbajWd" width="11.355" height="5.77" x="10.062" y="1.8" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.12549 0 0 0 0 0.431373 0 0 0 0 0.721569 0 0 0 0.5 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1950"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:mechanic-medium-dark" /></template>
<style>
.a1bm_7bxi {
  d: path("M13.475 9.279a.91.91 0 0 0-.877 1.151h1.76a1 1 0 0 0 .033-.24a.917.917 0 0 0-.916-.911");
}

.a6zw9sbfb {
  d: path("M17.934 9.279a.91.91 0 0 1 .878 1.151h-1.76a.915.915 0 0 1 .882-1.151");
}

.a969r93lb {
  stop-color: var(--svg-color--d3c8dc, #D3C8DC);
}

.ac3zxpbrp {
  stop-color: var(--svg-color--623549, #623549);
}

.agilw2byy {
  stop-color: var(--svg-color--936b5d, #936B5D);
}

.an9lfrbqg {
  d: path("M10.183 7.095h.733v2.662h-.98z");
}

.ar7lpj8pp {
  stop-color: var(--svg-color--7a4b42, #7A4B42);
  stop-opacity: 0;
}

.arngw003p {
  stop-color: var(--svg-color--754e54, #754E54);
}

.bbyb_mbsk {
  stop-color: var(--svg-color--664842, #664842);
}

.biuac8r4x {
  d: path("M22.775 18.043V30h2.979l.981-3.5c0-3.401-1.54-6.44-3.96-8.457");
}

.bjz-35bmd {
  stop-color: var(--svg-color--d6cbdf, #D6CBDF);
  stop-opacity: 0;
}

.bl8avbcrx {
  fill: var(--svg-color--845b55, #845B55);
  d: path("m15.315 9.971l-.543 1.877c-.11.386.155.772.531.772h.803c.377 0 .642-.392.532-.772l-.543-1.877c-.116-.415-.659-.415-.78 0");
}

.bnz0cu8sy {
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M14.325 13.256c.398.207.873.327 1.38.327c.511 0 .981-.12 1.38-.327a.23.23 0 0 1 .275.045c.065.068.09.177.024.276m-3.059-.321l2.996.28m-2.996-.28a.23.23 0 0 0-.275.047a.215.215 0 0 0-.024.275m.3-.322l-.237.28m3.295.041l-.063-.041m.063.041l-.063-.041m.063.041a2.01 2.01 0 0 1-1.68.897a2.01 2.01 0 0 1-1.678-.896m3.295-.042a1.93 1.93 0 0 1-1.616.863a1.93 1.93 0 0 1-1.616-.863m-.063.042l.063-.042m-.063.042v-.001l.063-.041");
}

.bzyp_ibbo {
  stop-color: var(--svg-color--71404f, #71404F);
}

.c-tzwtb6q {
  stop-color: var(--svg-color--345cbf, #345CBF);
  stop-opacity: 0;
}

.c5x-f3bwv {
  stop-color: var(--svg-color--ffe4f7, #FFE4F7);
  stop-opacity: 0;
}

.cbe6sn2ns {
  stop-color: var(--svg-color--d2c9de, #D2C9DE);
}

.cjboikbop {
  stop-color: var(--svg-color--744a4a, #744A4A);
  stop-opacity: 0;
}

.cjq4b16bn {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M23.503 25.992H25.3");
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.d__di5b1k {
  stop-color: var(--svg-color--d2c4ec, #D2C4EC);
}

.d1nqo1ozq {
  d: path("M20.667 11.977a1.67 1.67 0 0 0 .923-.315v.95c0 .912-.543 1.724-1.368 2.061q.262-.556.353-1.204z");
}

.d337rwvie {
  stop-color: var(--svg-color--e0ccf0, #E0CCF0);
}

.dcb4tlblp {
  stop-color: var(--svg-color--986e66, #986E66);
  stop-opacity: 0;
}

.dfc36bbxx {
  stop-color: var(--svg-color--836158, #836158);
}

.dvr2s59yl {
  d: path("M26.245 23.1c.55 0 1 .45 1 1v2.29h-2V24.1c0-.55.45-1 1-1");
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.e4t6-lb6y {
  stop-color: var(--svg-color--9a6e61, #9A6E61);
}

.e60pjifpz {
  stroke: var(--svg-color--353535, #353535);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M19.34 8.056c-.288-.303-.916-.519-1.69-.389");
}

.ekxsm__ep {
  stop-color: var(--svg-color--93776e, #93776E);
  stop-opacity: 0;
}

.enihb_bho {
  stop-color: var(--svg-color--754e54, #754E54);
  stop-opacity: 0;
}

.eqaszhbhb {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M23.503 28.602H25.3");
}

.eqmylox_y {
  stop-color: var(--svg-color--a17c72, #A17C72);
}

.etju2kb3q {
  stop-color: var(--svg-color--87004e, #87004E);
}

.f7vxzf2re {
  stop-color: var(--svg-color--8e7f98, #8E7F98);
}

.fajfg00jo {
  stop-color: var(--svg-color--855e5a, #855E5A);
}

.ft5dv1b6b {
  fill: none;
}

.fusa66-jk {
  stop-color: var(--svg-color--704b4b, #704B4B);
}

.fxowcsv6r {
  stop-color: var(--svg-color--847596, #847596);
}

.g1lr41sok {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.264 9.001c-.666 0-1.23.46-1.383 1.081a.28.28 0 0 0 .274.348h2.277a.235.235 0 0 0 .232-.277A1.43 1.43 0 0 0 13.264 9");
}

.g21-8bc8z {
  stop-color: var(--svg-color--c7acea, #C7ACEA);
}

.g7fwrrnhw {
  fill: var(--svg-color--202020, #202020);
  d: path("M12.223 7.81a2.83 2.83 0 0 1 1.775-.367a.283.283 0 0 1-.069.563a2.27 2.27 0 0 0-1.415.29a1 1 0 0 0-.094.061l-.003.002a.283.283 0 0 1-.346-.447z");
}

.ganm9fbbs {
  stop-color: var(--svg-color--bab5c6, #BAB5C6);
  stop-opacity: 0;
}

.gbm0j7buv {
  d: path("M10.743 11.977a1.67 1.67 0 0 1-.924-.315v.95c0 .912.543 1.724 1.369 2.061a4.2 4.2 0 0 1-.353-1.204z");
}

.gg1n47rtb {
  stop-color: var(--svg-color--463c39, #463C39);
}

.ghamttb0q {
  stop-color: var(--svg-color--99959a, #99959A);
}

.gmjyv1b7b {
  stop-color: var(--svg-color--aba1bb, #ABA1BB);
  stop-opacity: 0;
}

.gvyr5190s {
  stop-color: var(--svg-color--d2c9de, #D2C9DE);
  stop-opacity: 0;
}

.h3kh2yb2k {
  stop-color: var(--svg-color--936b5d, #936B5D);
  stop-opacity: 0;
}

.h5mxx_cud {
  stop-color: var(--svg-color--dbbaf9, #DBBAF9);
}

.hfyjss5uq {
  stop-color: var(--svg-color--3f8aad, #3F8AAD);
}

.hhi9hubjb {
  stop-color: var(--svg-color--754c4c, #754C4C);
}

.hhwr7-ozw {
  d: path("M18.746 10.07a.86.86 0 0 0-.236-.472l-.266.29l.12.234z");
}

.hmj-ymbzq {
  stop-color: var(--svg-color--93776e, #93776E);
}

.hv4xcjbfa {
  fill: var(--svg-color--7c4d5c, #7C4D5C);
  d: path("M15.71 18.676c-1.524-.508-1.825-1.445-1.91-1.84h3.921c-.356 1.237-1.494 1.738-2.012 1.84");
}

.hwgxlbc5v {
  stop-color: var(--svg-color--2b5fb7, #2B5FB7);
}

.i9dyq3bii {
  fill: var(--svg-color--000, #000);
  d: path("M13.997 10.19a.52.52 0 0 0-.522-.522a.52.52 0 0 0-.463.762h.923a.5.5 0 0 0 .062-.24");
}

.iazz9lb4s {
  stop-color: var(--svg-color--87004d, #87004D);
}

.iodgi0b6i {
  stop-color: var(--svg-color--47c4ff, #47C4FF);
}

.jsu2z0bfz {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M17.867 9.471c.065.087-.07.193-.225.308c-.154.116-.268.197-.333.11s.007-.25.162-.366c.154-.115.331-.138.396-.052");
}

.k48h9jq7n {
  fill: var(--svg-color--6f3f46, #6F3F46);
  d: path("m15.209 10.171l-.649 1.877c-.11.386.155.772.532.772h.803c.376 0 .642-.392.531-.772l-.542-1.877c-.117-.416-.554-.416-.675 0");
}

.kieesbm_x {
  stop-color: var(--svg-color--815f52, #815F52);
}

.kpgj139iy {
  d: path("m20.493 7.095l.784-.098l.196 2.76h-.98z");
}

.kvfq7h_0m {
  d: path("M8.775 30V17.99a10.98 10.98 0 0 0-4.03 8.51V30z");
}

.l0m9-xrem {
  fill: var(--svg-color--202020, #202020);
  d: path("M19.515 7.93a1.9 1.9 0 0 0-.701-.42c-.311-.098-.7-.124-1.238-.059a.283.283 0 1 0 .069.562c.49-.06.792-.029.999.037c.202.063.339.167.5.306a.283.283 0 0 0 .371-.427");
}

.l6ffphqdg {
  stop-color: var(--svg-color--744a4a, #744A4A);
}

.ldn_ouzqy {
  stop-color: var(--svg-color--c6c4d3, #C6C4D3);
}

.lf8a5e78i {
  stop-color: var(--svg-color--664139, #664139);
}

.lg98p_5je {
  stop-color: var(--svg-color--70424e, #70424E);
  stop-opacity: 0;
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.llp516bpm {
  fill: var(--svg-color--f4e6ff, #F4E6FF);
  d: path("M19.674 16.233v4.908c0 .433-.418.668-.813.379L15.74 18.8a.1.1 0 0 1-.034-.076v-1.322l1.7-1.776c.787.122 1.546.327 2.269.607");
}

.ln8xouyxx {
  stop-color: var(--svg-color--866163, #866163);
  stop-opacity: 0;
}

.lsjj5yb-k {
  stop-color: var(--svg-color--6a4544, #6A4544);
}

.lu6dbhl8o {
  d: path("M20.77 11.405q.06-.97.113-1.943a.975.975 0 0 1-.113 1.943");
}

.luyfkt2yj {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M23.425 27.297h1.797");
}

.lwc2zdrqr {
  d: path("M13.155 24.45c.71 0 1.29.58 1.29 1.29s-.58 1.29-1.29 1.29h-1.45c-.71 0-1.29-.58-1.29-1.29s.58-1.29 1.29-1.29zm0-.5h-1.45c-.99 0-1.79.8-1.79 1.79s.8 1.79 1.79 1.79h1.45c.99 0 1.79-.8 1.79-1.79s-.8-1.79-1.79-1.79");
}

.lxdipdb-v {
  stop-color: var(--svg-color--593652, #593652);
  stop-opacity: 0;
}

.lxinqpbky {
  d: path("M20.729 12.07q.102-1.63.188-3.258a1.643 1.643 0 0 1-.188 3.258");
}

.m_eaw6bxg {
  stop-color: var(--svg-color--57353c, #57353C);
}

.m1cydckkt {
  stop-color: var(--svg-color--e0c7fa, #E0C7FA);
  stop-opacity: 0;
}

.m1i1rlbvk {
  d: path("M15.745 15.5c-6.07 0-11 4.92-11 11V30h21.08l.91-3.5c0-6.08-4.92-11-10.99-11");
}

.m3se_ob2r {
  fill: var(--svg-color--eddffd, #EDDFFD);
  d: path("M11.736 16.236v4.905c0 .433.418.668.813.379l3.122-2.72a.1.1 0 0 0 .034-.076v-1.322l-1.699-1.775c-.787.123-1.547.329-2.27.61");
}

.mb4bnzbbk {
  stop-color: var(--svg-color--7c4c46, #7C4C46);
  stop-opacity: 0;
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.momee7bch {
  d: path("M13.155 27.03h-1.45c-.71 0-1.29-.58-1.29-1.29s.58-1.29 1.29-1.29h1.45c.71 0 1.29.58 1.29 1.29c0 .72-.57 1.29-1.29 1.29");
}

.n5xzb8_yo {
  stop-color: var(--svg-color--e0c6f6, #E0C6F6);
}

.n9ebefe8q {
  stop-color: var(--svg-color--4f2c2a, #4F2C2A);
  stop-opacity: 0;
}

.nal-rljch {
  stop-color: var(--svg-color--7d5449, #7D5449);
}

.nk_trfbso {
  stop-color: var(--svg-color--5b3336, #5B3336);
}

.nmn3kcc9t {
  d: path("M15.705 13.658a3.1 3.1 0 0 1-1.414-.336c-.14-.07-.29.087-.202.214a1.93 1.93 0 0 0 1.616.863c.678 0 1.274-.345 1.616-.863c.088-.132-.062-.285-.202-.214a3.05 3.05 0 0 1-1.414.336");
}

.o2y-twbma {
  stop-color: var(--svg-color--2780b8, #2780B8);
}

.o5bua8boy {
  stop-color: var(--svg-color--45c0ff, #45C0FF);
}

.o7pw9mb8f {
  stop-color: var(--svg-color--f03a62, #F03A62);
}

.o847wybrn {
  stop-color: var(--svg-color--875455, #875455);
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.ogijq9bup {
  stroke: var(--svg-color--353535, #353535);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M12.262 8.096c.262-.188.916-.52 1.69-.39");
}

.oh9185bnq {
  stop-color: var(--svg-color--2860c0, #2860C0);
  stop-opacity: 0;
}

.oj6on8fvq {
  stop-color: var(--svg-color--847596, #847596);
  stop-opacity: 0;
}

.p54kb3bjj {
  stop-color: var(--svg-color--98786d, #98786D);
}

.pft2s7y0a {
  stop-color: var(--svg-color--221c27, #221C27);
}

.pimvl5kot {
  d: path("M22.927 25.326a.73.73 0 0 1 .727-.732h2.39a1.2 1.2 0 0 1 1.2 1.2V29a1 1 0 0 1-1 1h-2.59a.731.731 0 0 1-.32-1.389a.735.735 0 0 1 0-1.314a.735.735 0 0 1 0-1.314a.74.74 0 0 1-.407-.657");
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pkjt6qfem {
  stop-color: var(--svg-color--9c7b71, #9C7B71);
}

.pl8yez_4c {
  d: path("m15.315 9.971l-.543 1.877c-.11.386.155.772.531.772h.803c.377 0 .642-.392.532-.772l-.543-1.877c-.116-.415-.659-.415-.78 0");
}

.psv7auxid {
  d: path("M16.795 2c1.44 0 2.82.43 3.73 1.51c.7.83 1.08 2.36.8 4.06c-.6-.57-1.21-.99-1.89-1.31a8.76 8.76 0 0 0-7.39 0c-.68.31-1.29.74-1.89 1.31c-.28-1.71.1-3.23.8-4.06c.91-1.08 2.29-1.51 3.73-1.51z");
}

.ptx8-dg4d {
  stop-color: var(--svg-color--e0c7fa, #E0C7FA);
}

.pvjcf1omm {
  stop-color: var(--svg-color--4fbfff, #4FBFFF);
}

.pxeuj6buu {
  stop-color: var(--svg-color--70424e, #70424E);
}

.pxu01k21v {
  stop-color: var(--svg-color--976c5f, #976C5F);
}

.q53v6mhsp {
  stop-color: var(--svg-color--1b141e, #1B141E);
}

.q8910qc9y {
  d: path("M10.78 13.523A4 4 0 0 0 14.746 17h1.926a4 4 0 0 0 3.966-3.477c.12-1.923.284-4.479.374-6.4c-.011-.783-.67-.788-1.45-.821h-1.43a2.47 2.47 0 0 1-2.257-1.473a.68.68 0 0 0-.628-.427h-1.3c-1.884 0-3.446.815-3.446 2.72c0 1.9.154 4.497.279 6.401");
}

.qcmtsylcx {
  stop-color: var(--svg-color--e73c75, #E73C75);
}

.qi731gbjb {
  stop-color: var(--svg-color--282121, #282121);
}

.qoe9pbqhg {
  stop-color: var(--svg-color--7e4d5c, #7E4D5C);
  stop-opacity: 0;
}

.qsncw6btn {
  stop-color: var(--svg-color--7d465b, #7D465B);
}

.qunsngokg {
  stop-color: var(--svg-color--7c6987, #7C6987);
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.qw3t0fbxr {
  stop-color: var(--svg-color--815758, #815758);
}

.r0i0_6b9f {
  stop-color: var(--svg-color--947068, #947068);
}

.r0l64jbzx {
  stop-color: var(--svg-color--b7a9c2, #B7A9C2);
}

.rm9y2hb6m {
  stop-color: var(--svg-color--98786d, #98786D);
  stop-opacity: 0;
}

.rra4r9bnq {
  stop-color: var(--svg-color--3c3b3c, #3C3B3C);
}

.s2-xryl0i {
  d: path("M12.045 6.26c-.68.31-1.29.74-1.89 1.31l.41.51c.31.38.85.49 1.28.25c.76-.42 2.11-.99 3.9-.99s3.14.57 3.9.99a1 1 0 0 0 1.27-.25l.41-.51c-.6-.57-1.21-.99-1.89-1.31a8.76 8.76 0 0 0-7.39 0");
}

.s8-qpgb5g {
  stop-color: var(--svg-color--3b71d9, #3B71D9);
}

.sf2388bnl {
  stop-color: var(--svg-color--bab5c6, #BAB5C6);
}

.sf65_-b_u {
  stop-color: var(--svg-color--4f2c2a, #4F2C2A);
}

.sicchzd0u {
  stop-color: var(--svg-color--a17c72, #A17C72);
  stop-opacity: 0;
}

.sim-rnb6d {
  stop-color: var(--svg-color--815f58, #815F58);
  stop-opacity: 0;
}

.sp6_o9bxd {
  d: path("M20.735 16.696v5.877c0 .23-.18.41-.41.41h-9.07c-.23 0-.41-.18-.41-.41v-5.92q-.21.102-.413.213a11 11 0 0 0-1.657 1.127V30h14.03V18.068a11 11 0 0 0-2.07-1.372");
}

.srn41o2oz {
  stop-color: var(--svg-color--836158, #836158);
  stop-opacity: 0;
}

.sxoyafbbn {
  stop-color: var(--svg-color--805d4c, #805D4C);
  stop-opacity: 0;
}

.t_m5csgaz {
  stop-color: var(--svg-color--866163, #866163);
}

.t2xb9pb8a {
  stop-color: var(--svg-color--2860c0, #2860C0);
}

.t4yt-y83y {
  stop-color: var(--svg-color--7f4070, #7F4070);
}

.t4zox_b8l {
  fill: var(--svg-color--000, #000);
  d: path("M17.413 10.19a.52.52 0 0 1 .521-.522a.52.52 0 0 1 .464.762h-.923a.5.5 0 0 1-.062-.24");
}

.tdvgs2sbs {
  stop-color: var(--svg-color--9872bb, #9872BB);
}

.tri7bg95c {
  stop-color: var(--svg-color--805d4c, #805D4C);
}

.ty8nzq04x {
  stop-color: var(--svg-color--373032, #373032);
}

.tz6f6rbmx {
  stop-color: var(--svg-color--9872bb, #9872BB);
  stop-opacity: 0;
}

.u1e8ikbzb {
  d: path("M25.93 17.043c-.191-.1-.432.03-.432.25v1.551c0 .42-.341.77-.763.76a.746.746 0 0 1-.733-.75v-1.561c0-.22-.24-.36-.432-.26a2.48 2.48 0 0 0-1.315 2.171c-.01.97.552 1.821 1.366 2.241c.09.05.15.15.15.25V28a1.005 1.005 0 0 0 2.008.001v-6.324c0-.1.06-.2.15-.25a2.49 2.49 0 0 0 1.326-2.202a2.52 2.52 0 0 0-1.325-2.181");
}

.u3w_lm5rg {
  d: path("M10.563 9.479a.976.976 0 0 0 .085 1.918a80 80 0 0 1-.085-1.918");
}

.u7j5qywzc {
  fill: var(--svg-color--b1a1bf, #B1A1BF);
  d: path("M19.301 21.515v-4.908A11 11 0 0 0 17.033 16l-1.7 1.776l-1.7-1.775c-.787.123-1.546.329-2.27.609v4.905c0 .433.419.668.813.379l3.122-2.72a.1.1 0 0 0 .034-.076a.1.1 0 0 0 .035.076l3.122 2.72c.394.289.812.054.812-.38");
}

.uf4kgmbxa {
  stop-color: var(--svg-color--271d21, #271D21);
}

.uhp0yeb2h {
  stop-color: var(--svg-color--c6b9db, #C6B9DB);
}

.ul2cu2h0c {
  stop-color: var(--svg-color--f0e1ff, #F0E1FF);
  stop-opacity: 0;
}

.unsdl8pjp {
  stop-color: var(--svg-color--9b80b4, #9B80B4);
}

.uo14aq7gq {
  stop-color: var(--svg-color--593652, #593652);
}

.v7xhdx32s {
  stop-color: var(--svg-color--7d465b, #7D465B);
  stop-opacity: 0;
}

.vcv8c754j {
  fill: var(--svg-color--9e88ad, #9E88AD);
  d: path("M25.93 17.043c-.191-.1-.432.03-.432.25v1.551c0 .42-.341.77-.763.76a.746.746 0 0 1-.733-.75v-1.561c0-.22-.24-.36-.432-.26a2.48 2.48 0 0 0-1.315 2.171c-.01.97.552 1.821 1.366 2.241c.09.05.15.15.15.25V28a1.005 1.005 0 0 0 2.008.001v-6.324c0-.1.06-.2.15-.25a2.49 2.49 0 0 0 1.326-2.202a2.52 2.52 0 0 0-1.325-2.181");
}

.vx5g9qbgu {
  stop-color: var(--svg-color--815f58, #815F58);
}

.w_o-5kbak {
  stop-color: var(--svg-color--7c4c46, #7C4C46);
}

.w58utkb1j {
  stop-color: var(--svg-color--643838, #643838);
}

.w63ac8ldj {
  d: path("M17.867 9.471c.065.087-.07.193-.225.308c-.154.116-.268.197-.333.11s.007-.25.162-.366c.154-.115.331-.138.396-.052");
}

.wpa_x2uhd {
  stop-color: var(--svg-color--855e5a, #855E5A);
  stop-opacity: 0;
}

.x2409oaqt {
  stop-color: var(--svg-color--3a69a2, #3A69A2);
}

.x8h5m09gp {
  cx: 13.201px;
  cy: 9.668px;
  rx: 0.398px;
  ry: 0.201px;
}

.x9ttejxmc {
  stop-color: var(--svg-color--825d56, #825D56);
}

.xh-hzrtoi {
  stop-color: var(--svg-color--2f83be, #2F83BE);
}

.xn6dhjjio {
  d: path("M19.674 16.233v4.908c0 .433-.418.668-.813.379L15.74 18.8a.1.1 0 0 1-.034-.076v-1.322l1.7-1.776c.787.122 1.546.327 2.269.607");
}

.xron-kbnx {
  stop-color: var(--svg-color--71404f, #71404F);
  stop-opacity: 0;
}

.xwhv343ph {
  cx: 13.201px;
  cy: 9.668px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.398px;
  ry: 0.201px;
}

.y7cstgbaj {
  d: path("M14.308 10.083c0-.295-.24-.491-.304-.55l-.295.284l.181.37z");
}

.y9jato2vd {
  stop-color: var(--svg-color--3f8aad, #3F8AAD);
  stop-opacity: 0;
}

.yga9n3beu {
  d: path("M10.546 8.804a1.643 1.643 0 0 0 .141 3.266a80 80 0 0 1-.141-3.266");
}

.z-0dlhbai {
  stop-color: var(--svg-color--875455, #875455);
  stop-opacity: 0;
}

.z1an05bwi {
  stop-color: var(--svg-color--99959a, #99959A);
  stop-opacity: 0;
}

.z2i69vhci {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.146 9.001c.666 0 1.23.46 1.383 1.081a.28.28 0 0 1-.274.348h-2.277a.235.235 0 0 1-.232-.277A1.43 1.43 0 0 1 18.146 9");
}

.z4q6dwvkw {
  stop-color: var(--svg-color--2b5fb7, #2B5FB7);
  stop-opacity: 0;
}

.z5g21op2e {
  fill: var(--svg-color--b3a4c6, #B3A4C6);
  d: path("M24.755 21.651h.78v3.662h-.78z");
}

.z8optlbcz {
  stop-color: var(--svg-color--9680b0, #9680B0);
}

.z9cu3vbra {
  stop-color: var(--svg-color--fff7ff, #FFF7FF);
}

.zmama0ttw {
  stop-color: var(--svg-color--46403d, #46403D);
}

.zqss5obsp {
  d: path("M11.736 16.236v4.905c0 .433.418.668.813.379l3.122-2.72a.1.1 0 0 0 .034-.076v-1.322l-1.699-1.775c-.787.123-1.547.329-2.27.61");
}

.zsyglhsdv {
  stop-color: var(--svg-color--eee0fe, #EEE0FE);
  stop-opacity: 0;
}

.zwo8xvbzg {
  stop-color: var(--svg-color--345cbf, #345CBF);
}

</style>
