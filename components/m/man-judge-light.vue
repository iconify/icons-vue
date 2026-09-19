<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iGm3OZc)" class="clv4kpjtq"/><path fill="url(#ijLeONc)" class="clv4kpjtq"/><path fill="url(#iJL3ZLd)" class="clv4kpjtq"/><path fill="url(#i8rOCzb)" class="ql23wcbqi"/><path fill="url(#iTU2xGX)" class="ql23wcbqi"/><path fill="url(#irIj2qt)" class="ql23wcbqi"/><path fill="url(#iKN6tVd)" class="ql23wcbqi"/><path fill="url(#ipwI7qX)" class="hdyivgbfk"/><path fill="url(#iGuE85c)" class="hdyivgbfk"/><g filter="url(#i2xepGe)"><path fill="url(#iywnbgd)" class="kke8m1amm"/><path fill="url(#iIDYXKc)" class="kke8m1amm"/><path fill="url(#iZV0Trb)" class="kke8m1amm"/></g><path fill="url(#iZVANFd)" class="qi2-45w0u"/><path fill="url(#iFAquKc)" class="rnoyg417s"/><path fill="url(#iffwXhd)" class="l55w7ob1j"/><path fill="url(#iYKEfEe)" class="l55w7ob1j"/><path fill="url(#izhxxld)" class="l55w7ob1j"/><path fill="url(#ixP3ZYc)" class="i68df5d4m"/><path fill="url(#iRpI2Me)" class="i68df5d4m"/><path fill="url(#iiIhITd)" class="k53e7yruh"/><path fill="url(#i0z8YFb)" class="k53e7yruh"/><path fill="url(#iVtLKMc)" class="k53e7yruh"/><path fill="url(#iE7vcsc)" class="k53e7yruh"/><path fill="url(#iTatXte)" class="k53e7yruh"/><path fill="url(#ix9T1Kc)" class="x_kgjuy6x"/><path fill="url(#iZrAUzd)" class="x_kgjuy6x"/><path fill="url(#iBG2TYd)" class="x_kgjuy6x"/><path fill="url(#i81vgmd)" class="x_kgjuy6x"/><path fill="url(#i9iPpmj)" class="xgy7k56lm"/><path fill="url(#irAuIxe)" class="xgy7k56lm"/><path fill="url(#ig2fJfc)" class="xgy7k56lm"/><path fill="url(#iaDg4gZ)" class="dfjvh2pvz"/><path fill="url(#iEP39pd)" class="dfjvh2pvz"/><g filter="url(#is4ZJfG)"><path fill="url(#iI2Wc0c)" class="s0bgd4ckb"/><path fill="url(#iARK8vd)" class="s0bgd4ckb"/><path fill="url(#iZjHS4c)" class="s0bgd4ckb"/><path fill="url(#i27JcWb)" class="s0bgd4ckb"/><path fill="url(#i4QXMrc)" class="s0bgd4ckb"/></g><rect fill="url(#iN5HEbD)" class="u4r37-1cm"/><rect fill="url(#ijJc1xY)" class="u4r37-1cm"/><g filter="url(#infzYQc)"><path fill="url(#iEzouAb)" class="k1xozdbog"/></g><g filter="url(#iVhQbme)"><path fill="url(#iBVCuLb)" class="kti_km3lf"/></g><g filter="url(#i2pZKJb)"><path fill="url(#iv1rAPc)" class="th7rrm5vu"/></g><g filter="url(#iZIR2ge)"><path stroke="url(#ihjAftd)" class="mui4zsl_w"/></g><g filter="url(#iPVrIPb)"><path stroke="url(#iUZzsXc)" class="ntmzxmb0n"/></g><g filter="url(#iq8zWgd)"><path stroke="url(#iJnUApc)" class="u2z7cu58j"/></g><g filter="url(#i34aBPc)"><circle fill="url(#ijP3rRQ)" class="rez4i8s2j"/></g><g filter="url(#iYZk3Je)"><circle fill="url(#ib3957c)" class="t5hfiulty"/></g><g filter="url(#iNsPrae)"><circle fill="url(#iwP13se)" class="x3w8iu_4c"/><circle fill="url(#i9iEq6c)" class="x3w8iu_4c"/></g><g filter="url(#iybqcSb)"><circle class="we3s8mb2t"/><circle fill="url(#ixrlJJu)" class="rpeopjbni"/><circle fill="url(#iQVw1xe)" class="rpeopjbni"/></g><g filter="url(#isZ7wzi)"><path fill="url(#iiZRB7b)" class="p3xsy3blv"/><path fill="url(#iJ3hI6X)" class="p3xsy3blv"/><path fill="url(#inZHo7b)" class="p3xsy3blv"/><path fill="url(#iW4e2mb)" class="p3xsy3blv"/><path fill="url(#ifhpmMb)" class="p3xsy3blv"/><path fill="url(#iXII3bd)" class="p3xsy3blv"/></g><g filter="url(#iBMS0Be)"><path fill="url(#igh3B3c)" class="nkzewz0ks"/></g><g filter="url(#icpRunc)"><path class="hz5j10bxw"/><path fill="url(#ij8HFke)" class="je6jnibdt"/><path fill="url(#iVkTCjd)" class="je6jnibdt"/><path fill="url(#i6S4Uyd)" class="je6jnibdt"/><path fill="url(#isBMxAc)" class="je6jnibdt"/></g><g filter="url(#i3zY37r)"><path class="z9s532b4z"/></g><g filter="url(#ibIPnec)"><path class="bm05nxp8u"/><path fill="url(#i1LI7id)" class="gghx_qbqk"/><path fill="url(#iJQxAPc)" class="gghx_qbqk"/><path fill="url(#i1eGKGX)" class="gghx_qbqk"/><path fill="url(#ihc9Qtq)" class="gghx_qbqk"/></g><path fill="url(#i2IELvm)" class="gghx_qbqk"/><path stroke="url(#ikuvE2h)" class="c84b5obat"/><g filter="url(#isssuAd)"><path class="rlmcgkbis"/></g><g filter="url(#iadXVOd)"><path class="y49ru_b1d"/></g><path class="rp0wt3btz"/><path fill="url(#idM8ewc)" class="cy_61ebnw"/><path class="wy9dudb8o"/><g filter="url(#ijclhqe)"><path class="wyn-zr57q"/><path fill="url(#idnPWwO)" class="b6s91nlgi"/></g><g filter="url(#ijmxzkb)"><path fill="url(#iyGz4Gb)" class="daxincb9e"/></g><path class="tbjczjb4u"/><path fill="url(#iOILsnG)" class="xen1_3bnh"/><path class="pzlmopb6h"/><g filter="url(#iUxwGnb)"><path fill="url(#idEktkC)" class="t98e19bfz"/></g><g filter="url(#iU7xW1o)"><ellipse transform="rotate(-27.914 13.385 9.882)" class="qs9c4ngvv"/><ellipse fill="url(#ic001hN)" transform="rotate(-27.914 13.385 9.882)" class="sshpf1iar"/></g><g filter="url(#iVaBmCe)"><path stroke="url(#iMimVNb)" class="cvey70g5d"/></g><g filter="url(#iZfHamy)"><path stroke="url(#iJIQn3Z)" class="wblwu61sc"/></g><g filter="url(#iRetxZc)"><path stroke="url(#iNFbiqd)" class="bsea0t9qr"/></g><defs><linearGradient id="iGm3OZc" x1="15.855" x2="15.855" y1="15.544" y2="30.429" gradientUnits="userSpaceOnUse"><stop class="jko77nbfm"/><stop offset="1" class="jaal1e-1o"/></linearGradient><linearGradient id="ijLeONc" x1="23.283" x2="20.752" y1="26.598" y2="26.629" gradientUnits="userSpaceOnUse"><stop class="pxynpwacq"/><stop offset="1" class="js7rwm17w"/></linearGradient><linearGradient id="iJL3ZLd" x1="8.311" x2="10.527" y1="26.413" y2="26.413" gradientUnits="userSpaceOnUse"><stop class="r7k3cqb2o"/><stop offset="1" class="e16pzouhw"/></linearGradient><linearGradient id="iKN6tVd" x1="8.774" x2="8.339" y1="28.07" y2="28.07" gradientUnits="userSpaceOnUse"><stop offset=".444" class="o2uld0acg"/><stop offset="1" class="pts6vr7ld"/></linearGradient><linearGradient id="iywnbgd" x1="22.595" x2="16.72" y1="18.504" y2="18.504" gradientUnits="userSpaceOnUse"><stop class="l4epxabbu"/><stop offset="1" class="mjg0akbde"/></linearGradient><linearGradient id="iZVANFd" x1="16.986" x2="15.689" y1="19.082" y2="20.004" gradientUnits="userSpaceOnUse"><stop offset=".048" class="iluzr5dja"/><stop offset="1" class="huftmtb3i"/></linearGradient><linearGradient id="iiIhITd" x1="27.595" x2="24.22" y1="20.723" y2="20.348" gradientUnits="userSpaceOnUse"><stop offset=".15" class="yslyejzkq"/><stop offset="1" class="a697hhbbx"/></linearGradient><linearGradient id="i0z8YFb" x1="25.316" x2="25.316" y1="20.988" y2="20.473" gradientUnits="userSpaceOnUse"><stop class="j4l_ybb-i"/><stop offset="1" class="hmw0arboa"/></linearGradient><linearGradient id="iE7vcsc" x1="25.316" x2="25.316" y1="16.843" y2="17.473" gradientUnits="userSpaceOnUse"><stop class="xjh-ixbfp"/><stop offset="1" class="dj_b1_bgk"/></linearGradient><linearGradient id="iTatXte" x1="23.019" x2="23.76" y1="19.19" y2="19.19" gradientUnits="userSpaceOnUse"><stop class="sl5klgbuk"/><stop offset="1" class="ofpq3rdpo"/></linearGradient><linearGradient id="ix9T1Kc" x1="23.189" x2="21.892" y1="18.974" y2="18.974" gradientUnits="userSpaceOnUse"><stop offset=".277" class="o5smz7bvt"/><stop offset=".819" class="ioik6xbji"/></linearGradient><linearGradient id="iZrAUzd" x1="23.439" x2="23.049" y1="19.254" y2="19.254" gradientUnits="userSpaceOnUse"><stop class="k9y_vhbis"/><stop offset="1" class="aib520jbl"/></linearGradient><linearGradient id="iBG2TYd" x1="22.644" x2="22.644" y1="21.084" y2="20.422" gradientUnits="userSpaceOnUse"><stop class="f6yu9itto"/><stop offset="1" class="pt18zyb3d"/></linearGradient><linearGradient id="i9iPpmj" x1="28.89" x2="27.27" y1="19.421" y2="19.421" gradientUnits="userSpaceOnUse"><stop class="lwc0fqtbi"/><stop offset="1" class="b439v2bdt"/></linearGradient><linearGradient id="irAuIxe" x1="28.189" x2="28.189" y1="21.058" y2="20.535" gradientUnits="userSpaceOnUse"><stop class="c2_0e5baj"/><stop offset="1" class="zx6sfmbib"/></linearGradient><linearGradient id="iEP39pd" x1="25.317" x2="25.345" y1="22" y2="22.355" gradientUnits="userSpaceOnUse"><stop class="vhte_3bib"/><stop offset="1" class="h0-3hob0r"/></linearGradient><linearGradient id="iI2Wc0c" x1="27.314" x2="23.286" y1="28.066" y2="28.066" gradientUnits="userSpaceOnUse"><stop offset=".146" class="v5rheyc4i"/><stop offset=".861" class="j1qr75obr"/></linearGradient><linearGradient id="ijJc1xY" x1="25.328" x2="25.328" y1="20.816" y2="21.277" gradientUnits="userSpaceOnUse"><stop offset=".22" class="bwtslccfc"/><stop offset="1" class="aq7ukmb7b"/></linearGradient><linearGradient id="iEzouAb" x1="16.905" x2="16.905" y1="29.607" y2="22.93" gradientUnits="userSpaceOnUse"><stop class="sxo3xwbvl"/><stop offset="1" class="cfl87rzth"/></linearGradient><linearGradient id="iBVCuLb" x1="12.899" x2="12.899" y1="29.607" y2="22.93" gradientUnits="userSpaceOnUse"><stop class="sxo3xwbvl"/><stop offset="1" class="cfl87rzth"/></linearGradient><linearGradient id="iv1rAPc" x1="20.892" x2="20.892" y1="29.607" y2="22.93" gradientUnits="userSpaceOnUse"><stop class="sxo3xwbvl"/><stop offset="1" class="cfl87rzth"/></linearGradient><linearGradient id="ihjAftd" x1="23.806" x2="25.516" y1="26.074" y2="26.074" gradientUnits="userSpaceOnUse"><stop class="vx-77wbda"/><stop offset="1" class="r0p9vfbnw"/></linearGradient><linearGradient id="iUZzsXc" x1="23.728" x2="25.438" y1="27.379" y2="27.379" gradientUnits="userSpaceOnUse"><stop class="vx-77wbda"/><stop offset="1" class="r0p9vfbnw"/></linearGradient><linearGradient id="iJnUApc" x1="23.806" x2="25.516" y1="28.683" y2="28.683" gradientUnits="userSpaceOnUse"><stop class="vx-77wbda"/><stop offset="1" class="r0p9vfbnw"/></linearGradient><linearGradient id="ib3957c" x1="11.093" x2="10.452" y1="10.939" y2="10.939" gradientUnits="userSpaceOnUse"><stop class="wachewblq"/><stop offset="1" class="px4pa2bzd"/></linearGradient><linearGradient id="iwP13se" x1="21.692" x2="20.873" y1="9.569" y2="12.105" gradientUnits="userSpaceOnUse"><stop class="fuy988_rs"/><stop offset="1" class="h2u-65bda"/></linearGradient><linearGradient id="iiZRB7b" x1="19.876" x2="12.24" y1="11.049" y2="12.187" gradientUnits="userSpaceOnUse"><stop class="z8y6fgvmn"/><stop offset="1" class="tqgh1edwg"/></linearGradient><linearGradient id="inZHo7b" x1="10.198" x2="13.556" y1="12.577" y2="12.69" gradientUnits="userSpaceOnUse"><stop class="z3n_1mwef"/><stop offset="1" class="rvf3-0bfj"/></linearGradient><linearGradient id="iW4e2mb" x1="10.445" x2="12.326" y1="13.745" y2="13.678" gradientUnits="userSpaceOnUse"><stop class="hmo3unbrx"/><stop offset="1" class="yyvs3obha"/></linearGradient><linearGradient id="igh3B3c" x1="15.309" x2="23.452" y1="8.065" y2="5.149" gradientUnits="userSpaceOnUse"><stop class="sbbw_6vcc"/><stop offset="1" class="b7cutjkii"/></linearGradient><linearGradient id="i1LI7id" x1="14.976" x2="15.914" y1="11.709" y2="11.709" gradientUnits="userSpaceOnUse"><stop class="h7h6nwjtb"/><stop offset="1" class="btip4dbzo"/></linearGradient><linearGradient id="iJQxAPc" x1="16.779" x2="15.753" y1="12.031" y2="12.016" gradientUnits="userSpaceOnUse"><stop class="ag4c77bht"/><stop offset="1" class="qb120pbsb"/></linearGradient><linearGradient id="i1eGKGX" x1="16.035" x2="16.035" y1="12.773" y2="12.2" gradientUnits="userSpaceOnUse"><stop class="rlzetx3ey"/><stop offset="1" class="zf2atv-8x"/></linearGradient><linearGradient id="i2IELvm" x1="15.966" x2="15.966" y1="12.815" y2="12.648" gradientUnits="userSpaceOnUse"><stop class="l1er17byo"/><stop offset="1" class="abcg0lbyl"/></linearGradient><linearGradient id="ikuvE2h" x1="14.803" x2="15.238" y1="14.388" y2="13.701" gradientUnits="userSpaceOnUse"><stop class="wl-j51biu"/><stop offset=".663" class="i-vkeo5mo"/></linearGradient><linearGradient id="iyGz4Gb" x1="18.797" x2="18.483" y1="10.032" y2="10.225" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="idEktkC" x1="14.4" x2="14.086" y1="10.032" y2="10.225" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iMimVNb" x1="18.813" x2="18.392" y1="7.892" y2="7.034" gradientUnits="userSpaceOnUse"><stop class="wi8di0b_n"/><stop offset="1" class="zx1idre_k"/></linearGradient><linearGradient id="iJIQn3Z" x1="13.508" x2="12.319" y1="7.765" y2="7.266" gradientUnits="userSpaceOnUse"><stop class="wi8di0b_n"/><stop offset="1" class="zx1idre_k"/></linearGradient><linearGradient id="iNFbiqd" x1="11.179" x2="11.179" y1="5.75" y2="7.907" gradientUnits="userSpaceOnUse"><stop class="nc1ak66ax"/><stop offset="1" class="vpvekld5v"/></linearGradient><radialGradient id="i8rOCzb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -19.1787 5.74827 0 4.778 30.004)" gradientUnits="userSpaceOnUse"><stop class="ogfz3obbf"/><stop offset=".434" class="odeeueq9k"/><stop offset="1" class="w950_6h3e"/></radialGradient><radialGradient id="iTU2xGX" cx="0" cy="0" r="1" gradientTransform="matrix(0 -10.533 .84225 0 8.627 30.004)" gradientUnits="userSpaceOnUse"><stop offset=".286" class="u3uwpbbrc"/><stop offset="1" class="ebol5nf6u"/></radialGradient><radialGradient id="irIj2qt" cx="0" cy="0" r="1" gradientTransform="matrix(0 7.20963 -.92291 0 8.627 23.055)" gradientUnits="userSpaceOnUse"><stop class="af-h-_b2n"/><stop offset="1" class="km_8bqcup"/></radialGradient><radialGradient id="ipwI7qX" cx="0" cy="0" r="1" gradientTransform="rotate(-100.677 24.94 4.636)scale(10.3854 2.97327)" gradientUnits="userSpaceOnUse"><stop class="g27cpdbvv"/><stop offset="1" class="q3c-4jb0v"/></radialGradient><radialGradient id="iGuE85c" cx="0" cy="0" r="1" gradientTransform="matrix(.55555 12.0481 -1.01912 .047 22.909 23.157)" gradientUnits="userSpaceOnUse"><stop offset=".177" class="lqqi92blh"/><stop offset="1" class="tcm21mbym"/></radialGradient><radialGradient id="iIDYXKc" cx="0" cy="0" r="1" gradientTransform="matrix(5.96102 5.60934 -10.1311 10.76628 15.869 14.816)" gradientUnits="userSpaceOnUse"><stop offset=".91" class="w-er2h93j"/><stop offset=".937" class="nbg9ac2nn"/></radialGradient><radialGradient id="iZV0Trb" cx="0" cy="0" r="1" gradientTransform="matrix(-5.11642 0 0 -3.80242 15.869 16.394)" gradientUnits="userSpaceOnUse"><stop class="qbrho_b3d"/><stop offset="1" class="jxn3-wb7y"/></radialGradient><radialGradient id="iFAquKc" cx="0" cy="0" r="1" gradientTransform="matrix(0 3.03125 -2.76048 0 15.856 18.504)" gradientUnits="userSpaceOnUse"><stop offset=".464" class="o5ej-52sf"/><stop offset="1" class="wyytu2b0o"/></radialGradient><radialGradient id="iffwXhd" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.27137 -3.54923 0 16.629 16.466)" gradientUnits="userSpaceOnUse"><stop class="fqxr12j4i"/><stop offset="1" class="rhyy10bsj"/></radialGradient><radialGradient id="iYKEfEe" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.42297 -2.45165 0 15.859 15.378)" gradientUnits="userSpaceOnUse"><stop offset=".612" class="c1m1iubdt"/><stop offset=".923" class="uupgmqj6k"/></radialGradient><radialGradient id="izhxxld" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.42187 -.53125 0 14.548 16.223)" gradientUnits="userSpaceOnUse"><stop offset=".418" class="n50spdbkh"/><stop offset="1" class="a-vopxe4e"/></radialGradient><radialGradient id="ixP3ZYc" cx="0" cy="0" r="1" gradientTransform="rotate(154.355 11.351 15.127)scale(2.33554 2.29591)" gradientUnits="userSpaceOnUse"><stop offset=".524" class="tj2vllbvr"/><stop offset=".956" class="fop80r8ws"/></radialGradient><radialGradient id="iRpI2Me" cx="0" cy="0" r="1" gradientTransform="rotate(-37.372 48.297 -28.755)scale(.9457 .72531)" gradientUnits="userSpaceOnUse"><stop offset=".132" class="q7l79-2rh"/><stop offset="1" class="aszpk2bre"/></radialGradient><radialGradient id="iVtLKMc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.9294 0 0 -.32098 26.554 17.397)" gradientUnits="userSpaceOnUse"><stop class="ie4iw9rqt"/><stop offset="1" class="y78upfugg"/></radialGradient><radialGradient id="i81vgmd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.07813 0 0 -.3432 23.267 17.223)" gradientUnits="userSpaceOnUse"><stop class="gwbo6ccta"/><stop offset="1" class="e_7rjsbau"/></radialGradient><radialGradient id="ig2fJfc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.0625 0 0 -.29688 29.033 17.473)" gradientUnits="userSpaceOnUse"><stop class="hjqvsnb9q"/><stop offset="1" class="kc7tdcpzt"/></radialGradient><radialGradient id="iaDg4gZ" cx="0" cy="0" r="1" gradientTransform="matrix(-1.15625 0 0 -6.89354 25.955 24.288)" gradientUnits="userSpaceOnUse"><stop class="guhwv3amf"/><stop offset=".851" class="eknpx1bxe"/></radialGradient><radialGradient id="iARK8vd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .8017 -1.35439 0 25.723 25.308)" gradientUnits="userSpaceOnUse"><stop offset=".106" class="uzac_3qef"/><stop offset="1" class="b570nlb5r"/></radialGradient><radialGradient id="iZjHS4c" cx="0" cy="0" r="1" gradientTransform="matrix(0 .85938 -1.45182 0 25.723 26.603)" gradientUnits="userSpaceOnUse"><stop offset=".109" class="uzac_3qef"/><stop offset="1" class="b570nlb5r"/></radialGradient><radialGradient id="i27JcWb" cx="0" cy="0" r="1" gradientTransform="matrix(0 .71875 -1.21425 0 25.723 27.853)" gradientUnits="userSpaceOnUse"><stop offset=".109" class="uzac_3qef"/><stop offset="1" class="b570nlb5r"/></radialGradient><radialGradient id="i4QXMrc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .79938 -1.7273 0 25.723 29.204)" gradientUnits="userSpaceOnUse"><stop offset=".186" class="uzac_3qef"/><stop offset="1" class="b570nlb5r"/></radialGradient><radialGradient id="iN5HEbD" cx="0" cy="0" r="1" gradientTransform="matrix(-1.97656 0 0 -.375 26.4 21.465)" gradientUnits="userSpaceOnUse"><stop class="awi5873rb"/><stop offset="1" class="qwu7q3ojv"/></radialGradient><radialGradient id="ijP3rRQ" cx="0" cy="0" r="1" gradientTransform="matrix(1.75471 0 0 3.07077 9.424 10.66)" gradientUnits="userSpaceOnUse"><stop offset=".351" class="crp6d4bqv"/><stop offset="1" class="lu78seb9e"/></radialGradient><radialGradient id="i9iEq6c" cx="0" cy="0" r="1" gradientTransform="matrix(.82663 -.60192 .68701 .9435 20.977 10.395)" gradientUnits="userSpaceOnUse"><stop offset=".543" class="wdqn7tq-u"/><stop offset="1" class="r3t82tbzk"/></radialGradient><radialGradient id="ixrlJJu" cx="0" cy="0" r="1" gradientTransform="matrix(.8212 -1.5104 .88405 .48065 20.564 11.481)" gradientUnits="userSpaceOnUse"><stop offset=".755" class="n7c5lw_4k"/><stop offset=".916" class="bw8j_5egh"/></radialGradient><radialGradient id="iQVw1xe" cx="0" cy="0" r="1" gradientTransform="rotate(44.707 -2.659 30.383)scale(.3648 .47028)" gradientUnits="userSpaceOnUse"><stop class="fa9i5bbvu"/><stop offset="1" class="x8d9utbsu"/></radialGradient><radialGradient id="iJ3hI6X" cx="0" cy="0" r="1" gradientTransform="matrix(0 8.90609 -12.0895 0 15.87 8.735)" gradientUnits="userSpaceOnUse"><stop offset=".557" class="cr5_lwfgk"/><stop offset="1" class="hz1zkz7hg"/></radialGradient><radialGradient id="ifhpmMb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.30697 1.60858 0 18.186 9.389)" gradientUnits="userSpaceOnUse"><stop class="m459pab_j"/><stop offset="1" class="rcuz4uefu"/></radialGradient><radialGradient id="iXII3bd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.39075 1.72952 0 13.629 9.355)" gradientUnits="userSpaceOnUse"><stop class="hplqxft1w"/><stop offset="1" class="ay1rn8bxh"/></radialGradient><radialGradient id="ij8HFke" cx="0" cy="0" r="1" gradientTransform="rotate(-74.899 14.371 -9.9)scale(3.06211 1.13553)" gradientUnits="userSpaceOnUse"><stop class="ui2kgq2tt"/><stop offset="1" class="bumyo9b5s"/></radialGradient><radialGradient id="iVkTCjd" cx="0" cy="0" r="1" gradientTransform="rotate(5.258 -42.936 204.319)scale(3.84067 2.0651)" gradientUnits="userSpaceOnUse"><stop offset=".335" class="d4d293bim"/><stop offset="1" class="yf9erdbmk"/></radialGradient><radialGradient id="i6S4Uyd" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.67903 -2.60035 0 15.84 2.06)" gradientUnits="userSpaceOnUse"><stop class="qc5tyzrav"/><stop offset="1" class="m_1e2qbpe"/></radialGradient><radialGradient id="isBMxAc" cx="0" cy="0" r="1" gradientTransform="matrix(3.07368 -2.25248 3.5289 4.81545 9.392 8.877)" gradientUnits="userSpaceOnUse"><stop class="gg1n47rtb"/><stop offset="1" class="uk24qccae"/></radialGradient><radialGradient id="ihc9Qtq" cx="0" cy="0" r="1" gradientTransform="matrix(0 .19688 -.63254 0 16.168 12.266)" gradientUnits="userSpaceOnUse"><stop class="a7vfdrbiy"/><stop offset="1" class="x6mjr8bji"/></radialGradient><radialGradient id="idM8ewc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81106 -1.29009 0 18.02 9.978)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="idnPWwO" cx="0" cy="0" r="1" gradientTransform="matrix(-.23184 -.29876 .41132 -.3192 17.79 10.062)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iOILsnG" cx="0" cy="0" r="1" gradientTransform="matrix(0 .8111 -1.29015 0 13.656 9.978)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="ic001hN" cx="0" cy="0" r="1" gradientTransform="rotate(-90.897 11.704 -1.483)scale(.49399 .59379)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><filter id="i2xepGe" width="14.254" height="7.618" x="8.842" y="15.299" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.15"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.2 0 0 0 0 0.141176 0 0 0 0 0.254902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1742"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy=".1"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.419608 0 0 0 0 0.4 0 0 0 0 0.439216 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1742" result="effect2_innerShadow_4002_1742"/></filter><filter id="is4ZJfG" width="4.468" height="5.556" x="23.286" y="24.447" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.15"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.729412 0 0 0 0 0.509804 0 0 0 0 0.603922 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1742"/></filter><filter id="infzYQc" width="1.192" height="6.826" x="15.273" y="23.297" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1742" stdDeviation=".125"/></filter><filter id="iVhQbme" width="1.192" height="6.826" x="11.266" y="23.297" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1742" stdDeviation=".125"/></filter><filter id="i2pZKJb" width="1.192" height="6.826" x="19.259" y="23.297" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1742" stdDeviation=".125"/></filter><filter id="iZIR2ge" width="2.097" height=".3" x="23.656" y="25.846" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1742" stdDeviation=".05"/></filter><filter id="iPVrIPb" width="2.097" height=".3" x="23.578" y="27.151" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1742" stdDeviation=".05"/></filter><filter id="iq8zWgd" width="2.097" height=".3" x="23.656" y="28.455" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1742" stdDeviation=".05"/></filter><filter id="i34aBPc" width="3.539" height="3.339" x="9.424" y="8.991" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.917647 0 0 0 0 0.694118 0 0 0 0 0.607843 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1742"/></filter><filter id="iYZk3Je" width="2.99" height="2.99" x="9.598" y="9.165" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1742" stdDeviation=".25"/></filter><filter id="iNsPrae" width="3.589" height="3.589" x="18.936" y="8.741" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.843137 0 0 0 0 0.623529 0 0 0 0 0.580392 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1742"/></filter><filter id="iybqcSb" width="2.99" height="2.99" x="19.11" y="9.165" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1742" stdDeviation=".25"/></filter><filter id="isZ7wzi" width="10.373" height="12.277" x="10.683" y="5.036" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".25"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.819608 0 0 0 0 0.615686 0 0 0 0 0.509804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1742"/></filter><filter id="iBMS0Be" width="8.246" height="7.066" x="14.01" y="3.036" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1742" stdDeviation="1"/></filter><filter id="icpRunc" width="12.601" height="8.543" x="9.54" y="1.559" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0392157 0 0 0 0 0.00784314 0 0 0 0 0.0196078 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1742"/></filter><filter id="i3zY37r" width="3.26" height="4.181" x="13.972" y="9.505" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1742" stdDeviation=".375"/></filter><filter id="ibIPnec" width="2.377" height="3.181" x="14.652" y="9.842" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1742" stdDeviation=".125"/></filter><filter id="isssuAd" width="2.979" height="1.873" x="17.023" y="7.011" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0431373 0 0 0 0 0.0196078 0 0 0 0 0.027451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1742"/></filter><filter id="iadXVOd" width="2.98" height="1.873" x="11.875" y="7.011" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0431373 0 0 0 0 0.0196078 0 0 0 0 0.027451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1742"/></filter><filter id="ijclhqe" width=".787" height=".696" x="17.285" y="9.538" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1742" stdDeviation=".05"/></filter><filter id="ijmxzkb" width=".891" height=".913" x="18.125" y="9.613" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1742" stdDeviation=".1"/></filter><filter id="iUxwGnb" width=".986" height="1.04" x="13.683" y="9.55" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1742" stdDeviation=".1"/></filter><filter id="iU7xW1o" width=".913" height=".704" x="12.929" y="9.53" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1742" stdDeviation=".05"/></filter><filter id="iVaBmCe" width="3.099" height="1.681" x="16.876" y="7.137" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1742" stdDeviation=".25"/></filter><filter id="iZfHamy" width="3.177" height="1.738" x="11.657" y="7.201" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1742" stdDeviation=".25"/></filter><filter id="iRetxZc" width="1.008" height="2.269" x="10.675" y="5.474" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1742" stdDeviation=".125"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:man-judge-light" /></template>
<style>
.a-vopxe4e {
  stop-color: var(--svg-color--cf9c8e, #CF9C8E);
  stop-opacity: 0;
}

.a697hhbbx {
  stop-color: var(--svg-color--663e3d, #663E3D);
}

.a7vfdrbiy {
  stop-color: var(--svg-color--ffd7c1, #FFD7C1);
}

.abcg0lbyl {
  stop-color: var(--svg-color--d6938e, #D6938E);
  stop-opacity: 0;
}

.af-h-_b2n {
  stop-color: var(--svg-color--4e425a, #4E425A);
}

.ag4c77bht {
  stop-color: var(--svg-color--ffdfc4, #FFDFC4);
}

.aib520jbl {
  stop-color: var(--svg-color--532820, #532820);
  stop-opacity: 0;
}

.aq7ukmb7b {
  stop-color: var(--svg-color--54201c, #54201C);
  stop-opacity: 0;
}

.aszpk2bre {
  stop-color: var(--svg-color--f7ceb9, #F7CEB9);
  stop-opacity: 0;
}

.awi5873rb {
  stop-color: var(--svg-color--7c5f5a, #7C5F5A);
}

.ay1rn8bxh {
  stop-color: var(--svg-color--d0958d, #D0958D);
  stop-opacity: 0;
}

.b439v2bdt {
  stop-color: var(--svg-color--62312b, #62312B);
}

.b570nlb5r {
  stop-color: var(--svg-color--ffd1bb, #FFD1BB);
  stop-opacity: 0;
}

.b6s91nlgi {
  d: path("M17.956 9.69c.063.085-.07.188-.22.301c-.152.113-.264.193-.328.108c-.063-.085.008-.246.159-.359c.15-.113.325-.135.389-.05");
}

.b7cutjkii {
  stop-color: var(--svg-color--ffdec4, #FFDEC4);
  stop-opacity: 0;
}

.bm05nxp8u {
  fill: var(--svg-color--fbc4b1, #FBC4B1);
  d: path("m15.458 10.375l-.531 1.7a.54.54 0 0 0 .52.698h.787a.54.54 0 0 0 .52-.699l-.531-1.7c-.114-.376-.645-.376-.765 0");
}

.bsea0t9qr {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M11.308 5.85v.897c-.008.148-.07.48-.258.621");
}

.btip4dbzo {
  stop-color: var(--svg-color--dfa790, #DFA790);
  stop-opacity: 0;
}

.bumyo9b5s {
  stop-color: var(--svg-color--464344, #464344);
  stop-opacity: 0;
}

.bw8j_5egh {
  stop-color: var(--svg-color--d6a38d, #D6A38D);
}

.bwtslccfc {
  stop-color: var(--svg-color--54201c, #54201C);
}

.c1m1iubdt {
  stop-color: var(--svg-color--b88168, #B88168);
  stop-opacity: 0;
}

.c2_0e5baj {
  stop-color: var(--svg-color--7a464a, #7A464A);
}

.c84b5obat {
  fill: var(--svg-color--88024e, #88024E);
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M14.479 13.417c.393.205.862.323 1.361.323c.505 0 .969-.118 1.362-.323a.2.2 0 0 1 .242.04c.058.06.079.154.02.24m-2.985-.28l2.944.253m-2.944-.253h-.001a.2.2 0 0 0-.242.042a.19.19 0 0 0-.02.24m.263-.282l-.221.253m3.207.028l-.042-.028m.042.028l-.042-.028m.042.028a1.94 1.94 0 0 1-1.625.868c-.681 0-1.28-.347-1.624-.868m3.207-.028a1.9 1.9 0 0 1-1.583.846a1.9 1.9 0 0 1-1.582-.846m-.042.028l.042-.028m-.042.028l.042-.028");
}

.cfl87rzth {
  stop-color: var(--svg-color--3f3647, #3F3647);
  stop-opacity: 0;
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.clv4kpjtq {
  d: path("M15.859 15.544c-6.115 0-11.08 4.907-11.08 10.97v3.49h21.65a.5.5 0 0 0 .5-.5v-2.99c0-6.063-4.956-10.97-11.07-10.97");
}

.cr5_lwfgk {
  stop-color: var(--svg-color--dba29e, #DBA29E);
  stop-opacity: 0;
}

.crp6d4bqv {
  stop-color: var(--svg-color--cf9888, #CF9888);
}

.cvey70g5d {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M17.5 7.796c.43-.076 1.27-.054 1.85.397");
}

.cy_61ebnw {
  d: path("M18.021 9.501a.892.892 0 0 1 .86 1.128h-1.724a.896.896 0 0 1 .864-1.127");
}

.d4d293bim {
  stop-color: var(--svg-color--4a4648, #4A4648);
}

.daxincb9e {
  d: path("M18.816 10.276a.84.84 0 0 0-.232-.463l-.26.285l.118.228z");
}

.dfjvh2pvz {
  d: path("M24.562 21.075V27.5h1.511v-6.426z");
}

.dj_b1_bgk {
  stop-color: var(--svg-color--755144, #755144);
  stop-opacity: 0;
}

.e_7rjsbau {
  stop-color: var(--svg-color--745e58, #745E58);
  stop-opacity: 0;
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.e16pzouhw {
  stop-color: var(--svg-color--5a4e68, #5A4E68);
  stop-opacity: 0;
}

.ebol5nf6u {
  stop-color: var(--svg-color--4f445b, #4F445B);
  stop-opacity: 0;
}

.eknpx1bxe {
  stop-color: var(--svg-color--754636, #754636);
}

.f6yu9itto {
  stop-color: var(--svg-color--663848, #663848);
}

.fa9i5bbvu {
  stop-color: var(--svg-color--d5a58e, #D5A58E);
}

.fop80r8ws {
  stop-color: var(--svg-color--c79175, #C79175);
}

.fqxr12j4i {
  stop-color: var(--svg-color--d29b92, #D29B92);
}

.ft5dv1b6b {
  fill: none;
}

.fuy988_rs {
  stop-color: var(--svg-color--fbd3bd, #FBD3BD);
}

.g27cpdbvv {
  stop-color: var(--svg-color--736782, #736782);
}

.gg1n47rtb {
  stop-color: var(--svg-color--463c39, #463C39);
}

.gghx_qbqk {
  d: path("m15.458 10.375l-.531 1.7a.54.54 0 0 0 .52.698h.787a.54.54 0 0 0 .52-.699l-.531-1.7c-.114-.376-.645-.376-.765 0");
}

.guhwv3amf {
  stop-color: var(--svg-color--82625c, #82625C);
}

.gwbo6ccta {
  stop-color: var(--svg-color--745e58, #745E58);
}

.h0-3hob0r {
  stop-color: var(--svg-color--523135, #523135);
  stop-opacity: 0;
}

.h2u-65bda {
  stop-color: var(--svg-color--f0b8a4, #F0B8A4);
}

.h7h6nwjtb {
  stop-color: var(--svg-color--dfa790, #DFA790);
}

.hdyivgbfk {
  d: path("M23.08 30.004v-11.8c2.357 2.01 3.85 4.986 3.85 8.31v2.49a1 1 0 0 1-1 1z");
}

.hjqvsnb9q {
  stop-color: var(--svg-color--83645e, #83645E);
}

.hmo3unbrx {
  stop-color: var(--svg-color--e8ad97, #E8AD97);
}

.hmw0arboa {
  stop-color: var(--svg-color--703e47, #703E47);
  stop-opacity: 0;
}

.hplqxft1w {
  stop-color: var(--svg-color--d0958d, #D0958D);
}

.huftmtb3i {
  stop-color: var(--svg-color--ada3a2, #ADA3A2);
}

.hz1zkz7hg {
  stop-color: var(--svg-color--d58b81, #D58B81);
}

.hz5j10bxw {
  fill: var(--svg-color--242324, #242324);
  d: path("m20.659 4.183l.429.213c.75.373 1.18 1.227 1.019 2.133l-.59 3.04c-.053.314-.26.525-.572.533h-.018s.054-.906.107-1.44c.044-.433-.032-.565-.429-.96c-.214-.213-.375-.533-.375-.853v-.853c0-.267-.215-.48-.43-.533c-.643-.16-1.984-.427-3.915-.427c-1.93 0-3.271.267-3.915.427a.52.52 0 0 0-.43.533v.853c0 .32-.106.64-.375.853l-.16.16c-.215.16-.322.48-.322.747c.053.587.107 1.44.107 1.44l-.05-.002a.63.63 0 0 1-.594-.531l-.59-3.04c-.107-.853.322-1.707 1.073-2.08l.43-.213c.267-.16.536-.374.804-.587l.965-1.013c.59-.534 1.448-.694 2.2-.32a2.94 2.94 0 0 0 1.662 0c.804-.267 1.716-.054 2.36.533l.804.8c.215.267.483.427.805.587");
}

.i-vkeo5mo {
  stop-color: var(--svg-color--d9a4a4, #D9A4A4);
  stop-opacity: 0;
}

.i68df5d4m {
  d: path("M26.642 22.937c.532 0 .959.427.959.958v2.189h-1.907v-2.189a.94.94 0 0 1 .948-.958");
}

.ie4iw9rqt {
  stop-color: var(--svg-color--8a6a62, #8A6A62);
}

.iluzr5dja {
  stop-color: var(--svg-color--978b8d, #978B8D);
}

.ioik6xbji {
  stop-color: var(--svg-color--64423e, #64423E);
}

.j1qr75obr {
  stop-color: var(--svg-color--d8a696, #D8A696);
}

.j4l_ybb-i {
  stop-color: var(--svg-color--703e47, #703E47);
}

.jaal1e-1o {
  stop-color: var(--svg-color--544168, #544168);
}

.je6jnibdt {
  d: path("m20.659 4.183l.429.213c.75.373 1.18 1.227 1.019 2.133l-.59 3.04c-.053.314-.26.525-.572.533h-.018s.054-.906.107-1.44c.044-.433-.032-.565-.429-.96c-.214-.213-.375-.533-.375-.853v-.853c0-.267-.215-.48-.43-.533c-.643-.16-1.984-.427-3.915-.427c-1.93 0-3.271.267-3.915.427a.52.52 0 0 0-.43.533v.853c0 .32-.106.64-.375.853l-.16.16c-.215.16-.322.48-.322.747c.053.587.107 1.44.107 1.44l-.05-.002a.63.63 0 0 1-.594-.531l-.59-3.04c-.107-.853.322-1.707 1.073-2.08l.43-.213c.267-.16.536-.374.804-.587l.965-1.013c.59-.534 1.448-.694 2.2-.32a2.94 2.94 0 0 0 1.662 0c.804-.267 1.716-.054 2.36.533l.804.8c.215.267.483.427.805.587");
}

.jko77nbfm {
  stop-color: var(--svg-color--546, #546);
}

.js7rwm17w {
  stop-color: var(--svg-color--493757, #493757);
  stop-opacity: 0;
}

.jxn3-wb7y {
  stop-color: var(--svg-color--3b2321, #3B2321);
  stop-opacity: 0;
}

.k1xozdbog {
  d: path("M15.523 23.547h.692v6.326h-.692z");
}

.k53e7yruh {
  d: path("M26.766 16.959h-2.9a.505.505 0 0 0-.504.504v3.022c0 .271.221.503.503.503h2.901a.505.505 0 0 0 .504-.503v-3.022a.51.51 0 0 0-.504-.504");
}

.k9y_vhbis {
  stop-color: var(--svg-color--52251c, #52251C);
}

.kc7tdcpzt {
  stop-color: var(--svg-color--83645e, #83645E);
  stop-opacity: 0;
}

.kke8m1amm {
  d: path("M8.93 17.872c1.974-1.646 4.385-2.423 6.939-2.423c2.553 0 4.965.777 6.94 2.423a.24.24 0 0 1 .06.296c-1.354 2.69-3.772 4.65-7 4.65s-5.646-1.96-7.001-4.65a.24.24 0 0 1 .061-.296");
}

.km_8bqcup {
  stop-color: var(--svg-color--4e425a, #4E425A);
  stop-opacity: 0;
}

.kti_km3lf {
  d: path("M11.516 23.547h.692v6.326h-.692z");
}

.l1er17byo {
  stop-color: var(--svg-color--d6938e, #D6938E);
}

.l4epxabbu {
  stop-color: var(--svg-color--564d5b, #564D5B);
}

.l55w7ob1j {
  d: path("M15.859 18.738a2.07 2.07 0 0 1-2.075-2.075v-2.58a2.07 2.07 0 0 1 2.075-2.064c1.148 0 2.075.926 2.075 2.075v2.579a2.083 2.083 0 0 1-2.075 2.065");
}

.l7c47o-wr {
  stop-color: var(--svg-color--664944, #664944);
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lqqi92blh {
  stop-color: var(--svg-color--3f2a51, #3F2A51);
}

.lu78seb9e {
  stop-color: var(--svg-color--be8c77, #BE8C77);
}

.lwc0fqtbi {
  stop-color: var(--svg-color--8b6961, #8B6961);
}

.m_1e2qbpe {
  stop-color: var(--svg-color--423d3f, #423D3F);
  stop-opacity: 0;
}

.m459pab_j {
  stop-color: var(--svg-color--f5b7a7, #F5B7A7);
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mjg0akbde {
  stop-color: var(--svg-color--433945, #433945);
}

.mui4zsl_w {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M23.806 25.996h1.797");
}

.n50spdbkh {
  stop-color: var(--svg-color--cf9c8e, #CF9C8E);
}

.n7c5lw_4k {
  stop-color: var(--svg-color--d6a38d, #D6A38D);
  stop-opacity: 0;
}

.nbg9ac2nn {
  stop-color: var(--svg-color--59545e, #59545E);
}

.nc1ak66ax {
  stop-color: var(--svg-color--3c393a, #3C393A);
}

.nkzewz0ks {
  d: path("m19.804 5.036l-3.078 1.026a1.047 1.047 0 0 0 .47 2.031l3.06-.41z");
}

.ntmzxmb0n {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M23.728 27.3h1.797");
}

.o2uld0acg {
  stop-color: var(--svg-color--433850, #433850);
}

.o5ej-52sf {
  stop-color: var(--svg-color--d7cace, #D7CACE);
}

.o5smz7bvt {
  stop-color: var(--svg-color--6d5150, #6D5150);
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.odeeueq9k {
  stop-color: var(--svg-color--675375, #675375);
}

.ofpq3rdpo {
  stop-color: var(--svg-color--4c1912, #4C1912);
  stop-opacity: 0;
}

.ogfz3obbf {
  stop-color: var(--svg-color--957b8d, #957B8D);
}

.p3xsy3blv {
  d: path("M10.683 8.609c0-.267.107-.587.322-.747l.16-.16c.269-.213.376-.533.376-.853v-.853c0-.267.16-.48.429-.533c.644-.16 1.984-.427 3.915-.427s3.272.267 3.916.427c.214.053.429.266.429.533v.853c0 .32.16.64.375.853c.502.352.471.546.43.96a46 46 0 0 0-.108 1.44h.018l-.266 3.958c-.16 1.77-1.551 3.003-3.21 3.003h-3.21c-1.712 0-3.05-1.233-3.21-3.003c-.14-1.816-.2-3.638-.366-5.451");
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pt18zyb3d {
  stop-color: var(--svg-color--663848, #663848);
  stop-opacity: 0;
}

.pts6vr7ld {
  stop-color: var(--svg-color--433850, #433850);
  stop-opacity: 0;
}

.px4pa2bzd {
  stop-color: var(--svg-color--be8474, #BE8474);
}

.pxynpwacq {
  stop-color: var(--svg-color--6e6478, #6E6478);
}

.pzlmopb6h {
  fill: var(--svg-color--000, #000);
  d: path("M14.165 10.393a.51.51 0 0 0-.51-.51a.51.51 0 0 0-.455.746h.905a.5.5 0 0 0 .06-.236");
}

.q3c-4jb0v {
  stop-color: var(--svg-color--5f5070, #5F5070);
}

.q7l79-2rh {
  stop-color: var(--svg-color--f7ceb9, #F7CEB9);
}

.qb120pbsb {
  stop-color: var(--svg-color--ffdfc4, #FFDFC4);
  stop-opacity: 0;
}

.qbrho_b3d {
  stop-color: var(--svg-color--3b2321, #3B2321);
}

.qc5tyzrav {
  stop-color: var(--svg-color--423d3f, #423D3F);
}

.qi2-45w0u {
  d: path("m16.786 19.765l-.655.584a.416.416 0 0 1-.554 0l-.655-.584a3.47 3.47 0 0 1-1.148-2.569v-3.112a2.085 2.085 0 0 1 2.085-2.065c1.148 0 2.075.926 2.075 2.075v3.112a3.5 3.5 0 0 1-1.149 2.559");
}

.ql23wcbqi {
  d: path("M8.627 30.004v-11.8c-2.356 2.01-3.849 4.986-3.849 8.31v3.49z");
}

.qs9c4ngvv {
  cx: 13.385px;
  cy: 9.882px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.389px;
  ry: 0.197px;
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.qwu7q3ojv {
  stop-color: var(--svg-color--5d383b, #5D383B);
}

.r0p9vfbnw {
  stop-color: var(--svg-color--ca8b73, #CA8B73);
  stop-opacity: 0;
}

.r3t82tbzk {
  stop-color: var(--svg-color--d9aa94, #D9AA94);
  stop-opacity: 0;
}

.r7k3cqb2o {
  stop-color: var(--svg-color--5a4e68, #5A4E68);
}

.rcuz4uefu {
  stop-color: var(--svg-color--f5b7a7, #F5B7A7);
  stop-opacity: 0;
}

.rez4i8s2j {
  cx: 11.093px;
  cy: 10.66px;
  r: 1.669px;
}

.rhyy10bsj {
  stop-color: var(--svg-color--e4b09e, #E4B09E);
}

.rlmcgkbis {
  fill: var(--svg-color--1e1e1e, #1E1E1E);
  d: path("M19.56 7.94h-.002l-.002-.002l-.004-.004l-.012-.01a2 2 0 0 0-.155-.107c-.1-.062-.24-.14-.42-.21a2.83 2.83 0 0 0-1.492-.159a.534.534 0 1 0 .166 1.054c.398-.063.717.01.934.097a1.5 1.5 0 0 1 .308.165a.534.534 0 0 0 .679-.824");
}

.rlzetx3ey {
  stop-color: var(--svg-color--dc9c96, #DC9C96);
}

.rnoyg417s {
  d: path("m16.65 19.887l.136-.122a3.5 3.5 0 0 0 1.148-2.549v-1.964h-4.15l-.006 1.912c0 .052.004.147 0 .2c.045.916.46 1.784 1.144 2.401l.16.143l.666-1.01a.13.13 0 0 1 .221 0z");
}

.rp0wt3btz {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.228 9.23c.653 0 1.204.45 1.354 1.058a.274.274 0 0 1-.267.34h-2.23a.23.23 0 0 1-.228-.271a1.4 1.4 0 0 1 1.371-1.128");
}

.rpeopjbni {
  cx: 20.605px;
  cy: 10.66px;
  r: 0.995px;
}

.rvf3-0bfj {
  stop-color: var(--svg-color--dead9d, #DEAD9D);
  stop-opacity: 0;
}

.s0bgd4ckb {
  d: path("M23.286 25.33c0-.402.325-.733.727-.733h2.391a1.2 1.2 0 0 1 1.2 1.2v3.207a1 1 0 0 1-1 1h-2.591a.731.731 0 0 1-.32-1.39a.735.735 0 0 1 0-1.314a.735.735 0 0 1 0-1.314a.74.74 0 0 1-.407-.657");
}

.sbbw_6vcc {
  stop-color: var(--svg-color--ffdec4, #FFDEC4);
}

.sl5klgbuk {
  stop-color: var(--svg-color--4c1912, #4C1912);
}

.sshpf1iar {
  cx: 13.385px;
  cy: 9.882px;
  rx: 0.389px;
  ry: 0.197px;
}

.sxo3xwbvl {
  stop-color: var(--svg-color--3f3647, #3F3647);
}

.t5hfiulty {
  cx: 11.093px;
  cy: 10.66px;
  r: 0.995px;
}

.t98e19bfz {
  d: path("M14.47 10.288c0-.288-.235-.48-.298-.538l-.289.279l.178.36z");
}

.tbjczjb4u {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.448 9.23c-.653 0-1.205.45-1.355 1.058c-.045.174.09.34.268.34h2.23a.23.23 0 0 0 .227-.271a1.4 1.4 0 0 0-1.37-1.128");
}

.tcm21mbym {
  stop-color: var(--svg-color--3f2a51, #3F2A51);
  stop-opacity: 0;
}

.th7rrm5vu {
  d: path("M19.509 23.547h.692v6.326h-.692z");
}

.tj2vllbvr {
  stop-color: var(--svg-color--f3c6af, #F3C6AF);
}

.tqgh1edwg {
  stop-color: var(--svg-color--eaab97, #EAAB97);
}

.u2z7cu58j {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M23.806 28.605h1.797");
}

.u3uwpbbrc {
  stop-color: var(--svg-color--4f445b, #4F445B);
}

.u4r37-1cm {
  width: 2.773px;
  height: 1.082px;
  x: 23.941px;
  y: 20.988px;
  rx: 0.541px;
}

.ui2kgq2tt {
  stop-color: var(--svg-color--464344, #464344);
}

.uk24qccae {
  stop-color: var(--svg-color--463c39, #463C39);
  stop-opacity: 0;
}

.uupgmqj6k {
  stop-color: var(--svg-color--b88168, #B88168);
}

.uzac_3qef {
  stop-color: var(--svg-color--ffd1bb, #FFD1BB);
}

.v5rheyc4i {
  stop-color: var(--svg-color--ffd7bf, #FFD7BF);
}

.vhte_3bib {
  stop-color: var(--svg-color--523135, #523135);
}

.vpvekld5v {
  stop-color: var(--svg-color--3c393a, #3C393A);
  stop-opacity: 0;
}

.vx-77wbda {
  stop-color: var(--svg-color--ca8b73, #CA8B73);
}

.w-er2h93j {
  stop-color: var(--svg-color--59545e, #59545E);
  stop-opacity: 0;
}

.w950_6h3e {
  stop-color: var(--svg-color--4d4159, #4D4159);
}

.wachewblq {
  stop-color: var(--svg-color--ba7c6b, #BA7C6B);
}

.wblwu61sc {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M12.282 8.314c.327-.289 1.041-.593 1.927-.452");
}

.wdqn7tq-u {
  stop-color: var(--svg-color--d9aa94, #D9AA94);
}

.we3s8mb2t {
  cx: 20.605px;
  cy: 10.66px;
  r: 0.995px;
  fill: var(--svg-color--e4af9a, #E4AF9A);
}

.wi8di0b_n {
  stop-color: var(--svg-color--353435, #353435);
}

.wl-j51biu {
  stop-color: var(--svg-color--d9a4a4, #D9A4A4);
}

.wy9dudb8o {
  fill: var(--svg-color--000, #000);
  d: path("M17.51 10.393c0-.284.227-.51.511-.51a.51.51 0 0 1 .454.746h-.904a.46.46 0 0 1-.06-.236");
}

.wyn-zr57q {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M17.956 9.69c.063.085-.07.188-.22.301c-.152.113-.264.193-.328.108c-.063-.085.008-.246.159-.359c.15-.113.325-.135.389-.05");
}

.wyytu2b0o {
  stop-color: var(--svg-color--897576, #897576);
}

.x_kgjuy6x {
  d: path("M22.861 16.959h-.613a.505.505 0 0 0-.504.504v3.022c0 .271.222.503.504.503h.613a.505.505 0 0 0 .504-.503v-3.022a.51.51 0 0 0-.504-.504");
}

.x3w8iu_4c {
  cx: 20.605px;
  cy: 10.66px;
  r: 1.669px;
}

.x6mjr8bji {
  stop-color: var(--svg-color--ffd7c1, #FFD7C1);
  stop-opacity: 0;
}

.x8d9utbsu {
  stop-color: var(--svg-color--d5a58e, #D5A58E);
  stop-opacity: 0;
}

.xen1_3bnh {
  d: path("M13.654 9.501a.892.892 0 0 0-.86 1.127h1.724a1 1 0 0 0 .033-.235a.9.9 0 0 0-.897-.892");
}

.xgy7k56lm {
  d: path("M28.387 16.959h-.613a.505.505 0 0 0-.504.504v3.022c0 .271.222.503.504.503h.613a.505.505 0 0 0 .503-.503v-3.022a.51.51 0 0 0-.503-.504");
}

.xjh-ixbfp {
  stop-color: var(--svg-color--755144, #755144);
}

.y49ru_b1d {
  fill: var(--svg-color--1e1e1e, #1E1E1E);
  d: path("M12.067 7.94h.002l.001-.002l.005-.004l.012-.01a1.4 1.4 0 0 1 .155-.107c.1-.062.24-.14.42-.21a2.83 2.83 0 0 1 1.492-.159a.534.534 0 0 1-.166 1.054a1.77 1.77 0 0 0-.934.097a1.5 1.5 0 0 0-.308.165a.534.534 0 0 1-.679-.823");
}

.y78upfugg {
  stop-color: var(--svg-color--8a6a62, #8A6A62);
  stop-opacity: 0;
}

.yf9erdbmk {
  stop-color: var(--svg-color--4a4648, #4A4648);
  stop-opacity: 0;
}

.yslyejzkq {
  stop-color: var(--svg-color--8e6b62, #8E6B62);
}

.yyvs3obha {
  stop-color: var(--svg-color--e8ad97, #E8AD97);
  stop-opacity: 0;
}

.z3n_1mwef {
  stop-color: var(--svg-color--a58787, #A58787);
}

.z8y6fgvmn {
  stop-color: var(--svg-color--ffdabf, #FFDABF);
}

.z9s532b4z {
  fill: var(--svg-color--d89992, #D89992);
  d: path("m15.565 10.538l-.82 1.7c-.102.349.142.698.488.698h.737c.346 0 .59-.355.488-.699l-.498-1.7c-.107-.376-.283-.376-.395 0");
}

.zf2atv-8x {
  stop-color: var(--svg-color--dc9c96, #DC9C96);
  stop-opacity: 0;
}

.zx1idre_k {
  stop-color: var(--svg-color--353435, #353435);
  stop-opacity: 0;
}

.zx6sfmbib {
  stop-color: var(--svg-color--7a464a, #7A464A);
  stop-opacity: 0;
}

</style>
