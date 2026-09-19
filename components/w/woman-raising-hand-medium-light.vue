<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#i9X6mRc)" class="bmvchab_b"/><path fill="url(#iMATq0c)" class="bmvchab_b"/><path fill="url(#iDbPmXA)" class="bmvchab_b"/><path fill="url(#iLqJpQc)" class="bmvchab_b"/><path fill="url(#izgbHqc)" class="bmvchab_b"/><path fill="url(#iXpl6Nc)" class="bmvchab_b"/><path fill="url(#ixMTToY)" class="bmvchab_b"/><path fill="url(#iWsVz1Q)" class="bmvchab_b"/><path fill="url(#ikxUXie)" class="bmvchab_b"/><path fill="url(#ip0sFzb)" class="bmvchab_b"/><path fill="url(#igyq8Wb)" class="bmvchab_b"/><path fill="url(#i6MYp6d)" class="bmvchab_b"/><g filter="url(#ipgWDub)"><path stroke="url(#i6jYcbA)" class="ravvfdb0z"/></g><g filter="url(#ibbYbsr)"><path stroke="url(#i95itTc)" class="m9_oypdgy"/></g><g filter="url(#i0IYDZd)"><path stroke="url(#iOftEUG)" class="dnaysbb3x"/></g><g filter="url(#iT2j7Wc)"><path stroke="url(#irkS97b)" class="fpskzy_vd"/></g><g filter="url(#ihSj9Od)"><path stroke="url(#iCwnI3c)" class="b1y17zvfr"/></g><g filter="url(#iRI6CQe)"><path stroke="url(#i4F5qoc)" class="k7vb4qsjy"/></g><g filter="url(#iSGtoCe)"><path stroke="url(#i0p83te)" class="jecjimben"/></g><g filter="url(#iQNANje)"><path stroke="url(#iLnNAIb)" class="o_y73w1dt"/></g><g filter="url(#iI2EPgc)"><path stroke="url(#iQkg0oe)" class="k4dlqmj_f"/></g><g filter="url(#igpBHQb)"><path stroke="url(#inYPYZd)" class="z3h433bvk"/></g><g filter="url(#iRwiBuc)"><path fill="url(#iU5vmBd)" clip-rule="evenodd" class="tub2-2b9t"/><path fill="url(#i6JCNhL)" clip-rule="evenodd" class="tub2-2b9t"/><path fill="url(#iF1Iumb)" clip-rule="evenodd" class="tub2-2b9t"/><path fill="url(#iooluCc)" clip-rule="evenodd" class="tub2-2b9t"/><path fill="url(#isujCfe)" clip-rule="evenodd" class="tub2-2b9t"/><path fill="url(#ijX5pic)" clip-rule="evenodd" class="tub2-2b9t"/><path fill="url(#iDsN8oc)" clip-rule="evenodd" class="tub2-2b9t"/><path fill="url(#ilmITUd)" clip-rule="evenodd" class="tub2-2b9t"/><path fill="url(#if20k1c)" clip-rule="evenodd" class="tub2-2b9t"/><path fill="url(#iGUUpgc)" clip-rule="evenodd" class="tub2-2b9t"/></g><path fill="url(#iyFBXTq)" clip-rule="evenodd" class="tub2-2b9t"/><path fill="url(#i4a2Xpd)" clip-rule="evenodd" class="tub2-2b9t"/><path fill="url(#ilXEaEb)" clip-rule="evenodd" class="tub2-2b9t"/><path fill="url(#ianahPd)" clip-rule="evenodd" class="tub2-2b9t"/><path fill="url(#iNJBdkU)" class="b5g3i3mag"/><path fill="url(#iidsVGS)" class="b5g3i3mag"/><path fill="url(#injsPjF)" class="b5g3i3mag"/><path fill="url(#i72TxPd)" class="zar_-tbdp"/><path fill="url(#i2Q42Cd)" class="zar_-tbdp"/><path fill="url(#ierll2n)" class="zar_-tbdp"/><path fill="url(#id8vtIc)" class="zoqmhxs6u"/><path fill="url(#iu5VJGd)" class="zoqmhxs6u"/><path fill="url(#ifUceYy)" class="zoqmhxs6u"/><path fill="url(#icgRCed)" class="zoqmhxs6u"/><path fill="url(#iaaTy8d)" class="zoqmhxs6u"/><path fill="url(#ilN7RCM)" class="zoqmhxs6u"/><path fill="url(#ilryHbe)" class="xrgpjcb6i"/><g filter="url(#ieZvDJe)"><path stroke="url(#iAXZo0S)" class="phx3m2o6y"/></g><g filter="url(#iZBFgod)"><path fill="url(#ixZ5Jee)" class="e4n4qif-p"/></g><g filter="url(#iBrlT6c)"><path fill="url(#iwes4xb)" class="vt-rtgbrf"/><path fill="url(#iLSptQb)" class="vt-rtgbrf"/></g><g filter="url(#iO69o1b)"><path class="h24gdjb-v"/><path fill="url(#iBZ3lRc)" class="cx93g4bax"/></g><g filter="url(#iOkESLe)"><path class="gzo0it26u"/><path fill="url(#iDOV87b)" class="fa1d93bwu"/></g><g filter="url(#iDTcOPe)"><path fill="url(#imHjNbn)" class="m9-9n-5ej"/><path fill="url(#iBcz5hb)" class="m9-9n-5ej"/><path fill="url(#izHNvSU)" class="m9-9n-5ej"/><path fill="url(#iQ7w44c)" class="m9-9n-5ej"/><path fill="url(#ivdh2db)" class="m9-9n-5ej"/><path fill="url(#iB4EmEd)" class="m9-9n-5ej"/><path fill="url(#ijZI0Ic)" class="m9-9n-5ej"/></g><path fill="url(#i7tXAxd)" class="ml_a1u4oz"/><g filter="url(#iVxGvUk)"><path class="p_e0yoqmp"/></g><g filter="url(#iCMF1kN)"><path class="h_byehbbh"/><path fill="url(#iPme9md)" class="t-8ibsbxr"/><path fill="url(#iQDA71c)" class="t-8ibsbxr"/><path fill="url(#izLYmqe)" class="t-8ibsbxr"/></g><path fill="url(#iiFKDAc)" class="t-8ibsbxr"/><path fill="url(#i7mt0gd)" class="t-8ibsbxr"/><path stroke="url(#icqIWTc)" class="z-_7oacfe"/><g filter="url(#iPlHBjw)"><path class="ch93a3r8k"/></g><g filter="url(#ioCCQld)"><path class="foel_kbmk"/></g><g filter="url(#ipVdjde)"><path class="fx4asob1d"/></g><g filter="url(#ixCrHTd)"><path clip-rule="evenodd" class="hghwk2bds"/></g><path class="qv1dxt4je"/><path fill="url(#i4USmyd)" class="pxlkji3vy"/><path class="p80yl1i4o"/><g filter="url(#iI90eNe)"><path class="x97mw867e"/><path fill="url(#idXXCJb)" class="qzl83lbyv"/></g><g filter="url(#iNbIvTb)"><path fill="url(#iItTzLe)" class="txryfdvnp"/></g><path class="z2bgibbpv"/><path fill="url(#iPFwrmb)" class="zj_jchdfe"/><path class="dz04i7o9z"/><g filter="url(#iJqRVbv)"><path fill="url(#iAYsele)" class="disi-gbvn"/></g><g filter="url(#iYcXWyl)"><ellipse transform="rotate(-27.914 15.706 13.22)" class="oct_5_7qz"/><ellipse fill="url(#ibLX0yb)" transform="rotate(-27.914 15.706 13.22)" class="j0x8wibsd"/></g><g filter="url(#icSu8ui)"><path class="jg3z8snxe"/></g><g filter="url(#iahqZrc)"><path class="rxux9wbns"/></g><g filter="url(#iJh1TcO)"><path fill="url(#iC1xvKd)" class="q40vy1rvh"/><path fill="url(#igVCUkb)" class="q40vy1rvh"/></g><g filter="url(#idBkc8J)"><path fill="url(#ijJSQod)" class="rlsay17ko"/><path fill="url(#iuItRne)" class="rlsay17ko"/><path fill="url(#ij82TXV)" class="rlsay17ko"/></g><g filter="url(#iBBIhGe)"><path stroke="url(#iydjT5c)" class="ajuiysbyf"/></g><defs><radialGradient id="i9X6mRc" cx="0" cy="0" r="1" gradientTransform="matrix(2.33335 -6.04232 7.22855 2.79144 5.478 11.434)" gradientUnits="userSpaceOnUse"><stop offset=".475" class="vpa8ubcez"/><stop offset="1" class="nick4i1gd"/></radialGradient><radialGradient id="iMATq0c" cx="0" cy="0" r="1" gradientTransform="rotate(130.764 2.684 7.006)scale(9.5721 2.30417)" gradientUnits="userSpaceOnUse"><stop offset=".147" class="tvy-4obul"/><stop offset="1" class="rlvwxbcbx"/></radialGradient><radialGradient id="iLqJpQc" cx="0" cy="0" r="1" gradientTransform="matrix(.19531 2.2578 -.27074 .02342 4.203 4.62)" gradientUnits="userSpaceOnUse"><stop offset=".077" class="i1fbwbbit"/><stop offset="1" class="lc7szmbjn"/></radialGradient><radialGradient id="izgbHqc" cx="0" cy="0" r="1" gradientTransform="matrix(-.04685 3.40625 -.266 -.00366 5.851 3.457)" gradientUnits="userSpaceOnUse"><stop class="i1fbwbbit"/><stop offset="1" class="lc7szmbjn"/></radialGradient><radialGradient id="iXpl6Nc" cx="0" cy="0" r="1" gradientTransform="rotate(99.609 2.773 4.65)scale(4.02522 .49917)" gradientUnits="userSpaceOnUse"><stop offset=".202" class="i1fbwbbit"/><stop offset="1" class="lc7szmbjn"/></radialGradient><radialGradient id="ixMTToY" cx="0" cy="0" r="1" gradientTransform="matrix(-.6629 .73793 -.64825 -.58233 9.32 3.05)" gradientUnits="userSpaceOnUse"><stop class="nkqxn1-bm"/><stop offset="1" class="jfno0m0sa"/></radialGradient><radialGradient id="iWsVz1Q" cx="0" cy="0" r="1" gradientTransform="matrix(-.6504 1.06501 -.658 -.40183 7.394 2.024)" gradientUnits="userSpaceOnUse"><stop class="nkqxn1-bm"/><stop offset="1" class="jfno0m0sa"/></radialGradient><radialGradient id="ikxUXie" cx="0" cy="0" r="1" gradientTransform="rotate(99.841 1.565 3.549)scale(1.24402 .95461)" gradientUnits="userSpaceOnUse"><stop class="nkqxn1-bm"/><stop offset="1" class="jfno0m0sa"/></radialGradient><radialGradient id="ip0sFzb" cx="0" cy="0" r="1" gradientTransform="matrix(-.13758 .96306 -.68465 -.0978 3.578 3.84)" gradientUnits="userSpaceOnUse"><stop class="nkqxn1-bm"/><stop offset="1" class="jfno0m0sa"/></radialGradient><radialGradient id="igyq8Wb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.09125 1.09125 -.85394 -.85394 11.614 6.32)" gradientUnits="userSpaceOnUse"><stop class="nkqxn1-bm"/><stop offset="1" class="jfno0m0sa"/></radialGradient><radialGradient id="i6JCNhL" cx="0" cy="0" r="1" gradientTransform="matrix(2.13975 -4.4441 10.13285 4.87877 24.479 21.213)" gradientUnits="userSpaceOnUse"><stop class="rjxj417_v"/><stop offset="1" class="p1sg1mumi"/></radialGradient><radialGradient id="iF1Iumb" cx="0" cy="0" r="1" gradientTransform="matrix(-.1646 6.7896 -6.35551 -.15407 17.895 16.234)" gradientUnits="userSpaceOnUse"><stop offset=".591" class="ta36f8b7v"/><stop offset="1" class="hcuenbefp"/></radialGradient><radialGradient id="iooluCc" cx="0" cy="0" r="1" gradientTransform="matrix(-3.868 3.0039 -3.69764 -4.7613 14.891 17.469)" gradientUnits="userSpaceOnUse"><stop offset=".205" class="hxuphr-8h"/><stop offset="1" class="v-9s4u7ch"/></radialGradient><radialGradient id="isujCfe" cx="0" cy="0" r="1" gradientTransform="rotate(125.038 2.656 10.492)scale(2.1862 1.98715)" gradientUnits="userSpaceOnUse"><stop offset=".334" class="ybvptdnhb"/><stop offset="1" class="ue-yx0baa"/></radialGradient><radialGradient id="ijX5pic" cx="0" cy="0" r="1" gradientTransform="rotate(-167.428 7.404 5.515)scale(2.93012 4.3073)" gradientUnits="userSpaceOnUse"><stop offset=".226" class="sqmgyf2vi"/><stop offset="1" class="mvuactshi"/></radialGradient><radialGradient id="iDsN8oc" cx="0" cy="0" r="1" gradientTransform="rotate(55.684 2.484 15.646)scale(4.70808 8.21624)" gradientUnits="userSpaceOnUse"><stop class="vrnylccvf"/><stop offset="1" class="b442o21cz"/></radialGradient><radialGradient id="ilmITUd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.35791 1.48138 -2.0702 -1.89766 25.466 7.017)" gradientUnits="userSpaceOnUse"><stop class="di6ktzbyk"/><stop offset="1" class="ejv935bph"/></radialGradient><radialGradient id="if20k1c" cx="0" cy="0" r="1" gradientTransform="matrix(-2.2631 .6584 -1.43257 -4.9242 27.935 13.024)" gradientUnits="userSpaceOnUse"><stop class="kdig6mnba"/><stop offset="1" class="him6rrbhz"/></radialGradient><radialGradient id="iGUUpgc" cx="0" cy="0" r="1" gradientTransform="matrix(-3.86803 1.64594 -2.6225 -6.16294 27.606 16.44)" gradientUnits="userSpaceOnUse"><stop class="c2fnpwywz"/><stop offset="1" class="c5g3vhi-m"/></radialGradient><radialGradient id="i4a2Xpd" cx="0" cy="0" r="1" gradientTransform="matrix(3.70356 -5.86162 5.80828 3.66985 23.23 22.036)" gradientUnits="userSpaceOnUse"><stop offset=".345" class="jjuf3rb5e"/><stop offset="1" class="edfa78b2t"/></radialGradient><radialGradient id="ilXEaEb" cx="0" cy="0" r="1" gradientTransform="matrix(-5.53628 -6.14715 7.35834 -6.6271 17.044 21.062)" gradientUnits="userSpaceOnUse"><stop offset=".363" class="d3_wocczf"/><stop offset="1" class="ch4zcsb2m"/></radialGradient><radialGradient id="ianahPd" cx="0" cy="0" r="1" gradientTransform="matrix(0 15.1197 -20.5796 0 18.953 9.76)" gradientUnits="userSpaceOnUse"><stop offset=".77" class="n4q03-1wn"/><stop offset=".944" class="wmtmv1hbb"/></radialGradient><radialGradient id="iidsVGS" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.10937 -1.15625 0 6.835 12.039)" gradientUnits="userSpaceOnUse"><stop class="vm40c2rnb"/><stop offset="1" class="in_wled_m"/></radialGradient><radialGradient id="i2Q42Cd" cx="0" cy="0" r="1" gradientTransform="matrix(-8.05789 2.36576 -2.0517 -6.98818 25.18 27.22)" gradientUnits="userSpaceOnUse"><stop class="cedqx2rkm"/><stop offset="1" class="xi0shyhbu"/></radialGradient><radialGradient id="ierll2n" cx="0" cy="0" r="1" gradientTransform="matrix(0 -4.62502 2.65624 0 10.595 29.586)" gradientUnits="userSpaceOnUse"><stop class="fp2gw167u"/><stop offset="1" class="rnij5z0qd"/></radialGradient><radialGradient id="iu5VJGd" cx="0" cy="0" r="1" gradientTransform="matrix(0 8.65452 -5.4375 0 2.648 12.586)" gradientUnits="userSpaceOnUse"><stop class="rz1t4jbgv"/><stop offset="1" class="xkxmx1bvv"/></radialGradient><radialGradient id="ifUceYy" cx="0" cy="0" r="1" gradientTransform="rotate(-168.087 9.721 9.023)scale(10.3318 4.37074)" gradientUnits="userSpaceOnUse"><stop offset=".287" class="m2mta8b_j"/><stop offset="1" class="tx_pqhb7h"/></radialGradient><radialGradient id="icgRCed" cx="0" cy="0" r="1" gradientTransform="matrix(-5.69115 0 0 -5.6259 11.418 15.446)" gradientUnits="userSpaceOnUse"><stop offset=".132" class="m2mta8b_j"/><stop offset="1" class="tx_pqhb7h"/></radialGradient><radialGradient id="ilryHbe" cx="0" cy="0" r="1" gradientTransform="matrix(1.96875 3.9375 -4.4375 2.21876 17.875 19.343)" gradientUnits="userSpaceOnUse"><stop offset=".477" class="ao9_-bbfj"/><stop offset="1" class="op15yplgp"/></radialGradient><radialGradient id="iwes4xb" cx="0" cy="0" r="1" gradientTransform="matrix(3.05533 -1.38879 1.69564 3.7304 23.677 14.609)" gradientUnits="userSpaceOnUse"><stop offset=".572" class="qmmvvysmp"/><stop offset=".905" class="epx_cgb2c"/></radialGradient><radialGradient id="iLSptQb" cx="0" cy="0" r="1" gradientTransform="matrix(1.22418 .34977 -.18389 .6436 24.931 11.883)" gradientUnits="userSpaceOnUse"><stop class="aso-vybjw"/><stop offset="1" class="krvd34mtu"/></radialGradient><radialGradient id="iBZ3lRc" cx="0" cy="0" r="1" gradientTransform="rotate(-20.298 52.293 -60.849)scale(1.60138)" gradientUnits="userSpaceOnUse"><stop offset=".71" class="la61skb4q"/><stop offset="1" class="urs_pbb4x"/></radialGradient><radialGradient id="iDOV87b" cx="0" cy="0" r="1" gradientTransform="matrix(-1.4937 0 0 -1.42882 12.99 14.07)" gradientUnits="userSpaceOnUse"><stop offset=".573" class="prydr8bcy"/><stop offset="1" class="ybx_6zbxd"/></radialGradient><radialGradient id="imHjNbn" cx="0" cy="0" r="1" gradientTransform="rotate(155.244 9.642 9.144)scale(8.79107 11.7667)" gradientUnits="userSpaceOnUse"><stop class="uy3z2gbbp"/><stop offset="1" class="gvh2bspmv"/></radialGradient><radialGradient id="iBcz5hb" cx="0" cy="0" r="1" gradientTransform="matrix(-2.5897 1.3698 -1.16217 -2.19718 21.05 14.266)" gradientUnits="userSpaceOnUse"><stop class="j8hkuac-d"/><stop offset="1" class="cre_5tbhq"/></radialGradient><radialGradient id="izHNvSU" cx="0" cy="0" r="1" gradientTransform="rotate(-78.311 21.368 1.017)scale(5.07057 6.43361)" gradientUnits="userSpaceOnUse"><stop class="t6jzi2-1t"/><stop offset="1" class="i3g5qu-9r"/></radialGradient><radialGradient id="iQ7w44c" cx="0" cy="0" r="1" gradientTransform="matrix(-1.48144 8.84705 -10.63296 -1.7805 19.747 13.436)" gradientUnits="userSpaceOnUse"><stop offset=".631" class="pj__wrb2a"/><stop offset="1" class="hiw8w_whp"/></radialGradient><radialGradient id="ivdh2db" cx="0" cy="0" r="1" gradientTransform="rotate(172.34 9.205 8.79)scale(7.09986 12.2238)" gradientUnits="userSpaceOnUse"><stop offset=".813" class="zzstxpr9j"/><stop offset="1" class="irzp_cb7o"/></radialGradient><radialGradient id="iB4EmEd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.41257 2.03074 0 21.543 12.896)" gradientUnits="userSpaceOnUse"><stop offset=".259" class="mt3h7fbpd"/><stop offset="1" class="wcr1klbjh"/></radialGradient><radialGradient id="ijZI0Ic" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.66941 1.91325 0 16.363 13.003)" gradientUnits="userSpaceOnUse"><stop class="r-jog4w_t"/><stop offset="1" class="xjkdvxqyn"/></radialGradient><radialGradient id="i7tXAxd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.65339 0 0 -5.443 24.973 14.722)" gradientUnits="userSpaceOnUse"><stop class="yhs2bn2id"/><stop offset="1" class="g1fw3-bff"/></radialGradient><radialGradient id="iPme9md" cx="0" cy="0" r="1" gradientTransform="matrix(-.85613 -3.00706 1.72068 -.48989 19.68 15.614)" gradientUnits="userSpaceOnUse"><stop offset=".017" class="xjug-415a"/><stop offset="1" class="bd8jqdorr"/></radialGradient><radialGradient id="i7mt0gd" cx="0" cy="0" r="1" gradientTransform="rotate(144.462 7.104 10.644)scale(1.93318 2.58935)" gradientUnits="userSpaceOnUse"><stop offset=".797" class="atsjj9bsj"/><stop offset="1" class="vyevcqbzs"/></radialGradient><radialGradient id="i4USmyd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .9959 -1.58408 0 21.396 13.337)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="idXXCJb" cx="0" cy="0" r="1" gradientTransform="matrix(-.28468 -.36685 .50506 -.39193 21.116 13.44)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iPFwrmb" cx="0" cy="0" r="1" gradientTransform="matrix(0 .9959 -1.58409 0 16.04 13.337)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="ibLX0yb" cx="0" cy="0" r="1" gradientTransform="matrix(-.0095 -.60646 .72899 -.01141 15.688 13.606)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iC1xvKd" cx="0" cy="0" r="1" gradientTransform="matrix(2.37508 3.29191 -6.54104 4.71928 11.405 6.4)" gradientUnits="userSpaceOnUse"><stop offset=".403" class="hi5yi9bqv"/><stop offset="1" class="d8y_5zbge"/></radialGradient><radialGradient id="igVCUkb" cx="0" cy="0" r="1" gradientTransform="rotate(127.118 6.03 7.17)scale(3.81874 2.99489)" gradientUnits="userSpaceOnUse"><stop class="g6mu4o3fz"/><stop offset="1" class="dx30lgbdy"/></radialGradient><radialGradient id="ijJSQod" cx="0" cy="0" r="1" gradientTransform="rotate(115.684 9.167 8.792)scale(5.9815 8.50545)" gradientUnits="userSpaceOnUse"><stop offset=".595" class="iz4jcxg0j"/><stop offset="1" class="qflnpfbur"/></radialGradient><radialGradient id="iuItRne" cx="0" cy="0" r="1" gradientTransform="rotate(104.957 8.559 11.168)scale(4.07493 7.27387)" gradientUnits="userSpaceOnUse"><stop class="mv8kv7beo"/><stop offset="1" class="g_ulzrbqz"/></radialGradient><radialGradient id="ij82TXV" cx="0" cy="0" r="1" gradientTransform="rotate(-119.068 13.825 .273)scale(8.85086 7.92279)" gradientUnits="userSpaceOnUse"><stop offset=".891" class="w58maet4h"/><stop offset=".979" class="drxq29wnr"/></radialGradient><filter id="ipgWDub" width=".423" height="2.22" x="4.058" y="4.647" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3872" stdDeviation=".05"/></filter><filter id="ibbYbsr" width=".345" height="2.572" x="5.613" y="4.218" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3872" stdDeviation=".05"/></filter><filter id="i0IYDZd" width=".509" height="1.681" x="7.089" y="4.819" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3872" stdDeviation=".05"/></filter><filter id="iT2j7Wc" width="1.556" height="3.487" x="2.923" y="3.997" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3872" stdDeviation=".2"/></filter><filter id="ihSj9Od" width="1.2" height="3.889" x="4.609" y="3.068" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3872" stdDeviation=".2"/></filter><filter id="iRI6CQe" width="1.488" height="4.773" x="6.156" y="2.142" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3872" stdDeviation=".2"/></filter><filter id="iSGtoCe" width="2.002" height="4.299" x="7.56" y="3.157" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3872" stdDeviation=".2"/></filter><filter id="iQNANje" width="1.412" height="1.358" x="3.214" y="6.515" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3872" stdDeviation=".1"/></filter><filter id="iI2EPgc" width="1.118" height=".999" x="4.862" y="6.307" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3872" stdDeviation=".1"/></filter><filter id="igpBHQb" width="1.312" height="1.023" x="6.128" y="6.115" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3872" stdDeviation=".1"/></filter><filter id="iRwiBuc" width="18.685" height="19.185" x="9.5" y="2.851" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.75"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.886275 0 0 0 0 0.698039 0 0 0 0 0.607843 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3872"/></filter><filter id="ieZvDJe" width="9.217" height="11.911" x="5.06" y="12.014" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3872" stdDeviation=".75"/></filter><filter id="iZBFgod" width="4.1" height="4.2" x="10.991" y="12.095" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy=".25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.858824 0 0 0 0 0.635294 0 0 0 0 0.533333 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3872"/></filter><filter id="iBrlT6c" width="3.95" height="4.2" x="22.668" y="11.845" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.827451 0 0 0 0 0.568627 0 0 0 0 0.505882 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3872"/></filter><filter id="iO69o1b" width="3.637" height="3.637" x="22.825" y="12.251" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3872" stdDeviation=".25"/></filter><filter id="iOkESLe" width="3.437" height="3.437" x="11.271" y="12.351" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3872" stdDeviation=".2"/></filter><filter id="iDTcOPe" width="12.509" height="13.751" x="12.463" y="8.047" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.745098 0 0 0 0 0.486275 0 0 0 0 0.384314 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3872"/></filter><filter id="iVxGvUk" width="3.304" height="4.292" x="16.866" y="12.95" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3872" stdDeviation=".25"/></filter><filter id="iCMF1kN" width="2.804" height="3.792" x="17.316" y="13.03" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3872" stdDeviation=".125"/></filter><filter id="iPlHBjw" width="3.639" height="1.578" x="19.92" y="12.345" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.141176 0 0 0 0 0.0862745 0 0 0 0 0.176471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3872"/></filter><filter id="ioCCQld" width="3.639" height="1.578" x="13.878" y="12.345" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.133333 0 0 0 0 0.0784314 0 0 0 0 0.168627 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3872"/></filter><filter id="ipVdjde" width="2.965" height="1.294" x="14.043" y="10.643" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.47451 0 0 0 0 0.262745 0 0 0 0 0.164706 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3872"/></filter><filter id="ixCrHTd" width="2.965" height="1.294" x="20.693" y="10.643" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.47451 0 0 0 0 0.262745 0 0 0 0 0.164706 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3872"/></filter><filter id="iI90eNe" width=".92" height=".809" x="20.518" y="12.819" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3872" stdDeviation=".05"/></filter><filter id="iNbIvTb" width="1.003" height="1.03" x="21.572" y="12.934" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3872" stdDeviation=".1"/></filter><filter id="iJqRVbv" width="1.12" height="1.186" x="16.118" y="12.857" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3872" stdDeviation=".1"/></filter><filter id="iYcXWyl" width="1.075" height=".819" x="15.169" y="12.81" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3872" stdDeviation=".05"/></filter><filter id="icSu8ui" width="3.239" height="1.664" x="20.499" y="10.516" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3872" stdDeviation=".2"/></filter><filter id="iahqZrc" width="3.239" height="1.664" x="13.807" y="10.516" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3872" stdDeviation=".2"/></filter><filter id="iJh1TcO" width="5.535" height="6.717" x="10.898" y="5.309" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3872" stdDeviation=".375"/></filter><filter id="idBkc8J" width="11.828" height="7.981" x="14.203" y="3.715" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3872" stdDeviation=".375"/></filter><filter id="iBBIhGe" width="1.269" height="2.699" x="14.869" y="5.739" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3872" stdDeviation=".1"/></filter><linearGradient id="iDbPmXA" x1="5.961" x2="5.961" y1="12.094" y2="10.391" gradientUnits="userSpaceOnUse"><stop class="mwk8f57wh"/><stop offset="1" class="ily2h4rfo"/></linearGradient><linearGradient id="i6MYp6d" x1="2.563" x2="3.373" y1="8.978" y2="8.9" gradientUnits="userSpaceOnUse"><stop class="qe0h-qt8x"/><stop offset="1" class="je3tjybua"/></linearGradient><linearGradient id="i6jYcbA" x1="4.451" x2="3.499" y1="4.788" y2="6.574" gradientUnits="userSpaceOnUse"><stop class="zhwoeykns"/><stop offset="1" class="vrs9uvb1p"/></linearGradient><linearGradient id="i95itTc" x1="5.871" x2="4.57" y1="4.359" y2="5.338" gradientUnits="userSpaceOnUse"><stop class="zhwoeykns"/><stop offset="1" class="vrs9uvb1p"/></linearGradient><linearGradient id="iOftEUG" x1="7.63" x2="7.249" y1="4.959" y2="6.523" gradientUnits="userSpaceOnUse"><stop class="zhwoeykns"/><stop offset="1" class="vrs9uvb1p"/></linearGradient><linearGradient id="irkS97b" x1="3.217" x2="3.636" y1="4.901" y2="7.508" gradientUnits="userSpaceOnUse"><stop class="n2lghubug"/><stop offset="1" class="o-9gnobjq"/></linearGradient><linearGradient id="iCwnI3c" x1="4.361" x2="4.573" y1="4.027" y2="7.151" gradientUnits="userSpaceOnUse"><stop class="n2lghubug"/><stop offset="1" class="o-9gnobjq"/></linearGradient><linearGradient id="i4F5qoc" x1="6.511" x2="7.613" y1="3.271" y2="6.947" gradientUnits="userSpaceOnUse"><stop class="n2lghubug"/><stop offset="1" class="o-9gnobjq"/></linearGradient><linearGradient id="i0p83te" x1="7.465" x2="7.781" y1="4.22" y2="7.652" gradientUnits="userSpaceOnUse"><stop class="n2lghubug"/><stop offset="1" class="o-9gnobjq"/></linearGradient><linearGradient id="iLnNAIb" x1="4.511" x2="3.419" y1="6.768" y2="6.699" gradientUnits="userSpaceOnUse"><stop class="qnynbebrn"/><stop offset="1" class="ogs4x8_bh"/></linearGradient><linearGradient id="iQkg0oe" x1="5.783" x2="5.219" y1="6.596" y2="6.455" gradientUnits="userSpaceOnUse"><stop class="qnynbebrn"/><stop offset="1" class="ogs4x8_bh"/></linearGradient><linearGradient id="inYPYZd" x1="7.284" x2="6.481" y1="6.409" y2="6.196" gradientUnits="userSpaceOnUse"><stop class="qnynbebrn"/><stop offset="1" class="ogs4x8_bh"/></linearGradient><linearGradient id="iU5vmBd" x1="24.479" x2="16.126" y1="5.535" y2="21.007" gradientUnits="userSpaceOnUse"><stop class="p6otu2-6b"/><stop offset="1" class="q5mih6mme"/></linearGradient><linearGradient id="iyFBXTq" x1="18.718" x2="18.718" y1="22.489" y2="20.761" gradientUnits="userSpaceOnUse"><stop class="hqpka7yim"/><stop offset="1" class="jj4p15bbx"/></linearGradient><linearGradient id="iNJBdkU" x1="3.904" x2="8.279" y1="12.149" y2="12.149" gradientUnits="userSpaceOnUse"><stop class="u-9w58unm"/><stop offset=".743" class="gv7qteejy"/></linearGradient><linearGradient id="injsPjF" x1="6.174" x2="6.174" y1="11.563" y2="11.821" gradientUnits="userSpaceOnUse"><stop class="s68njbc8b"/><stop offset="1" class="ha46_3b_b"/></linearGradient><linearGradient id="i72TxPd" x1="18.688" x2="5.165" y1="28.764" y2="12.586" gradientUnits="userSpaceOnUse"><stop class="dkttnh3ka"/><stop offset=".751" class="j0qmv8b6d"/></linearGradient><linearGradient id="id8vtIc" x1="9.133" x2="11.026" y1="26.009" y2="19.818" gradientUnits="userSpaceOnUse"><stop offset=".1" class="nrxnoi8to"/><stop offset="1" class="o8-s5pjlc"/></linearGradient><linearGradient id="iaaTy8d" x1="13.471" x2="12.687" y1="24.32" y2="22.687" gradientUnits="userSpaceOnUse"><stop class="hzm5vwgac"/><stop offset=".732" class="yy_71ub6o"/></linearGradient><linearGradient id="ilN7RCM" x1="6.662" x2="6.662" y1="12.586" y2="13.608" gradientUnits="userSpaceOnUse"><stop class="ignlpnblb"/><stop offset="1" class="a8kog2b_j"/></linearGradient><linearGradient id="iAXZo0S" x1="6.717" x2="12.467" y1="14.294" y2="22.575" gradientUnits="userSpaceOnUse"><stop class="ius0mclhc"/><stop offset="1" class="f3d24-ppq"/></linearGradient><linearGradient id="ixZ5Jee" x1="10.991" x2="14.624" y1="14.177" y2="14.177" gradientUnits="userSpaceOnUse"><stop class="nka4--b6e"/><stop offset="1" class="aps1jhbfc"/></linearGradient><linearGradient id="iQDA71c" x1="17.433" x2="18.482" y1="15.636" y2="15.764" gradientUnits="userSpaceOnUse"><stop class="urkjpbftr"/><stop offset="1" class="lwjatlajn"/></linearGradient><linearGradient id="izLYmqe" x1="18.718" x2="18.718" y1="16.684" y2="15.935" gradientUnits="userSpaceOnUse"><stop class="dvyniwihb"/><stop offset="1" class="e5pm1bciq"/></linearGradient><linearGradient id="iiFKDAc" x1="18.814" x2="18.814" y1="16.652" y2="16.481" gradientUnits="userSpaceOnUse"><stop class="vyevcqbzs"/><stop offset="1" class="atsjj9bsj"/></linearGradient><linearGradient id="icqIWTc" x1="17.823" x2="18.378" y1="18.497" y2="17.427" gradientUnits="userSpaceOnUse"><stop class="b1eb00egl"/><stop offset="1" class="t5ewf8b-q"/></linearGradient><linearGradient id="iItTzLe" x1="22.351" x2="21.966" y1="13.403" y2="13.64" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iAYsele" x1="16.953" x2="16.567" y1="13.403" y2="13.64" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iydjT5c" x1="15.169" x2="15.838" y1="6.461" y2="8.025" gradientUnits="userSpaceOnUse"><stop class="gjbrx7i8b"/><stop offset="1" class="zcr9jykfw"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:woman-raising-hand-medium-light" /></template>
<style>
.a8kog2b_j {
  stop-color: var(--svg-color--6a51a2, #6A51A2);
  stop-opacity: 0;
}

.ajuiysbyf {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M15.169 6.04c.028.298.288 1.42.669 2.098");
}

.ao9_-bbfj {
  stop-color: var(--svg-color--935d65, #935D65);
}

.aps1jhbfc {
  stop-color: var(--svg-color--b47860, #B47860);
}

.aso-vybjw {
  stop-color: var(--svg-color--d59566, #D59566);
}

.atsjj9bsj {
  stop-color: var(--svg-color--c27b7c, #C27B7C);
  stop-opacity: 0;
}

.b1eb00egl {
  stop-color: var(--svg-color--ce9591, #CE9591);
}

.b1y17zvfr {
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M5.209 3.468v3.089");
}

.b442o21cz {
  stop-color: var(--svg-color--dcc893, #DCC893);
  stop-opacity: 0;
}

.b5g3i3mag {
  d: path("M4.068 11.763c0-.11.09-.2.2-.2H8.08c.11 0 .2.09.2.2v1.714H4.07z");
}

.bd8jqdorr {
  stop-color: var(--svg-color--fdc9a8, #FDC9A8);
  stop-opacity: 0;
}

.bmvchab_b {
  d: path("M2.899 8.798c-.125-1.922-.282-2.959-.329-3.641c-.035-.512.024-1.066.711-1.191c.598-.075.883.451.907.66c-.003-.2 0-.68 0-.805c0-.21.007-.977.859-.977c.601 0 .816.588.8.864c.011-.102.023-.414.036-.707c.018-.434.251-.99.945-.977c.598.04.793.613.766.977l-.117 1.867c.023-.188.102-.665.277-1.34s.702-.72.957-.684c.326.047.88.361.648 1.274c-.275 1.156-.462 2.644-.527 3.285c.324-.133.642-.413 1.002-.788s.887-.382 1.183-.16c.34.293.522.968.12 1.37c-.463.425-2.13 2.405-2.957 3.394c-.23.292-.997.875-2.235.875c-2.203-.093-2.941-1.676-3.046-3.296");
}

.c2fnpwywz {
  stop-color: var(--svg-color--fff4bc, #FFF4BC);
}

.c5g3vhi-m {
  stop-color: var(--svg-color--fff4bc, #FFF4BC);
  stop-opacity: 0;
}

.cedqx2rkm {
  stop-color: var(--svg-color--9e7fdf, #9E7FDF);
}

.ch4zcsb2m {
  stop-color: var(--svg-color--f1ba9c, #F1BA9C);
  stop-opacity: 0;
}

.ch93a3r8k {
  fill: var(--svg-color--635d5f, #635D5F);
  d: path("M20.12 13.371c.326-.573.82-1.026 1.887-1.026c.467 0 .917.13 1.317.453c.33.267.286.608.03.736l-.682.39c-.8-.26-1.685-.294-2.552-.553");
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cre_5tbhq {
  stop-color: var(--svg-color--ffc89e, #FFC89E);
  stop-opacity: 0;
}

.cx93g4bax {
  d: path("M24.643 15.388a1.318 1.318 0 1 0 0-2.637a1.318 1.318 0 0 0 0 2.637");
}

.d3_wocczf {
  stop-color: var(--svg-color--896349, #896349);
}

.d8y_5zbge {
  stop-color: var(--svg-color--daa88f, #DAA88F);
}

.di6ktzbyk {
  stop-color: var(--svg-color--ffffbf, #FFFFBF);
}

.disi-gbvn {
  d: path("M17.038 13.718c0-.354-.288-.59-.366-.661l-.354.342l.218.444z");
}

.dkttnh3ka {
  stop-color: var(--svg-color--8663c9, #8663C9);
}

.dnaysbb3x {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-075px, 0.075px);
  d: path("m7.46 4.957l-.233 1.406");
}

.drxq29wnr {
  stop-color: var(--svg-color--dac493, #DAC493);
}

.dvyniwihb {
  stop-color: var(--svg-color--c57f82, #C57F82);
}

.dx30lgbdy {
  stop-color: var(--svg-color--fee2a9, #FEE2A9);
  stop-opacity: 0;
}

.dz04i7o9z {
  fill: var(--svg-color--000, #000);
  d: path("M16.664 13.847a.625.625 0 0 0-.627-.628a.625.625 0 0 0-.558.917h1.11a.6.6 0 0 0 .075-.29");
}

.e4n4qif-p {
  d: path("M12.966 16.045a1.975 1.975 0 1 0 0-3.95a1.975 1.975 0 0 0 0 3.95");
}

.e5pm1bciq {
  stop-color: var(--svg-color--c57f82, #C57F82);
  stop-opacity: 0;
}

.edfa78b2t {
  stop-color: var(--svg-color--eeb69b, #EEB69B);
  stop-opacity: 0;
}

.ejv935bph {
  stop-color: var(--svg-color--ffffbf, #FFFFBF);
  stop-opacity: 0;
}

.epx_cgb2c {
  stop-color: var(--svg-color--f6c3a3, #F6C3A3);
}

.f3d24-ppq {
  stop-color: var(--svg-color--9478ce, #9478CE);
  stop-opacity: 0;
}

.fa1d93bwu {
  d: path("M12.99 15.388a1.318 1.318 0 1 0 0-2.637a1.318 1.318 0 0 0 0 2.637");
}

.foel_kbmk {
  fill: var(--svg-color--635d5f, #635D5F);
  d: path("M17.316 13.371c-.325-.573-.82-1.026-1.887-1.026c-.467 0-.917.13-1.317.453c-.33.267-.286.608-.03.736l.683.39c.8-.26 1.685-.294 2.551-.553");
}

.fp2gw167u {
  stop-color: var(--svg-color--8969ba, #8969BA);
}

.fpskzy_vd {
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("m3.521 4.424l.36 2.633");
}

.ft5dv1b6b {
  fill: none;
}

.fx4asob1d {
  fill: var(--svg-color--9f6836, #9F6836);
  d: path("m14.547 11.887l-.005.003a.33.33 0 0 1-.338-.564l.001-.002l.004-.002l.012-.006a3 3 0 0 1 .182-.095a4 4 0 0 1 .503-.198c.417-.133 1-.245 1.63-.134a.33.33 0 0 1-.114.648c-.49-.086-.96 0-1.316.113a3.4 3.4 0 0 0-.559.237");
}

.g_ulzrbqz {
  stop-color: var(--svg-color--ffffc0, #FFFFC0);
  stop-opacity: 0;
}

.g1fw3-bff {
  stop-color: var(--svg-color--f4c099, #F4C099);
  stop-opacity: 0;
}

.g6mu4o3fz {
  stop-color: var(--svg-color--fee2a9, #FEE2A9);
}

.gh784hb2c {
  stop-color: var(--svg-color--85534d, #85534D);
}

.gjbrx7i8b {
  stop-color: var(--svg-color--ebce91, #EBCE91);
}

.gv7qteejy {
  stop-color: var(--svg-color--463168, #463168);
}

.gvh2bspmv {
  stop-color: var(--svg-color--d39b88, #D39B88);
}

.gzo0it26u {
  fill: var(--svg-color--b47a6c, #B47A6C);
  d: path("M12.99 15.388a1.318 1.318 0 1 0 0-2.637a1.318 1.318 0 0 0 0 2.637");
}

.h_byehbbh {
  fill: var(--svg-color--efb696, #EFB696);
  d: path("m18.249 13.626l-.653 2.087a.662.662 0 0 0 .64.859h.965a.664.664 0 0 0 .639-.859l-.653-2.087c-.14-.462-.792-.462-.938 0");
}

.h24gdjb-v {
  fill: var(--svg-color--e5aa8b, #E5AA8B);
  d: path("M24.643 15.388a1.318 1.318 0 1 0 0-2.637a1.318 1.318 0 0 0 0 2.637");
}

.ha46_3b_b {
  stop-color: var(--svg-color--4f396f, #4F396F);
  stop-opacity: 0;
}

.hcuenbefp {
  stop-color: var(--svg-color--c7897d, #C7897D);
  stop-opacity: 0;
}

.hghwk2bds {
  fill: var(--svg-color--9f6836, #9F6836);
  fill-rule: evenodd;
  d: path("m23.298 11.326l-.169.282za.33.33 0 0 1-.34.564l-.005-.003l-.026-.015l-.112-.056c-.1-.048-.244-.11-.42-.166c-.357-.114-.827-.2-1.316-.113a.33.33 0 1 1-.115-.648c.63-.111 1.213 0 1.63.134a4 4 0 0 1 .686.293l.012.006l.003.003z");
}

.hi5yi9bqv {
  stop-color: var(--svg-color--daa88f, #DAA88F);
  stop-opacity: 0;
}

.him6rrbhz {
  stop-color: var(--svg-color--fffabe, #FFFABE);
  stop-opacity: 0;
}

.hiw8w_whp {
  stop-color: var(--svg-color--b36d8d, #B36D8D);
}

.hqpka7yim {
  stop-color: var(--svg-color--d08d9c, #D08D9C);
}

.hxuphr-8h {
  stop-color: var(--svg-color--cf987b, #CF987B);
}

.hzm5vwgac {
  stop-color: var(--svg-color--8967cb, #8967CB);
}

.i1fbwbbit {
  stop-color: var(--svg-color--cd8d5e, #CD8D5E);
}

.i3g5qu-9r {
  stop-color: var(--svg-color--b97783, #B97783);
  stop-opacity: 0;
}

.ignlpnblb {
  stop-color: var(--svg-color--6a51a2, #6A51A2);
}

.ily2h4rfo {
  stop-color: var(--svg-color--cf8a62, #CF8A62);
  stop-opacity: 0;
}

.in_wled_m {
  stop-color: var(--svg-color--655188, #655188);
  stop-opacity: 0;
}

.irzp_cb7o {
  stop-color: var(--svg-color--e3ab91, #E3AB91);
}

.ius0mclhc {
  stop-color: var(--svg-color--9478ce, #9478CE);
}

.iz4jcxg0j {
  stop-color: var(--svg-color--f0c6a3, #F0C6A3);
  stop-opacity: 0;
}

.j0qmv8b6d {
  stop-color: var(--svg-color--7a5fb3, #7A5FB3);
}

.j0x8wibsd {
  cx: 15.706px;
  cy: 13.219px;
  rx: 0.478px;
  ry: 0.242px;
}

.j8hkuac-d {
  stop-color: var(--svg-color--ffc89e, #FFC89E);
}

.je3tjybua {
  stop-color: var(--svg-color--ffc3a0, #FFC3A0);
  stop-opacity: 0;
}

.jecjimben {
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M8.967 3.604L8.154 7.01");
}

.jfno0m0sa {
  stop-color: var(--svg-color--f2c4a1, #F2C4A1);
  stop-opacity: 0;
}

.jg3z8snxe {
  stroke: var(--svg-color--a57045, #A57045);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M21.099 11.157c.396-.096 1.38-.048 2.038.423");
}

.jj4p15bbx {
  stop-color: var(--svg-color--d08d9c, #D08D9C);
  stop-opacity: 0;
}

.jjuf3rb5e {
  stop-color: var(--svg-color--eeb69b, #EEB69B);
}

.k4dlqmj_f {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M5.68 6.607c-.13.165-.332.3-.518.4");
}

.k7vb4qsjy {
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M7.045 2.557L6.755 6.5");
}

.kdig6mnba {
  stop-color: var(--svg-color--fffabe, #FFFABE);
}

.krvd34mtu {
  stop-color: var(--svg-color--d59566, #D59566);
  stop-opacity: 0;
}

.la61skb4q {
  stop-color: var(--svg-color--e3a280, #E3A280);
  stop-opacity: 0;
}

.lc7szmbjn {
  stop-color: var(--svg-color--cd8d5e, #CD8D5E);
  stop-opacity: 0;
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lwjatlajn {
  stop-color: var(--svg-color--d1987a, #D1987A);
  stop-opacity: 0;
}

.m2mta8b_j {
  stop-color: var(--svg-color--362659, #362659);
}

.m9_oypdgy {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-075px, 0.075px);
  d: path("m5.82 4.355l-.07 2.297");
}

.m9-9n-5ej {
  d: path("m12.476 12.194l-.013-.376c.026-1.164.705-1.615.995-1.765l.063-.026l.063-.025a2.83 2.83 0 0 0 1.46-1.515l.1-.238a.324.324 0 0 1 .567-.063a4.74 4.74 0 0 0 3.915 2.054h3.952c.221 0 1.329.108 1.395 1.636l-.146 3.772c-.151 3.44-2.838 5.75-6.117 5.75s-5.966-2.31-6.117-5.75z");
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.ml_a1u4oz {
  d: path("M12.473 12.52h.016l-.013-.326l-.013-.376c.026-1.164.705-1.615.995-1.765l.063-.026l.063-.025a2.83 2.83 0 0 0 1.46-1.515l.1-.238a.324.324 0 0 1 .567-.063a4.74 4.74 0 0 0 3.915 2.054h3.952c.221 0 1.329.108 1.395 1.636l-.146 3.772c-.151 3.44-2.838 5.75-6.117 5.75s-5.966-2.31-6.117-5.75z");
}

.mt3h7fbpd {
  stop-color: var(--svg-color--e3a48e, #E3A48E);
}

.mv8kv7beo {
  stop-color: var(--svg-color--ffffc0, #FFFFC0);
}

.mvuactshi {
  stop-color: var(--svg-color--c49070, #C49070);
  stop-opacity: 0;
}

.mwk8f57wh {
  stop-color: var(--svg-color--cf8a62, #CF8A62);
}

.n2lghubug {
  stop-color: var(--svg-color--f1bea1, #F1BEA1);
}

.n4q03-1wn {
  stop-color: var(--svg-color--a4746c, #A4746C);
  stop-opacity: 0;
}

.nick4i1gd {
  stop-color: var(--svg-color--e5b38f, #E5B38F);
}

.nka4--b6e {
  stop-color: var(--svg-color--c48b78, #C48B78);
}

.nkqxn1-bm {
  stop-color: var(--svg-color--f2c4a1, #F2C4A1);
}

.nrxnoi8to {
  stop-color: var(--svg-color--6b45ad, #6B45AD);
}

.o_y73w1dt {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M3.514 7.573c.109-.063.617-.38.812-.758");
}

.o-9gnobjq {
  stop-color: var(--svg-color--f1bea1, #F1BEA1);
  stop-opacity: 0;
}

.o8-s5pjlc {
  stop-color: var(--svg-color--6b45ad, #6B45AD);
  stop-opacity: 0;
}

.oct_5_7qz {
  cx: 15.706px;
  cy: 13.219px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.478px;
  ry: 0.242px;
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.ogs4x8_bh {
  stop-color: var(--svg-color--efb99b, #EFB99B);
  stop-opacity: 0;
}

.op15yplgp {
  stop-color: var(--svg-color--ad7b7c, #AD7B7C);
}

.p_e0yoqmp {
  fill: var(--svg-color--c28178, #C28178);
  d: path("m18.236 13.796l-.84 2.087a.662.662 0 0 0 .64.858h.965a.664.664 0 0 0 .64-.858l-.653-2.087c-.14-.462-.605-.462-.752 0");
}

.p1sg1mumi {
  stop-color: var(--svg-color--ffc3a8, #FFC3A8);
  stop-opacity: 0;
}

.p6otu2-6b {
  stop-color: var(--svg-color--ffffbe, #FFFFBE);
}

.p80yl1i4o {
  fill: var(--svg-color--000, #000);
  d: path("M20.772 13.847c0-.349.278-.628.627-.628a.625.625 0 0 1 .558.917h-1.11a.57.57 0 0 1-.076-.29");
}

.phx3m2o6y {
  d: path("M7.06 13.514v5.172a2 2 0 0 0 1.38 1.901l4.183 1.363");
}

.pj__wrb2a {
  stop-color: var(--svg-color--b36d8d, #B36D8D);
  stop-opacity: 0;
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.prydr8bcy {
  stop-color: var(--svg-color--b0725a, #B0725A);
  stop-opacity: 0;
}

.pxlkji3vy {
  d: path("M21.399 12.751a1.096 1.096 0 0 1 1.055 1.385h-2.116a1.1 1.1 0 0 1 1.06-1.384");
}

.q40vy1rvh {
  d: path("M12.71 6.687c.763-.678 1.862-.685 2.48-.576l.493 1.585c-.315-.048-.596.061-.833.288c-.556 2.057-2.654 1.749-3.066 3.292c-.185-1.832-.39-3.416.926-4.589");
}

.q5mih6mme {
  stop-color: var(--svg-color--e5ae90, #E5AE90);
}

.qe0h-qt8x {
  stop-color: var(--svg-color--ffc3a0, #FFC3A0);
}

.qflnpfbur {
  stop-color: var(--svg-color--f0c6a3, #F0C6A3);
}

.qmmvvysmp {
  stop-color: var(--svg-color--e1a792, #E1A792);
}

.qnynbebrn {
  stop-color: var(--svg-color--efb99b, #EFB99B);
}

.qv1dxt4je {
  fill: var(--svg-color--fff, #fff);
  d: path("M21.653 12.418c.802 0 1.479.552 1.663 1.3a.336.336 0 0 1-.329.417H20.25a.283.283 0 0 1-.28-.333a1.716 1.716 0 0 1 1.684-1.384");
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.qzl83lbyv {
  d: path("M21.318 12.983c.078.104-.085.231-.27.37c-.186.139-.323.236-.401.132s.009-.301.194-.44c.186-.139.4-.167.477-.062");
}

.r-jog4w_t {
  stop-color: var(--svg-color--c2847a, #C2847A);
}

.ravvfdb0z {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-075px, 0.075px);
  d: path("m4.195 4.785l.149 1.945");
}

.rjxj417_v {
  stop-color: var(--svg-color--f9bfa4, #F9BFA4);
}

.rlsay17ko {
  d: path("M17.977 4.507c-1.39-.307-2.88 1.172-3.024 1.687c1.893 4.444 4.8 4.02 8.024 3.662c1.93-.215 2.14.665 2.304 1.09c-.535-4.979-4.135-5.74-7.304-6.44");
}

.rlvwxbcbx {
  stop-color: var(--svg-color--cf9271, #CF9271);
  stop-opacity: 0;
}

.rnij5z0qd {
  stop-color: var(--svg-color--8969ba, #8969BA);
  stop-opacity: 0;
}

.rxux9wbns {
  stroke: var(--svg-color--a57045, #A57045);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M16.445 11.157c-.396-.096-1.38-.048-2.038.423");
}

.rz1t4jbgv {
  stop-color: var(--svg-color--8b6ebc, #8B6EBC);
}

.s68njbc8b {
  stop-color: var(--svg-color--4f396f, #4F396F);
}

.sqmgyf2vi {
  stop-color: var(--svg-color--c49070, #C49070);
}

.t-8ibsbxr {
  d: path("m18.249 13.626l-.653 2.087a.662.662 0 0 0 .64.859h.965a.664.664 0 0 0 .639-.859l-.653-2.087c-.14-.462-.792-.462-.938 0");
}

.t5ewf8b-q {
  stop-color: var(--svg-color--ce9591, #CE9591);
  stop-opacity: 0;
}

.t6jzi2-1t {
  stop-color: var(--svg-color--b97783, #B97783);
}

.ta36f8b7v {
  stop-color: var(--svg-color--c7897d, #C7897D);
}

.tub2-2b9t {
  fill-rule: evenodd;
  d: path("M27.538 15.8a4 4 0 0 0 .397-1.751a4 4 0 0 0-.33-1.603h.007a4 4 0 0 0-.345-.63l-.002-.004a4 4 0 0 1-.646-2.173v-.013a4.05 4.05 0 0 0-4.05-4.05a.66.66 0 0 1-.56-.285a4.06 4.06 0 0 0-3.291-1.69c-1.354 0-2.56.671-3.292 1.69a.7.7 0 0 1-.56.285l-.104.002a4.05 4.05 0 0 0-3.945 4.048v.013c0 .77-.223 1.527-.646 2.174l-.003.004a4.05 4.05 0 0 0-.27 3.983a.63.63 0 0 1 0 .56a4 4 0 0 0-.398 1.726a3.944 3.944 0 0 0 3.95 3.95h10.535a3.944 3.944 0 0 0 3.95-3.95c0-.621-.149-1.205-.397-1.727a.63.63 0 0 1 0-.559m-15.05-3.28h-.015l1.472 2.891c.151 3.44 1.494 0 4.773 0s4.709 3.83 4.86.39l1.395-3.925c-.066-1.528-1.174-1.636-1.395-1.636h-3.952a4.74 4.74 0 0 1-3.915-2.054a.324.324 0 0 0-.567.063l-.1.238a2.83 2.83 0 0 1-1.523 1.54l-.063.025c-.29.15-.97.602-.995 1.766l.013.376z");
}

.tvy-4obul {
  stop-color: var(--svg-color--c3806d, #C3806D);
}

.tx_pqhb7h {
  stop-color: var(--svg-color--5e4490, #5E4490);
  stop-opacity: 0;
}

.txryfdvnp {
  d: path("M22.375 13.702a1.03 1.03 0 0 0-.284-.568l-.32.35l.145.28z");
}

.u-9w58unm {
  stop-color: var(--svg-color--745c92, #745C92);
}

.ue-yx0baa {
  stop-color: var(--svg-color--c58e72, #C58E72);
  stop-opacity: 0;
}

.urkjpbftr {
  stop-color: var(--svg-color--d1987a, #D1987A);
}

.urs_pbb4x {
  stop-color: var(--svg-color--e3a280, #E3A280);
}

.uy3z2gbbp {
  stop-color: var(--svg-color--ffc59d, #FFC59D);
}

.v-9s4u7ch {
  stop-color: var(--svg-color--cf987b, #CF987B);
  stop-opacity: 0;
}

.v60bq3cin {
  stop-color: var(--svg-color--925c51, #925C51);
}

.vm40c2rnb {
  stop-color: var(--svg-color--655188, #655188);
}

.vpa8ubcez {
  stop-color: var(--svg-color--e1a88d, #E1A88D);
}

.vrnylccvf {
  stop-color: var(--svg-color--dcc893, #DCC893);
}

.vrs9uvb1p {
  stop-color: var(--svg-color--ca895a, #CA895A);
  stop-opacity: 0;
}

.vt-rtgbrf {
  d: path("M24.643 16.045a1.975 1.975 0 1 0 0-3.95a1.975 1.975 0 0 0 0 3.95");
}

.vyevcqbzs {
  stop-color: var(--svg-color--c27b7c, #C27B7C);
}

.w58maet4h {
  stop-color: var(--svg-color--dac493, #DAC493);
  stop-opacity: 0;
}

.wcr1klbjh {
  stop-color: var(--svg-color--e3a48e, #E3A48E);
  stop-opacity: 0;
}

.wmtmv1hbb {
  stop-color: var(--svg-color--a4746c, #A4746C);
}

.x97mw867e {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M21.318 12.983c.078.104-.085.231-.27.37c-.186.139-.323.236-.401.132s.009-.301.194-.44c.186-.139.4-.167.477-.062");
}

.xi0shyhbu {
  stop-color: var(--svg-color--9e7fdf, #9E7FDF);
  stop-opacity: 0;
}

.xjkdvxqyn {
  stop-color: var(--svg-color--c2847a, #C2847A);
  stop-opacity: 0;
}

.xjug-415a {
  stop-color: var(--svg-color--fdc9a8, #FDC9A8);
}

.xkxmx1bvv {
  stop-color: var(--svg-color--8b6ebc, #8B6EBC);
  stop-opacity: 0;
}

.xrgpjcb6i {
  d: path("M18.718 23.692c-1.268 0-2.296-.986-2.296-2.2v-2.6c0-1.215 1.028-2.2 2.296-2.2s2.296.985 2.296 2.2v2.6c0 1.214-1.028 2.2-2.296 2.2");
}

.ybvptdnhb {
  stop-color: var(--svg-color--c58e72, #C58E72);
}

.ybx_6zbxd {
  stop-color: var(--svg-color--b0725a, #B0725A);
}

.yhs2bn2id {
  stop-color: var(--svg-color--f4c099, #F4C099);
}

.yy_71ub6o {
  stop-color: var(--svg-color--8967cb, #8967CB);
  stop-opacity: 0;
}

.z-_7oacfe {
  fill: var(--svg-color--88014e, #88014E);
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M16.996 17.176a3.66 3.66 0 0 0 1.722.418c.637 0 1.224-.152 1.721-.418a.24.24 0 0 1 .29.049a.23.23 0 0 1 .025.292m-3.758-.34l3.716.313m-3.716-.314a.24.24 0 0 0-.29.051a.23.23 0 0 0-.024.29m.314-.34l-.272.313m4.03.027l-.042-.027m.042.027l-.042-.027m.042.027a2.42 2.42 0 0 1-4.072 0m4.03-.027a2.37 2.37 0 0 1-3.988 0m-.042.027l.042-.027m-.042.027l.042-.027");
}

.z2bgibbpv {
  fill: var(--svg-color--fff, #fff);
  d: path("M15.783 12.418c-.802 0-1.479.552-1.663 1.3a.336.336 0 0 0 .329.417h2.738a.284.284 0 0 0 .28-.333a1.72 1.72 0 0 0-1.684-1.384");
}

.z3h433bvk {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M7.14 6.415c-.13.165-.501.36-.712.423");
}

.zar_-tbdp {
  d: path("M19.683 20.586h.97c2.49 0 7.472 3.5 7.472 9H10.192v-3.5a.67.67 0 0 0-.414-.625l-3.073-1.375c-2.49-1-3.487-3.5-3.487-5.198v-5.287c0-.564.423-1.015.932-1.015h4.114c.517 0 .932.461.932 1.015v3.985c0 1.302.996 1.5.996 1.5l5.977 1.5z");
}

.zcr9jykfw {
  stop-color: var(--svg-color--e6bd9f, #E6BD9F);
}

.zhwoeykns {
  stop-color: var(--svg-color--ca895a, #CA895A);
}

.zj_jchdfe {
  d: path("M16.037 12.751a1.096 1.096 0 0 0-1.056 1.384h2.117q.038-.14.04-.288a1.103 1.103 0 0 0-1.101-1.096");
}

.zoqmhxs6u {
  d: path("m10.168 25.908l7.87-5.15l-1.614-.172h-.255l-5.977-1.5s-.996-.198-.996-1.5v-3.97l-.016-.034c0-.543-.415-.996-.935-.996H4.15c-.509 0-.932.451-.932 1.015v5.287c0 1.698.996 4.198 3.487 5.198l3.073 1.375a.66.66 0 0 1 .39.447");
}

.zzstxpr9j {
  stop-color: var(--svg-color--e3ab91, #E3AB91);
  stop-opacity: 0;
}

</style>
