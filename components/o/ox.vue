<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#ik9o6Ph)"><path fill="url(#iZT254c)" class="pr-pk3__q"/><path fill="url(#i60Srae)" class="pr-pk3__q"/><path fill="url(#igWtn6d)" class="v6vhlpbuw"/><path fill="url(#iNBg6de)" class="v6vhlpbuw"/><path fill="url(#irHtYYd)" class="v6vhlpbuw"/><path fill="url(#isb5hge)" class="sqhrrmowg"/><path fill="url(#i13kPOe)" class="sqhrrmowg"/><path fill="url(#ivlYsZc)" class="sqhrrmowg"/><path fill="url(#i49FmId)" class="sqhrrmowg"/><path fill="url(#iHA9lMk)" class="sqhrrmowg"/><path fill="url(#i4FSxQb)" class="sqhrrmowg"/><path fill="url(#ikv5rEe)" class="sqhrrmowg"/><path fill="url(#iXMtsrc)" class="sqhrrmowg"/><g filter="url(#iMroHob)"><path stroke="url(#iE1Th2c)" class="mzyojabzj"/></g><g filter="url(#iULnFwZ)"><path stroke="url(#iNJzJie)" class="taa2vacos"/></g><path fill="url(#iL7H8Tb)" class="dus-_qgnv"/><path fill="url(#iRJ4eWd)" clip-rule="evenodd" class="sgtz5aczw"/><path fill="url(#ix0rmLm)" clip-rule="evenodd" class="sgtz5aczw"/><path fill="url(#iLe9Xbc)" clip-rule="evenodd" class="fx5xpcbuq"/><g filter="url(#igrpZRb)"><path fill="url(#ia6FKfe)" class="zz0_n766y"/></g><path fill="url(#i3751vd)" class="ush7zc-kq"/><path fill="url(#i7WyHHe)" class="ush7zc-kq"/><path fill="url(#ijRQf0b)" class="ush7zc-kq"/><path fill="url(#i3Scvld)" class="oo-vl2wdu"/><path fill="url(#iJFHbnd)" class="oo-vl2wdu"/><path fill="url(#iSp045b)" class="oo-vl2wdu"/><path fill="url(#ijTpgCe)" class="oo-vl2wdu"/><path fill="url(#iaB3ucb)" class="oo-vl2wdu"/><path fill="url(#iaR8NaR)" class="oo-vl2wdu"/><path fill="url(#irrUdrG)" class="oo-vl2wdu"/><path fill="url(#iAFCcge)" class="s1rfn162m"/><g filter="url(#iEWhc3b)"><path class="nug63cbpf"/></g><path fill="url(#ipqYNNc)" class="gpskjf_sn"/><g filter="url(#iemCZxe)"><rect class="i7_dzzbdx"/></g><rect fill="url(#iGLKuIb)" class="wy6kxcbgq"/><rect fill="url(#iEa6aIb)" class="wy6kxcbgq"/><g filter="url(#iAaT7fe)"><path stroke="url(#iHUCqad)" class="r57s5rz2o"/></g><g filter="url(#iGTjsKe)"><ellipse class="m8ckg97ht"/></g><g filter="url(#ixjPOAb)"><path stroke="url(#ixu58xe)" class="gau439y-u"/></g><g filter="url(#i4KqwPb)"><ellipse fill="url(#iID6Suh)" transform="rotate(-15.833 18.196 10.743)" class="gbmk__b_f"/></g><g filter="url(#iIlP4uP)"><ellipse fill="url(#iN9oU4d)" transform="rotate(-28.041 12.572 8.149)" class="rmg5tcbnx"/></g><g filter="url(#iT0zdcs)"><ellipse fill="url(#iaMXfJc)" transform="rotate(47.914 26.227 13.877)" class="oyj5hwbix"/></g><g filter="url(#i0zbfqp)"><path class="s_0hx04hh"/></g><path fill="url(#iVznBTu)" class="mnrgr9-xl"/><path fill="url(#iCQ7xJc)" class="mnrgr9-xl"/><path fill="url(#iW6Yvde)" class="xjymjbcnt"/><path fill="url(#iFjVgmd)" class="mnrgr9-xl"/><g filter="url(#iC29MEd)"><path fill="url(#inAEWHb)" class="cmhu7-xju"/></g><g filter="url(#istwgIc)"><path stroke="url(#i8jyAPD)" class="u3rou6bjt"/></g><g filter="url(#iJOkCkF)"><path stroke="url(#iosDhwc)" class="bqb_deyps"/></g></g><defs><linearGradient id="iZT254c" x1="21.329" x2="21.329" y1="22.623" y2="29.488" gradientUnits="userSpaceOnUse"><stop class="gtbnm0b9r"/><stop offset="1" class="lmgvntb0q"/></linearGradient><linearGradient id="i60Srae" x1="19.486" x2="19.486" y1="30.12" y2="29.236" gradientUnits="userSpaceOnUse"><stop class="e5f94y7jr"/><stop offset="1" class="fbrm1804t"/></linearGradient><linearGradient id="igWtn6d" x1="16" x2="16" y1="21.688" y2="29.438" gradientUnits="userSpaceOnUse"><stop class="gtbnm0b9r"/><stop offset="1" class="lmgvntb0q"/></linearGradient><linearGradient id="iNBg6de" x1="14.365" x2="14.365" y1="30.15" y2="29.152" gradientUnits="userSpaceOnUse"><stop class="e5f94y7jr"/><stop offset="1" class="fbrm1804t"/></linearGradient><linearGradient id="irHtYYd" x1="14.365" x2="16.455" y1="30.15" y2="30.15" gradientUnits="userSpaceOnUse"><stop class="e5f94y7jr"/><stop offset="1" class="fbrm1804t"/></linearGradient><linearGradient id="isb5hge" x1="17.142" x2="17.142" y1="32.787" y2="9.787" gradientUnits="userSpaceOnUse"><stop class="z5rl6vp6m"/><stop offset="1" class="eh7noq4nb"/></linearGradient><linearGradient id="ivlYsZc" x1="18.517" x2="18.517" y1="2.975" y2="10.225" gradientUnits="userSpaceOnUse"><stop class="ik2h44jfq"/><stop offset="1" class="quk50ghag"/></linearGradient><linearGradient id="ikv5rEe" x1="6.299" x2="13.518" y1="20.319" y2="18.85" gradientUnits="userSpaceOnUse"><stop class="o7e71qmqs"/><stop offset="1" class="qn2viwbtl"/></linearGradient><linearGradient id="iXMtsrc" x1="4.46" x2="4.46" y1="30.725" y2="28.225" gradientUnits="userSpaceOnUse"><stop class="e5f94y7jr"/><stop offset="1" class="fbrm1804t"/></linearGradient><linearGradient id="iE1Th2c" x1="29.705" x2="29.705" y1="27.944" y2="16.287" gradientUnits="userSpaceOnUse"><stop class="vpbaw696x"/><stop offset="1" class="tfhiadamg"/></linearGradient><linearGradient id="iNJzJie" x1="14.393" x2="14.393" y1="27.944" y2="24.162" gradientUnits="userSpaceOnUse"><stop class="vpbaw696x"/><stop offset="1" class="tfhiadamg"/></linearGradient><linearGradient id="ia6FKfe" x1="9.182" x2="5.684" y1="5.404" y2="6.217" gradientUnits="userSpaceOnUse"><stop offset=".001" class="clo5b4d0y"/><stop offset="1" class="jd5jsof3p"/></linearGradient><linearGradient id="i3751vd" x1="5.314" x2="6.314" y1="6.475" y2="8.037" gradientUnits="userSpaceOnUse"><stop class="clo5b4d0y"/><stop offset=".784" class="jd5jsof3p"/></linearGradient><linearGradient id="i3Scvld" x1="4.83" x2="11.736" y1="4.965" y2="4.965" gradientUnits="userSpaceOnUse"><stop class="e2a7rcbkj"/><stop offset=".994" class="ixz6v2bhs"/></linearGradient><linearGradient id="iJFHbnd" x1="8.049" x2="8.049" y1="7.037" y2="5.725" gradientUnits="userSpaceOnUse"><stop class="r7c_c84nt"/><stop offset="1" class="jlw4o4bdz"/></linearGradient><linearGradient id="iaB3ucb" x1="9.393" x2="9.393" y1="1.709" y2="6.912" gradientUnits="userSpaceOnUse"><stop offset=".919" class="n-g51fctk"/><stop offset="1" class="dbg7ck8qh"/></linearGradient><linearGradient id="iaR8NaR" x1="13.955" x2="4.518" y1="7.037" y2="6.805" gradientUnits="userSpaceOnUse"><stop class="f04kk6_vi"/><stop offset="1" class="f-0ieq8gx"/></linearGradient><linearGradient id="iGLKuIb" x1="7.893" x2="7.299" y1="9.105" y2="9.105" gradientUnits="userSpaceOnUse"><stop class="dyysy0bzo"/><stop offset=".855" class="co-foyhmg"/></linearGradient><linearGradient id="iEa6aIb" x1="8.2" x2="8.2" y1="10.305" y2="9.594" gradientUnits="userSpaceOnUse"><stop class="aztbnnbvp"/><stop offset="1" class="jqmybnbeu"/></linearGradient><linearGradient id="iHUCqad" x1="5.736" x2="8.486" y1="3.709" y2="5.709" gradientUnits="userSpaceOnUse"><stop class="e2a7rcbkj"/><stop offset="1" class="shxfbkb6h"/></linearGradient><linearGradient id="ixu58xe" x1="10.814" x2="12.252" y1="7.936" y2="9.506" gradientUnits="userSpaceOnUse"><stop class="l2pybdj6k"/><stop offset="1" class="h1h6hg1qi"/></linearGradient><linearGradient id="inAEWHb" x1="12.978" x2="13.174" y1="21.225" y2="27.312" gradientUnits="userSpaceOnUse"><stop class="tvmca_42l"/><stop offset="1" class="m27n2762h"/></linearGradient><linearGradient id="i8jyAPD" x1="18.361" x2="18.361" y1="29.537" y2="18.444" gradientUnits="userSpaceOnUse"><stop class="h9watlb2v"/><stop offset="1" class="fax5mpb4w"/></linearGradient><linearGradient id="iosDhwc" x1="23.563" x2="23.563" y1="29.544" y2="19.037" gradientUnits="userSpaceOnUse"><stop class="h9watlb2v"/><stop offset="1" class="fax5mpb4w"/></linearGradient><radialGradient id="i13kPOe" cx="0" cy="0" r="1" gradientTransform="matrix(0 -16.3125 20.5732 0 18.517 30.225)" gradientUnits="userSpaceOnUse"><stop offset=".165" class="p4y5r8b9e"/><stop offset="1" class="j7o2zybhp"/></radialGradient><radialGradient id="i49FmId" cx="0" cy="0" r="1" gradientTransform="matrix(-1.875 3.8125 -7.6303 -3.75258 24.767 7.975)" gradientUnits="userSpaceOnUse"><stop class="ik2h44jfq"/><stop offset="1" class="quk50ghag"/></radialGradient><radialGradient id="iHA9lMk" cx="0" cy="0" r="1" gradientTransform="rotate(-61.343 34.038 -7.361)scale(3.06266 3.34985)" gradientUnits="userSpaceOnUse"><stop class="e5f94y7jr"/><stop offset=".889" class="fbrm1804t"/></radialGradient><radialGradient id="i4FSxQb" cx="0" cy="0" r="1" gradientTransform="matrix(3.26562 -4.01562 2.33383 1.89794 8.22 23.85)" gradientUnits="userSpaceOnUse"><stop class="e5f94y7jr"/><stop offset=".856" class="fbrm1804t"/></radialGradient><radialGradient id="iL7H8Tb" cx="0" cy="0" r="1" gradientTransform="matrix(.25 -2.04688 .82312 .10053 28.892 20.194)" gradientUnits="userSpaceOnUse"><stop class="e5f94y7jr"/><stop offset="1" class="fbrm1804t"/></radialGradient><radialGradient id="iRJ4eWd" cx="0" cy="0" r="1" gradientTransform="matrix(-5.21956 -10.06567 6.1179 -3.17244 17.78 26.726)" gradientUnits="userSpaceOnUse"><stop offset=".212" class="e5f94y7jr"/><stop offset="1" class="fbrm1804t"/></radialGradient><radialGradient id="ix0rmLm" cx="0" cy="0" r="1" gradientTransform="rotate(-70.241 28.65 -.455)scale(6.84025 4.15749)" gradientUnits="userSpaceOnUse"><stop offset=".212" class="e5f94y7jr"/><stop offset="1" class="fbrm1804t"/></radialGradient><radialGradient id="iLe9Xbc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.09375 4 -1.8473 -.50512 28.549 22.662)" gradientUnits="userSpaceOnUse"><stop class="polkaob1u"/><stop offset="1" class="ghjc5p1oh"/></radialGradient><radialGradient id="i7WyHHe" cx="0" cy="0" r="1" gradientTransform="matrix(5.03124 -2.41995 3.1687 6.58797 2.627 11.225)" gradientUnits="userSpaceOnUse"><stop offset=".177" class="hrouo0bdt"/><stop offset=".767" class="ktciwhudd"/></radialGradient><radialGradient id="ijRQf0b" cx="0" cy="0" r="1" gradientTransform="matrix(3.4375 -4 2.21868 1.90668 4.424 14.381)" gradientUnits="userSpaceOnUse"><stop offset=".194" class="e5f94y7jr"/><stop offset=".889" class="fbrm1804t"/></radialGradient><radialGradient id="iSp045b" cx="0" cy="0" r="1" gradientTransform="matrix(-.93748 2.64062 -4.05022 -1.43792 8.049 4.287)" gradientUnits="userSpaceOnUse"><stop offset=".611" class="n-g51fctk"/><stop offset="1" class="q192u5b1a"/></radialGradient><radialGradient id="ijTpgCe" cx="0" cy="0" r="1" gradientTransform="rotate(115.45 2.72 4.728)scale(2.87249 3.96142)" gradientUnits="userSpaceOnUse"><stop offset=".812" class="n-g51fctk"/><stop offset="1" class="dbg7ck8qh"/></radialGradient><radialGradient id="irrUdrG" cx="0" cy="0" r="1" gradientTransform="matrix(.29688 2.2428 -1.96937 .26068 7.314 3.123)" gradientUnits="userSpaceOnUse"><stop class="vem8wsb9y"/><stop offset="1" class="trco5lbrf"/></radialGradient><radialGradient id="iAFCcge" cx="0" cy="0" r="1" gradientTransform="matrix(.57031 0 0 1.11138 3.94 10.85)" gradientUnits="userSpaceOnUse"><stop class="ysksrestg"/><stop offset="1" class="c5xhtsbqk"/></radialGradient><radialGradient id="ipqYNNc" cx="0" cy="0" r="1" gradientTransform="rotate(-170.851 16.235 11.375)scale(2.40561)" gradientUnits="userSpaceOnUse"><stop class="xwk5udbbs"/><stop offset="1" class="p3h7bebar"/></radialGradient><radialGradient id="iID6Suh" cx="0" cy="0" r="1" gradientTransform="rotate(88.397 4.096 14.22)scale(2.75063 1.9563)" gradientUnits="userSpaceOnUse"><stop class="tvmca_42l"/><stop offset="1" class="m27n2762h"/></radialGradient><radialGradient id="iN9oU4d" cx="0" cy="0" r="1" gradientTransform="rotate(169.927 6.426 4.56)scale(2.30367 4.29292)" gradientUnits="userSpaceOnUse"><stop class="tvmca_42l"/><stop offset="1" class="m27n2762h"/></radialGradient><radialGradient id="iaMXfJc" cx="0" cy="0" r="1" gradientTransform="rotate(87.903 7.216 19.256)scale(4.82161 3.03966)" gradientUnits="userSpaceOnUse"><stop class="gy8hgubiu"/><stop offset="1" class="m27n2762h"/></radialGradient><radialGradient id="iVznBTu" cx="0" cy="0" r="1" gradientTransform="matrix(-1.78125 1.82812 -3.12353 -3.04345 12.705 8.366)" gradientUnits="userSpaceOnUse"><stop class="ju9zw6uwt"/><stop offset="1" class="ayxtrobyb"/></radialGradient><radialGradient id="iCQ7xJc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.625 1.6875 -2.32813 -2.2419 12.408 8.662)" gradientUnits="userSpaceOnUse"><stop offset=".617" class="l16box48k"/><stop offset=".955" class="xcq4s9bgd"/></radialGradient><radialGradient id="iW6Yvde" cx="0" cy="0" r="1" gradientTransform="matrix(-1.53125 1.71875 -2.23438 -1.99062 12.314 8.631)" gradientUnits="userSpaceOnUse"><stop offset=".761" class="qppeqz8wx"/><stop offset=".955" class="wke-vgb5h"/></radialGradient><radialGradient id="iFjVgmd" cx="0" cy="0" r="1" gradientTransform="matrix(-.5625 -.14062 .10987 -.43947 13.814 10.381)" gradientUnits="userSpaceOnUse"><stop class="l2pybdj6k"/><stop offset="1" class="h1h6hg1qi"/></radialGradient><filter id="iMroHob" width="1.8" height="10.75" x="26.492" y="19.162" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_2831" stdDeviation=".375"/></filter><filter id="iULnFwZ" width="1.4" height="6.2" x="11.38" y="23.562" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_2831" stdDeviation=".3"/></filter><filter id="igrpZRb" width="5.196" height="2.977" x="6.243" y="5.226" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_2831" stdDeviation=".25"/></filter><filter id="iEWhc3b" width=".9" height="5.644" x="29.286" y="17.934" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_2831" stdDeviation=".2"/></filter><filter id="iemCZxe" width="1.787" height="2.592" x="6.334" y="7.809" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_2831" stdDeviation=".25"/></filter><filter id="iAaT7fe" width="3.734" height="3.031" x="4.799" y="2.897" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_2831" stdDeviation=".25"/></filter><filter id="iGTjsKe" width="1.975" height="2.25" x="9.508" y="4.553" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_2831" stdDeviation=".375"/></filter><filter id="ixjPOAb" width="2.5" height="2.602" x="10.471" y="7.28" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_2831" stdDeviation=".125"/></filter><filter id="i4KqwPb" width="5.505" height="6.472" x="15.444" y="7.507" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_2831" stdDeviation=".5"/></filter><filter id="iIlP4uP" width="6.112" height="7.505" x="9.516" y="4.396" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_2831" stdDeviation=".5"/></filter><filter id="iT0zdcs" width="8.162" height="8.204" x="22.146" y="9.776" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_2831" stdDeviation=".5"/></filter><filter id="i0zbfqp" width="4.485" height="4.483" x="9.244" y="6.979" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_2831" stdDeviation=".25"/></filter><filter id="iC29MEd" width="4.078" height="6.594" x="11.08" y="21.1" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_2831" stdDeviation=".5"/></filter><filter id="istwgIc" width="2.394" height="7.134" x="15.432" y="22.549" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_2831" stdDeviation=".3"/></filter><filter id="iJOkCkF" width="2.921" height="6.822" x="19.526" y="22.892" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_2831" stdDeviation=".3"/></filter><clipPath id="ik9o6Ph"><path class="wycjhibbk"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:ox" /></template>
<style>
.ayxtrobyb {
  stop-color: var(--svg-color--60363d, #60363D);
}

.aztbnnbvp {
  stop-color: var(--svg-color--552d52, #552D52);
}

.bqb_deyps {
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M21.799 23.506L20.174 29.1");
}

.c5xhtsbqk {
  stop-color: var(--svg-color--4e2425, #4E2425);
}

.clo5b4d0y {
  stop-color: var(--svg-color--5d352e, #5D352E);
}

.cmhu7-xju {
  d: path("M12.08 22.35a.25.25 0 0 1 .25-.25h1.578a.25.25 0 0 1 .25.25v1.415a3 3 0 0 1-1.511 2.605l-.567.324z");
}

.co-foyhmg {
  stop-color: var(--svg-color--31232c, #31232C);
}

.dbg7ck8qh {
  stop-color: var(--svg-color--9d6647, #9D6647);
}

.dus-_qgnv {
  d: path("m29.08 23.412l.344-.14v-5.325c0-.106-.145-.139-.19-.043l-1.092 2.282a.84.84 0 0 1 .25-.316c.259-.204.688-.033.688.296z");
}

.dyysy0bzo {
  stop-color: var(--svg-color--594c4f, #594C4F);
}

.e2a7rcbkj {
  stop-color: var(--svg-color--ffdea7, #FFDEA7);
}

.e5f94y7jr {
  stop-color: var(--svg-color--782666, #782666);
}

.eh7noq4nb {
  stop-color: var(--svg-color--865950, #865950);
}

.f-0ieq8gx {
  stop-color: var(--svg-color--e99354, #E99354);
  stop-opacity: 0;
}

.f04kk6_vi {
  stop-color: var(--svg-color--e99354, #E99354);
}

.fax5mpb4w {
  stop-color: var(--svg-color--d6b0a9, #D6B0A9);
  stop-opacity: 0;
}

.fbrm1804t {
  stop-color: var(--svg-color--693452, #693452);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.fx5xpcbuq {
  fill-rule: evenodd;
  d: path("M28.08 23.696c-.574.238-1 1.102-1 2.13c0 1.03.426 1.893 1 2.13z");
}

.gau439y-u {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("m10.846 7.655l1.75 1.851");
}

.gbmk__b_f {
  cx: 18.196px;
  cy: 10.743px;
  rx: 1.704px;
  ry: 2.273px;
}

.ghjc5p1oh {
  stop-color: var(--svg-color--291d1e, #291D1E);
  stop-opacity: 0;
}

.gpskjf_sn {
  d: path("M29.585 26.743c.268.068.495-.162.495-.438v-3.5c-1.1 0-2 .9-2 2c0 .93.643 1.716 1.505 1.938");
}

.gtbnm0b9r {
  stop-color: var(--svg-color--4c2325, #4C2325);
}

.gy8hgubiu {
  stop-color: var(--svg-color--976e66, #976E66);
}

.h1h6hg1qi {
  stop-color: var(--svg-color--7e5952, #7E5952);
  stop-opacity: 0;
}

.h9watlb2v {
  stop-color: var(--svg-color--d6b0a9, #D6B0A9);
}

.hrouo0bdt {
  stop-color: var(--svg-color--916153, #916153);
}

.i7_dzzbdx {
  width: 0.787px;
  height: 1.592px;
  x: 6.834px;
  y: 8.309px;
  fill: var(--svg-color--5b2f2c, #5B2F2C);
  rx: 0.393px;
}

.ik2h44jfq {
  stop-color: var(--svg-color--744036, #744036);
}

.ixz6v2bhs {
  stop-color: var(--svg-color--dc872a, #DC872A);
}

.j7o2zybhp {
  stop-color: var(--svg-color--5c302d, #5C302D);
  stop-opacity: 0;
}

.jd5jsof3p {
  stop-color: var(--svg-color--5d352e, #5D352E);
  stop-opacity: 0;
}

.jlw4o4bdz {
  stop-color: var(--svg-color--de9360, #DE9360);
  stop-opacity: 0;
}

.jqmybnbeu {
  stop-color: var(--svg-color--552d52, #552D52);
  stop-opacity: 0;
}

.ju9zw6uwt {
  stop-color: var(--svg-color--7d5953, #7D5953);
}

.ktciwhudd {
  stop-color: var(--svg-color--86594c, #86594C);
  stop-opacity: 0;
}

.l16box48k {
  stop-color: var(--svg-color--4d282e, #4D282E);
  stop-opacity: 0;
}

.l2pybdj6k {
  stop-color: var(--svg-color--7e5952, #7E5952);
}

.lmgvntb0q {
  stop-color: var(--svg-color--754a4d, #754A4D);
}

.m27n2762h {
  stop-color: var(--svg-color--976e66, #976E66);
  stop-opacity: 0;
}

.m8ckg97ht {
  cx: 10.495px;
  cy: 5.678px;
  fill: var(--svg-color--ffdea7, #FFDEA7);
  rx: 0.237px;
  ry: 0.375px;
}

.mnrgr9-xl {
  d: path("M10.932 7.246c-.227-.226-.608-.183-.712.12a2.601 2.601 0 0 0 3.307 3.299c.3-.104.341-.482.117-.706z");
}

.mzyojabzj {
  stroke-width: var(--svg-stroke-width--0-3px, 0.3px);
  d: path("M27.393 29.162v-9.25");
}

.n-g51fctk {
  stop-color: var(--svg-color--b47b5b, #B47B5B);
  stop-opacity: 0;
}

.nug63cbpf {
  stroke: var(--svg-color--a77c73, #A77C73);
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M29.736 23.178v-4.844");
}

.o7e71qmqs {
  stop-color: var(--svg-color--672d2b, #672D2B);
}

.oo-vl2wdu {
  d: path("M8.049 4.805a3 3 0 0 1-2.5-1.55c-.11-.21-.43-.16-.46.08c-.03.15-.04.3-.04.45c-.01 1.66 1.39 3.02 3.05 3.02h1.95c.55 0 1-.45 1-1s-.45-1-1-1z");
}

.oyj5hwbix {
  cx: 26.227px;
  cy: 13.877px;
  rx: 3.191px;
  ry: 2.988px;
}

.p3h7bebar {
  stop-color: var(--svg-color--412824, #412824);
}

.p4y5r8b9e {
  stop-color: var(--svg-color--5c302d, #5C302D);
}

.polkaob1u {
  stop-color: var(--svg-color--291d1e, #291D1E);
}

.pr-pk3__q {
  d: path("M20.84 29.805h-1.48c-.17 0-.29-.16-.24-.32l2.43-8.53h2l-2.47 8.67c-.03.11-.13.18-.24.18");
}

.q192u5b1a {
  stop-color: var(--svg-color--b47b5b, #B47B5B);
}

.qn2viwbtl {
  stop-color: var(--svg-color--644645, #644645);
  stop-opacity: 0;
}

.qppeqz8wx {
  stop-color: var(--svg-color--3a2327, #3A2327);
  stop-opacity: 0;
}

.quk50ghag {
  stop-color: var(--svg-color--744036, #744036);
  stop-opacity: 0;
}

.r57s5rz2o {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M5.424 3.522c.406 1 1.184 1.781 2.484 1.781");
}

.r7c_c84nt {
  stop-color: var(--svg-color--ca7134, #CA7134);
}

.rmg5tcbnx {
  cx: 12.572px;
  cy: 8.149px;
  rx: 1.704px;
  ry: 2.983px;
}

.s_0hx04hh {
  fill: var(--svg-color--5b2f2c, #5B2F2C);
  d: path("M11.29 7.824c-.57-.57-1.546-.428-1.546.377a2.763 2.763 0 0 0 2.761 2.761c.81 0 .948-.974.376-1.546z");
}

.s1rfn162m {
  d: path("M4.18 11.215c-.28 0-.5-.22-.5-.5v-.55c0-.28.22-.5.5-.5s.5.22.5.5v.55c0 .28-.22.5-.5.5");
}

.sgtz5aczw {
  fill-rule: evenodd;
  d: path("m22.158 23.011l2.984-5.724l-13.75-1.5l3.138 7.786v-.24a.5.5 0 0 1 .498-.5l5.432-.028c.43 0 .829-.104 1.185-.284c.184-.093.432.03.463.234q.02.13.05.256");
}

.shxfbkb6h {
  stop-color: var(--svg-color--ffdea7, #FFDEA7);
  stop-opacity: 0;
}

.sqhrrmowg {
  d: path("M25.39 9.805h-3.76c-.62 0-1.2-.27-1.63-.72a3.93 3.93 0 0 0-2.92-1.28h-2c-.16 0-.31-.08-.39-.22l-.56-.96a3.63 3.63 0 0 0-3.15-1.82h-.89c-.79 0-1.55.23-2.21.67l-5.1 3.4c-.43.29-.7.79-.7 1.32c0 1.43 1.13 2.61 2.56 2.61h2.022a.5.5 0 0 1 .492.41l.656 3.62l.68 3.9a2.55 2.55 0 0 0 1.639 1.951c.226.082.401.284.401.525v6.374c0 .14.11.25.25.25h1.5c.14 0 .25-.11.25-.25v-2.443a.5.5 0 0 1 .274-.446l.596-.301c.69-.35 1.13-1.05 1.13-1.82v-1.242a.5.5 0 0 1 .498-.5l5.432-.028c.43 0 .829-.104 1.185-.284c.184-.093.432.03.463.234a3.26 3.26 0 0 0 2.442 2.67l1.15.286a.5.5 0 0 1 .38.485v3.359c0 .14.11.25.25.25h1.5c.14 0 .25-.11.25-.25v-9.078c0-.239.125-.46.312-.607c.259-.204.688-.033.688.296v3.649h1v-9.31c0-2.6-2.1-4.7-4.69-4.7");
}

.taa2vacos {
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M12.08 29.162v-5");
}

.tfhiadamg {
  stop-color: var(--svg-color--a77c73, #A77C73);
  stop-opacity: 0;
}

.trco5lbrf {
  stop-color: var(--svg-color--ffda9e, #FFDA9E);
  stop-opacity: 0;
}

.tvmca_42l {
  stop-color: var(--svg-color--976e66, #976E66);
  stop-opacity: 0.75;
}

.u3rou6bjt {
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("m16.08 23.162l1.094 3.782l-.625 2.125");
}

.ush7zc-kq {
  d: path("M10.98 4.805c1.3 0 2.569.67 3.15 1.82s-3.55 4.1-7.05 6.18H4.64c-1.43 0-2.56-1.18-2.56-2.61c0-.53.27-1.03.7-1.32l5.1-3.4a3.96 3.96 0 0 1 2.21-.67z");
}

.v6vhlpbuw {
  d: path("M16.03 19.805h-2l1.98 6.91c.02.06.02.12 0 .17l-.76 2.59c-.05.16.07.32.24.32h1.48c.11 0 .21-.07.24-.18l.7-2.39c.08-.28.08-.58 0-.87z");
}

.vem8wsb9y {
  stop-color: var(--svg-color--ffda9e, #FFDA9E);
}

.vpbaw696x {
  stop-color: var(--svg-color--a77c73, #A77C73);
}

.wke-vgb5h {
  stop-color: var(--svg-color--3a2327, #3A2327);
}

.wy6kxcbgq {
  width: 0.969px;
  height: 1.96px;
  x: 7.08px;
  y: 8.125px;
  rx: 0.484px;
}

.wycjhibbk {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h32v32H0z");
}

.xcq4s9bgd {
  stop-color: var(--svg-color--4d282e, #4D282E);
}

.xjymjbcnt {
  fill-opacity: var(--svg-fill-opacity--0-5, 0.5);
  d: path("M10.932 7.246c-.227-.226-.608-.183-.712.12a2.601 2.601 0 0 0 3.307 3.299c.3-.104.341-.482.117-.706z");
}

.xwk5udbbs {
  stop-color: var(--svg-color--755b59, #755B59);
}

.ysksrestg {
  stop-color: var(--svg-color--6a4342, #6A4342);
}

.z5rl6vp6m {
  stop-color: var(--svg-color--763f52, #763F52);
}

.zz0_n766y {
  d: path("m6.743 6.4l4.196-.674a1.53 1.53 0 0 1-1.286 1.51l-2.91.466z");
}

</style>
