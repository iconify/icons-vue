<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#ihe15Vd)"><path class="pk84u7jjf"/><path fill="url(#iYUPgCn)" class="pn5jbtt9h"/></g><path fill="url(#ibC1qLe)" class="pn5jbtt9h"/><path fill="url(#iIAQn6c)" class="pn5jbtt9h"/><path fill="url(#i1wcfOb)" class="pn5jbtt9h"/><path fill="url(#id94ewd)" class="pn5jbtt9h"/><g filter="url(#itwlbLc)"><path class="y79whbcii"/><path fill="url(#iTH78cb)" class="z0pxpnkbw"/></g><path class="fugdzyb1o"/><path fill="url(#iTIjaLd)" class="hr107sbjg"/><path fill="url(#ioDmBkd)" class="sgu32ab0w"/><path fill="url(#ijic07z)" class="sf2boes3b"/><path fill="url(#isyGmte)" class="sf2boes3b"/><g filter="url(#iIdbKtc)"><path fill="url(#icOIhCe)" class="lbpgcfbob"/><path fill="url(#i0RjV5w)" class="lbpgcfbob"/></g><g filter="url(#i9R24Fc)"><circle fill="url(#ilkWDkd)" class="dkktn1hof"/></g><g filter="url(#iwfZpxd)"><circle fill="url(#iR7ViFc)" class="uh8iu31tc"/></g><g filter="url(#iziWXMb)"><circle fill="url(#iVwnzxc)" class="a5a4koq8x"/></g><rect fill="url(#iWebikb)" transform="rotate(26.595 20.662 12.81)" class="toe447tsm"/><g filter="url(#i1KLQke)"><path fill="url(#icaasDe)" class="qd_9svrfx"/></g><path class="dldw44uej"/><g filter="url(#iGpMn6b)"><path class="wwdaicbmw"/><path fill="url(#irkuSNb)" class="xzkoa2bwe"/><path fill="url(#idqNGMe)" class="xzkoa2bwe"/></g><g filter="url(#iJoyMQb)"><path fill="url(#i1Jl7Lb)" class="cjqtkw6wk"/><path fill="url(#iMNduJc)" class="cjqtkw6wk"/><path fill="url(#iYKGKBb)" class="cjqtkw6wk"/></g><path fill="url(#i4w2n6b)" class="llo96eq-p"/><path fill="url(#inhy8AL)" class="llo96eq-p"/><path clip-rule="evenodd" class="n-63dkbfe"/><path fill="url(#ibw8yfe)" clip-rule="evenodd" class="y-2lu0bml"/><path clip-rule="evenodd" class="qe-ha1b7i"/><path fill="url(#i7JGUkc)" clip-rule="evenodd" class="xy8jbrbcm"/><path clip-rule="evenodd" class="iwur3y2uz"/><path fill="url(#iyLPjHb)" clip-rule="evenodd" class="ngpy26t4k"/><path clip-rule="evenodd" class="vurnokzna"/><path fill="url(#iyiSuIb)" clip-rule="evenodd" class="wvwy8egxn"/><path class="ekge1hb-m"/><path fill="url(#iCdksNe)" class="lalq_3f3j"/><g filter="url(#i5YMdac)"><path fill="url(#iR6HFdd)" class="r8fjj8bcd"/></g><g filter="url(#iXgdUAb)"><path fill="url(#iXY4Urd)" class="siwrhab8g"/></g><g filter="url(#iSApWRb)"><path stroke="url(#izUdOib)" class="j6zxuhbzj"/></g><path fill="url(#iWcLq3b)" class="g313knb1g"/><path fill="url(#iX4Qx4b)" class="hksadnbgt"/><g filter="url(#iPnilbd)"><path fill="url(#iPFUx3f)" class="s0_pk0b8f"/><path fill="url(#ijes2hE)" class="s0_pk0b8f"/></g><path fill="url(#iLaJy2K)" class="s0_pk0b8f"/><path fill="url(#iHqrbFv)" class="s0_pk0b8f"/><path fill="url(#isOAzKb)" class="s0_pk0b8f"/><path fill="url(#incshFe)" class="s0_pk0b8f"/><path fill="url(#ikhw9mz)" class="s0_pk0b8f"/><path fill="url(#i1vc6hc)" class="s0_pk0b8f"/><path fill="url(#iRWTmnc)" class="s0_pk0b8f"/><path fill="url(#i0btdGb)" class="s0_pk0b8f"/><g filter="url(#ibUb7sc)"><path class="fclb0ab6s"/></g><g filter="url(#ivwrDCe)"><path class="qcj1azgqb"/><path fill="url(#ihJxu3c)" class="x8wej50xc"/><path fill="url(#i8kxYRd)" class="x8wej50xc"/><path fill="url(#i2xR2yc)" class="x8wej50xc"/><path fill="url(#iMfLrae)" class="x8wej50xc"/></g><g filter="url(#iI4IoPc)"><path stroke="url(#ih83zbe)" class="snqb9vbfx"/></g><path fill="url(#iW1fIIb)" class="pmq6e3bfb"/><g filter="url(#ikNNKib)"><path fill="url(#iaz1vlb)" class="hkq60bc0j"/></g><path fill="url(#ikrgvGe)" class="hkq60bc0j"/><path fill="url(#iZzwzVd)" class="hkq60bc0j"/><path fill="url(#iKYEq5c)" class="hkq60bc0j"/><g filter="url(#iK66m6b)"><path class="c460libih"/></g><g filter="url(#ieed3Ed)"><path class="r5xl_rbek"/></g><g filter="url(#iEuvs2d)"><path class="foeokcbhk"/><path fill="url(#i1hWJZx)" class="gy1-g1k7m"/><path fill="url(#iqIOb5c)" class="gy1-g1k7m"/></g><g filter="url(#ig8QFrc)"><path class="gmhxxfsuk"/><path fill="url(#i7Rs14B)" class="wzzpsp2nr"/><path fill="url(#i4PaIUV)" class="wzzpsp2nr"/><path fill="url(#i0stPHb)" class="wzzpsp2nr"/></g><path class="xmm-zsbso"/><path fill="url(#i7tpboc)" class="fybni6bjd"/><path class="yniof8bcm"/><g filter="url(#iWqqcMe)"><path class="rgak10b7q"/><path fill="url(#i4h5zJc)" class="f7t6fqb9p"/></g><g filter="url(#i0wAcWR)"><path fill="url(#ieUIsUb)" class="g5zjc-bnl"/></g><path class="lxkfx39hx"/><path fill="url(#ijIMMUd)" class="l-l5eobrc"/><path class="afibpcr-t"/><g filter="url(#iB3m3Cv)"><path fill="url(#iIVyFYb)" class="vgm-ugbvo"/></g><g filter="url(#ixUSmtc)"><ellipse transform="rotate(-27.914 13.093 5.695)" class="tfbfyubeo"/><ellipse fill="url(#i63QHlb)" transform="rotate(-27.914 13.093 5.695)" class="h9ufu6biz"/></g><path fill="url(#i6hVY6d)" class="lud9hwblg"/><path fill="url(#i9mxcSb)" class="lud9hwblg"/><path fill="url(#ijRPune)" class="lud9hwblg"/><path fill="url(#iCGJy2d)" class="lud9hwblg"/><path fill="url(#iZtHSIc)" class="rl7c1sw4y"/><path fill="url(#in5pZze)" class="rl7c1sw4y"/><g filter="url(#idYLsTc)"><path fill="url(#iFA9Z9b)" class="c82dd39yk"/></g><g filter="url(#i8dJmSd)"><path fill="url(#iQ2vXZg)" class="t9rw6xbgs"/></g><g filter="url(#izFkzde)"><path class="yujm55bam"/></g><defs><radialGradient id="ibC1qLe" cx="0" cy="0" r="1" gradientTransform="matrix(3.84373 7.81251 -11.27829 5.54887 20.985 21.77)" gradientUnits="userSpaceOnUse"><stop offset=".7" class="er0557b1s"/><stop offset=".913" class="qg0p67bet"/></radialGradient><radialGradient id="i1wcfOb" cx="0" cy="0" r="1" gradientTransform="matrix(3.5625 -6.125 3.8162 2.21963 22.204 21.926)" gradientUnits="userSpaceOnUse"><stop class="vj0--9brr"/><stop offset="1" class="holozbkuz"/></radialGradient><radialGradient id="id94ewd" cx="0" cy="0" r="1" gradientTransform="matrix(2.15625 -12.12496 23.16436 4.11944 23.61 28.77)" gradientUnits="userSpaceOnUse"><stop offset=".931" class="ro0d6lgcg"/><stop offset="1" class="ghsb7_-dv"/></radialGradient><radialGradient id="iTH78cb" cx="0" cy="0" r="1" gradientTransform="matrix(1.09706 3.375 -16.62038 5.40254 16.17 25.208)" gradientUnits="userSpaceOnUse"><stop offset=".716" class="czuo201bw"/><stop offset="1" class="ecs-9379l"/></radialGradient><radialGradient id="iTIjaLd" cx="0" cy="0" r="1" gradientTransform="matrix(-.83721 2.51163 -.64638 -.21546 9.76 25.141)" gradientUnits="userSpaceOnUse"><stop class="gsejooqnz"/><stop offset="1" class="of4__9yml"/></radialGradient><radialGradient id="isyGmte" cx="0" cy="0" r="1" gradientTransform="matrix(-.73437 -1.28906 .42946 -.24466 23.579 25.473)" gradientUnits="userSpaceOnUse"><stop class="kzew_oulk"/><stop offset="1" class="ui2bqrbyd"/></radialGradient><radialGradient id="i0RjV5w" cx="0" cy="0" r="1" gradientTransform="rotate(-110.045 20.742 2.818)scale(2.46162 1.62421)" gradientUnits="userSpaceOnUse"><stop class="of_rz239k"/><stop offset="1" class="lvv_hcmig"/></radialGradient><radialGradient id="ilkWDkd" cx="0" cy="0" r="1" gradientTransform="rotate(146.686 11.215 11.138)scale(2.36974 1.91739)" gradientUnits="userSpaceOnUse"><stop offset=".171" class="b07bm3qgt"/><stop offset="1" class="n-jrenige"/></radialGradient><radialGradient id="iR7ViFc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.47607 .92253 -.74644 -1.19432 29.42 12.556)" gradientUnits="userSpaceOnUse"><stop class="fdd72shlv"/><stop offset="1" class="n-jrenige"/></radialGradient><radialGradient id="iVwnzxc" cx="0" cy="0" r="1" gradientTransform="rotate(147.995 12.168 9.172)scale(1.52552 1.23432)" gradientUnits="userSpaceOnUse"><stop class="fdd72shlv"/><stop offset="1" class="n-jrenige"/></radialGradient><radialGradient id="iWebikb" cx="0" cy="0" r="1" gradientTransform="matrix(-.06342 .73199 -.55995 -.04852 21.024 13.108)" gradientUnits="userSpaceOnUse"><stop offset=".317" class="eb_ebqvii"/><stop offset="1" class="wqensyb5w"/></radialGradient><radialGradient id="icaasDe" cx="0" cy="0" r="1" gradientTransform="rotate(139.295 9.2 10.925)scale(2.80315 2.75944)" gradientUnits="userSpaceOnUse"><stop class="xtqzqnbwf"/><stop offset="1" class="god345nqf"/></radialGradient><radialGradient id="irkuSNb" cx="0" cy="0" r="1" gradientTransform="rotate(142.524 4.926 6.717)scale(4.72526 1.21438)" gradientUnits="userSpaceOnUse"><stop offset=".263" class="yt5sdf2gy"/><stop offset="1" class="n0_4eow9o"/></radialGradient><radialGradient id="idqNGMe" cx="0" cy="0" r="1" gradientTransform="rotate(103.462 2.335 10.553)scale(4.16121 1.35388)" gradientUnits="userSpaceOnUse"><stop class="nf0740e8o"/><stop offset="1" class="fltjd-k8p"/></radialGradient><radialGradient id="iMNduJc" cx="0" cy="0" r="1" gradientTransform="matrix(4.2188 -6.78122 .53719 .3342 11.329 24.426)" gradientUnits="userSpaceOnUse"><stop class="qfyn005sz"/><stop offset="1" class="inzu6lb7s"/></radialGradient><radialGradient id="iYKGKBb" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.09375 -2.46875 0 13.766 8.239)" gradientUnits="userSpaceOnUse"><stop offset=".543" class="fu31k5bmq"/><stop offset="1" class="zkqd2ycat"/></radialGradient><radialGradient id="inhy8AL" cx="0" cy="0" r="1" gradientTransform="rotate(24.436 -15.525 48.348)scale(3.39814 2.30082)" gradientUnits="userSpaceOnUse"><stop offset=".317" class="s41d30h-g"/><stop offset="1" class="woc0miqaj"/></radialGradient><radialGradient id="ibw8yfe" cx="0" cy="0" r="1" gradientTransform="rotate(-139.897 5.2 5.918)scale(1.34825 1.69882)" gradientUnits="userSpaceOnUse"><stop offset=".321" class="ajhe7ybyb"/><stop offset=".769" class="omf6kkb4j"/></radialGradient><radialGradient id="i7JGUkc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.24388 -.94214 1.33264 -1.75944 5.77 14.69)" gradientUnits="userSpaceOnUse"><stop offset=".321" class="ajhe7ybyb"/><stop offset=".769" class="omf6kkb4j"/></radialGradient><radialGradient id="iyLPjHb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.23007 -1.01775 1.46904 -1.7755 5.598 15.256)" gradientUnits="userSpaceOnUse"><stop offset=".321" class="ajhe7ybyb"/><stop offset=".769" class="omf6kkb4j"/></radialGradient><radialGradient id="iyiSuIb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.04688 -.89062 1.29178 -1.51843 5.802 15.488)" gradientUnits="userSpaceOnUse"><stop offset=".321" class="ajhe7ybyb"/><stop offset=".769" class="omf6kkb4j"/></radialGradient><radialGradient id="iCdksNe" cx="0" cy="0" r="1" gradientTransform="matrix(.14063 .15625 -.6598 .59382 7.037 14.78)" gradientUnits="userSpaceOnUse"><stop class="pzzto25mw"/><stop offset="1" class="pfxo1bxwi"/></radialGradient><radialGradient id="iR6HFdd" cx="0" cy="0" r="1" gradientTransform="rotate(135 10.508 15.402)scale(15.9541 20.2938)" gradientUnits="userSpaceOnUse"><stop class="q7quaubxc"/><stop offset="1" class="kf-sl5b6g"/></radialGradient><radialGradient id="iWcLq3b" cx="0" cy="0" r="1" gradientTransform="matrix(.33109 .89299 -1.0608 .3933 16.28 6.558)" gradientUnits="userSpaceOnUse"><stop offset=".215" class="hb-rh6b9c"/><stop offset="1" class="o5jc2cxps"/></radialGradient><radialGradient id="iX4Qx4b" cx="0" cy="0" r="1" gradientTransform="matrix(.65285 .20518 -.633 2.01409 11.5 6.775)" gradientUnits="userSpaceOnUse"><stop class="v_2gjcb5l"/><stop offset=".746" class="vzzhqfd0u"/></radialGradient><radialGradient id="iPFUx3f" cx="0" cy="0" r="1" gradientTransform="matrix(-2.08044 0 0 -3.68028 15.419 6.142)" gradientUnits="userSpaceOnUse"><stop class="hdsgirtov"/><stop offset="1" class="j213y8b_z"/></radialGradient><radialGradient id="ijes2hE" cx="0" cy="0" r="1" gradientTransform="matrix(-.77078 1.27477 -1.05243 -.63634 15.25 3.94)" gradientUnits="userSpaceOnUse"><stop offset=".078" class="v3vg2fbhx"/><stop offset="1" class="jon81gnkc"/></radialGradient><radialGradient id="iHqrbFv" cx="0" cy="0" r="1" gradientTransform="matrix(-.45202 5.49334 -4.54915 -.37433 14.877 3.527)" gradientUnits="userSpaceOnUse"><stop offset=".767" class="d830_kb2q"/><stop offset="1" class="z_hqhdb1q"/></radialGradient><radialGradient id="isOAzKb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.50777 .62837 0 15.26 5.562)" gradientUnits="userSpaceOnUse"><stop offset=".325" class="kud2-ccnc"/><stop offset="1" class="qjdbe6bhy"/></radialGradient><radialGradient id="incshFe" cx="0" cy="0" r="1" gradientTransform="matrix(.00174 -.48386 .52655 .0019 13.16 5.582)" gradientUnits="userSpaceOnUse"><stop offset=".378" class="g101ufbyh"/><stop offset="1" class="ofu8odbdi"/></radialGradient><radialGradient id="ikhw9mz" cx="0" cy="0" r="1" gradientTransform="rotate(176.388 7.744 3.537)scale(3.76418 9.61559)" gradientUnits="userSpaceOnUse"><stop offset=".836" class="c-0f6obbw"/><stop offset="1" class="q4oz8ebqu"/></radialGradient><radialGradient id="i1vc6hc" cx="0" cy="0" r="1" gradientTransform="rotate(-40.741 12.23 -12.58)scale(1.97594 .58366)" gradientUnits="userSpaceOnUse"><stop offset=".539" class="gl-yj8bin"/><stop offset="1" class="b1x_r2coy"/></radialGradient><radialGradient id="iRWTmnc" cx="0" cy="0" r="1" gradientTransform="matrix(-.10376 1.1043 -.44144 -.04148 16.63 4.852)" gradientUnits="userSpaceOnUse"><stop offset=".245" class="y4noiz6ri"/><stop offset="1" class="n64jnw11q"/></radialGradient><radialGradient id="i0btdGb" cx="0" cy="0" r="1" gradientTransform="matrix(0 .3854 -.73984 0 13.198 5.923)" gradientUnits="userSpaceOnUse"><stop class="rlwq00h2l"/><stop offset="1" class="uhv9b32lc"/></radialGradient><radialGradient id="i8kxYRd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .10794 -.33923 0 14.383 6.744)" gradientUnits="userSpaceOnUse"><stop class="ifoj0vbnx"/><stop offset="1" class="fd01o6-ig"/></radialGradient><radialGradient id="iMfLrae" cx="0" cy="0" r="1" gradientTransform="matrix(-.74818 .33167 -.53303 -1.20239 14.435 6.492)" gradientUnits="userSpaceOnUse"><stop offset=".702" class="xqbp6db-u"/><stop offset="1" class="l6ffphqdg"/><stop offset="1" class="bi0efq_rm"/></radialGradient><radialGradient id="iW1fIIb" cx="0" cy="0" r="1" gradientTransform="matrix(.96482 -.47433 1.90835 3.8817 13.96 7.744)" gradientUnits="userSpaceOnUse"><stop offset=".562" class="i_5kuqxuv"/><stop offset="1" class="iazz9lb4s"/></radialGradient><radialGradient id="ikrgvGe" cx="0" cy="0" r="1" gradientTransform="rotate(-69.027 9.674 -5.828)scale(3.38566 4.80422)" gradientUnits="userSpaceOnUse"><stop class="gzjm9absi"/><stop offset="1" class="xys9jruze"/></radialGradient><radialGradient id="iZzwzVd" cx="0" cy="0" r="1" gradientTransform="matrix(-.6718 -2.8979 4.11209 -.95328 16.686 5.317)" gradientUnits="userSpaceOnUse"><stop offset=".303" class="gzjm9absi"/><stop offset="1" class="xys9jruze"/></radialGradient><radialGradient id="iKYEq5c" cx="0" cy="0" r="1" gradientTransform="matrix(-.50055 -1.05378 1.244 -.59091 15.605 3.42)" gradientUnits="userSpaceOnUse"><stop class="vm3i05jbz"/><stop offset="1" class="o0n2z3bef"/></radialGradient><radialGradient id="i1hWJZx" cx="0" cy="0" r="1" gradientTransform="matrix(-.97328 0 0 -.36122 14.29 2.962)" gradientUnits="userSpaceOnUse"><stop class="ur78mwbxs"/><stop offset="1" class="xxn4m8bxd"/></radialGradient><radialGradient id="iqIOb5c" cx="0" cy="0" r="1" gradientTransform="matrix(1.42299 -2.25307 2.49617 1.57653 11.776 4.705)" gradientUnits="userSpaceOnUse"><stop offset=".093" class="oxzu0y4el"/><stop offset=".311" class="h09cq_pwq"/><stop offset="1" class="fdnwjygjt"/></radialGradient><radialGradient id="i7Rs14B" cx="0" cy="0" r="1" gradientTransform="rotate(-38.837 13.317 -19.266)scale(1.99546 3.09253)" gradientUnits="userSpaceOnUse"><stop class="wv5n4khjs"/><stop offset=".445" class="oywlam1jg"/></radialGradient><radialGradient id="i4PaIUV" cx="0" cy="0" r="1" gradientTransform="rotate(-41.829 13.753 -17.749)scale(1.75582 3.21446)" gradientUnits="userSpaceOnUse"><stop offset=".857" class="ut-a4zo6y"/><stop offset="1" class="mw5vlrbvk"/></radialGradient><radialGradient id="i0stPHb" cx="0" cy="0" r="1" gradientTransform="matrix(1.42613 .3202 -.13406 .5971 14.96 3.843)" gradientUnits="userSpaceOnUse"><stop class="rxg51vbwm"/><stop offset="1" class="g9z9sr5ky"/></radialGradient><radialGradient id="i7tpboc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .35874 -.57062 0 15.142 5.737)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="bbyb_mbsk"/></radialGradient><radialGradient id="i4h5zJc" cx="0" cy="0" r="1" gradientTransform="matrix(-.10255 -.13215 .18193 -.14118 15.041 5.774)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="ijIMMUd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .35876 -.57065 0 13.213 5.737)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="bbyb_mbsk"/></radialGradient><radialGradient id="i63QHlb" cx="0" cy="0" r="1" gradientTransform="matrix(-.00342 -.21847 .26261 -.00411 13.086 5.834)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="i9mxcSb" cx="0" cy="0" r="1" gradientTransform="matrix(.27792 .99192 -.94637 .26516 16.22 5.743)" gradientUnits="userSpaceOnUse"><stop offset=".856" class="k-8l2bbtm"/><stop offset="1" class="j8b6y4byx"/></radialGradient><radialGradient id="ijRPune" cx="0" cy="0" r="1" gradientTransform="rotate(-53.92 14.072 -13.108)scale(.59149 .49578)" gradientUnits="userSpaceOnUse"><stop offset=".664" class="gvb-xxmau"/><stop offset="1" class="wbdnw-owo"/></radialGradient><radialGradient id="iCGJy2d" cx="0" cy="0" r="1" gradientTransform="matrix(.25955 -.68556 .916 .3468 16.429 6.06)" gradientUnits="userSpaceOnUse"><stop offset=".803" class="nx86noq5t"/><stop offset="1" class="mchm9tbqp"/></radialGradient><radialGradient id="in5pZze" cx="0" cy="0" r="1" gradientTransform="matrix(-.73324 0 0 -.81876 12.004 6.027)" gradientUnits="userSpaceOnUse"><stop offset=".778" class="ok_b4wzpx"/><stop offset="1" class="mtikk0bwo"/></radialGradient><radialGradient id="iFA9Z9b" cx="0" cy="0" r="1" gradientTransform="matrix(-.40524 .06956 -.07132 -.4155 12.005 6.028)" gradientUnits="userSpaceOnUse"><stop class="qkgshibem"/><stop offset="1" class="b89ok8b-l"/></radialGradient><filter id="ihe15Vd" width="23.977" height="13.398" x="6.016" y="16.362" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.25098 0 0 0 0 0.729412 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_22997"/></filter><filter id="itwlbLc" width="20.681" height="10.082" x="6.11" y="20.25" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_22997" stdDeviation=".75"/></filter><filter id="iIdbKtc" width="24.344" height="8.644" x="2.007" y="21.127" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.490196 0 0 0 0 0.415686 0 0 0 0 0.839216 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_22997"/></filter><filter id="i9R24Fc" width="2.686" height="2.686" x="24.571" y="13.369" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.290196 0 0 0 0 0.619608 0 0 0 0 0.952941 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_22997"/></filter><filter id="iwfZpxd" width="2.186" height="2.186" x="27.821" y="11.67" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.290196 0 0 0 0 0.619608 0 0 0 0 0.952941 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_22997"/></filter><filter id="iziWXMb" width="1.928" height="1.928" x="25.946" y="9.713" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".225"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.290196 0 0 0 0 0.619608 0 0 0 0 0.952941 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_22997"/></filter><filter id="i1KLQke" width="2.857" height="2.898" x="20.532" y="12.137" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.592157 0 0 0 0 0.34902 0 0 0 0 0.313726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_22997"/></filter><filter id="iGpMn6b" width="5.571" height="6.952" x="7.773" y="7.834" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.15" dy="-.6"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.976471 0 0 0 0 0.305882 0 0 0 0 0.196078 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_22997"/></filter><filter id="iJoyMQb" width="14.97" height="18.153" x="8.427" y="7.606" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy=".2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.521569 0 0 0 0 0.415686 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_22997"/></filter><filter id="i5YMdac" width="17.737" height="14.8" x="13.579" y="15.851" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_22997" stdDeviation="1"/></filter><filter id="iXgdUAb" width="6.506" height="14.75" x="14.572" y="7.41" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_22997" stdDeviation=".375"/></filter><filter id="iSApWRb" width="5.506" height="5.421" x="17.991" y="7.485" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_22997" stdDeviation=".3"/></filter><filter id="iPnilbd" width="5.519" height="5.557" x="11.939" y="3.413" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1"/><feGaussianBlur stdDeviation=".7"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.584314 0 0 0 0 0.427451 0 0 0 0 0.376471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_22997"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".1"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.419608 0 0 0 0 0.25098 0 0 0 0 0.262745 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_22997" result="effect2_innerShadow_3987_22997"/></filter><filter id="ibUb7sc" width="2.772" height="3.282" x="12.728" y="4.777" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_22997" stdDeviation=".5"/></filter><filter id="ivwrDCe" width=".93" height="1.382" x="13.712" y="5.641" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_22997" stdDeviation=".025"/></filter><filter id="iI4IoPc" width="1.723" height=".774" x="13.316" y="7.12" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_22997" stdDeviation=".05"/></filter><filter id="ikNNKib" width="5.692" height="3.974" x="11.331" y="1.73" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.266667 0 0 0 0 0.152941 0 0 0 0 0.184314 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_22997"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.258824 0 0 0 0 0.133333 0 0 0 0 0.172549 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_22997" result="effect2_innerShadow_3987_22997"/></filter><filter id="iK66m6b" width="1.09" height=".638" x="14.88" y="4.402" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.243137 0 0 0 0 0.121569 0 0 0 0 0.2 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_22997"/></filter><filter id="ieed3Ed" width="1.09" height=".631" x="12.556" y="4.408" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.243137 0 0 0 0 0.121569 0 0 0 0 0.2 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_22997"/></filter><filter id="iEuvs2d" width="2.89" height="2.608" x="11.499" y="2.522" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.364706 0 0 0 0 0.286275 0 0 0 0 0.270588 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_22997"/><feGaussianBlur result="effect2_foregroundBlur_3987_22997" stdDeviation=".05"/></filter><filter id="ig8QFrc" width="3.67" height="2.927" x="14.14" y="2.326" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1" dy="-.5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.282353 0 0 0 0 0.168627 0 0 0 0 0.188235 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_22997"/><feGaussianBlur result="effect2_foregroundBlur_3987_22997" stdDeviation=".075"/></filter><filter id="iWqqcMe" width=".459" height=".419" x="14.762" y="5.487" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_22997" stdDeviation=".05"/></filter><filter id="i0wAcWR" width=".617" height=".627" x="15.078" y="5.464" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_22997" stdDeviation=".1"/></filter><filter id="iB3m3Cv" width=".659" height=".683" x="13.113" y="5.436" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_22997" stdDeviation=".1"/></filter><filter id="ixUSmtc" width=".515" height=".423" x="12.835" y="5.483" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_22997" stdDeviation=".05"/></filter><filter id="idYLsTc" width=".867" height="1.331" x="11.349" y="5.362" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_22997" stdDeviation=".125"/></filter><filter id="i8dJmSd" width="1.356" height="1.777" x="15.911" y="5.136" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_22997" stdDeviation=".25"/></filter><filter id="izFkzde" width="2.21" height="1.184" x="14.708" y="2.971" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_22997" stdDeviation=".125"/></filter><linearGradient id="iYUPgCn" x1="7.172" x2="16.735" y1="29.364" y2="29.364" gradientUnits="userSpaceOnUse"><stop class="e_8e_fe6a"/><stop offset="1" class="t2zfh_b3c"/></linearGradient><linearGradient id="iIAQn6c" x1="16.86" x2="16.766" y1="30.27" y2="28.645" gradientUnits="userSpaceOnUse"><stop offset=".178" class="oste98bcz"/><stop offset="1" class="ojj5yabro"/></linearGradient><linearGradient id="ioDmBkd" x1="21.172" x2="19.469" y1="21.926" y2="23.012" gradientUnits="userSpaceOnUse"><stop class="szw4sibdg"/><stop offset="1" class="k794rrb7o"/></linearGradient><linearGradient id="ijic07z" x1="22.095" x2="23.329" y1="24.832" y2="26.114" gradientUnits="userSpaceOnUse"><stop class="jikp3gouc"/><stop offset="1" class="esa0tobpk"/></linearGradient><linearGradient id="icOIhCe" x1="5.891" x2="25.735" y1="29.239" y2="22.332" gradientUnits="userSpaceOnUse"><stop class="d9q_ne9mx"/><stop offset="1" class="y110racyj"/></linearGradient><linearGradient id="i1Jl7Lb" x1="15.777" x2="15.777" y1="7.606" y2="25.567" gradientUnits="userSpaceOnUse"><stop class="nmvycabwt"/><stop offset=".978" class="xujwu-wlk"/></linearGradient><linearGradient id="i4w2n6b" x1="22.329" x2="16.517" y1="11.925" y2="8.549" gradientUnits="userSpaceOnUse"><stop class="ku_swbhun"/><stop offset=".888" class="upowizugn"/></linearGradient><linearGradient id="iXY4Urd" x1="17.826" x2="20.269" y1="8.16" y2="21.397" gradientUnits="userSpaceOnUse"><stop class="e95gaqibw"/><stop offset="1" class="mtqjbpbdp"/></linearGradient><linearGradient id="izUdOib" x1="22.438" x2="18.766" y1="11.879" y2="7.989" gradientUnits="userSpaceOnUse"><stop class="yjjppjb0c"/><stop offset="1" class="fvilr_bly"/></linearGradient><linearGradient id="iLaJy2K" x1="16.458" x2="15.34" y1="6.887" y2="6.887" gradientUnits="userSpaceOnUse"><stop class="cgoojyxdz"/><stop offset="1" class="zvhz6qbam"/></linearGradient><linearGradient id="ihJxu3c" x1="14.548" x2="14.177" y1="6.44" y2="6.456" gradientUnits="userSpaceOnUse"><stop offset=".36" class="gb7af0bvz"/><stop offset="1" class="gafrz43pc"/></linearGradient><linearGradient id="i2xR2yc" x1="14.177" x2="14.177" y1="6.944" y2="6.738" gradientUnits="userSpaceOnUse"><stop class="q7066kb0m"/><stop offset="1" class="se5f_fbvx"/></linearGradient><linearGradient id="ih83zbe" x1="13.646" x2="13.787" y1="7.639" y2="7.27" gradientUnits="userSpaceOnUse"><stop class="sjwz8ccmm"/><stop offset="1" class="itcx93bci"/></linearGradient><linearGradient id="iaz1vlb" x1="17.207" x2="12.073" y1="3.638" y2="3.638" gradientUnits="userSpaceOnUse"><stop offset=".471" class="vj4yuc0qg"/><stop offset="1" class="yd6vs-kvu"/></linearGradient><linearGradient id="ieUIsUb" x1="15.486" x2="15.348" y1="5.761" y2="5.846" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iIVyFYb" x1="13.542" x2="13.403" y1="5.761" y2="5.846" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="i6hVY6d" x1="17.023" x2="16.49" y1="5.773" y2="6.735" gradientUnits="userSpaceOnUse"><stop class="r-tgpdb_v"/><stop offset="1" class="o8077h_4a"/></linearGradient><linearGradient id="iZtHSIc" x1="11.591" x2="12.236" y1="6.084" y2="6.028" gradientUnits="userSpaceOnUse"><stop class="d7c3jfbwh"/><stop offset="1" class="zvm05wbin"/></linearGradient><linearGradient id="iQ2vXZg" x1="16.589" x2="16.589" y1="5.636" y2="6.413" gradientUnits="userSpaceOnUse"><stop class="aj8ithlra"/><stop offset="1" class="a9_46dbsd"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:person-surfing-medium" /></template>
<style>
.a5a4koq8x {
  cx: 26.86px;
  cy: 10.727px;
  r: 0.914px;
}

