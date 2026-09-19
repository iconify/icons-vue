<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iGSn8Dc)" clip-rule="evenodd" class="uylc3es2x"/><path fill="url(#iYin6db)" clip-rule="evenodd" class="uylc3es2x"/><g filter="url(#ipAvYzc)"><path stroke="url(#iZ8AUhe)" class="rfksyecjs"/></g><path fill="url(#ijf66ub)" clip-rule="evenodd" class="itisl1bsn"/><path fill="url(#itUwzHc)" clip-rule="evenodd" class="itisl1bsn"/><g filter="url(#ijBAgQc)"><path stroke="url(#i1I4aae)" class="pgkimacqn"/></g><path fill="url(#icmzFec)" clip-rule="evenodd" class="e314ej6ax"/><path fill="url(#iAf8Hpe)" clip-rule="evenodd" class="e314ej6ax"/><g filter="url(#iMtpBod)"><path stroke="url(#ixwriRw)" class="k3z32yv2o"/></g><path fill="url(#ik1sdFc)" clip-rule="evenodd" class="or_xa3b0i"/><path class="asc597bjx"/><path fill="url(#ix1QTlc)" class="r5wm-vlaj"/><path fill="url(#iJ6s1me)" class="r5wm-vlaj"/><path fill="url(#iYE41Zf)" class="r5wm-vlaj"/><path fill="url(#igXiHgc)" class="r5wm-vlaj"/><path fill="url(#iselgIc)" class="r5wm-vlaj"/><g filter="url(#iT5BW2d)"><path class="ypv5ckobw"/><path fill="url(#ixEuNeb)" class="itdn4bbbj"/></g><path fill="url(#iB98R1c)" clip-rule="evenodd" class="tghnx9bfm"/><path fill="url(#iFouQGe)" clip-rule="evenodd" class="tghnx9bfm"/><path fill="url(#idKcIze)" clip-rule="evenodd" class="tghnx9bfm"/><path fill="url(#iR2VAAb)" clip-rule="evenodd" class="tghnx9bfm"/><path fill="url(#iLE8Epb)" clip-rule="evenodd" class="a1_a0ybzq"/><path fill="url(#iVRG0wb)" clip-rule="evenodd" class="a1_a0ybzq"/><path fill="url(#iGPTVhC)" clip-rule="evenodd" class="a1_a0ybzq"/><path fill="url(#iu2tmcN)" clip-rule="evenodd" class="a1_a0ybzq"/><path fill="url(#iDJAbBe)" clip-rule="evenodd" class="ktv_vnokm"/><path fill="url(#iSSu21b)" clip-rule="evenodd" class="ktv_vnokm"/><path fill="url(#iqDXrhc)" clip-rule="evenodd" class="ktv_vnokm"/><path fill="url(#ikifllb)" clip-rule="evenodd" class="ktv_vnokm"/><path fill="url(#iyjUVad)" clip-rule="evenodd" class="s83e-pbfa"/><path fill="url(#ipBX8Gd)" clip-rule="evenodd" class="s83e-pbfa"/><path fill="url(#iLGTcye)" clip-rule="evenodd" class="s83e-pbfa"/><path fill="url(#i3sGs1d)" class="jno7r7bdm"/><path fill="url(#iMhWFEe)" class="jno7r7bdm"/><path fill="url(#iT4ZMie)" class="akc1ait7x"/><path fill="url(#iKmPkrF)" class="akc1ait7x"/><g filter="url(#i0Hxslb)"><path fill="url(#i6JcXkx)" clip-rule="evenodd" class="ljdhcwzej"/><path fill="url(#itd3jvb)" clip-rule="evenodd" class="ljdhcwzej"/><path fill="url(#iNmJ6bW)" clip-rule="evenodd" class="ljdhcwzej"/><path fill="url(#iUbLYJe)" clip-rule="evenodd" class="ljdhcwzej"/><path fill="url(#i7saV5c)" clip-rule="evenodd" class="ljdhcwzej"/><path fill="url(#i1T2kAd)" clip-rule="evenodd" class="ljdhcwzej"/><path fill="url(#i2tG16I)" clip-rule="evenodd" class="ljdhcwzej"/><path fill="url(#iq0IO8d)" clip-rule="evenodd" class="ljdhcwzej"/><path fill="url(#id1MBpe)" clip-rule="evenodd" class="ljdhcwzej"/><path fill="url(#iLvoSld)" clip-rule="evenodd" class="ljdhcwzej"/></g><path fill="url(#ii1C7rb)" clip-rule="evenodd" class="ljdhcwzej"/><path fill="url(#iyP05Eb)" clip-rule="evenodd" class="ljdhcwzej"/><g filter="url(#iuyIo3G)"><path fill="url(#iMIbyoe)" class="n5s5_2bqw"/><path fill="url(#i7d7fve)" class="n5s5_2bqw"/><path fill="url(#i7yKwgb)" class="n5s5_2bqw"/><path fill="url(#idUMZNb)" class="n5s5_2bqw"/><path fill="url(#immQfib)" class="n5s5_2bqw"/><path fill="url(#iyXBk7b)" class="n5s5_2bqw"/></g><path fill="url(#i3lm0nc)" class="rzcy09zij"/><g filter="url(#ic407Mb)"><path stroke="url(#iTHmK7L)" class="v4-mqdbdd"/></g><g filter="url(#i2KwceU)"><path fill="url(#il5Csde)" class="hqdi37blq"/></g><g filter="url(#iJAakbc)"><path fill="url(#i1II7td)" class="fyvjd117n"/></g><g filter="url(#iJqQAtK)"><path class="mqmffujbx"/><path fill="url(#iZKWnuD)" class="zpbw70bqz"/></g><g filter="url(#irHimsk)"><path class="zydwoybdo"/><path fill="url(#iwfuyXd)" class="kif-qobwv"/></g><g filter="url(#idPegNb)"><path fill="url(#irF8jIS)" class="d6_yjultm"/><path fill="url(#ic1273b)" class="d6_yjultm"/><path fill="url(#iDgH9ec)" class="d6_yjultm"/><path fill="url(#ivYwlNb)" class="d6_yjultm"/><path fill="url(#igxJFpd)" class="d6_yjultm"/><path fill="url(#i57EZtc)" class="d6_yjultm"/><path fill="url(#iZOPE0b)" class="d6_yjultm"/></g><path fill="url(#izRU85c)" class="d6_yjultm"/><g filter="url(#ipvzKRd)"><path class="ghe4b4spn"/></g><g filter="url(#iDbWVgc)"><path fill="url(#iTfPXJe)" class="h8bujacjt"/><path fill="url(#i81ecfC)" class="h8bujacjt"/><path fill="url(#ip16kcc)" class="h8bujacjt"/><path fill="url(#i2v1dDb)" class="h8bujacjt"/></g><path fill="url(#iSGrupH)" class="h8bujacjt"/><path fill="url(#iDWDhIb)" class="h8bujacjt"/><g filter="url(#iuNwoub)"><path class="x60pkg4lv"/></g><g filter="url(#ij1PcKd)"><path class="nnzcbc3rt"/></g><g filter="url(#iiCThHc)"><path class="jsiskrbki"/></g><g filter="url(#i0LtTod)"><path clip-rule="evenodd" class="wt_o-stsp"/></g><path class="e2ws2-aal"/><path fill="url(#inmVapb)" class="r-j2d-z1g"/><path class="azivutbkb"/><g filter="url(#iKH76Xf)"><path class="sm6z2kbxm"/><path fill="url(#iATQwyb)" class="hl38jrbve"/></g><g filter="url(#ifNKcDe)"><path fill="url(#iRTjXNd)" class="f_v_9cc1z"/></g><path class="ah3mw7bny"/><path fill="url(#iCl72fO)" class="lw1cgpbnn"/><path class="j5rov2v4m"/><g filter="url(#imASONp)"><path fill="url(#i6XWkDe)" class="oavmczy7b"/></g><g filter="url(#i46spgp)"><ellipse transform="rotate(-31.984 13.465 12.44)" class="b19nkub2g"/><ellipse fill="url(#ifQD0Rd)" transform="rotate(-31.984 13.465 12.44)" class="ip600ebeq"/></g><g filter="url(#itsZpGe)"><path class="fgcyigbue"/></g><g filter="url(#iMLMxse)"><path class="fycz5d1rm"/></g><g filter="url(#iL8apte)"><path fill="url(#i9qKjmd)" class="gzd0mwbdr"/><path fill="url(#itywfdb)" class="gzd0mwbdr"/></g><g filter="url(#i0k0tOd)"><path fill="url(#iALiJyc)" class="huke00buv"/><path fill="url(#iZ0dK0c)" class="huke00buv"/><path fill="url(#io7jJpd)" class="huke00buv"/></g><g filter="url(#iFfCxUc)"><path stroke="url(#i8WKTOe)" class="j0zz2-fsm"/></g><g filter="url(#iSFGEXb)"><ellipse stroke="url(#i6QJAFd)" class="vzxfiw78q"/></g><ellipse class="u9r9_zbwx"/><g filter="url(#ibtzlVb)"><path class="k4mvvh2gm"/></g><g filter="url(#iAU2dQd)"><path class="xh771qbff"/></g><g filter="url(#itNqZ9c)"><path stroke="url(#iKmYNmK)" class="t59-q-b0g"/></g><defs><radialGradient id="iYin6db" cx="0" cy="0" r="1" gradientTransform="rotate(160.563 1.553 6.597)scale(1.8701 4.54015)" gradientUnits="userSpaceOnUse"><stop offset=".525" class="snr00mg_h"/><stop offset=".902" class="p9i49dbyg"/></radialGradient><radialGradient id="itUwzHc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.17357 1.11344 -2.78778 -2.93833 3.824 12.676)" gradientUnits="userSpaceOnUse"><stop offset=".525" class="snr00mg_h"/><stop offset=".902" class="p9i49dbyg"/></radialGradient><radialGradient id="iAf8Hpe" cx="0" cy="0" r="1" gradientTransform="matrix(-1.26983 1.10163 -2.12498 -2.44943 4.03 13.622)" gradientUnits="userSpaceOnUse"><stop offset=".604" class="snr00mg_h"/><stop offset=".925" class="p9i49dbyg"/></radialGradient><radialGradient id="ix1QTlc" cx="0" cy="0" r="1" gradientTransform="matrix(1.4212 1.08482 -.6854 .89793 5.055 13.773)" gradientUnits="userSpaceOnUse"><stop class="tomvsgg1z"/><stop offset="1" class="w1ze_ourm"/></radialGradient><radialGradient id="igXiHgc" cx="0" cy="0" r="1" gradientTransform="matrix(-.52138 .86916 -1.0215 -.61276 7.166 11.483)" gradientUnits="userSpaceOnUse"><stop class="xnz12146t"/><stop offset="1" class="kss0s4bml"/></radialGradient><radialGradient id="iselgIc" cx="0" cy="0" r="1" gradientTransform="matrix(-2.01562 .20314 -.08201 -.81376 6.447 16.269)" gradientUnits="userSpaceOnUse"><stop offset=".203" class="sal1d01zm"/><stop offset="1" class="csb_25bkg"/></radialGradient><radialGradient id="iFouQGe" cx="0" cy="0" r="1" gradientTransform="matrix(-.87189 .7983 -.7298 -.79708 28.847 12.057)" gradientUnits="userSpaceOnUse"><stop class="ula9ko11i"/><stop offset="1" class="jr88e7bxh"/></radialGradient><radialGradient id="idKcIze" cx="0" cy="0" r="1" gradientTransform="matrix(1.96876 1.54687 -3.48696 4.43799 26.158 12.269)" gradientUnits="userSpaceOnUse"><stop offset=".675" class="k7amnqbjh"/><stop offset=".927" class="hslupxxwt"/></radialGradient><radialGradient id="iR2VAAb" cx="0" cy="0" r="1" gradientTransform="matrix(-.875 -.78125 .88576 -.99206 27.822 13.487)" gradientUnits="userSpaceOnUse"><stop class="y_uk6ubie"/><stop offset="1" class="s6ysz-krq"/></radialGradient><radialGradient id="iVRG0wb" cx="0" cy="0" r="1" gradientTransform="rotate(131.73 12.166 12.9)scale(1.16966 1.06648)" gradientUnits="userSpaceOnUse"><stop class="ula9ko11i"/><stop offset="1" class="jr88e7bxh"/></radialGradient><radialGradient id="iGPTVhC" cx="0" cy="0" r="1" gradientTransform="matrix(1.08542 1.24122 -5.12978 4.48588 28.12 13.365)" gradientUnits="userSpaceOnUse"><stop offset=".556" class="k7amnqbjh"/><stop offset=".912" class="hslupxxwt"/></radialGradient><radialGradient id="iu2tmcN" cx="0" cy="0" r="1" gradientTransform="rotate(-134.288 17.405 .891)scale(1.55128 1.67148)" gradientUnits="userSpaceOnUse"><stop class="y_uk6ubie"/><stop offset="1" class="s6ysz-krq"/></radialGradient><radialGradient id="iSSu21b" cx="0" cy="0" r="1" gradientTransform="matrix(1.10937 .9375 -3.17994 3.76294 27.869 14.237)" gradientUnits="userSpaceOnUse"><stop offset=".715" class="k7amnqbjh"/><stop offset="1" class="hslupxxwt"/></radialGradient><radialGradient id="iqDXrhc" cx="0" cy="0" r="1" gradientTransform="rotate(138.972 12.45 12.286)scale(1.18852 1.0803)" gradientUnits="userSpaceOnUse"><stop class="ula9ko11i"/><stop offset="1" class="jr88e7bxh"/></radialGradient><radialGradient id="ikifllb" cx="0" cy="0" r="1" gradientTransform="rotate(-137.781 17.28 1.82)scale(1.45679 1.64014)" gradientUnits="userSpaceOnUse"><stop class="y_uk6ubie"/><stop offset="1" class="s6ysz-krq"/></radialGradient><radialGradient id="ipBX8Gd" cx="0" cy="0" r="1" gradientTransform="matrix(.73437 1.86015 -3.71825 1.46794 27.337 14.722)" gradientUnits="userSpaceOnUse"><stop offset=".7" class="davf0hbbe"/><stop offset="1" class="ewsia9bsk"/></radialGradient><radialGradient id="iLGTcye" cx="0" cy="0" r="1" gradientTransform="matrix(-.89843 .6875 -.60902 -.79588 29.595 14.37)" gradientUnits="userSpaceOnUse"><stop class="ula9ko11i"/><stop offset="1" class="jr88e7bxh"/></radialGradient><radialGradient id="i3sGs1d" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.94297 -2.39063 0 26.203 16.425)" gradientUnits="userSpaceOnUse"><stop class="crw1_cc4c"/><stop offset="1" class="v04pkwb5w"/></radialGradient><radialGradient id="iT4ZMie" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.24766 -2.29189 0 7.369 16.558)" gradientUnits="userSpaceOnUse"><stop class="na2yypbsd"/><stop offset="1" class="ue3np3b_s"/></radialGradient><radialGradient id="itd3jvb" cx="0" cy="0" r="1" gradientTransform="rotate(17.529 -41.31 71.489)scale(2.32264 3.2899)" gradientUnits="userSpaceOnUse"><stop class="w3-vy4c8j"/><stop offset="1" class="w72oynbwi"/></radialGradient><radialGradient id="iNmJ6bW" cx="0" cy="0" r="1" gradientTransform="matrix(.29718 4.17651 -2.5162 .17904 11.663 15.136)" gradientUnits="userSpaceOnUse"><stop class="lcrdwk1fj"/><stop offset="1" class="denqa3bda"/></radialGradient><radialGradient id="iUbLYJe" cx="0" cy="0" r="1" gradientTransform="rotate(85.93 -.032 16.023)scale(5.23424 5.45242)" gradientUnits="userSpaceOnUse"><stop offset=".617" class="ag6fa4z4y"/><stop offset="1" class="qir_1cb0f"/></radialGradient><radialGradient id="i7saV5c" cx="0" cy="0" r="1" gradientTransform="matrix(-1.05543 1.59175 -1.5455 -1.02477 11.23 13.553)" gradientUnits="userSpaceOnUse"><stop offset=".161" class="ha2cq84sa"/><stop offset="1" class="p4wkjrbae"/></radialGradient><radialGradient id="i1T2kAd" cx="0" cy="0" r="1" gradientTransform="rotate(96.467 .796 10.804)scale(2.40234 1.94473)" gradientUnits="userSpaceOnUse"><stop offset=".3" class="c42_rqbzh"/><stop offset="1" class="ybrvbdb9p"/></radialGradient><radialGradient id="i2tG16I" cx="0" cy="0" r="1" gradientTransform="rotate(58.534 .362 14.107)scale(2.23704 4.26152)" gradientUnits="userSpaceOnUse"><stop offset=".222" class="esx41hbqq"/><stop offset=".921" class="v9rq5jjti"/></radialGradient><radialGradient id="iq0IO8d" cx="0" cy="0" r="1" gradientTransform="rotate(128.44 8.558 8.557)scale(1.53817 2.14956)" gradientUnits="userSpaceOnUse"><stop class="duwob45dr"/><stop offset="1" class="v61l3jbat"/></radialGradient><radialGradient id="id1MBpe" cx="0" cy="0" r="1" gradientTransform="rotate(159.709 10.355 7.852)scale(1.80403 3.92534)" gradientUnits="userSpaceOnUse"><stop class="u0-djrvhx"/><stop offset="1" class="hottnizrg"/><stop offset="1" class="fj67tibom"/></radialGradient><radialGradient id="iLvoSld" cx="0" cy="0" r="1" gradientTransform="rotate(-137.386 14.488 5.315)scale(4.38034 6.29068)" gradientUnits="userSpaceOnUse"><stop class="yqk-2gbyp"/><stop offset="1" class="oaxszm67z"/></radialGradient><radialGradient id="ii1C7rb" cx="0" cy="0" r="1" gradientTransform="matrix(.52307 -2.625 5.14922 1.02606 15.743 18.774)" gradientUnits="userSpaceOnUse"><stop class="t5k-dybbr"/><stop offset="1" class="z87_gpr3p"/></radialGradient><radialGradient id="iyP05Eb" cx="0" cy="0" r="1" gradientTransform="matrix(.99994 10.28129 -14.7096 1.43063 16.11 9.555)" gradientUnits="userSpaceOnUse"><stop offset=".777" class="jbn_vnsxl"/><stop offset="1" class="f_foh-blv"/></radialGradient><radialGradient id="iMIbyoe" cx="0" cy="0" r="1" gradientTransform="matrix(0 -16.4411 10.6867 0 19.921 29.41)" gradientUnits="userSpaceOnUse"><stop offset=".155" class="i9y57psai"/><stop offset="1" class="vz30bz9hs"/></radialGradient><radialGradient id="i7d7fve" cx="0" cy="0" r="1" gradientTransform="rotate(130.485 .29 12.275)scale(4.64639 1.15364)" gradientUnits="userSpaceOnUse"><stop class="k9011xajc"/><stop offset="1" class="upmwye1mi"/></radialGradient><radialGradient id="i7yKwgb" cx="0" cy="0" r="1" gradientTransform="matrix(-2.5323 -4.48916 1.47345 -.83116 24.516 27.087)" gradientUnits="userSpaceOnUse"><stop class="jlublfbcv"/><stop offset="1" class="h3d7w4j4j"/></radialGradient><radialGradient id="idUMZNb" cx="0" cy="0" r="1" gradientTransform="matrix(0 7.46944 -4.08022 0 27.015 16.972)" gradientUnits="userSpaceOnUse"><stop class="vio74z7fz"/><stop offset="1" class="ey8rcibsm"/></radialGradient><radialGradient id="immQfib" cx="0" cy="0" r="1" gradientTransform="matrix(-2.2344 3.40893 -.52728 -.3456 9.719 20.149)" gradientUnits="userSpaceOnUse"><stop class="cgtm3g8-v"/><stop offset="1" class="dol2bxb1e"/></radialGradient><radialGradient id="iyXBk7b" cx="0" cy="0" r="1" gradientTransform="matrix(-5.68753 3.4062 -1.542 -2.57478 14.422 17.899)" gradientUnits="userSpaceOnUse"><stop offset=".066" class="rn19hbczg"/><stop offset="1" class="biwbjbv7w"/></radialGradient><radialGradient id="i3lm0nc" cx="0" cy="0" r="1" gradientTransform="matrix(3.09375 2.20253 -3.34177 4.69396 14.578 18.274)" gradientUnits="userSpaceOnUse"><stop offset=".118" class="k45k_8b7e"/><stop offset="1" class="phn2g3b9r"/></radialGradient><radialGradient id="i1II7td" cx="0" cy="0" r="1" gradientTransform="matrix(2.25725 -1.22631 1.49727 2.756 19.626 13.067)" gradientUnits="userSpaceOnUse"><stop offset=".572" class="qtr_-gj2q"/><stop offset=".905" class="yomsttbzk"/></radialGradient><radialGradient id="iZKWnuD" cx="0" cy="0" r="1" gradientTransform="rotate(-24.368 39.805 -40.197)scale(1.22573)" gradientUnits="userSpaceOnUse"><stop offset=".71" class="iy3kcbc1e"/><stop offset="1" class="nfa0q6zfs"/></radialGradient><radialGradient id="iwfuyXd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.00663 .07163 -.06852 -.96291 11.438 13.236)" gradientUnits="userSpaceOnUse"><stop offset=".415" class="e3owjub-t"/><stop offset="1" class="qb0464bzj"/></radialGradient><radialGradient id="irF8jIS" cx="0" cy="0" r="1" gradientTransform="rotate(151.174 7.656 8.487)scale(6.72884 9.00644)" gradientUnits="userSpaceOnUse"><stop class="wa9cqx9pi"/><stop offset="1" class="m45oyzb-o"/></radialGradient><radialGradient id="ic1273b" cx="0" cy="0" r="1" gradientTransform="matrix(-1.9028 1.1865 -1.00667 -1.61439 17.602 12.948)" gradientUnits="userSpaceOnUse"><stop class="pb_rvfc5z"/><stop offset="1" class="v2k4g1b_w"/></radialGradient><radialGradient id="iDgH9ec" cx="0" cy="0" r="1" gradientTransform="matrix(.51458 -3.84685 4.88094 .6529 14.184 18.924)" gradientUnits="userSpaceOnUse"><stop class="wrs_9y9vq"/><stop offset="1" class="z-gb6n28y"/></radialGradient><radialGradient id="ivYwlNb" cx="0" cy="0" r="1" gradientTransform="rotate(85.93 1.314 14.312)scale(6.99083 11.1033)" gradientUnits="userSpaceOnUse"><stop offset=".613" class="y7tqbcbso"/><stop offset=".942" class="z2mbpqb1g"/></radialGradient><radialGradient id="igxJFpd" cx="0" cy="0" r="1" gradientTransform="matrix(-4.98194 1.76694 -3.04212 -8.57736 16.473 13.932)" gradientUnits="userSpaceOnUse"><stop offset=".877" class="ud-bjxb5c"/><stop offset="1" class="a9dfe182j"/></radialGradient><radialGradient id="i57EZtc" cx="0" cy="0" r="1" gradientTransform="matrix(-.07674 -1.07848 1.3236 -.09418 17.904 11.875)" gradientUnits="userSpaceOnUse"><stop class="e0lgwbeaw"/><stop offset="1" class="y7n0ymbzx"/></radialGradient><radialGradient id="iZOPE0b" cx="0" cy="0" r="1" gradientTransform="rotate(-94.07 12.677 -.38)scale(1.27779 1.46444)" gradientUnits="userSpaceOnUse"><stop class="w2e_edyjl"/><stop offset="1" class="gsggv-b-p"/></radialGradient><radialGradient id="izRU85c" cx="0" cy="0" r="1" gradientTransform="rotate(175.93 10.078 6.908)scale(1.26553 4.16618)" gradientUnits="userSpaceOnUse"><stop class="f902gfhfn"/><stop offset="1" class="jh40i5bvl"/></radialGradient><radialGradient id="i81ecfC" cx="0" cy="0" r="1" gradientTransform="rotate(-109.962 13.238 1.2)scale(2.39313 1.36938)" gradientUnits="userSpaceOnUse"><stop offset=".017" class="itt9z7bbf"/><stop offset="1" class="eh2hzabiv"/></radialGradient><radialGradient id="iDWDhIb" cx="0" cy="0" r="1" gradientTransform="rotate(140.392 5.594 9.781)scale(1.47969 1.98194)" gradientUnits="userSpaceOnUse"><stop offset=".797" class="e6-lebcyw"/><stop offset="1" class="b8os9sbcy"/></radialGradient><radialGradient id="inmVapb" cx="0" cy="0" r="1" gradientTransform="rotate(85.93 2.348 15.675)scale(.76228 1.21247)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="iATQwyb" cx="0" cy="0" r="1" gradientTransform="matrix(-.23709 -.2644 .36402 -.32641 17.607 12.314)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iCl72fO" cx="0" cy="0" r="1" gradientTransform="rotate(85.93 .146 13.624)scale(.76228 1.21249)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="ifQD0Rd" cx="0" cy="0" r="1" gradientTransform="matrix(-.00726 -.46382 .55753 -.00873 13.45 12.735)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="i9qKjmd" cx="0" cy="0" r="1" gradientTransform="matrix(-2.9284 4.10803 -1.79164 -1.27716 12.802 6.59)" gradientUnits="userSpaceOnUse"><stop offset=".396" class="esh4v5qtq"/><stop offset=".911" class="nria2ku7r"/></radialGradient><radialGradient id="itywfdb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.96017 1.51352 -.74918 -.97027 12.865 7.47)" gradientUnits="userSpaceOnUse"><stop offset=".12" class="dpv-wxbjb"/><stop offset="1" class="abu2lcc5n"/><stop offset="1" class="sxoxd_kke"/></radialGradient><radialGradient id="iALiJyc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.74432 4.41464 -6.26805 -2.47664 16.948 5.191)" gradientUnits="userSpaceOnUse"><stop offset=".627" class="crfaaqblp"/><stop offset="1" class="ehjghj3fe"/></radialGradient><radialGradient id="iZ0dK0c" cx="0" cy="0" r="1" gradientTransform="rotate(101.839 6.286 10.348)scale(3.2321 6.77346)" gradientUnits="userSpaceOnUse"><stop offset=".132" class="z-gx2rb2w"/><stop offset="1" class="gbpc14bxe"/></radialGradient><radialGradient id="io7jJpd" cx="0" cy="0" r="1" gradientTransform="matrix(-3.63347 -5.83333 5.21464 -3.2481 16.805 11.686)" gradientUnits="userSpaceOnUse"><stop offset=".898" class="s3t3owbgt"/><stop offset="1" class="yehxt3bls"/></radialGradient><filter id="ipAvYzc" width="3.652" height="3.139" x="3.372" y="11.417" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4180" stdDeviation=".25"/></filter><filter id="ijBAgQc" width="3.727" height="3.323" x="2.293" y="11.697" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4180" stdDeviation=".25"/></filter><filter id="iMtpBod" width="3.867" height="3.135" x="2.223" y="12.707" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4180" stdDeviation=".25"/></filter><filter id="iT5BW2d" width="3.408" height="5.156" x="23.701" y="11.483" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.843137 0 0 0 0 0.611765 0 0 0 0 0.25098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_4180"/></filter><filter id="i0Hxslb" width="14.56" height="14.627" x="8.764" y="4.675" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.87451 0 0 0 0 0.498039 0 0 0 0 0.105882 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_4180"/></filter><filter id="iuyIo3G" width="23.107" height="13.423" x="4.624" y="16.722" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.498039 0 0 0 0 0.278431 0 0 0 0 0.843137 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_4180"/></filter><filter id="ic407Mb" width="4.031" height="2.858" x="2.522" y="13.758" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4180" stdDeviation=".25"/></filter><filter id="i2KwceU" width="3.124" height="3.174" x="9.907" y="11.726" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy=".15"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.835294 0 0 0 0 0.627451 0 0 0 0 0.305882 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_4180"/></filter><filter id="iJAakbc" width="3.024" height="3.274" x="18.823" y="10.842" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.937255 0 0 0 0 0.576471 0 0 0 0 0.341176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_4180"/></filter><filter id="iJqQAtK" width="3.018" height="3.019" x="18.826" y="11.094" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4180" stdDeviation=".25"/></filter><filter id="irHimsk" width="2.518" height="2.519" x="10.178" y="11.977" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4180" stdDeviation=".125"/></filter><filter id="idPegNb" width="9.652" height="10.43" x="10.91" y="8.504" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.92549 0 0 0 0 0.529412 0 0 0 0 0.137255 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_4180"/></filter><filter id="ipvzKRd" width="2.762" height="3.547" x="14.387" y="11.957" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4180" stdDeviation=".25"/></filter><filter id="iDbWVgc" width="2.262" height="3.042" x="14.78" y="12.071" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4180" stdDeviation=".125"/></filter><filter id="iuNwoub" width="2.818" height="1.173" x="16.643" y="11.425" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.141176 0 0 0 0 0.0862745 0 0 0 0 0.176471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_4180"/></filter><filter id="ij1PcKd" width="2.835" height="1.248" x="12.068" y="11.781" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.133333 0 0 0 0 0.0784314 0 0 0 0 0.168627 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_4180"/></filter><filter id="iiCThHc" width="2.291" height="1.131" x="12.107" y="10.403" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.658824 0 0 0 0 0.270588 0 0 0 0 0.141176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_4180"/></filter><filter id="i0LtTod" width="2.334" height=".953" x="17.163" y="10.105" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.658824 0 0 0 0 0.270588 0 0 0 0 0.141176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_4180"/></filter><filter id="iKH76Xf" width=".731" height=".689" x="17.124" y="11.814" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4180" stdDeviation=".05"/></filter><filter id="ifNKcDe" width=".872" height=".89" x="17.91" y="11.828" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4180" stdDeviation=".1"/></filter><filter id="imASONp" width=".966" height="1.006" x="13.742" y="12.063" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4180" stdDeviation=".1"/></filter><filter id="i46spgp" width=".851" height=".699" x="13.04" y="12.09" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4180" stdDeviation=".05"/></filter><filter id="itsZpGe" width="2.179" height=".872" x="17.17" y="10.212" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4180" stdDeviation=".1"/></filter><filter id="iMLMxse" width="2.134" height="1.047" x="12.084" y="10.512" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4180" stdDeviation=".1"/></filter><filter id="iL8apte" width="4.681" height="5.156" x="9.216" y="6.277" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4180" stdDeviation=".375"/></filter><filter id="i0k0tOd" width="9.144" height="5.534" x="12.008" y="5.15" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4180" stdDeviation=".25"/></filter><filter id="iFfCxUc" width="1.225" height="2.166" x="12.365" y="6.687" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4180" stdDeviation=".125"/></filter><filter id="iSFGEXb" width="1.709" height="1.724" x="15.279" y="15.316" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4180" stdDeviation=".05"/></filter><filter id="ibtzlVb" width="8.199" height="8.945" x="5.11" y="16.743" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4180" stdDeviation=".75"/></filter><filter id="iAU2dQd" width="7.102" height="7.913" x="20.462" y="17.274" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4180" stdDeviation=".625"/></filter><filter id="itNqZ9c" width="3.956" height="6.956" x="9.209" y="19.369" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_4180" stdDeviation=".25"/></filter><linearGradient id="iGSn8Dc" x1="3.186" x2="5.185" y1="11.319" y2="13.656" gradientUnits="userSpaceOnUse"><stop class="qql0_6xdf"/><stop offset="1" class="q8bnjpbvp"/></linearGradient><linearGradient id="iZ8AUhe" x1="4.368" x2="6.779" y1="12.068" y2="14.282" gradientUnits="userSpaceOnUse"><stop class="px7lweb9d"/><stop offset="1" class="xdt-8bbcb"/></linearGradient><linearGradient id="ijf66ub" x1="2.313" x2="5.301" y1="12.167" y2="13.333" gradientUnits="userSpaceOnUse"><stop class="qql0_6xdf"/><stop offset=".988" class="q8bnjpbvp"/></linearGradient><linearGradient id="i1I4aae" x1="3.305" x2="5.715" y1="12.441" y2="14.655" gradientUnits="userSpaceOnUse"><stop class="px7lweb9d"/><stop offset="1" class="xdt-8bbcb"/></linearGradient><linearGradient id="icmzFec" x1="2.119" x2="6.853" y1="12.659" y2="14.753" gradientUnits="userSpaceOnUse"><stop class="qql0_6xdf"/><stop offset=".709" class="q8bnjpbvp"/></linearGradient><linearGradient id="ixwriRw" x1="3.229" x2="5.82" y1="13.432" y2="15.431" gradientUnits="userSpaceOnUse"><stop class="px7lweb9d"/><stop offset="1" class="xdt-8bbcb"/></linearGradient><linearGradient id="ik1sdFc" x1="3.337" x2="6.134" y1="15.237" y2="15.237" gradientUnits="userSpaceOnUse"><stop class="qql0_6xdf"/><stop offset="1" class="q8bnjpbvp"/></linearGradient><linearGradient id="iJ6s1me" x1="7.805" x2="7.805" y1="16.639" y2="15.884" gradientUnits="userSpaceOnUse"><stop class="d4zyoh72j"/><stop offset="1" class="y70euksvi"/></linearGradient><linearGradient id="iYE41Zf" x1="8.865" x2="8.024" y1="15.716" y2="15.716" gradientUnits="userSpaceOnUse"><stop offset=".005" class="zhlpa-bmw"/><stop offset="1" class="gp6jyoetb"/></linearGradient><linearGradient id="ixEuNeb" x1="23.159" x2="25.615" y1="15.615" y2="15.615" gradientUnits="userSpaceOnUse"><stop class="lx3uihbvp"/><stop offset="1" class="mqki6tbbj"/></linearGradient><linearGradient id="iB98R1c" x1="28.173" x2="26.036" y1="12.511" y2="14.212" gradientUnits="userSpaceOnUse"><stop class="b93mgob3x"/><stop offset="1" class="frlmzd7od"/></linearGradient><linearGradient id="iLE8Epb" x1="29.064" x2="26.541" y1="13.073" y2="14.765" gradientUnits="userSpaceOnUse"><stop class="b93mgob3x"/><stop offset="1" class="frlmzd7od"/></linearGradient><linearGradient id="iDJAbBe" x1="29.343" x2="26.573" y1="15.155" y2="15.111" gradientUnits="userSpaceOnUse"><stop class="b93mgob3x"/><stop offset="1" class="frlmzd7od"/></linearGradient><linearGradient id="iyjUVad" x1="29.029" x2="26.254" y1="15.934" y2="15.884" gradientUnits="userSpaceOnUse"><stop class="b93mgob3x"/><stop offset="1" class="frlmzd7od"/></linearGradient><linearGradient id="iMhWFEe" x1="23.662" x2="24.149" y1="17.407" y2="17.399" gradientUnits="userSpaceOnUse"><stop class="b3rpq3bxe"/><stop offset="1" class="gkm3jmb3y"/></linearGradient><linearGradient id="iKmPkrF" x1="8.86" x2="7.828" y1="17.29" y2="17.29" gradientUnits="userSpaceOnUse"><stop class="b3rpq3bxe"/><stop offset="1" class="gkm3jmb3y"/></linearGradient><linearGradient id="i6JcXkx" x1="19.745" x2="13.855" y1="6.096" y2="19.177" gradientUnits="userSpaceOnUse"><stop class="yr1vjkbzu"/><stop offset="1" class="btu9i2bec"/></linearGradient><linearGradient id="iTHmK7L" x1="3.518" x2="6.325" y1="14.46" y2="16.141" gradientUnits="userSpaceOnUse"><stop class="px7lweb9d"/><stop offset="1" class="xdt-8bbcb"/></linearGradient><linearGradient id="il5Csde" x1="9.917" x2="12.691" y1="13.427" y2="13.229" gradientUnits="userSpaceOnUse"><stop class="o2mdgcyjr"/><stop offset="1" class="l3wo7wctf"/></linearGradient><linearGradient id="iTfPXJe" x1="15.947" x2="15.768" y1="14.835" y2="12.322" gradientUnits="userSpaceOnUse"><stop class="um-di3lxj"/><stop offset="1" class="fkdj3ejgt"/></linearGradient><linearGradient id="ip16kcc" x1="14.915" x2="15.723" y1="14.191" y2="14.232" gradientUnits="userSpaceOnUse"><stop class="enxo4ub-d"/><stop offset="1" class="vsluyubzo"/></linearGradient><linearGradient id="i2v1dDb" x1="15.953" x2="15.912" y1="14.922" y2="14.35" gradientUnits="userSpaceOnUse"><stop class="kpdurub6t"/><stop offset="1" class="qwjswe-rp"/></linearGradient><linearGradient id="iSGrupH" x1="16.024" x2="16.015" y1="14.892" y2="14.761" gradientUnits="userSpaceOnUse"><stop class="b8os9sbcy"/><stop offset="1" class="e6-lebcyw"/></linearGradient><linearGradient id="iRTjXNd" x1="18.548" x2="18.267" y1="12.219" y2="12.421" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="i6XWkDe" x1="14.426" x2="14.145" y1="12.512" y2="12.713" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="i8WKTOe" x1="12.688" x2="13.283" y1="7.309" y2="8.467" gradientUnits="userSpaceOnUse"><stop class="riyyv6xjv"/><stop offset="1" class="lfjsh038a"/></linearGradient><linearGradient id="i6QJAFd" x1="15.808" x2="16.082" y1="16.84" y2="15.843" gradientUnits="userSpaceOnUse"><stop class="e42abaczg"/><stop offset="1" class="lrj4dijcb"/></linearGradient><linearGradient id="iKmYNmK" x1="9.86" x2="12.86" y1="26.144" y2="20.487" gradientUnits="userSpaceOnUse"><stop class="g8oi3mbhp"/><stop offset="1" class="ynqid7b9h"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:woman-shrugging" /></template>
<style>
.a1_a0ybzq {
  fill-rule: evenodd;
  d: path("M29.647 12.147a.7.7 0 0 0-.978.157q-.05.071-.115.168c-.261.39-.92 1.113-1.732 1.46c-.356.153-.503.45-.32.876c.152.355.733.502 1.088.35c1.246-.533 1.935-1.603 2.156-1.945l.058-.089a.7.7 0 0 0-.157-.977");
}

.a9dfe182j {
  stop-color: var(--svg-color--d4993e, #D4993E);
}

.abu2lcc5n {
  stop-color: var(--svg-color--ffe134, #FFE134);
  stop-opacity: 0;
}

.ag6fa4z4y {
  stop-color: var(--svg-color--e26b25, #E26B25);
}

.ah3mw7bny {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.48 11.823a1.31 1.31 0 0 0-1.199 1.083a.258.258 0 0 0 .274.301l2.09-.148a.216.216 0 0 0 .195-.27a1.316 1.316 0 0 0-1.36-.966");
}

.akc1ait7x {
  d: path("M5.158 16.675a.25.25 0 0 1 .25-.25h2.93a.25.25 0 0 1 .25.25v1.13h-3.43z");
}

.asc597bjx {
  fill: var(--svg-color--e0a32a, #E0A32A);
  d: path("M6.123 11.638a.75.75 0 0 1 1.051.138l.805 1.047c.37.48.57 1.07.57 1.675v2.141H5.29v-2.698h1.626a1.3 1.3 0 0 0-.128-.204l-.804-1.047a.75.75 0 0 1 .138-1.052");
}

.azivutbkb {
  fill: var(--svg-color--000, #000);
  d: path("M17.366 12.644a.48.48 0 0 1 .445-.514a.478.478 0 0 1 .476.67l-.848.06a.43.43 0 0 1-.073-.216");
}

.b19nkub2g {
  cx: 13.465px;
  cy: 12.44px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.366px;
  ry: 0.185px;
}

.b3rpq3bxe {
  stop-color: var(--svg-color--784490, #784490);
}

.b8os9sbcy {
  stop-color: var(--svg-color--e2802f, #E2802F);
}

.b93mgob3x {
  stop-color: var(--svg-color--ffb620, #FFB620);
}

.biwbjbv7w {
  stop-color: var(--svg-color--7750a7, #7750A7);
  stop-opacity: 0;
}

.btu9i2bec {
  stop-color: var(--svg-color--e37923, #E37923);
}

.c42_rqbzh {
  stop-color: var(--svg-color--d77016, #D77016);
}

.cgtm3g8-v {
  stop-color: var(--svg-color--9a71e1, #9A71E1);
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.crfaaqblp {
  stop-color: var(--svg-color--f49523, #F49523);
  stop-opacity: 0;
}

.crw1_cc4c {
  stop-color: var(--svg-color--a881e3, #A881E3);
}

.csb_25bkg {
  stop-color: var(--svg-color--f4a82e, #F4A82E);
  stop-opacity: 0;
}

.d4zyoh72j {
  stop-color: var(--svg-color--f0a330, #F0A330);
}

.d6_yjultm {
  d: path("M10.959 12.081h.011l-.027-.248l-.03-.287c-.044-.89.45-1.271.663-1.402l.047-.023l.047-.022a2.17 2.17 0 0 0 1.032-1.236l.064-.188a.248.248 0 0 1 .43-.078a3.63 3.63 0 0 0 3.1 1.355l3.018-.214c.168-.012 1.02.01 1.153 1.172l.094 2.888c.07 2.635-1.855 4.545-4.358 4.723c-2.504.178-4.68-1.44-4.983-4.058z");
}

.davf0hbbe {
  stop-color: var(--svg-color--e08f52, #E08F52);
  stop-opacity: 0;
}

.denqa3bda {
  stop-color: var(--svg-color--d77117, #D77117);
  stop-opacity: 0;
}

.dol2bxb1e {
  stop-color: var(--svg-color--9a71e1, #9A71E1);
  stop-opacity: 0;
}

.dpv-wxbjb {
  stop-color: var(--svg-color--ffca2d, #FFCA2D);
}

.duwob45dr {
  stop-color: var(--svg-color--ffdf3c, #FFDF3C);
}

.e0lgwbeaw {
  stop-color: var(--svg-color--ffbb31, #FFBB31);
}

.e2ws2-aal {
  fill: var(--svg-color--fff, #fff);
  d: path("M17.962 11.505a1.31 1.31 0 0 1 1.34.901a.258.258 0 0 1-.228.338l-2.091.148a.216.216 0 0 1-.231-.24a1.31 1.31 0 0 1 1.21-1.147");
}

.e314ej6ax {
  fill-rule: evenodd;
  d: path("M2.57 13.169a.7.7 0 0 1 .98.142q.042.054.087.118c.301.42.763 1.062 1.778 1.062a.7.7 0 1 1 0 1.4c-1.775 0-2.636-1.24-2.924-1.655l-.062-.087a.7.7 0 0 1 .142-.98");
}

.e3owjub-t {
  stop-color: var(--svg-color--d67923, #D67923);
  stop-opacity: 0;
}

.e42abaczg {
  stop-color: var(--svg-color--ffb63a, #FFB63A);
}

.e6-lebcyw {
  stop-color: var(--svg-color--e2802f, #E2802F);
  stop-opacity: 0;
}

.eh2hzabiv {
  stop-color: var(--svg-color--ffe848, #FFE848);
  stop-opacity: 0;
}

.ehjghj3fe {
  stop-color: var(--svg-color--f49523, #F49523);
}

.enxo4ub-d {
  stop-color: var(--svg-color--f8a322, #F8A322);
}

.esh4v5qtq {
  stop-color: var(--svg-color--ee971b, #EE971B);
  stop-opacity: 0;
}

.esx41hbqq {
  stop-color: var(--svg-color--cba140, #CBA140);
}

.ewsia9bsk {
  stop-color: var(--svg-color--e08f52, #E08F52);
}

.ey8rcibsm {
  stop-color: var(--svg-color--a980f0, #A980F0);
  stop-opacity: 0;
}

.f_foh-blv {
  stop-color: var(--svg-color--723527, #723527);
}

.f_v_9cc1z {
  d: path("M18.582 12.446a.8.8 0 0 0-.247-.418l-.225.284l.125.206z");
}

.f902gfhfn {
  stop-color: var(--svg-color--ffda39, #FFDA39);
}

.fgcyigbue {
  stroke: var(--svg-color--c9725d, #C9725D);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M17.47 10.572c.297-.095 1.052-.111 1.58.212");
}

.fj67tibom {
  stop-color: var(--svg-color--ffd537, #FFD537);
  stop-opacity: 0;
}

.fkdj3ejgt {
  stop-color: var(--svg-color--f8c73f, #F8C73F);
}

.frlmzd7od {
  stop-color: var(--svg-color--ffd02e, #FFD02E);
}

.ft5dv1b6b {
  fill: none;
}

.fycz5d1rm {
  stroke: var(--svg-color--c9725d, #C9725D);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M13.917 10.825c-.307-.052-1.056.038-1.533.434");
}

.fyvjd117n {
  d: path("M20.442 14.111a1.512 1.512 0 1 0-.214-3.016a1.512 1.512 0 0 0 .214 3.016");
}

.g8oi3mbhp {
  stop-color: var(--svg-color--7346c5, #7346C5);
}

.gbpc14bxe {
  stop-color: var(--svg-color--ffe337, #FFE337);
  stop-opacity: 0;
}

.gh784hb2c {
  stop-color: var(--svg-color--85534d, #85534D);
}

.ghe4b4spn {
  fill: var(--svg-color--eb8b29, #EB8B29);
  d: path("m15.428 12.743l-.527 1.639a.507.507 0 0 0 .534.62l.737-.052a.508.508 0 0 0 .441-.69l-.61-1.558c-.133-.345-.488-.32-.575.04");
}

.gkm3jmb3y {
  stop-color: var(--svg-color--784490, #784490);
  stop-opacity: 0;
}

.gp6jyoetb {
  stop-color: var(--svg-color--d6933e, #D6933E);
  stop-opacity: 0;
}

.gsggv-b-p {
  stop-color: var(--svg-color--f09429, #F09429);
  stop-opacity: 0;
}

.gzd0mwbdr {
  d: path("M10.823 7.616c.545-.56 1.384-.625 1.861-.575l.464 1.183c-.244-.02-.453.08-.621.265c-.343 1.212-1.765 1.967-2.433 2.194c-.241-1.388-.213-2.1.729-3.067");
}

.h3d7w4j4j {
  stop-color: var(--svg-color--783edb, #783EDB);
  stop-opacity: 0;
}

.h8bujacjt {
  d: path("m15.428 12.612l-.384 1.629a.507.507 0 0 0 .534.62l.737-.052a.508.508 0 0 0 .441-.69l-.611-1.558c-.132-.345-.63-.31-.717.051");
}

.ha2cq84sa {
  stop-color: var(--svg-color--c9681c, #C9681C);
}

.hl38jrbve {
  d: path("M17.737 11.955c.065.075-.053.18-.187.297c-.134.115-.233.197-.299.122s-.01-.23.125-.346c.134-.116.295-.149.36-.074");
}

.hottnizrg {
  stop-color: var(--svg-color--ffd336, #FFD336);
  stop-opacity: 0;
}

.hqdi37blq {
  d: path("M11.527 14.746a1.512 1.512 0 1 0-.215-3.016a1.512 1.512 0 0 0 .215 3.016");
}

.hslupxxwt {
  stop-color: var(--svg-color--e6b03b, #E6B03B);
}

.huke00buv {
  d: path("M14.726 5.664c-1.078-.159-2.136 1.052-2.218 1.453c1.687 3.29 3.883 2.809 6.326 2.36c1.462-.269 1.67.391 1.818.707c-.679-3.772-3.47-4.158-5.926-4.52");
}

.i9y57psai {
  stop-color: var(--svg-color--a879fb, #A879FB);
}

.ip600ebeq {
  cx: 13.465px;
  cy: 12.44px;
  rx: 0.366px;
  ry: 0.185px;
}

.itdn4bbbj {
  d: path("M26.127 11.638a.75.75 0 0 0-1.051.138l-.805 1.047a2.75 2.75 0 0 0-.57 1.675v2.141h3.258v-2.698h-1.626q.053-.108.127-.204l.805-1.047a.75.75 0 0 0-.138-1.052");
}

.itisl1bsn {
  fill-rule: evenodd;
  d: path("M2.603 12.147a.7.7 0 0 1 .977.157q.05.071.115.168c.262.39.704 1.052 1.516 1.4a.7.7 0 0 1-.551 1.286c-1.246-.533-1.935-1.603-2.156-1.945l-.058-.089a.7.7 0 0 1 .157-.977");
}

.itt9z7bbf {
  stop-color: var(--svg-color--ffe848, #FFE848);
}

.iy3kcbc1e {
  stop-color: var(--svg-color--ffba25, #FFBA25);
  stop-opacity: 0;
}

.j0zz2-fsm {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M12.665 6.987c.038.226.297 1.068.624 1.566");
}

.j5rov2v4m {
  fill: var(--svg-color--000, #000);
  d: path("M14.23 12.867a.48.48 0 0 0-.512-.445a.478.478 0 0 0-.377.73l.848-.06a.5.5 0 0 0 .042-.225");
}

.jbn_vnsxl {
  stop-color: var(--svg-color--d16422, #D16422);
  stop-opacity: 0;
}

.jh40i5bvl {
  stop-color: var(--svg-color--ffda39, #FFDA39);
  stop-opacity: 0;
}

.jlublfbcv {
  stop-color: var(--svg-color--783edb, #783EDB);
}

.jno7r7bdm {
  d: path("M27.092 16.675a.25.25 0 0 0-.25-.25h-2.93a.25.25 0 0 0-.25.25v1.318h3.43z");
}

.jr88e7bxh {
  stop-color: var(--svg-color--ffdb42, #FFDB42);
  stop-opacity: 0;
}

.jsiskrbki {
  fill: var(--svg-color--bd4f26, #BD4F26);
  d: path("m12.508 11.486l-.004.002a.252.252 0 0 1-.29-.412h.001l.001-.001l.003-.002l.008-.006l.03-.019l.104-.063c.09-.05.217-.116.374-.179c.311-.124.75-.241 1.238-.19a.252.252 0 1 1-.053.5a2.1 2.1 0 0 0-.998.158a2.6 2.6 0 0 0-.414.212");
}

.k3z32yv2o {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-6px, 0.6px);
  d: path("M3.023 13.507c.239.483.967 1.38 2.267 1.534");
}

.k45k_8b7e {
  stop-color: var(--svg-color--dd882a, #DD882A);
}

.k4mvvh2gm {
  stroke: var(--svg-color--9465e3, #9465E3);
  stroke-linecap: square;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.36 18.993v3.442a1 1 0 0 0 1.566.823l1.84-1.265");
}

.k7amnqbjh {
  stop-color: var(--svg-color--e6b03b, #E6B03B);
  stop-opacity: 0;
}

.k9011xajc {
  stop-color: var(--svg-color--895fc7, #895FC7);
}

.kif-qobwv {
  d: path("M11.51 14.243a1.01 1.01 0 1 0-.144-2.013a1.01 1.01 0 0 0 .143 2.013");
}

.kpdurub6t {
  stop-color: var(--svg-color--e48538, #E48538);
}

.kss0s4bml {
  stop-color: var(--svg-color--eaa82a, #EAA82A);
  stop-opacity: 0;
}

.ktv_vnokm {
  fill-rule: evenodd;
  d: path("M29.679 13.169a.7.7 0 0 0-.98.142l-.086.118c-.302.42-.763 1.062-1.779 1.062a.7.7 0 1 0 0 1.4c1.776 0 2.637-1.24 2.925-1.655q.037-.054.062-.087a.7.7 0 0 0-.142-.98");
}

.l3wo7wctf {
  stop-color: var(--svg-color--d17e2a, #D17E2A);
}

.lcrdwk1fj {
  stop-color: var(--svg-color--c9641b, #C9641B);
}

.lfjsh038a {
  stop-color: var(--svg-color--db6008, #DB6008);
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.ljdhcwzej {
  fill-rule: evenodd;
  d: path("M22.639 13.767c.17-.422.242-.884.208-1.359a3.1 3.1 0 0 0-.339-1.205h.005a3 3 0 0 0-.298-.463l-.002-.002a3.04 3.04 0 0 1-.611-1.625v-.01a3.1 3.1 0 0 0-3.313-2.871a.5.5 0 0 1-.442-.188a3.1 3.1 0 0 0-2.605-1.111a3.1 3.1 0 0 0-2.422 1.469a.53.53 0 0 1-.411.248l-.08.007a3.1 3.1 0 0 0-2.792 3.305v.01a3.04 3.04 0 0 1-.374 1.694l-.002.004a3.1 3.1 0 0 0 .01 3.056a.48.48 0 0 1 .03.426a3.02 3.02 0 0 0 3.021 4.141l8.043-.572a3.02 3.02 0 0 0 2.404-4.527a.48.48 0 0 1-.03-.427M10.97 12.08l-.011.001l1.28 2.128c.303 2.618 1.14-.081 3.644-.26c2.504-.178 3.804 2.668 3.733.033l.85-3.072c-.133-1.163-.984-1.184-1.152-1.172l-3.018.214a3.63 3.63 0 0 1-3.1-1.355a.248.248 0 0 0-.43.078l-.064.188a2.17 2.17 0 0 1-1.032 1.236l-.047.022l-.047.023c-.213.13-.707.512-.663 1.402l.03.286z");
}

.lrj4dijcb {
  stop-color: var(--svg-color--ffb63a, #FFB63A);
  stop-opacity: 0;
}

.lw1cgpbnn {
  d: path("M13.692 12.064a.84.84 0 0 0-.73 1.114l1.615-.115a.844.844 0 0 0-.885-1");
}

.lx3uihbvp {
  stop-color: var(--svg-color--f4a421, #F4A421);
}

.m45oyzb-o {
  stop-color: var(--svg-color--eb9235, #EB9235);
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mqki6tbbj {
  stop-color: var(--svg-color--f4a421, #F4A421);
  stop-opacity: 0;
}

.mqmffujbx {
  fill: var(--svg-color--ffca38, #FFCA38);
  d: path("M20.406 13.61a1.01 1.01 0 1 0-.143-2.013a1.01 1.01 0 0 0 .143 2.013");
}

.n5s5_2bqw {
  d: path("M9.484 20.903a.25.25 0 0 1-.375-.216v-2.563a.6.6 0 0 0-.6-.6H5.224a.6.6 0 0 0-.6.6v4.286c-.005.849.112 2.507 1.485 3.383c1.148.733 2.5.57 3.213.347a.16.16 0 0 1 .208.148v3.706c0 .083.068.15.15.15h12.994a.15.15 0 0 0 .15-.15v-3.706c0-.106.108-.18.209-.148c.713.222 2.065.386 3.213-.347c1.373-.876 1.49-2.534 1.485-3.383v-4.286a.6.6 0 0 0-.6-.6h-3.285a.6.6 0 0 0-.6.6v2.563a.25.25 0 0 1-.375.216l-6.694-3.931z");
}

.na2yypbsd {
  stop-color: var(--svg-color--8f67c4, #8F67C4);
}

.nfa0q6zfs {
  stop-color: var(--svg-color--ffba25, #FFBA25);
}

.nnzcbc3rt {
  fill: var(--svg-color--635d5f, #635D5F);
  d: path("M14.703 12.468c-.28-.42-.683-.738-1.497-.68a1.56 1.56 0 0 0-.98.417c-.238.221-.186.48.016.563l.542.26c.597-.24 1.27-.315 1.919-.56");
}

.nria2ku7r {
  stop-color: var(--svg-color--d8772c, #D8772C);
}

.o2mdgcyjr {
  stop-color: var(--svg-color--e29128, #E29128);
}

.oavmczy7b {
  d: path("M14.508 12.747c-.02-.27-.252-.434-.315-.484l-.251.28l.19.326z");
}

.oaxszm67z {
  stop-color: var(--svg-color--cb6325, #CB6325);
  stop-opacity: 0;
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.or_xa3b0i {
  fill-rule: evenodd;
  d: path("M2.883 14.2a.7.7 0 0 1 .98.142c.181.242.653.84 1.873.84a.7.7 0 1 1 0 1.4c-1.827 0-2.668-.965-2.995-1.402a.7.7 0 0 1 .142-.98");
}

.p4wkjrbae {
  stop-color: var(--svg-color--c9681c, #C9681C);
  stop-opacity: 0;
}

.p9i49dbyg {
  stop-color: var(--svg-color--cd9143, #CD9143);
}

.pb_rvfc5z {
  stop-color: var(--svg-color--ffe842, #FFE842);
}

.pgkimacqn {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-6px, 0.6px);
  d: path("M3.094 12.497c.196.502.844 1.459 2.127 1.723");
}

.phn2g3b9r {
  stop-color: var(--svg-color--ffd038, #FFD038);
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.px7lweb9d {
  stop-color: var(--svg-color--ffba34, #FFBA34);
}

.q8bnjpbvp {
  stop-color: var(--svg-color--e0a32a, #E0A32A);
}

.qb0464bzj {
  stop-color: var(--svg-color--d67923, #D67923);
}

.qir_1cb0f {
  stop-color: var(--svg-color--e26b25, #E26B25);
  stop-opacity: 0;
}

.qql0_6xdf {
  stop-color: var(--svg-color--ea9c30, #EA9C30);
}

.qtr_-gj2q {
  stop-color: var(--svg-color--ffc531, #FFC531);
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.qwjswe-rp {
  stop-color: var(--svg-color--e48538, #E48538);
  stop-opacity: 0;
}

.r-j2d-z1g {
  d: path("M17.786 11.773a.838.838 0 0 1 .881 1l-1.616.114a.842.842 0 0 1 .735-1.114");
}

.r5wm-vlaj {
  d: path("M6.123 11.638a.75.75 0 0 1 1.051.138l.805 1.047c.37.48.57 1.07.57 1.675v2.141H5.29v-2.698h1.626a1.3 1.3 0 0 0-.128-.204l-.804-1.047a.75.75 0 0 1 .138-1.052");
}

.rfksyecjs {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-6px, 0.6px);
  d: path("M4.172 12.217c.196.502 1.018 1.388 2.052 1.54");
}

.riyyv6xjv {
  stop-color: var(--svg-color--faa719, #FAA719);
}

.rn19hbczg {
  stop-color: var(--svg-color--61305c, #61305C);
}

.rzcy09zij {
  d: path("M15.994 20.477c-1.105 0-2-.744-2-1.662v-1.963c0-.917.895-1.66 2-1.66s2 .743 2 1.66v1.963c0 .918-.896 1.662-2 1.662");
}

.s3t3owbgt {
  stop-color: var(--svg-color--ca9b37, #CA9B37);
  stop-opacity: 0;
}

.s6ysz-krq {
  stop-color: var(--svg-color--eea324, #EEA324);
  stop-opacity: 0;
}

.s83e-pbfa {
  fill-rule: evenodd;
  d: path("M29.367 14.2a.7.7 0 0 0-.98.142c-.181.242-.654.84-1.873.84a.7.7 0 1 0 0 1.4c1.827 0 2.668-.965 2.994-1.402a.7.7 0 0 0-.142-.98");
}

.sal1d01zm {
  stop-color: var(--svg-color--f4a82e, #F4A82E);
}

.sm6z2kbxm {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M17.737 11.955c.065.075-.053.18-.187.297c-.134.115-.233.197-.299.122s-.01-.23.125-.346c.134-.116.295-.149.36-.074");
}

.snr00mg_h {
  stop-color: var(--svg-color--cd9143, #CD9143);
  stop-opacity: 0;
}

.sxoxd_kke {
  stop-color: var(--svg-color--ffca2d, #FFCA2D);
  stop-opacity: 0;
}

.t59-q-b0g {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-3px, 0.3px);
  d: path("M9.86 25.675c.177-1.146.956-3.881 2.656-5.656");
}

.t5k-dybbr {
  stop-color: var(--svg-color--8d4108, #8D4108);
}

.tghnx9bfm {
  fill-rule: evenodd;
  d: path("M28.608 11.83a.7.7 0 0 0-.978.157a2 2 0 0 0-.115.183l-.006.01v.002l-.105.174a2 2 0 0 1-.294.37c-.233.228-.608.468-1.267.5a.7.7 0 1 0 .068 1.398c1.025-.05 1.718-.447 2.179-.898c.223-.22.382-.442.495-.618c.053-.084.098-.16.13-.216l.004-.007l.044-.075l.002-.002a.7.7 0 0 0-.157-.978");
}

.tomvsgg1z {
  stop-color: var(--svg-color--e9a92e, #E9A92E);
}

.u0-djrvhx {
  stop-color: var(--svg-color--ffd537, #FFD537);
}

.u9r9_zbwx {
  cx: 16.133px;
  cy: 16.178px;
  fill: var(--svg-color--88004d, #88004D);
  rx: 0.654px;
  ry: 0.662px;
}

.ud-bjxb5c {
  stop-color: var(--svg-color--d4993e, #D4993E);
  stop-opacity: 0;
}

.ue3np3b_s {
  stop-color: var(--svg-color--7752b3, #7752B3);
}

.ula9ko11i {
  stop-color: var(--svg-color--ffdb42, #FFDB42);
}

.um-di3lxj {
  stop-color: var(--svg-color--ffc134, #FFC134);
}

.upmwye1mi {
  stop-color: var(--svg-color--8358c9, #8358C9);
  stop-opacity: 0;
}

.uylc3es2x {
  fill-rule: evenodd;
  d: path("M3.642 11.83a.7.7 0 0 1 .977.157a2 2 0 0 1 .121.193l.001.002c.034.057.066.113.105.174c.077.12.17.25.294.37c.232.228.607.468 1.267.5a.7.7 0 0 1-.069 1.398c-1.024-.05-1.717-.447-2.178-.898a3.5 3.5 0 0 1-.495-.618a6 6 0 0 1-.13-.216l-.004-.007c-.029-.049-.04-.069-.045-.075l-.001-.002a.7.7 0 0 1 .157-.978");
}

.v04pkwb5w {
  stop-color: var(--svg-color--814ba6, #814BA6);
}

.v2k4g1b_w {
  stop-color: var(--svg-color--ffe842, #FFE842);
  stop-opacity: 0;
}

.v4-mqdbdd {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-6px, 0.6px);
  d: path("M3.322 14.558c.293.451 1.121 1.257 2.431 1.257");
}

.v60bq3cin {
  stop-color: var(--svg-color--925c51, #925C51);
}

.v61l3jbat {
  stop-color: var(--svg-color--ffdf3c, #FFDF3C);
  stop-opacity: 0;
}

.v9rq5jjti {
  stop-color: var(--svg-color--cba140, #CBA140);
  stop-opacity: 0;
}

.vio74z7fz {
  stop-color: var(--svg-color--a980f0, #A980F0);
}

.vsluyubzo {
  stop-color: var(--svg-color--f8a322, #F8A322);
  stop-opacity: 0;
}

.vz30bz9hs {
  stop-color: var(--svg-color--7d52c7, #7D52C7);
}

.vzxfiw78q {
  cx: 16.133px;
  cy: 16.178px;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  rx: 0.654px;
  ry: 0.662px;
}

.w1ze_ourm {
  stop-color: var(--svg-color--e9a92e, #E9A92E);
  stop-opacity: 0;
}

.w2e_edyjl {
  stop-color: var(--svg-color--f09429, #F09429);
}

.w3-vy4c8j {
  stop-color: var(--svg-color--e38923, #E38923);
}

.w72oynbwi {
  stop-color: var(--svg-color--e38923, #E38923);
  stop-opacity: 0;
}

.wa9cqx9pi {
  stop-color: var(--svg-color--ffe644, #FFE644);
}

.wrs_9y9vq {
  stop-color: var(--svg-color--e4883f, #E4883F);
}

.wt_o-stsp {
  fill: var(--svg-color--bd4f26, #BD4F26);
  fill-rule: evenodd;
  d: path("m19.159 10.582l-.114.224za.252.252 0 0 1-.228.45l-.004-.003a1 1 0 0 0-.11-.047a3 3 0 0 0-.33-.104a2.1 2.1 0 0 0-1.01-.014a.252.252 0 1 1-.123-.49a2.65 2.65 0 0 1 1.252.015a3 3 0 0 1 .54.186l.008.004l.003.002z");
}

.x60pkg4lv {
  fill: var(--svg-color--635d5f, #635D5F);
  d: path("M16.843 12.316c.218-.455.571-.828 1.385-.886c.357-.025.707.05 1.03.274c.267.186.251.449.063.56l-.5.335c-.625-.154-1.302-.133-1.978-.283");
}

.xdt-8bbcb {
  stop-color: var(--svg-color--ffba34, #FFBA34);
  stop-opacity: 0;
}

.xh771qbff {
  stroke: var(--svg-color--a57cec, #A57CEC);
  stroke-linecap: square;
  d: path("M25.814 19.024v3.41a1 1 0 0 1-1.567.824l-1.84-1.265");
}

.xnz12146t {
  stop-color: var(--svg-color--eaa82a, #EAA82A);
}

.y_uk6ubie {
  stop-color: var(--svg-color--eea324, #EEA324);
}

.y70euksvi {
  stop-color: var(--svg-color--f0a330, #F0A330);
  stop-opacity: 0;
}

.y7n0ymbzx {
  stop-color: var(--svg-color--ffbb31, #FFBB31);
  stop-opacity: 0;
}

.y7tqbcbso {
  stop-color: var(--svg-color--de8839, #DE8839);
  stop-opacity: 0;
}

.ybrvbdb9p {
  stop-color: var(--svg-color--d77016, #D77016);
  stop-opacity: 0;
}

.yehxt3bls {
  stop-color: var(--svg-color--ca9b37, #CA9B37);
}

.ynqid7b9h {
  stop-color: var(--svg-color--7346c5, #7346C5);
  stop-opacity: 0;
}

.yomsttbzk {
  stop-color: var(--svg-color--ffe549, #FFE549);
}

.ypv5ckobw {
  fill: var(--svg-color--ffd02e, #FFD02E);
  d: path("M26.127 11.638a.75.75 0 0 0-1.051.138l-.805 1.047a2.75 2.75 0 0 0-.57 1.675v2.141h3.258v-2.698h-1.626q.053-.108.127-.204l.805-1.047a.75.75 0 0 0-.138-1.052");
}

.yqk-2gbyp {
  stop-color: var(--svg-color--cb6325, #CB6325);
}

.yr1vjkbzu {
  stop-color: var(--svg-color--ffd93c, #FFD93C);
}

.z-gb6n28y {
  stop-color: var(--svg-color--e4883f, #E4883F);
  stop-opacity: 0;
}

.z-gx2rb2w {
  stop-color: var(--svg-color--ffe337, #FFE337);
}

.z2mbpqb1g {
  stop-color: var(--svg-color--d17d2f, #D17D2F);
}

.z87_gpr3p {
  stop-color: var(--svg-color--8d4108, #8D4108);
  stop-opacity: 0;
}

.zhlpa-bmw {
  stop-color: var(--svg-color--d6933e, #D6933E);
}

.zpbw70bqz {
  d: path("M20.406 13.61a1.01 1.01 0 1 0-.143-2.013a1.01 1.01 0 0 0 .143 2.013");
}

.zydwoybdo {
  fill: var(--svg-color--e28527, #E28527);
  d: path("M11.51 14.243a1.01 1.01 0 1 0-.144-2.013a1.01 1.01 0 0 0 .143 2.013");
}

</style>
