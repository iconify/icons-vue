<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><circle fill="url(#iOokUYv)" class="r_bcr-ntk"/><circle fill="url(#ig6gRjd)" class="r_bcr-ntk"/><circle fill="url(#ifqCFkS)" class="iksuiqrgf"/><circle fill="url(#igczLIe)" transform="matrix(-1 0 0 1 21.326 16.165)" class="qnar36wle"/><circle fill="url(#iE9wJUA)" transform="matrix(-1 0 0 1 21.326 16.165)" class="qnar36wle"/><circle fill="url(#iiFjNse)" transform="matrix(-1 0 0 1 23.725 23.368)" class="n5l_opbqq"/><path fill="url(#i4UUWGe)" class="w8e9izb-y"/><path fill="url(#iFqMHgd)" class="w8e9izb-y"/><path fill="url(#iS6d3Rd)" class="w8e9izb-y"/><path fill="url(#i7GTaad)" class="rgs-6fbpw"/><path fill="url(#iU0xveW)" class="rgs-6fbpw"/><path class="lr6p412xr"/><path fill="url(#iJvbFZb)" class="gt-y46nru"/><path fill="url(#iMrfvye)" class="gt-y46nru"/><path fill="url(#ip742Bh)" class="gt-y46nru"/><path fill="url(#izyBClb)" class="gt-y46nru"/><path fill="url(#irX7roe)" class="gt-y46nru"/><path fill="url(#iB984Kc)" class="gt-y46nru"/><path class="dk0gm-byq"/><path fill="url(#i1Dor5L)" class="s6ufut5ul"/><path fill="url(#iv6Yn7W)" class="s6ufut5ul"/><path fill="url(#i4wIgAd)" class="s6ufut5ul"/><g filter="url(#iEojpxb)"><path fill="url(#i2qwzBe)" class="r_ngogb8h"/><path fill="url(#iI33mee)" class="r_ngogb8h"/><path fill="url(#i3pByEd)" class="r_ngogb8h"/></g><path class="wkmk90b2p"/><g filter="url(#i2aryab)"><path class="baaokjm-r"/></g><path fill="url(#i2rgnYb)" class="z0t4qbbcm"/><path fill="url(#ipY70oe)" class="xml1208at"/><g filter="url(#izSw54c)"><path fill="url(#iSHDu7c)" class="unful-65k"/><path fill="url(#i0HiF2m)" class="unful-65k"/></g><path fill="url(#ivVMlVc)" class="unful-65k"/><path fill="url(#iQaJ5Rb)" class="unful-65k"/><path fill="url(#iNo3oMd)" class="unful-65k"/><path fill="url(#iD3La9b)" class="unful-65k"/><path fill="url(#ih1jFge)" class="unful-65k"/><path fill="url(#iroNd6c)" class="unful-65k"/><path fill="url(#in8imge)" class="unful-65k"/><g filter="url(#iSKz9ve)"><path class="ro4fu5b8k"/></g><g filter="url(#i7QF0Ib)"><path class="scrsh_t7u"/><path fill="url(#iYRfEmg)" class="l3290_omc"/><path fill="url(#iofJLgc)" class="l3290_omc"/><path fill="url(#iNgGxhe)" class="l3290_omc"/><path fill="url(#i6ttvyd)" class="l3290_omc"/><path fill="url(#iKft6QM)" class="l3290_omc"/></g><g filter="url(#ib9ZMTr)"><path stroke="url(#iqdiwva)" class="n9_9y0bde"/></g><path fill="url(#is0UQrN)" class="hbwaqmrec"/><g filter="url(#ibx1bJc)"><path fill="url(#iBjWzne)" class="k8crpo2qf"/><path fill="url(#ipTcUsb)" class="k8crpo2qf"/><path fill="url(#iOKCx5x)" class="k8crpo2qf"/><path fill="url(#iZKxdsW)" class="k8crpo2qf"/><path fill="url(#iWFjLib)" class="k8crpo2qf"/></g><g filter="url(#inT74yb)"><path class="ba2anubkr"/></g><g filter="url(#irfjY6c)"><path class="yzv8aja2i"/></g><g filter="url(#idRQqUc)"><path class="p2sz_bbjj"/><path fill="url(#iO2xNnd)" class="weeq6_bsp"/><path fill="url(#iCViIhd)" class="weeq6_bsp"/></g><g filter="url(#iKlB5Db)"><path class="em8eybb3a"/><path fill="url(#is4K7Ed)" class="zab-z0bdv"/><path fill="url(#ilpDOWB)" class="zab-z0bdv"/></g><path class="f_o1x5bna"/><path fill="url(#i0r4fgb)" class="bn-zyfi_h"/><path class="q68kjqb7h"/><g filter="url(#iorlMTd)"><path class="nwldfrb3p"/><path fill="url(#iR0lLbq)" class="g5wyki2wj"/></g><g filter="url(#iDu5I0b)"><path fill="url(#ij00jXb)" class="r29v8vboh"/></g><path class="st6whsb7d"/><path fill="url(#i4hyl0d)" class="woq4pjb0f"/><path class="lcip4nb-l"/><g filter="url(#iV2vuBd)"><path fill="url(#imlYCrd)" class="z-90kcitb"/></g><g filter="url(#iIEXDOc)"><ellipse transform="rotate(-27.914 13.408 9.954)" class="dofztio7y"/><ellipse fill="url(#i0AAlkd)" transform="rotate(-27.914 13.408 9.954)" class="xycinvbud"/></g><path fill="url(#ilZoXmc)" class="lmxr-1n9l"/><path fill="url(#iqkoCfe)" class="lmxr-1n9l"/><path fill="url(#itqgqYC)" class="lmxr-1n9l"/><path fill="url(#iKjXKeb)" class="lmxr-1n9l"/><path fill="url(#iYOmmYd)" class="e9ay3vb3v"/><path fill="url(#i5WQazb)" class="e9ay3vb3v"/><g filter="url(#iDemddd)"><path fill="url(#iqQQmZd)" class="ipgpnwb8w"/></g><g filter="url(#i33dU4d)"><path fill="url(#iTFFXqW)" class="fh9srbb-t"/></g><g filter="url(#iYhq9od)"><path class="h4q3t1b3l"/></g><g filter="url(#iF0WP9D)"><path class="lczktvb4u"/></g><g filter="url(#iuH6F7d)"><path class="jxyxcprff"/></g><defs><radialGradient id="iOokUYv" cx="0" cy="0" r="1" gradientTransform="matrix(3.59375 -2.4375 2.72822 4.02238 6.877 17.33)" gradientUnits="userSpaceOnUse"><stop class="dgu6o60tg"/><stop offset="1" class="n_p-4bbbu"/></radialGradient><radialGradient id="ig6gRjd" cx="0" cy="0" r="1" gradientTransform="matrix(-.01562 -1.76562 2.48224 -.02197 8.596 17.83)" gradientUnits="userSpaceOnUse"><stop offset=".384" class="v6wds2dtn"/><stop offset="1" class="nz8ufunsm"/></radialGradient><radialGradient id="ifqCFkS" cx="0" cy="0" r="1" gradientTransform="matrix(-5.47138 9.4622 -7.02133 -4.05998 10.46 19.268)" gradientUnits="userSpaceOnUse"><stop class="qc0o5_36v"/><stop offset="1" class="snymmbrnj"/></radialGradient><radialGradient id="igczLIe" cx="0" cy="0" r="1" gradientTransform="rotate(44.444 -1.585 1.225)scale(4.68833)" gradientUnits="userSpaceOnUse"><stop class="qc07hnbjk"/><stop offset=".836" class="b_5radckw"/></radialGradient><radialGradient id="iE9wJUA" cx="0" cy="0" r="1" gradientTransform="matrix(-.03125 -1.59375 5.11385 -.10027 2.316 5.313)" gradientUnits="userSpaceOnUse"><stop offset=".201" class="vze8wny8i"/><stop offset="1" class="o4sg_vbnc"/></radialGradient><radialGradient id="iiFjNse" cx="0" cy="0" r="1" gradientTransform="matrix(4.95236 7.33803 -10.65664 7.19205 1.352 1.24)" gradientUnits="userSpaceOnUse"><stop offset=".192" class="r8td-ob5s"/><stop offset=".819" class="eegxz98yy"/></radialGradient><radialGradient id="i4UUWGe" cx="0" cy="0" r="1" gradientTransform="matrix(-1.35939 5.78125 -6.81223 -1.6018 23.096 22.58)" gradientUnits="userSpaceOnUse"><stop class="yf3t3eb5f"/><stop offset="1" class="a66gbwbzh"/></radialGradient><radialGradient id="i7GTaad" cx="0" cy="0" r="1" gradientTransform="matrix(6.87457 8.07189 -11.19707 9.5362 6.418 22.32)" gradientUnits="userSpaceOnUse"><stop class="pbkzvtx_w"/><stop offset="1" class="ykdcls_lk"/></radialGradient><radialGradient id="iJvbFZb" cx="0" cy="0" r="1" gradientTransform="matrix(-3.18749 3.03127 -6.31539 -6.64086 13.752 16.392)" gradientUnits="userSpaceOnUse"><stop offset=".208" class="k3qin7bzy"/><stop offset="1" class="x3axlob0n"/></radialGradient><radialGradient id="ip742Bh" cx="0" cy="0" r="1" gradientTransform="matrix(-4.82764 -11.66358 1.58185 -.65474 15.958 28.962)" gradientUnits="userSpaceOnUse"><stop class="z2ddyab4m"/><stop offset="1" class="cqgvl433q"/></radialGradient><radialGradient id="irX7roe" cx="0" cy="0" r="1" gradientTransform="matrix(-1.37282 -3.155 .92095 -.40073 16.346 27.58)" gradientUnits="userSpaceOnUse"><stop class="h3e5alaje"/><stop offset="1" class="u4bo2-o9a"/></radialGradient><radialGradient id="iB984Kc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.15863 -1.17796 1.62432 -1.59766 14.336 18.515)" gradientUnits="userSpaceOnUse"><stop offset=".328" class="gyulks50m"/><stop offset="1" class="atms-xm-n"/></radialGradient><radialGradient id="iv6Yn7W" cx="0" cy="0" r="1" gradientTransform="matrix(2.01563 -.67188 .83418 2.50254 17.502 18.33)" gradientUnits="userSpaceOnUse"><stop offset=".374" class="k-y64ibbx"/><stop offset="1" class="pjzr3aclu"/></radialGradient><radialGradient id="i4wIgAd" cx="0" cy="0" r="1" gradientTransform="rotate(110.875 2.49 18.294)scale(11.8396 2.00952)" gradientUnits="userSpaceOnUse"><stop class="bc2qs9bhj"/><stop offset="1" class="ktoycacxm"/></radialGradient><radialGradient id="iI33mee" cx="0" cy="0" r="1" gradientTransform="matrix(1.8125 1.75 -2.19025 2.26847 13.158 17.204)" gradientUnits="userSpaceOnUse"><stop offset=".275" class="zs_feibdl"/><stop offset="1" class="k6n7iqten"/></radialGradient><radialGradient id="i3pByEd" cx="0" cy="0" r="1" gradientTransform="matrix(0 3.01211 -.76307 0 16.64 16.221)" gradientUnits="userSpaceOnUse"><stop class="elw7f9boo"/><stop offset="1" class="x3v8yobev"/></radialGradient><radialGradient id="i2rgnYb" cx="0" cy="0" r="1" gradientTransform="matrix(.75578 2.03842 -2.42149 .8978 20.682 11.926)" gradientUnits="userSpaceOnUse"><stop offset=".215" class="cbylncbjf"/><stop offset="1" class="hj2nkngkt"/></radialGradient><radialGradient id="ipY70oe" cx="0" cy="0" r="1" gradientTransform="matrix(1.49027 .46837 -1.44496 4.59758 9.771 12.42)" gradientUnits="userSpaceOnUse"><stop class="i4otoyosx"/><stop offset=".746" class="zqff1532o"/></radialGradient><radialGradient id="iSHDu7c" cx="0" cy="0" r="1" gradientTransform="matrix(-5.27675 0 0 -9.33451 18.718 10.976)" gradientUnits="userSpaceOnUse"><stop class="e4t6-lb6y"/><stop offset="1" class="hhi9hubjb"/><stop offset="1" class="hhi9hubjb"/></radialGradient><radialGradient id="i0HiF2m" cx="0" cy="0" r="1" gradientTransform="matrix(-1.75946 2.90992 -2.40237 -1.45258 18.334 5.95)" gradientUnits="userSpaceOnUse"><stop offset=".078" class="fajfg00jo"/><stop offset="1" class="wpa_x2uhd"/></radialGradient><radialGradient id="iQaJ5Rb" cx="0" cy="0" r="1" gradientTransform="matrix(0 9.44336 -10.2809 0 15.932 8)" gradientUnits="userSpaceOnUse"><stop offset=".727" class="x18hoo9hy"/><stop offset=".977" class="nkh3ifbwu"/></radialGradient><radialGradient id="iNo3oMd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.15909 1.43437 0 18.354 9.65)" gradientUnits="userSpaceOnUse"><stop offset=".325" class="o847wybrn"/><stop offset="1" class="z-0dlhbai"/></radialGradient><radialGradient id="iD3La9b" cx="0" cy="0" r="1" gradientTransform="matrix(.00397 -1.10451 1.20197 .00432 13.563 9.697)" gradientUnits="userSpaceOnUse"><stop offset=".378" class="pxeuj6buu"/><stop offset="1" class="lg98p_5je"/></radialGradient><radialGradient id="ih1jFge" cx="0" cy="0" r="1" gradientTransform="matrix(-8.57544 .54132 -1.38281 -21.906 19.35 11.973)" gradientUnits="userSpaceOnUse"><stop offset=".836" class="sim-rnb6d"/><stop offset="1" class="vx5g9qbgu"/></radialGradient><radialGradient id="iroNd6c" cx="0" cy="0" r="1" gradientTransform="matrix(3.41746 -2.94374 .86953 1.00946 9.03 8.217)" gradientUnits="userSpaceOnUse"><stop offset=".539" class="sf65_-b_u"/><stop offset="1" class="n9ebefe8q"/></radialGradient><radialGradient id="in8imge" cx="0" cy="0" r="1" gradientTransform="matrix(-.23685 2.5208 -1.00767 -.09468 21.48 8.031)" gradientUnits="userSpaceOnUse"><stop offset=".245" class="p54kb3bjj"/><stop offset="1" class="rm9y2hb6m"/></radialGradient><radialGradient id="iofJLgc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .24639 -.77436 0 16.355 12.349)" gradientUnits="userSpaceOnUse"><stop class="eqmylox_y"/><stop offset="1" class="sicchzd0u"/></radialGradient><radialGradient id="i6ttvyd" cx="0" cy="0" r="1" gradientTransform="rotate(155.369 6.95 7.685)scale(1.68906 2.71445)" gradientUnits="userSpaceOnUse"><stop offset=".714" class="cjboikbop"/><stop offset="1" class="l6ffphqdg"/></radialGradient><radialGradient id="is0UQrN" cx="0" cy="0" r="1" gradientTransform="rotate(-26.18 39.16 -25.775)scale(2.45416 9.8737)" gradientUnits="userSpaceOnUse"><stop offset=".562" class="etju2kb3q"/><stop offset="1" class="iazz9lb4s"/></radialGradient><radialGradient id="ipTcUsb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -3.53407 8.93726 0 10.606 8.056)" gradientUnits="userSpaceOnUse"><stop offset=".536" class="ibt06e6rm"/><stop offset="1" class="k45xjwbmq"/></radialGradient><radialGradient id="iOKCx5x" cx="0" cy="0" r="1" gradientTransform="matrix(.1151 -2.53604 4.49336 .20395 20.79 9.379)" gradientUnits="userSpaceOnUse"><stop class="c98z413ze"/><stop offset="1" class="ovvtmacpn"/></radialGradient><radialGradient id="iZKxdsW" cx="0" cy="0" r="1" gradientTransform="matrix(-2.38089 -1.56592 1.14946 -1.7477 20.03 3.044)" gradientUnits="userSpaceOnUse"><stop class="jx9hffbwe"/><stop offset="1" class="mzj8iibqz"/></radialGradient><radialGradient id="iWFjLib" cx="0" cy="0" r="1" gradientTransform="matrix(.67796 1.20943 -2.80046 1.56984 14.97 1.437)" gradientUnits="userSpaceOnUse"><stop offset=".287" class="e8ajgab-k"/><stop offset="1" class="gxf7b0v7y"/></radialGradient><radialGradient id="iO2xNnd" cx="0" cy="0" r="1" gradientTransform="matrix(-2.22171 0 0 -.82456 16.14 3.717)" gradientUnits="userSpaceOnUse"><stop class="axstwemrb"/><stop offset="1" class="ez41_pbnb"/></radialGradient><radialGradient id="iCViIhd" cx="0" cy="0" r="1" gradientTransform="rotate(-57.724 12.183 -5.59)scale(6.08299 6.73932)" gradientUnits="userSpaceOnUse"><stop offset=".093" class="hnw0p1utu"/><stop offset=".311" class="dwl_ftd7p"/><stop offset="1" class="fch_lgr5q"/></radialGradient><radialGradient id="is4K7Ed" cx="0" cy="0" r="1" gradientTransform="matrix(2.70378 -2.57604 4.71606 4.94993 18.542 7.567)" gradientUnits="userSpaceOnUse"><stop offset=".857" class="stq0hsb2e"/><stop offset="1" class="i6xvtdb8e"/></radialGradient><radialGradient id="ilpDOWB" cx="0" cy="0" r="1" gradientTransform="matrix(3.2786 .38323 -.16045 1.37268 17.65 6.077)" gradientUnits="userSpaceOnUse"><stop class="unyhdjbdq"/><stop offset="1" class="w0a4mmrgb"/></radialGradient><radialGradient id="i0r4fgb" cx="0" cy="0" r="1" gradientTransform="matrix(0 .8189 -1.30256 0 18.087 10.05)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="bbyb_mbsk"/></radialGradient><radialGradient id="iR0lLbq" cx="0" cy="0" r="1" gradientTransform="matrix(-.23409 -.30165 .4153 -.32228 17.856 10.136)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="i4hyl0d" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81895 -1.30263 0 13.682 10.05)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="bbyb_mbsk"/></radialGradient><radialGradient id="i0AAlkd" cx="0" cy="0" r="1" gradientTransform="rotate(-90.897 11.753 -1.456)scale(.49877 .59953)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iqkoCfe" cx="0" cy="0" r="1" gradientTransform="rotate(74.348 3.636 18.579)scale(2.35146 2.24347)" gradientUnits="userSpaceOnUse"><stop offset=".856" class="xron-kbnx"/><stop offset="1" class="bzyp_ibbo"/></radialGradient><radialGradient id="itqgqYC" cx="0" cy="0" r="1" gradientTransform="matrix(.79515 -1.09121 .91466 .6665 20.909 10.615)" gradientUnits="userSpaceOnUse"><stop offset=".664" class="w_o-5kbak"/><stop offset="1" class="mb4bnzbbk"/></radialGradient><radialGradient id="iKjXKeb" cx="0" cy="0" r="1" gradientTransform="matrix(.5925 -1.56492 2.09095 .79165 21.024 10.788)" gradientUnits="userSpaceOnUse"><stop offset=".803" class="sxoyafbbn"/><stop offset="1" class="tri7bg95c"/></radialGradient><radialGradient id="i5WQazb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.67376 0 0 -1.869 10.923 10.712)" gradientUnits="userSpaceOnUse"><stop offset=".778" class="srn41o2oz"/><stop offset="1" class="dfc36bbxx"/></radialGradient><radialGradient id="iqQQmZd" cx="0" cy="0" r="1" gradientTransform="rotate(170.26 5.006 5.823)scale(.93858 .96234)" gradientUnits="userSpaceOnUse"><stop class="m_eaw6bxg"/><stop offset="1" class="nk_trfbso"/></radialGradient><filter id="iEojpxb" width="6.879" height="10.938" x="12.32" y="16.517" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.364706 0 0 0 0 0.160784 0 0 0 0 0.113725 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_782"/></filter><filter id="i2aryab" width="3.076" height="1.977" x="15.252" y="17.275" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_782" stdDeviation=".3"/></filter><filter id="izSw54c" width="11.316" height="12.657" x="10.774" y="4.747" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1"/><feGaussianBlur stdDeviation=".7"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.494118 0 0 0 0 0.352941 0 0 0 0 0.32549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_782"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".2"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.396078 0 0 0 0 0.215686 0 0 0 0 0.215686 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_782" result="effect2_innerShadow_4002_782"/></filter><filter id="iSKz9ve" width="3.763" height="4.927" x="13.859" y="9.144" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_782" stdDeviation=".5"/></filter><filter id="i7QF0Ib" width="2.295" height="3.327" x="14.737" y="9.746" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_782" stdDeviation=".1"/></filter><filter id="ib9ZMTr" width="3.749" height="1.583" x="14.01" y="13.3" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_782" stdDeviation=".05"/></filter><filter id="ibx1bJc" width="12.993" height="8.43" x="9.388" y="1.546" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.137255 0 0 0 0 0.0901961 0 0 0 0 0.145098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_782"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0784314 0 0 0 0 0.0352941 0 0 0 0 0.0470588 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_782" result="effect2_innerShadow_4002_782"/></filter><filter id="inT74yb" width="2.36" height="1.2" x="17.488" y="7.259" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.172549 0 0 0 0 0.0862745 0 0 0 0 0.156863 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_782"/></filter><filter id="irfjY6c" width="2.36" height="1.185" x="12.183" y="7.274" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.172549 0 0 0 0 0.0862745 0 0 0 0 0.156863 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_782"/></filter><filter id="idRQqUc" width="6.641" height="6.043" x="9.749" y="2.642" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy=".1"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.286275 0 0 0 0 0.243137 0 0 0 0 0.227451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_782"/><feGaussianBlur result="effect2_foregroundBlur_4002_782" stdDeviation=".125"/></filter><filter id="iKlB5Db" width="6.376" height="5.763" x="15.724" y="3.092" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_782" stdDeviation=".125"/></filter><filter id="iorlMTd" width=".792" height=".701" x="17.347" y="9.608" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_782" stdDeviation=".05"/></filter><filter id="iDu5I0b" width=".896" height=".918" x="18.195" y="9.685" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_782" stdDeviation=".1"/></filter><filter id="iV2vuBd" width=".992" height="1.046" x="13.711" y="9.621" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_782" stdDeviation=".1"/></filter><filter id="iIEXDOc" width=".92" height=".709" x="12.948" y="9.6" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_782" stdDeviation=".05"/></filter><filter id="iDemddd" width="1.337" height="2.397" x="9.749" y="9.516" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_782" stdDeviation=".125"/></filter><filter id="i33dU4d" width="1.955" height="2.921" x="20.373" y="9.247" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_782" stdDeviation=".25"/></filter><filter id="iYhq9od" width="2.421" height="1.164" x="12.105" y="7.351" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_782" stdDeviation=".125"/></filter><filter id="iF0WP9D" width="2.421" height="1.164" x="17.433" y="7.305" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_782" stdDeviation=".125"/></filter><filter id="iuH6F7d" width="5.301" height="3.02" x="16.779" y="3.536" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_782" stdDeviation=".375"/></filter><linearGradient id="iFqMHgd" x1="24.158" x2="24.189" y1="30.329" y2="26.673" gradientUnits="userSpaceOnUse"><stop offset=".078" class="npfrbd3jd"/><stop offset="1" class="w_5-rbc1a"/></linearGradient><linearGradient id="iS6d3Rd" x1="18.12" x2="19.472" y1="27.765" y2="28.151" gradientUnits="userSpaceOnUse"><stop class="p5jt_ib0l"/><stop offset="1" class="hw19_ybat"/></linearGradient><linearGradient id="iU0xveW" x1="13.658" x2="12.158" y1="28.736" y2="29.267" gradientUnits="userSpaceOnUse"><stop class="h65uoi6pi"/><stop offset="1" class="g04ogacjt"/></linearGradient><linearGradient id="iMrfvye" x1="12.315" x2="13.69" y1="27.392" y2="26.829" gradientUnits="userSpaceOnUse"><stop offset=".223" class="d05zivoho"/><stop offset="1" class="ue2ywxbfs"/></linearGradient><linearGradient id="izyBClb" x1="15.627" x2="14.221" y1="30.173" y2="29.486" gradientUnits="userSpaceOnUse"><stop offset=".208" class="cu8bl7b6w"/><stop offset="1" class="bkwavzmor"/></linearGradient><linearGradient id="i1Dor5L" x1="16.002" x2="18.033" y1="24.829" y2="25.736" gradientUnits="userSpaceOnUse"><stop class="ego3-fbwo"/><stop offset="1" class="up5p4s41k"/></linearGradient><linearGradient id="i2qwzBe" x1="16.367" x2="16.367" y1="25.145" y2="15.619" gradientUnits="userSpaceOnUse"><stop class="f7ghh-b7f"/><stop offset="1" class="nlaan9bmq"/></linearGradient><linearGradient id="ivVMlVc" x1="21.09" x2="18.537" y1="12.677" y2="12.677" gradientUnits="userSpaceOnUse"><stop class="agilw2byy"/><stop offset="1" class="h3kh2yb2k"/></linearGradient><linearGradient id="iYRfEmg" x1="16.73" x2="15.884" y1="11.657" y2="11.692" gradientUnits="userSpaceOnUse"><stop offset=".36" class="eqmylox_y"/><stop offset="1" class="sicchzd0u"/></linearGradient><linearGradient id="iNgGxhe" x1="15.884" x2="15.884" y1="12.807" y2="12.337" gradientUnits="userSpaceOnUse"><stop class="qsncw6btn"/><stop offset="1" class="v7xhdx32s"/></linearGradient><linearGradient id="iKft6QM" x1="15.884" x2="15.884" y1="10.076" y2="10.628" gradientUnits="userSpaceOnUse"><stop class="fok393bvn"/><stop offset="1" class="y4umwkb_f"/></linearGradient><linearGradient id="iqdiwva" x1="14.671" x2="14.993" y1="14.392" y2="13.55" gradientUnits="userSpaceOnUse"><stop class="t_m5csgaz"/><stop offset="1" class="ln8xouyxx"/></linearGradient><linearGradient id="iBjWzne" x1="22.8" x2="11.079" y1="5.26" y2="5.26" gradientUnits="userSpaceOnUse"><stop class="s5pji6bqr"/><stop offset="1" class="c7qpv738k"/></linearGradient><linearGradient id="ij00jXb" x1="18.872" x2="18.555" y1="10.105" y2="10.3" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="imlYCrd" x1="14.433" x2="14.116" y1="10.105" y2="10.3" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="ilZoXmc" x1="22.381" x2="21.163" y1="10.133" y2="12.329" gradientUnits="userSpaceOnUse"><stop class="pkjt6qfem"/><stop offset="1" class="qw3t0fbxr"/></linearGradient><linearGradient id="iYOmmYd" x1="9.98" x2="11.452" y1="10.843" y2="10.714" gradientUnits="userSpaceOnUse"><stop class="lsjj5yb-k"/><stop offset="1" class="ac3zxpbrp"/></linearGradient><linearGradient id="iTFFXqW" x1="21.351" x2="21.351" y1="9.747" y2="11.668" gradientUnits="userSpaceOnUse"><stop class="x9ttejxmc"/><stop offset="1" class="nal-rljch"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:person-in-steamy-room-medium-dark" /></template>
<style>
.a66gbwbzh {
  stop-color: var(--svg-color--f65c3e, #F65C3E);
}

.ac3zxpbrp {
  stop-color: var(--svg-color--623549, #623549);
}

.agilw2byy {
  stop-color: var(--svg-color--936b5d, #936B5D);
}

.atms-xm-n {
  stop-color: var(--svg-color--9e2625, #9E2625);
  stop-opacity: 0;
}

.axstwemrb {
  stop-color: var(--svg-color--423c3f, #423C3F);
}

.b_5radckw {
  stop-color: var(--svg-color--f2e8f1, #F2E8F1);
}

.ba2anubkr {
  fill: var(--svg-color--2e201f, #2E201F);
  d: path("M19.652 7.968a1.9 1.9 0 0 0-.694-.415c-.307-.097-.692-.123-1.224-.058a.28.28 0 0 0 .068.556c.486-.06.783-.028.988.036c.2.063.335.165.494.303a.28.28 0 1 0 .368-.422");
}

.baaokjm-r {
  stroke: var(--svg-color--907066, #907066);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-6px, 0.6px);
  d: path("M16.152 18.338c.19.027.71.032 1.275-.163");
}

.bbyb_mbsk {
  stop-color: var(--svg-color--664842, #664842);
}

.bc2qs9bhj {
  stop-color: var(--svg-color--ff7347, #FF7347);
}

.bkwavzmor {
  stop-color: var(--svg-color--dd5022, #DD5022);
  stop-opacity: 0;
}

.bn-zyfi_h {
  d: path("M18.089 9.57a.9.9 0 0 1 .868 1.138h-1.74a.904.904 0 0 1 .872-1.138");
}

.bzyp_ibbo {
  stop-color: var(--svg-color--71404f, #71404F);
}

.c7qpv738k {
  stop-color: var(--svg-color--362c2e, #362C2E);
}

.c98z413ze {
  stop-color: var(--svg-color--4f4d4d, #4F4D4D);
}

.cbylncbjf {
  stop-color: var(--svg-color--332f31, #332F31);
}

.cjboikbop {
  stop-color: var(--svg-color--744a4a, #744A4A);
  stop-opacity: 0;
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cqgvl433q {
  stop-color: var(--svg-color--f47246, #F47246);
  stop-opacity: 0;
}

.cu8bl7b6w {
  stop-color: var(--svg-color--dd5022, #DD5022);
}

.d05zivoho {
  stop-color: var(--svg-color--e45c36, #E45C36);
}

.dfc36bbxx {
  stop-color: var(--svg-color--836158, #836158);
}

.dgu6o60tg {
  stop-color: var(--svg-color--e1dae6, #E1DAE6);
}

.dk0gm-byq {
  fill: var(--svg-color--ec551b, #EC551B);
  d: path("M21.82 17.353c-.641-1.313-1.82-1.75-2.594-1.75h-2.61v2.875h2.47c.168.303.002.85-.102 1.086l-3.939 10.39h3.176c1.068-2.583 2.995-7.817 3.383-8.742c.42-1.004.81-2.476.216-3.86");
}

.dofztio7y {
  cx: 13.408px;
  cy: 9.954px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.393px;
  ry: 0.199px;
}

.dwl_ftd7p {
  stop-color: var(--svg-color--1c0c20, #1C0C20);
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.e4t6-lb6y {
  stop-color: var(--svg-color--9a6e61, #9A6E61);
}

.e8ajgab-k {
  stop-color: var(--svg-color--392f31, #392F31);
}

.e9ay3vb3v {
  d: path("M10.793 9.095a1.64 1.64 0 0 0-1.405 1.613c0 .867.68 1.575 1.535 1.621a79 79 0 0 1-.13-3.234");
}

.eegxz98yy {
  stop-color: var(--svg-color--dac9f0, #DAC9F0);
}

.ego3-fbwo {
  stop-color: var(--svg-color--ce3b1b, #CE3B1B);
}

.elw7f9boo {
  stop-color: var(--svg-color--7d5855, #7D5855);
}

.em8eybb3a {
  fill: var(--svg-color--2d171f, #2D171F);
  d: path("m21.146 8.605l-.03-.637c-.01-.771-.647-1.407-1.418-1.44h-1.413c-.898 0-1.716-.49-2.144-1.27c0 0-.062-.144-.125-.388c-.253-.97.674-1.707 1.654-1.49c.952.21 2.034.564 2.857 1.101c1.76 1.149 1.546 3.149.619 4.124");
}

.eqmylox_y {
  stop-color: var(--svg-color--a17c72, #A17C72);
}

.etju2kb3q {
  stop-color: var(--svg-color--87004e, #87004E);
}

.ez41_pbnb {
  stop-color: var(--svg-color--423c3f, #423C3F);
  stop-opacity: 0;
}

.f_o1x5bna {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.298 9.295c.659 0 1.216.454 1.367 1.069a.277.277 0 0 1-.27.343h-2.252a.232.232 0 0 1-.23-.274a1.41 1.41 0 0 1 1.385-1.138");
}

.f7ghh-b7f {
  stop-color: var(--svg-color--835953, #835953);
}

.fajfg00jo {
  stop-color: var(--svg-color--855e5a, #855E5A);
}

.fch_lgr5q {
  stop-color: var(--svg-color--1c0c20, #1C0C20);
  stop-opacity: 0;
}

.fh9srbb-t {
  d: path("M20.874 11.668q.058-.96.111-1.92a.965.965 0 0 1-.111 1.92");
}

.fok393bvn {
  stop-color: var(--svg-color--865c56, #865C56);
}

.ft5dv1b6b {
  fill: none;
}

.g04ogacjt {
  stop-color: var(--svg-color--d63c26, #D63C26);
  stop-opacity: 0;
}

.g5wyki2wj {
  d: path("M18.023 9.76c.064.086-.07.19-.223.304c-.152.114-.266.195-.33.109s.008-.248.16-.362c.153-.114.328-.137.393-.051");
}

.gt-y46nru {
  d: path("M9.9 17.353c.641-1.313 1.82-1.75 2.594-1.75h2.61v2.875h-2.47c-.168.303-.002.85.102 1.086l4.317 10.39h-3.176c-1.068-2.583-3.292-7.817-3.68-8.742c-.42-1.004-.89-2.476-.297-3.86");
}

.gxf7b0v7y {
  stop-color: var(--svg-color--392f31, #392F31);
  stop-opacity: 0;
}

.gyulks50m {
  stop-color: var(--svg-color--9e2625, #9E2625);
}

.h3e5alaje {
  stop-color: var(--svg-color--c03005, #C03005);
}

.h3kh2yb2k {
  stop-color: var(--svg-color--936b5d, #936B5D);
  stop-opacity: 0;
}

.h4q3t1b3l {
  stroke: var(--svg-color--433739, #433739);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M12.48 8.14c.26-.186.906-.513 1.67-.385");
}

.h65uoi6pi {
  stop-color: var(--svg-color--d63c26, #D63C26);
}

.hbwaqmrec {
  d: path("M15.884 13.9c-.512 0-.993-.121-1.398-.332c-.138-.07-.287.085-.2.21c.338.513.927.855 1.598.855s1.26-.342 1.599-.854c.087-.13-.062-.282-.2-.211a3 3 0 0 1-1.399.331");
}

.hhi9hubjb {
  stop-color: var(--svg-color--754c4c, #754C4C);
}

.hj2nkngkt {
  stop-color: var(--svg-color--221925, #221925);
}

.hnw0p1utu {
  stop-color: var(--svg-color--0b0306, #0B0306);
}

.hw19_ybat {
  stop-color: var(--svg-color--e04438, #E04438);
  stop-opacity: 0;
}

.i4otoyosx {
  stop-color: var(--svg-color--3e3330, #3E3330);
}

.i6xvtdb8e {
  stop-color: var(--svg-color--545051, #545051);
}

.iazz9lb4s {
  stop-color: var(--svg-color--87004d, #87004D);
}

.ibt06e6rm {
  stop-color: var(--svg-color--3e3433, #3E3433);
}

.iksuiqrgf {
  cx: 8.275px;
  cy: 23.368px;
  r: 6.305px;
}

.ipgpnwb8w {
  d: path("M10.752 9.766a.965.965 0 0 0 .084 1.897a79 79 0 0 1-.085-1.897");
}

.jx9hffbwe {
  stop-color: var(--svg-color--402c32, #402C32);
}

.jxyxcprff {
  fill: var(--svg-color--49373d, #49373D);
  d: path("M20.116 5.263h-2.1a.487.487 0 1 1 .078-.97c.545.086 1.268.207 1.753.328c1.096.271 1.398.805 1.483 1.185a1.53 1.53 0 0 0-1.214-.543");
}

.k-y64ibbx {
  stop-color: var(--svg-color--99201f, #99201F);
}

.k3qin7bzy {
  stop-color: var(--svg-color--b22307, #B22307);
}

.k45xjwbmq {
  stop-color: var(--svg-color--3e3433, #3E3433);
  stop-opacity: 0;
}

.k6n7iqten {
  stop-color: var(--svg-color--714a3d, #714A3D);
  stop-opacity: 0;
}

.k8crpo2qf {
  d: path("M20.785 4.27c.519.18.985.542 1.279 1.062a2.39 2.39 0 0 1-.107 2.55a1.57 1.57 0 0 0-.273.882v1.2a1.8 1.8 0 0 0-.674-.271l.08-1.622a1.463 1.463 0 0 0-1.392-1.445h-1.413a2.44 2.44 0 0 1-2.233-1.457a.67.67 0 0 0-.62-.422h-1.286c-1.863 0-3.372 1.527-3.372 3.41l.03 1.553a1.7 1.7 0 0 0-.726.266V8.764c0-.314-.097-.622-.273-.882a2.41 2.41 0 0 1-.145-2.469a2.37 2.37 0 0 1 1.312-1.137a2.7 2.7 0 0 0 1.397-1.12a2.35 2.35 0 0 1 2.918-.92a1.5 1.5 0 0 0 1.204 0c.284-.12.594-.19.92-.19c.852 0 1.596.46 2.008 1.142c.31.514.798.888 1.366 1.083");
}

.ktoycacxm {
  stop-color: var(--svg-color--f6682e, #F6682E);
  stop-opacity: 0;
}

.l3290_omc {
  d: path("m15.499 10.254l-.537 1.856c-.11.382.153.763.526.763h.793c.373 0 .635-.387.526-.763l-.537-1.856c-.115-.41-.651-.41-.771 0");
}

.l6ffphqdg {
  stop-color: var(--svg-color--744a4a, #744A4A);
}

.lcip4nb-l {
  fill: var(--svg-color--000, #000);
  d: path("M14.196 10.47a.514.514 0 0 0-.516-.516a.514.514 0 0 0-.459.753h.913a.5.5 0 0 0 .062-.237");
}

.lczktvb4u {
  stroke: var(--svg-color--433739, #433739);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M19.479 8.094c-.26-.186-.906-.514-1.671-.385");
}

.lg98p_5je {
  stop-color: var(--svg-color--70424e, #70424E);
  stop-opacity: 0;
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lmxr-1n9l {
  d: path("M20.852 12.329q.101-1.61.187-3.221a1.625 1.625 0 0 1-.187 3.221");
}

.ln8xouyxx {
  stop-color: var(--svg-color--866163, #866163);
  stop-opacity: 0;
}

.lr6p412xr {
  fill: var(--svg-color--ed561d, #ED561D);
  d: path("M9.9 17.353c.641-1.313 1.82-1.75 2.594-1.75h2.61v2.875h-2.47c-.168.303-.002.85.102 1.086l4.317 10.39h-3.176c-1.068-2.583-3.292-7.817-3.68-8.742c-.42-1.004-.89-2.476-.297-3.86");
}

.lsjj5yb-k {
  stop-color: var(--svg-color--6a4544, #6A4544);
}

.m_eaw6bxg {
  stop-color: var(--svg-color--57353c, #57353C);
}

.mb4bnzbbk {
  stop-color: var(--svg-color--7c4c46, #7C4C46);
  stop-opacity: 0;
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mzj8iibqz {
  stop-color: var(--svg-color--402c32, #402C32);
  stop-opacity: 0;
}

.n_p-4bbbu {
  stop-color: var(--svg-color--e6dee6, #E6DEE6);
}

.n5l_opbqq {
  r: 6.305px;
}

.n9_9y0bde {
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M14.52 13.501c.394.205.864.323 1.364.323c.506 0 .97-.118 1.364-.323a.23.23 0 0 1 .273.045c.065.067.09.176.024.274m-3.024-.319l2.962.278M14.52 13.5h-.001a.23.23 0 0 0-.273.047a.21.21 0 0 0-.023.273m.297-.32l-.235.278m3.26.041h-.001l-.062-.041m.062.041l-.062-.041m.062.041a1.99 1.99 0 0 1-1.66.888a1.99 1.99 0 0 1-1.66-.887m3.258-.042a1.91 1.91 0 0 1-1.599.854c-.67 0-1.26-.342-1.598-.854m-.062.042l.062-.042m-.062.042v-.001l.062-.041");
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

.nkh3ifbwu {
  stop-color: var(--svg-color--663236, #663236);
}

.nlaan9bmq {
  stop-color: var(--svg-color--855c4e, #855C4E);
}

.npfrbd3jd {
  stop-color: var(--svg-color--dd3537, #DD3537);
}

.nwldfrb3p {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M18.023 9.76c.064.086-.07.19-.223.304c-.152.114-.266.195-.33.109s.008-.248.16-.362c.153-.114.328-.137.393-.051");
}

.nz8ufunsm {
  stop-color: var(--svg-color--dad4de, #DAD4DE);
  stop-opacity: 0;
}

.o4sg_vbnc {
  stop-color: var(--svg-color--e8dee9, #E8DEE9);
  stop-opacity: 0;
}

.o847wybrn {
  stop-color: var(--svg-color--875455, #875455);
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.ovvtmacpn {
  stop-color: var(--svg-color--4f4d4d, #4F4D4D);
  stop-opacity: 0;
}

.p2sz_bbjj {
  fill: var(--svg-color--2d171f, #2D171F);
  d: path("m16.119 5.307l-.067-.138a.67.67 0 0 0-.62-.422h-1.286c-1.863 0-3.372 1.527-3.372 3.41v.279c-.343-.262-.775-.813-.775-1.704c0-1.082.79-1.629 1.292-1.978a2.5 2.5 0 0 0 .334-.255l.1-.106c.354-.374.982-1.04 2.08-1.332a5.5 5.5 0 0 1 1.53-.167c.472.012.805.42.805.893v1.507z");
}

.p54kb3bjj {
  stop-color: var(--svg-color--98786d, #98786D);
}

.p5jt_ib0l {
  stop-color: var(--svg-color--e04438, #E04438);
}

.pbkzvtx_w {
  stop-color: var(--svg-color--e06d3d, #E06D3D);
}

.pjzr3aclu {
  stop-color: var(--svg-color--d03d1c, #D03D1C);
  stop-opacity: 0;
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pkjt6qfem {
  stop-color: var(--svg-color--9c7b71, #9C7B71);
}

.pxeuj6buu {
  stop-color: var(--svg-color--70424e, #70424E);
}

.q68kjqb7h {
  fill: var(--svg-color--000, #000);
  d: path("M17.573 10.47c0-.286.23-.516.516-.516a.514.514 0 0 1 .459.754h-.914a.47.47 0 0 1-.061-.238");
}

.qc07hnbjk {
  stop-color: var(--svg-color--fbf7ff, #FBF7FF);
}

.qc0o5_36v {
  stop-color: var(--svg-color--e0d6e3, #E0D6E3);
}

.qnar36wle {
  r: 4.086px;
}

.qsncw6btn {
  stop-color: var(--svg-color--7d465b, #7D465B);
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.qw3t0fbxr {
  stop-color: var(--svg-color--815758, #815758);
}

.r_bcr-ntk {
  cx: 10.674px;
  cy: 16.165px;
  r: 4.086px;
}

.r_ngogb8h {
  d: path("M14.01 16.517h4v.887c.01.175.045.374.152.53a.8.8 0 0 0 .446.333l.464.164c.076.068.22.478.04.984c-.181.505-2.043 5.51-3.094 8.02v.02l-.004-.01l-.005.01v-.02c-1.052-2.51-3.139-7.515-3.32-8.02c-.18-.506-.122-.87-.046-.937l.68-.192c.218-.062.373-.14.515-.347c.113-.166.158-.39.172-.572z");
}

.r29v8vboh {
  d: path("M18.891 10.352a.85.85 0 0 0-.233-.467l-.263.287l.119.23z");
}

.r8td-ob5s {
  stop-color: var(--svg-color--f3ebfe, #F3EBFE);
}

.rgs-6fbpw {
  d: path("M5.096 29.939c0-7.961 4.617-9.875 5.375-10.383l5.047 10.383z");
}

.rm9y2hb6m {
  stop-color: var(--svg-color--98786d, #98786D);
  stop-opacity: 0;
}

.ro4fu5b8k {
  fill: var(--svg-color--6f3f46, #6F3F46);
  d: path("m15.479 10.452l-.596 1.855c-.102.382.142.764.489.764h.738c.346 0 .591-.388.49-.764l-.5-1.855c-.107-.411-.509-.411-.621 0");
}

.s5pji6bqr {
  stop-color: var(--svg-color--443237, #443237);
}

.s6ufut5ul {
  d: path("M21.82 17.353c-.641-1.313-1.82-1.75-2.594-1.75h-2.61v2.875h2.47c.168.303.002.85-.102 1.086l-3.939 10.39h3.176c1.068-2.583 2.995-7.817 3.383-8.742c.42-1.004.81-2.476.216-3.86");
}

.scrsh_t7u {
  fill: var(--svg-color--845b55, #845B55);
  d: path("m15.499 10.254l-.537 1.856c-.11.382.153.763.526.763h.793c.373 0 .635-.387.526-.763l-.537-1.856c-.115-.41-.651-.41-.771 0");
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

.snymmbrnj {
  stop-color: var(--svg-color--d5c4df, #D5C4DF);
}

.srn41o2oz {
  stop-color: var(--svg-color--836158, #836158);
  stop-opacity: 0;
}

.st6whsb7d {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.471 9.295a1.41 1.41 0 0 0-1.367 1.069a.277.277 0 0 0 .27.344h2.252a.232.232 0 0 0 .23-.275a1.414 1.414 0 0 0-1.385-1.138");
}

.stq0hsb2e {
  stop-color: var(--svg-color--545051, #545051);
  stop-opacity: 0;
}

.sxoyafbbn {
  stop-color: var(--svg-color--805d4c, #805D4C);
  stop-opacity: 0;
}

.t_m5csgaz {
  stop-color: var(--svg-color--866163, #866163);
}

.tri7bg95c {
  stop-color: var(--svg-color--805d4c, #805D4C);
}

.u4bo2-o9a {
  stop-color: var(--svg-color--d84f1a, #D84F1A);
  stop-opacity: 0;
}

.ue2ywxbfs {
  stop-color: var(--svg-color--e45c36, #E45C36);
  stop-opacity: 0;
}

.unful-65k {
  d: path("M11.014 13.766a3.95 3.95 0 0 0 3.922 3.438h1.904a3.95 3.95 0 0 0 3.922-3.438c.12-1.9.24-3.795.328-5.695a1.463 1.463 0 0 0-1.392-1.445h-1.413a2.44 2.44 0 0 1-2.233-1.457a.67.67 0 0 0-.62-.422h-1.286c-1.863 0-3.372 1.527-3.372 3.41c0 1.879.117 3.727.24 5.61");
}

.unyhdjbdq {
  stop-color: var(--svg-color--200e25, #200E25);
}

.up5p4s41k {
  stop-color: var(--svg-color--e64812, #E64812);
  stop-opacity: 0;
}

.v6wds2dtn {
  stop-color: var(--svg-color--dad4de, #DAD4DE);
}

.v7xhdx32s {
  stop-color: var(--svg-color--7d465b, #7D465B);
  stop-opacity: 0;
}

.vx5g9qbgu {
  stop-color: var(--svg-color--815f58, #815F58);
}

.vze8wny8i {
  stop-color: var(--svg-color--e8dee9, #E8DEE9);
}

.w_5-rbc1a {
  stop-color: var(--svg-color--dd3537, #DD3537);
  stop-opacity: 0;
}

.w_o-5kbak {
  stop-color: var(--svg-color--7c4c46, #7C4C46);
}

.w0a4mmrgb {
  stop-color: var(--svg-color--200e25, #200E25);
  stop-opacity: 0;
}

.w8e9izb-y {
  d: path("M26.947 29.939c0-7.961-4.617-9.875-5.375-10.383l-5.047 10.383z");
}

.weeq6_bsp {
  d: path("m16.119 5.307l-.067-.138a.67.67 0 0 0-.62-.422h-1.286c-1.863 0-3.372 1.527-3.372 3.41v.279c-.343-.262-.775-.813-.775-1.704c0-1.082.79-1.629 1.292-1.978a2.5 2.5 0 0 0 .334-.255l.1-.106c.354-.374.982-1.04 2.08-1.332a5.5 5.5 0 0 1 1.53-.167c.472.012.805.42.805.893v1.507z");
}

.wkmk90b2p {
  fill: var(--svg-color--e8d6ff, #E8D6FF);
  d: path("M1.97 24.017h3.298a5.94 5.94 0 0 1 5.937 5.937H1.971zm28.06 0h-3.298a5.94 5.94 0 0 0-5.937 5.937h9.234z");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.woq4pjb0f {
  d: path("M13.68 9.57a.9.9 0 0 0-.868 1.138h1.74a1 1 0 0 0 .033-.238a.907.907 0 0 0-.905-.9");
}

.wpa_x2uhd {
  stop-color: var(--svg-color--855e5a, #855E5A);
  stop-opacity: 0;
}

.x18hoo9hy {
  stop-color: var(--svg-color--7e4c56, #7E4C56);
  stop-opacity: 0;
}

.x3axlob0n {
  stop-color: var(--svg-color--e24c14, #E24C14);
  stop-opacity: 0;
}

.x3v8yobev {
  stop-color: var(--svg-color--7d5855, #7D5855);
  stop-opacity: 0;
}

.x9ttejxmc {
  stop-color: var(--svg-color--825d56, #825D56);
}

.xml1208at {
  d: path("M10.978 12.237a1.66 1.66 0 0 1-.913-.311v.94c0 .901.537 1.704 1.353 2.037a4.1 4.1 0 0 1-.35-1.19z");
}

.xron-kbnx {
  stop-color: var(--svg-color--71404f, #71404F);
  stop-opacity: 0;
}

.xycinvbud {
  cx: 13.408px;
  cy: 9.954px;
  rx: 0.393px;
  ry: 0.199px;
}

.y4umwkb_f {
  stop-color: var(--svg-color--865c56, #865C56);
  stop-opacity: 0;
}

.yf3t3eb5f {
  stop-color: var(--svg-color--ff8244, #FF8244);
}

.ykdcls_lk {
  stop-color: var(--svg-color--dd3d3d, #DD3D3D);
}

.yzv8aja2i {
  fill: var(--svg-color--2e201f, #2E201F);
  d: path("M12.441 7.858a2.8 2.8 0 0 1 1.755-.363a.28.28 0 0 1-.067.556a2.24 2.24 0 0 0-1.4.287a1 1 0 0 0-.093.06l-.002.003a.28.28 0 0 1-.343-.443z");
}

.z-0dlhbai {
  stop-color: var(--svg-color--875455, #875455);
  stop-opacity: 0;
}

.z-90kcitb {
  d: path("M14.503 10.364c0-.29-.237-.485-.3-.543l-.292.281l.18.365z");
}

.z0t4qbbcm {
  d: path("M20.791 12.237c.338-.01.655-.126.913-.311v.94c0 .901-.537 1.704-1.353 2.037q.26-.55.349-1.19z");
}

.z2ddyab4m {
  stop-color: var(--svg-color--f47246, #F47246);
}

.zab-z0bdv {
  d: path("m21.146 8.605l-.03-.637c-.01-.771-.647-1.407-1.418-1.44h-1.413c-.898 0-1.716-.49-2.144-1.27c0 0-.062-.144-.125-.388c-.253-.97.674-1.707 1.654-1.49c.952.21 2.034.564 2.857 1.101c1.76 1.149 1.546 3.149.619 4.124");
}

.zqff1532o {
  stop-color: var(--svg-color--201524, #201524);
}

.zs_feibdl {
  stop-color: var(--svg-color--5d2921, #5D2921);
}

</style>