.a9_46dbsd {
  stop-color: var(--svg-color--ad806f, #AD806F);
}

.afibpcr-t {
  fill: var(--svg-color--000, #000);
  d: path("M13.438 5.92c0-.125-.1-.225-.226-.225a.225.225 0 0 0-.201.33h.4a.2.2 0 0 0 .027-.104");
}

.aj8ithlra {
  stop-color: var(--svg-color--ac7f6f, #AC7F6F);
}

.ajhe7ybyb {
  stop-color: var(--svg-color--9b686d, #9B686D);
}

.b07bm3qgt {
  stop-color: var(--svg-color--64ddff, #64DDFF);
}

.b1x_r2coy {
  stop-color: var(--svg-color--63413d, #63413D);
  stop-opacity: 0;
}

.b89ok8b-l {
  stop-color: var(--svg-color--784e52, #784E52);
}

.bbyb_mbsk {
  stop-color: var(--svg-color--664842, #664842);
}

.bi0efq_rm {
  stop-color: var(--svg-color--8a5f5c, #8A5F5C);
}

.c-0f6obbw {
  stop-color: var(--svg-color--987064, #987064);
  stop-opacity: 0;
}

.c460libih {
  fill: var(--svg-color--462d2b, #462D2B);
  d: path("M15.828 4.825a.8.8 0 0 0-.304-.182c-.135-.043-.303-.054-.536-.026a.123.123 0 1 0 .03.244c.212-.026.343-.013.432.016a.6.6 0 0 1 .217.132a.123.123 0 0 0 .16-.184");
}

.c82dd39yk {
  d: path("M11.929 5.612a.423.423 0 0 0 .037.831a34 34 0 0 1-.037-.83");
}

.cgoojyxdz {
  stop-color: var(--svg-color--c2987e, #C2987E);
}

.cjqtkw6wk {
  d: path("M12.759 11.653c-.432-1.716.169-3.162.507-3.485l2.344-.562h1.742c1.524 0 2.822.189 4.203 1.258c1.354 1.047 1.622 2.799 1.589 3.592a.05.05 0 0 1-.051.046l-1.989-.074a.05.05 0 0 1-.049-.058c.038-.371-.066-1.273-1-2.014c-.606-.481-1.519-.532-2.146-.494a.373.373 0 0 0-.323.498c.316.955.84 2.513 1.212 3.52c.546 1.484-.11 2.952.375 4.484c.377 1.191 1.203 2.418 1.636 2.92a.04.04 0 0 1-.013.063l-1.834.852a.04.04 0 0 1-.048-.01c-1.848-2.158-2.5-3.826-2.562-3.99s-.23-.53-.574-.53c-.275 0-.59.35-.809.73l-4.667 7.137a.05.05 0 0 1-.056.02l-1.783-.52a.05.05 0 0 1-.032-.068c1.499-3.164 4.542-9.51 4.773-10.057c.21-.5.181-.917.14-1.086c-.03-.13-.218-.711-.585-2.172");
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.czuo201bw {
  stop-color: var(--svg-color--37a9ff, #37A9FF);
  stop-opacity: 0;
}

.d7c3jfbwh {
  stop-color: var(--svg-color--855d5a, #855D5A);
}

.d830_kb2q {
  stop-color: var(--svg-color--a16f71, #A16F71);
  stop-opacity: 0;
}

.d9q_ne9mx {
  stop-color: var(--svg-color--f54696, #F54696);
}

.dkktn1hof {
  cx: 25.864px;
  cy: 14.762px;
  r: 1.293px;
}

.dldw44uej {
  fill: var(--svg-color--aa846a, #AA846A);
  d: path("M7.602 12.776h.594c-.106.669.012 1.608.114 1.996c-1.006.131-1.637-.108-1.856-.246l-.11-1.461c.332-.256.977-.3 1.258-.29");
}

.e_8e_fe6a {
  stop-color: var(--svg-color--2d7cf2, #2D7CF2);
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.e95gaqibw {
  stop-color: var(--svg-color--ff965a, #FF965A);
}

.eb_ebqvii {
  stop-color: var(--svg-color--94625a, #94625A);
}

.ecs-9379l {
  stop-color: var(--svg-color--37a9ff, #37A9FF);
}

.ekge1hb-m {
  fill: var(--svg-color--aa846a, #AA846A);
  d: path("M6.126 14.887c.125-.137.398-.46.52-.605c.23 0 .91-.067 1.198-.098c-.39.715-.84 1.004-1.074 1.195c-.316.211-.605 0-.644-.066c-.047-.047-.157-.254 0-.426");
}

.er0557b1s {
  stop-color: var(--svg-color--3eb9ff, #3EB9FF);
  stop-opacity: 0;
}

.esa0tobpk {
  stop-color: var(--svg-color--9157c5, #9157C5);
}

.f7t6fqb9p {
  d: path("M15.114 5.61c.028.037-.03.083-.097.133s-.117.085-.145.047c-.028-.037.003-.108.07-.158s.144-.06.172-.023");
}

.fclb0ab6s {
  fill: var(--svg-color--6f3f46, #6F3F46);
  d: path("m14 5.913l-.261.812c-.045.168.062.335.214.335h.323c.152 0 .26-.17.215-.335l-.22-.812c-.046-.18-.222-.18-.271 0");
}

.fd01o6-ig {
  stop-color: var(--svg-color--c59a8a, #C59A8A);
  stop-opacity: 0;
}

.fdd72shlv {
  stop-color: var(--svg-color--65e0ff, #65E0FF);
}

.fdnwjygjt {
  stop-color: var(--svg-color--472438, #472438);
  stop-opacity: 0;
}

.fltjd-k8p {
  stop-color: var(--svg-color--ff4a2b, #FF4A2B);
  stop-opacity: 0;
}

.foeokcbhk {
  fill: var(--svg-color--533634, #533634);
  d: path("m14.28 3.659l-.029-.06a.29.29 0 0 0-.272-.186h-.563c-.816 0-1.477.67-1.477 1.495v.121c-.15-.114-.34-.355-.34-.746c0-.474.346-.714.566-.866c.063-.043.115-.08.147-.112l.044-.047c.154-.164.43-.456.91-.583q.109-.03.216-.045c.467-.073.808.346.808.819v.204z");
}

.ft5dv1b6b {
  fill: none;
}

.fu31k5bmq {
  stop-color: var(--svg-color--ff5714, #FF5714);
}

.fugdzyb1o {
  fill: var(--svg-color--ab7f67, #AB7F67);
  d: path("m7.305 27.348l1.172-2.39l1.766.304v1.04z");
}

.fvilr_bly {
  stop-color: var(--svg-color--ff9e61, #FF9E61);
  stop-opacity: 0;
}

.fybni6bjd {
  d: path("M15.143 5.526a.395.395 0 0 1 .38.499h-.762a.396.396 0 0 1 .382-.499");
}

.g101ufbyh {
  stop-color: var(--svg-color--8f5d66, #8F5D66);
}

.g313knb1g {
  d: path("M16.327 6.695a.73.73 0 0 0 .4-.137v.412a.96.96 0 0 1-.593.893q.113-.24.153-.522z");
}

.g5zjc-bnl {
  d: path("M15.495 5.869a.37.37 0 0 0-.103-.205l-.114.126l.051.101z");
}

.g9z9sr5ky {
  stop-color: var(--svg-color--4f2b3c, #4F2B3C);
  stop-opacity: 0;
}

.gafrz43pc {
  stop-color: var(--svg-color--cea58c, #CEA58C);
  stop-opacity: 0;
}

.gb7af0bvz {
  stop-color: var(--svg-color--cea58c, #CEA58C);
}

.ghsb7_-dv {
  stop-color: var(--svg-color--66b4dd, #66B4DD);
}

.gl-yj8bin {
  stop-color: var(--svg-color--63413d, #63413D);
}

.gmhxxfsuk {
  fill: var(--svg-color--563936, #563936);
  d: path("m16.482 5.103l-.012-.279a.65.65 0 0 0-.622-.63h-.619a1.07 1.07 0 0 1-.94-.557s.32-.92.848-.8c.386.087.799.223 1.115.43c.771.503.636 1.41.23 1.836");
}

.god345nqf {
  stop-color: var(--svg-color--a1706f, #A1706F);
}

.gsejooqnz {
  stop-color: var(--svg-color--ba917f, #BA917F);
}

.gvb-xxmau {
  stop-color: var(--svg-color--9e6a5c, #9E6A5C);
}

.gy1-g1k7m {
  d: path("m14.28 3.659l-.029-.06a.29.29 0 0 0-.272-.186h-.563c-.816 0-1.477.67-1.477 1.495v.121c-.15-.114-.34-.355-.34-.746c0-.474.346-.714.566-.866c.063-.043.115-.08.147-.112l.044-.047c.154-.164.43-.456.91-.583q.109-.03.216-.045c.467-.073.808.346.808.819v.204z");
}

.gzjm9absi {
  stop-color: var(--svg-color--604946, #604946);
}

.h09cq_pwq {
  stop-color: var(--svg-color--472438, #472438);
}

.h9ufu6biz {
  cx: 13.093px;
  cy: 5.695px;
  rx: 0.172px;
  ry: 0.087px;
}

.hb-rh6b9c {
  stop-color: var(--svg-color--493b3b, #493B3B);
}

.hdsgirtov {
  stop-color: var(--svg-color--c89980, #C89980);
}

.hkq60bc0j {
  d: path("M16.324 3.205a1.048 1.048 0 0 1 .514 1.582a.7.7 0 0 0-.12.386V5.7a.8.8 0 0 0-.295-.12l.035-.71a.64.64 0 0 0-.61-.633h-.62c-.421 0-.803-.249-.977-.638a.29.29 0 0 0-.272-.185h-.563c-.816 0-1.477.67-1.477 1.495l.013.68a.8.8 0 0 0-.318.116v-.53a.7.7 0 0 0-.12-.387a1.06 1.06 0 0 1-.063-1.082a1.04 1.04 0 0 1 .574-.498c.254-.09.47-.26.612-.49a1.03 1.03 0 0 1 1.279-.404a.66.66 0 0 0 .527 0a1.03 1.03 0 0 1 1.283.417c.136.226.35.39.598.475");
}

.hksadnbgt {
  d: path("M12.028 6.695a.73.73 0 0 1-.4-.137v.412a.96.96 0 0 0 .593.893a1.8 1.8 0 0 1-.153-.522z");
}

.holozbkuz {
  stop-color: var(--svg-color--4db5e2, #4DB5E2);
  stop-opacity: 0;
}

.hr107sbjg {
  d: path("m7.305 27.348l1.172-2.39l1.766.304v1.04z");
}

.i_5kuqxuv {
  stop-color: var(--svg-color--87014e, #87014E);
}

.iazz9lb4s {
  stop-color: var(--svg-color--87004d, #87004D);
}

.ifoj0vbnx {
  stop-color: var(--svg-color--c59a8a, #C59A8A);
}

.inzu6lb7s {
  stop-color: var(--svg-color--ff3e28, #FF3E28);
  stop-opacity: 0;
}

.itcx93bci {
  stop-color: var(--svg-color--ab817b, #AB817B);
  stop-opacity: 0;
}

.iwur3y2uz {
  fill: var(--svg-color--ab8572, #AB8572);
  fill-rule: evenodd;
  d: path("M5.25 14.667q-.005.007-.002 0a.375.375 0 0 1-.69-.295c.056-.129.165-.253.27-.354a2.5 2.5 0 0 1 .438-.328a2.5 2.5 0 0 1 1.336-.37a.375.375 0 1 1-.023.75a1.73 1.73 0 0 0-.927.263a1.8 1.8 0 0 0-.307.23a1 1 0 0 0-.095.104");
}

.j213y8b_z {
  stop-color: var(--svg-color--926763, #926763);
}

.j6zxuhbzj {
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M18.594 8.286c1.209-.021 3.782.828 4.104 4");
}

.j8b6y4byx {
  stop-color: var(--svg-color--9a676a, #9A676A);
}

.jikp3gouc {
  stop-color: var(--svg-color--b041ab, #B041AB);
}

.jon81gnkc {
  stop-color: var(--svg-color--af887b, #AF887B);
  stop-opacity: 0;
}

.k-8l2bbtm {
  stop-color: var(--svg-color--9a676a, #9A676A);
  stop-opacity: 0;
}

.k794rrb7o {
  stop-color: var(--svg-color--82574c, #82574C);
}

.kf-sl5b6g {
  stop-color: var(--svg-color--67ecff, #67ECFF);
  stop-opacity: 0;
}

.ku_swbhun {
  stop-color: var(--svg-color--ff8444, #FF8444);
}

.kud2-ccnc {
  stop-color: var(--svg-color--ab7872, #AB7872);
}

.kzew_oulk {
  stop-color: var(--svg-color--b77dc7, #B77DC7);
}

.l-l5eobrc {
  d: path("M13.212 5.526a.395.395 0 0 0-.38.499h.762a.397.397 0 0 0-.382-.499");
}

.l6ffphqdg {
  stop-color: var(--svg-color--744a4a, #744A4A);
}

.lalq_3f3j {
  d: path("M6.126 14.887c.125-.137.398-.46.52-.605c.23 0 .91-.067 1.198-.098c-.39.715-.84 1.004-1.074 1.195c-.316.211-.605 0-.644-.066c-.047-.047-.157-.254 0-.426");
}

.lbpgcfbob {
  d: path("M24.458 21.262L2.29 28.951a.421.421 0 0 0 .138.819h3.948c.487 0 .968-.099 1.156-.156c5.922-2.016 17.406-5.86 18.176-6.2c.443-.195.511-.378.605-.627v-.001c.094-.25.047-1.032-.5-1.454c-.437-.337-1.105-.184-1.355-.07");
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.llo96eq-p {
  d: path("M17.568 10.277a.37.37 0 0 1 .34-.415c.628-.038 1.541.013 2.147.494c.934.74 1.038 1.643 1 2.014c-.003.03.02.057.05.058l1.987.074a.05.05 0 0 0 .052-.046c.033-.793-.235-2.545-1.589-3.592c-1.381-1.07-2.68-1.258-4.203-1.258h-.39c-.157 1.285.25 2.193.606 2.671");
}

.lud9hwblg {
  d: path("M16.354 6.735q.044-.705.081-1.411a.712.712 0 0 1-.081 1.411");
}

.lvv_hcmig {
  stop-color: var(--svg-color--9eaef5, #9EAEF5);
  stop-opacity: 0;
}

.lxkfx39hx {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.12 5.406a.62.62 0 0 0-.599.468a.12.12 0 0 0 .118.15h.987a.102.102 0 0 0 .1-.12a.62.62 0 0 0-.606-.498");
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mchm9tbqp {
  stop-color: var(--svg-color--a47f62, #A47F62);
}

.mtikk0bwo {
  stop-color: var(--svg-color--9d7667, #9D7667);
}

.mtqjbpbdp {
  stop-color: var(--svg-color--ff8064, #FF8064);
}

.mw5vlrbvk {
  stop-color: var(--svg-color--685351, #685351);
}

.n-63dkbfe {
  fill: var(--svg-color--ab8572, #AB8572);
  fill-rule: evenodd;
  d: path("M7.127 13.544c-.941-.284-1.295.01-1.388.119a.375.375 0 1 1-.57-.488c.328-.383 1.014-.699 2.174-.35a.375.375 0 0 1-.216.719");
}

.n-jrenige {
  stop-color: var(--svg-color--36b0fc, #36B0FC);
}

.n0_4eow9o {
  stop-color: var(--svg-color--ff875c, #FF875C);
  stop-opacity: 0;
}

.n64jnw11q {
  stop-color: var(--svg-color--bf9980, #BF9980);
  stop-opacity: 0;
}

.nf0740e8o {
  stop-color: var(--svg-color--ff4a2b, #FF4A2B);
}

.ngpy26t4k {
  fill-rule: evenodd;
  d: path("M5.25 14.667q-.005.007-.002 0a.375.375 0 0 1-.69-.295c.056-.129.165-.253.27-.354a2.5 2.5 0 0 1 .438-.328a2.5 2.5 0 0 1 1.336-.37a.375.375 0 1 1-.023.75a1.73 1.73 0 0 0-.927.263a1.8 1.8 0 0 0-.307.23a1 1 0 0 0-.095.104");
}

.nmvycabwt {
  stop-color: var(--svg-color--ff7a3c, #FF7A3C);
}

.nx86noq5t {
  stop-color: var(--svg-color--a47f62, #A47F62);
  stop-opacity: 0;
}

.o0n2z3bef {
  stop-color: var(--svg-color--765a55, #765A55);
  stop-opacity: 0;
}

.o5jc2cxps {
  stop-color: var(--svg-color--311f2c, #311F2C);
}

.o8077h_4a {
  stop-color: var(--svg-color--b08175, #B08175);
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.of_rz239k {
  stop-color: var(--svg-color--9eaef5, #9EAEF5);
}

.of4__9yml {
  stop-color: var(--svg-color--ba917f, #BA917F);
  stop-opacity: 0;
}

.ofu8odbdi {
  stop-color: var(--svg-color--8f5d66, #8F5D66);
  stop-opacity: 0;
}

.ojj5yabro {
  stop-color: var(--svg-color--7f8fff, #7F8FFF);
  stop-opacity: 0;
}

.ok_b4wzpx {
  stop-color: var(--svg-color--9d7667, #9D7667);
  stop-opacity: 0;
}

.omf6kkb4j {
  stop-color: var(--svg-color--9b686d, #9B686D);
  stop-opacity: 0;
}

.oste98bcz {
  stop-color: var(--svg-color--7f8fff, #7F8FFF);
}

.oxzu0y4el {
  stop-color: var(--svg-color--37192c, #37192C);
}

.oywlam1jg {
  stop-color: var(--svg-color--532c3f, #532C3F);
  stop-opacity: 0;
}

.pfxo1bxwi {
  stop-color: var(--svg-color--bd9484, #BD9484);
  stop-opacity: 0;
}

.pk84u7jjf {
  fill: var(--svg-color--4bc4fd, #4BC4FD);
  d: path("M19.75 29.748H6.017c3.433-1.326 10.769-4.346 12.657-5.818c2.359-1.84 2.937-3.291 4.109-4.976s2.062-2.293 3.922-2.036c1.691.235 3.164 1.575 3.289 4.04c0 4.593-2.74 6.555-4.164 7.51c-1.907 1.28-4.625 1.327-6.078 1.28");
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pmq6e3bfb {
  d: path("M14.177 7.423c-.224 0-.435-.053-.612-.145c-.06-.031-.126.037-.088.092a.84.84 0 0 0 .7.374c.294 0 .553-.15.7-.374c.039-.057-.026-.123-.087-.092a1.3 1.3 0 0 1-.613.145");
}

.pn5jbtt9h {
  d: path("M19.75 29.748H6.017c3.433-1.326 10.769-4.346 12.657-5.818c2.359-1.84 2.937-3.291 4.109-4.976s2.062-2.293 3.922-2.036c1.691.235 3.164 1.575 3.289 4.04c0 4.593-2.74 6.555-4.164 7.51c-1.907 1.28-4.625 1.327-6.078 1.28");
}

.pzzto25mw {
  stop-color: var(--svg-color--bd9484, #BD9484);
}

.q4oz8ebqu {
  stop-color: var(--svg-color--987064, #987064);
}

.q7066kb0m {
  stop-color: var(--svg-color--9c6376, #9C6376);
}

.q7quaubxc {
  stop-color: var(--svg-color--67ecff, #67ECFF);
}

.qcj1azgqb {
  fill: var(--svg-color--a3776d, #A3776D);
  d: path("m14.008 5.826l-.235.813c-.048.167.068.334.23.334h.348c.163 0 .278-.17.23-.334l-.235-.813c-.05-.18-.285-.18-.338 0");
}

.qd_9svrfx {
  d: path("M20.68 13.849c.256-.588.373-1.22.399-1.462l2.047.024c.046.268-.04.583-.079.703c.088.322.037.687 0 .829c-.054.225-.178.713-.238.86c-.074.183-.183.246-.348.23a.4.4 0 0 1-.148-.043a.3.3 0 0 0-.23-.018a.43.43 0 0 1-.227.018a.43.43 0 0 1-.204-.112a.22.22 0 0 0-.195-.06a.5.5 0 0 1-.226.004a.36.36 0 0 1-.172-.115a.22.22 0 0 0-.175-.07c-.085.007-.183.002-.235-.042c-.098-.082-.219-.175.031-.746");
}

.qe-ha1b7i {
  fill: var(--svg-color--ab8572, #AB8572);
  fill-rule: evenodd;
  d: path("M5.404 14.139s.02-.028.083-.08a2.1 2.1 0 0 1 1.279-.412a.375.375 0 0 0 .024-.749a2.84 2.84 0 0 0-1.323.295c-.176.087-.33.185-.452.284c-.11.089-.234.211-.296.355a.375.375 0 0 0 .685.306");
}

.qfyn005sz {
  stop-color: var(--svg-color--ff3e28, #FF3E28);
}

.qg0p67bet {
  stop-color: var(--svg-color--7196ff, #7196FF);
}

.qjdbe6bhy {
  stop-color: var(--svg-color--ab7872, #AB7872);
  stop-opacity: 0;
}

.qkgshibem {
  stop-color: var(--svg-color--714b4d, #714B4D);
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.r-tgpdb_v {
  stop-color: var(--svg-color--c9a188, #C9A188);
}

.r5xl_rbek {
  fill: var(--svg-color--462d2b, #462D2B);
  d: path("M12.67 4.776q.059-.038.169-.083c.144-.056.351-.106.599-.076a.123.123 0 1 1-.03.244a.98.98 0 0 0-.646.147l-.008.005v.001a.123.123 0 0 1-.15-.194z");
}

.r8fjj8bcd {
  d: path("M26.485 24.332c.981-2.278.626-3.886.055-5.013c-.474-.936-.003-1.662 1.018-1.421c.737.174 1.364.694 1.54 1.431c.721 3.025-.313 6.182-3.582 7.816c-2.95 1.475-7.854 1.594-9.937 1.469c3 0 9.804-1.723 10.906-4.282");
}

.rgak10b7q {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M15.114 5.61c.028.037-.03.083-.097.133s-.117.085-.145.047c-.028-.037.003-.108.07-.158s.144-.06.172-.023");
}

.rl7c1sw4y {
  d: path("M11.947 5.318a.712.712 0 0 0 .057 1.417a35 35 0 0 1-.057-1.417");
}

.rlwq00h2l {
  stop-color: var(--svg-color--9e7765, #9E7765);
}

.ro0d6lgcg {
  stop-color: var(--svg-color--66b4dd, #66B4DD);
  stop-opacity: 0;
}

.rxg51vbwm {
  stop-color: var(--svg-color--4f2b3c, #4F2B3C);
}

.s0_pk0b8f {
  d: path("M12.044 7.365a1.73 1.73 0 0 0 1.718 1.506h.834a1.73 1.73 0 0 0 1.718-1.506c.053-.833.105-1.663.144-2.495a.64.64 0 0 0-.61-.634h-.62c-.421 0-.803-.249-.977-.638a.29.29 0 0 0-.272-.185h-.563c-.816 0-1.477.67-1.477 1.495c0 .822.051 1.632.105 2.457");
}

.s41d30h-g {
  stop-color: var(--svg-color--fe5346, #FE5346);
}

.se5f_fbvx {
  stop-color: var(--svg-color--9c6376, #9C6376);
  stop-opacity: 0;
}

.sf2boes3b {
  d: path("m23.469 25.327l-.422-1.143l-2.351.536l2.225 1.1a.396.396 0 0 0 .547-.493");
}

.sgu32ab0w {
  d: path("M19.837 23.012a29 29 0 0 1-.907-.867l1.867-.883c.075.131.51.8.72 1.117z");
}

.siwrhab8g {
  d: path("M16.782 13.45c-.65-1.28-1.166-3.185-1.443-4.423a.714.714 0 0 1 .588-.856c.447-.075.855.271.91.722c.205 1.698.95 3.373 1.445 4.682c.578 1.531.312 1.062.234 3.515c-.057 1.782 1.266 3.25 1.813 4.11l-.407.21c-.609-.827-2.203-2.945-2.203-4.85c0-1.792.063-1.141-.937-3.11");
}

.sjwz8ccmm {
  stop-color: var(--svg-color--ab817b, #AB817B);
}

.snqb9vbfx {
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M14.177 7.423c-.224 0-.435-.053-.612-.145c-.06-.031-.126.037-.088.092a.84.84 0 0 0 .7.374c.294 0 .553-.15.7-.374c.039-.057-.026-.123-.087-.092a1.3 1.3 0 0 1-.613.145Z");
}

.szw4sibdg {
  stop-color: var(--svg-color--c5a18a, #C5A18A);
}

.t2zfh_b3c {
  stop-color: var(--svg-color--2d7cf2, #2D7CF2);
  stop-opacity: 0;
}

.t9rw6xbgs {
  d: path("M16.41 6.413q.023-.389.042-.777c.178.024.315.188.315.387c0 .214-.16.388-.357.39");
}

.tfbfyubeo {
  cx: 13.093px;
  cy: 5.695px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.172px;
  ry: 0.087px;
}

.toe447tsm {
  width: 0.599px;
  height: 1.031px;
  x: 20.662px;
  y: 12.809px;
  rx: 0.299px;
}

.uh8iu31tc {
  cx: 28.864px;
  cy: 12.813px;
  r: 1.043px;
}

.uhv9b32lc {
  stop-color: var(--svg-color--9e7765, #9E7765);
  stop-opacity: 0;
}

.ui2bqrbyd {
  stop-color: var(--svg-color--b77dc7, #B77DC7);
  stop-opacity: 0;
}

.upowizugn {
  stop-color: var(--svg-color--ff783f, #FF783F);
}

.ur78mwbxs {
  stop-color: var(--svg-color--654647, #654647);
}

.ut-a4zo6y {
  stop-color: var(--svg-color--685351, #685351);
  stop-opacity: 0;
}

.v_2gjcb5l {
  stop-color: var(--svg-color--4c3c39, #4C3C39);
}

.v3vg2fbhx {
  stop-color: var(--svg-color--af887b, #AF887B);
}

.vgm-ugbvo {
  d: path("M13.572 5.874c0-.127-.103-.212-.131-.238l-.128.123l.079.16z");
}

.vj0--9brr {
  stop-color: var(--svg-color--4db5e2, #4DB5E2);
}

.vj4yuc0qg {
  stop-color: var(--svg-color--614440, #614440);
}

.vm3i05jbz {
  stop-color: var(--svg-color--765a55, #765A55);
}

.vurnokzna {
  fill: var(--svg-color--ab8572, #AB8572);
  fill-rule: evenodd;
  d: path("M5.611 14.945a.375.375 0 0 1-.69-.296c.093-.216.328-.445.6-.604a1.76 1.76 0 0 1 1.119-.237a.375.375 0 1 1-.099.744a1 1 0 0 0-.641.14c-.09.053-.163.111-.215.164a.5.5 0 0 0-.074.089");
}

.vzzhqfd0u {
  stop-color: var(--svg-color--2e1c2e, #2E1C2E);
}

.wbdnw-owo {
  stop-color: var(--svg-color--9e6a5c, #9E6A5C);
  stop-opacity: 0;
}

.woc0miqaj {
  stop-color: var(--svg-color--fe5346, #FE5346);
  stop-opacity: 0;
}

.wqensyb5w {
  stop-color: var(--svg-color--8d5050, #8D5050);
}

.wv5n4khjs {
  stop-color: var(--svg-color--532c3f, #532C3F);
}

.wvwy8egxn {
  fill-rule: evenodd;
  d: path("M5.611 14.945a.375.375 0 0 1-.69-.296c.093-.216.328-.445.6-.604a1.76 1.76 0 0 1 1.119-.237a.375.375 0 1 1-.099.744a1 1 0 0 0-.641.14c-.09.053-.163.111-.215.164a.5.5 0 0 0-.074.089");
}

.wwdaicbmw {
  fill: var(--svg-color--ff702b, #FF702B);
  d: path("M10.684 11.696c-.967.714-2.204 1.017-2.723 1.058c-.13 1 .107 1.771.243 2.032c.3-.028 1.148-.11 2.5-.72c1.679-.756 2.458-1.803 2.64-2.245l-.28-3.387c-.376 1.031-1.005 2.246-2.38 3.262");
}

.wzzpsp2nr {
  d: path("m16.482 5.103l-.012-.279a.65.65 0 0 0-.622-.63h-.619a1.07 1.07 0 0 1-.94-.557s.32-.92.848-.8c.386.087.799.223 1.115.43c.771.503.636 1.41.23 1.836");
}

.x8wej50xc {
  d: path("m14.008 5.826l-.235.813c-.048.167.068.334.23.334h.348c.163 0 .278-.17.23-.334l-.235-.813c-.05-.18-.285-.18-.338 0");
}

.xmm-zsbso {
  fill: var(--svg-color--fff, #fff);
  d: path("M15.235 5.406c.289 0 .533.199.599.468a.12.12 0 0 1-.118.15h-.987a.102.102 0 0 1-.1-.12a.62.62 0 0 1 .606-.498");
}

.xqbp6db-u {
  stop-color: var(--svg-color--8a5f5c, #8A5F5C);
  stop-opacity: 0;
}

.xtqzqnbwf {
  stop-color: var(--svg-color--c9a38e, #C9A38E);
}

.xujwu-wlk {
  stop-color: var(--svg-color--ff4d30, #FF4D30);
}

.xxn4m8bxd {
  stop-color: var(--svg-color--654647, #654647);
  stop-opacity: 0;
}

.xy8jbrbcm {
  fill-rule: evenodd;
  d: path("M5.404 14.139s.02-.028.083-.08a2.1 2.1 0 0 1 1.279-.412a.375.375 0 0 0 .024-.749a2.84 2.84 0 0 0-1.323.295c-.176.087-.33.185-.452.284c-.11.089-.234.211-.296.355a.375.375 0 0 0 .685.306");
}

.xys9jruze {
  stop-color: var(--svg-color--604946, #604946);
  stop-opacity: 0;
}

.xzkoa2bwe {
  d: path("M10.684 11.696c-.967.714-2.204 1.017-2.723 1.058c-.13 1 .107 1.771.243 2.032c.3-.028 1.148-.11 2.5-.72c1.679-.756 2.458-1.803 2.64-2.245l-.28-3.387c-.376 1.031-1.005 2.246-2.38 3.262");
}

.y-2lu0bml {
  fill-rule: evenodd;
  d: path("M7.127 13.544c-.941-.284-1.295.01-1.388.119a.375.375 0 1 1-.57-.488c.328-.383 1.014-.699 2.174-.35a.375.375 0 0 1-.216.719");
}

.y110racyj {
  stop-color: var(--svg-color--84a6e9, #84A6E9);
}

.y4noiz6ri {
  stop-color: var(--svg-color--bf9980, #BF9980);
}

.y79whbcii {
  fill: var(--svg-color--1b71cc, #1B71CC);
  d: path("m21.985 27.333l-14.375 1.5c4.687-2.24 11.938-4.407 14.375-6.188c1.826-1.334 2.896-1.2 3.281.563c.219 1-1.031 3.625-3.281 4.125");
}

.yd6vs-kvu {
  stop-color: var(--svg-color--543f3c, #543F3C);
}

.yjjppjb0c {
  stop-color: var(--svg-color--ff9e61, #FF9E61);
}

.yniof8bcm {
  fill: var(--svg-color--000, #000);
  d: path("M14.917 5.92c0-.125.1-.225.226-.225a.225.225 0 0 1 .201.33h-.4a.2.2 0 0 1-.027-.104");
}

.yt5sdf2gy {
  stop-color: var(--svg-color--ff875c, #FF875C);
}

.yujm55bam {
  fill: var(--svg-color--725050, #725050);
  d: path("M16.122 3.66h-.944a.22.22 0 1 1 .035-.436c.245.039.57.093.788.147c.493.122.63.362.667.534a.69.69 0 0 0-.546-.245");
}

.z_hqhdb1q {
  stop-color: var(--svg-color--a25b5d, #A25B5D);
}

.z0pxpnkbw {
  d: path("m21.985 27.333l-14.375 1.5c4.687-2.24 11.938-4.407 14.375-6.188c1.826-1.334 2.896-1.2 3.281.563c.219 1-1.031 3.625-3.281 4.125");
}

.zkqd2ycat {
  stop-color: var(--svg-color--ff5714, #FF5714);
  stop-opacity: 0;
}

.zvhz6qbam {
  stop-color: var(--svg-color--c2987e, #C2987E);
  stop-opacity: 0;
}

.zvm05wbin {
  stop-color: var(--svg-color--7d4d5b, #7D4D5B);
}

</style>
