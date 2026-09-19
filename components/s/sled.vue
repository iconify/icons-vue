<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="a84p2rb3l"/><path stroke="url(#iR4P2Rd)" class="c92j1ybhk"/><path stroke="url(#i8Q5Aic)" class="c92j1ybhk"/><path stroke="url(#iQOwOqi)" class="c92j1ybhk"/><path class="iuk_a1b5z"/><path stroke="url(#iEzUQsd)" class="ah99qqcvh"/><path stroke="url(#ilXj1pd)" class="ah99qqcvh"/><path stroke="url(#iSAKKtd)" class="ah99qqcvh"/><g filter="url(#iecmzee)" class="d8af_jbct"><path stroke="url(#i7KAqSd)" class="bdclkbxdi"/><path stroke="url(#iajpTqb)" class="bdclkbxdi"/><path stroke="url(#in1unky)" class="bdclkbxdi"/></g><g filter="url(#iLYlF6d)" class="d8af_jbct"><path stroke="url(#iuumXme)" class="o-c16gure"/><path stroke="url(#iwwBl7d)" class="o-c16gure"/></g><g filter="url(#i2rVEwd)"><rect fill="url(#iTHRSoe)" class="r--zxkbgx"/><rect fill="url(#i5Kvycc)" class="r--zxkbgx"/></g><g filter="url(#irLyWwe)"><path class="nkwuembyp"/><path fill="url(#i1BBiEA)" class="q2bhaimkf"/><path fill="url(#i29Uskc)" class="q2bhaimkf"/></g><path fill="url(#ihieGvd)" class="yvlra6byh"/><path fill="url(#iy5B9Nc)" class="yvlra6byh"/><path fill="url(#ibobdLb)" class="yvlra6byh"/><path fill="url(#iORz2oe)" class="p8cu0eq5m"/><path fill="url(#iC6wvtG)" class="p8cu0eq5m"/><path fill="url(#iXvZCCc)" class="p8cu0eq5m"/><g filter="url(#iN9VMbb)"><path class="ey9ovtlxh"/></g><defs><linearGradient id="iR4P2Rd" x1="12.451" x2="12.451" y1="22.019" y2="23.943" gradientUnits="userSpaceOnUse"><stop offset=".186" class="znv03of5i"/><stop offset="1" class="bmgcb3dxv"/></linearGradient><linearGradient id="i8Q5Aic" x1="10.527" x2="12.037" y1="23.943" y2="23.943" gradientUnits="userSpaceOnUse"><stop offset=".186" class="znv03of5i"/><stop offset="1" class="bmgcb3dxv"/></linearGradient><linearGradient id="iEzUQsd" x1="23.755" x2="24.63" y1="21.81" y2="23.591" gradientUnits="userSpaceOnUse"><stop offset=".336" class="i8yhl7b1q"/><stop offset="1" class="h859tdb5v"/></linearGradient><linearGradient id="ilXj1pd" x1="22.808" x2="24.568" y1="23.943" y2="23.943" gradientUnits="userSpaceOnUse"><stop offset=".186" class="i8yhl7b1q"/><stop offset="1" class="h859tdb5v"/></linearGradient><linearGradient id="i7KAqSd" x1="16.693" x2="16.693" y1="29.247" y2="25.935" gradientUnits="userSpaceOnUse"><stop class="uvqus6y_e"/><stop offset="1" class="w4-1d3eyn"/></linearGradient><linearGradient id="iuumXme" x1="16.693" x2="16.693" y1="20.841" y2="17.529" gradientUnits="userSpaceOnUse"><stop class="uvqus6y_e"/><stop offset="1" class="w4-1d3eyn"/></linearGradient><linearGradient id="iTHRSoe" x1="18.246" x2="18.246" y1="11" y2="21.31" gradientUnits="userSpaceOnUse"><stop class="nt6ruob0m"/><stop offset="1" class="nl42jtlgo"/></linearGradient><linearGradient id="i5Kvycc" x1="19.33" x2="19.33" y1="21.081" y2="20.709" gradientUnits="userSpaceOnUse"><stop class="crv2xwbdt"/><stop offset="1" class="kwqd_0z_v"/></linearGradient><linearGradient id="i1BBiEA" x1="29.535" x2="27.515" y1="21.719" y2="21.719" gradientUnits="userSpaceOnUse"><stop class="bujplac7c"/><stop offset="1" class="trjwl5b7e"/></linearGradient><linearGradient id="i29Uskc" x1="7.529" x2="9.126" y1="22.558" y2="22.558" gradientUnits="userSpaceOnUse"><stop class="re6vzs60c"/><stop offset="1" class="n03dx1biq"/></linearGradient><linearGradient id="ihieGvd" x1="8.255" x2="27.63" y1="14.997" y2="14.997" gradientUnits="userSpaceOnUse"><stop class="rx1lckolv"/><stop offset="1" class="rg81j723m"/></linearGradient><linearGradient id="iy5B9Nc" x1="7.529" x2="8.078" y1="14.741" y2="14.741" gradientUnits="userSpaceOnUse"><stop class="qqgm_bnmv"/><stop offset="1" class="tdb14gbhf"/></linearGradient><linearGradient id="ibobdLb" x1="29.143" x2="28.168" y1="14.644" y2="14.644" gradientUnits="userSpaceOnUse"><stop class="fg956rssn"/><stop offset="1" class="x-qi9vboy"/></linearGradient><linearGradient id="iORz2oe" x1="13.255" x2="27.63" y1="18.318" y2="18.318" gradientUnits="userSpaceOnUse"><stop class="rx1lckolv"/><stop offset="1" class="rg81j723m"/></linearGradient><linearGradient id="iC6wvtG" x1="7.529" x2="8.078" y1="18.062" y2="18.062" gradientUnits="userSpaceOnUse"><stop class="qqgm_bnmv"/><stop offset="1" class="tdb14gbhf"/></linearGradient><linearGradient id="iXvZCCc" x1="29.143" x2="28.168" y1="17.965" y2="17.965" gradientUnits="userSpaceOnUse"><stop class="fg956rssn"/><stop offset="1" class="x-qi9vboy"/></linearGradient><radialGradient id="iQOwOqi" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.82469 .90902 0 12.988 27.529)" gradientUnits="userSpaceOnUse"><stop class="kz4r3qo0r"/><stop offset="1" class="awme95d2l"/></radialGradient><radialGradient id="iSAKKtd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.82469 .90902 0 25.27 27.529)" gradientUnits="userSpaceOnUse"><stop class="wnk2vkbkn"/><stop offset="1" class="zr6--jigs"/></radialGradient><radialGradient id="iajpTqb" cx="0" cy="0" r="1" gradientTransform="matrix(-13.9688 0 0 -5.53125 27.974 28.841)" gradientUnits="userSpaceOnUse"><stop class="g00hgc-gl"/><stop offset="1" class="ry77lkgfc"/></radialGradient><radialGradient id="in1unky" cx="0" cy="0" r="1" gradientTransform="rotate(157.521 12.199 16.602)scale(1.96154 1.58091)" gradientUnits="userSpaceOnUse"><stop class="wiifu8bvh"/><stop offset="1" class="v_rt5kb-t"/></radialGradient><radialGradient id="iwwBl7d" cx="0" cy="0" r="1" gradientTransform="rotate(153.727 1.65 10.309)scale(1.80774 2.87508)" gradientUnits="userSpaceOnUse"><stop offset=".347" class="mokbsrbmg"/><stop offset="1" class="lees09bpy"/></radialGradient><filter id="iecmzee" width="28.106" height="5.356" x="1.943" y="23.672" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.776471 0 0 0 0 0.176471 0 0 0 0 0.345098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_3054"/></filter><filter id="iLYlF6d" width="25.2" height="5.356" x="1.943" y="15.266" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.776471 0 0 0 0 0.176471 0 0 0 0 0.345098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_3054"/></filter><filter id="i2rVEwd" width="22.234" height="11.858" x="7.029" y="10.7" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".3" dy="-.3"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.933333 0 0 0 0 0.623529 0 0 0 0 0.439216 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_3054"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.5" dy="-.3"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.870588 0 0 0 0 0.647059 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_3054" result="effect2_innerShadow_18_3054"/></filter><filter id="irLyWwe" width="21.434" height="2.909" x="7.529" y="19.799" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".15"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.972549 0 0 0 0 0.635294 0 0 0 0 0.615686 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_3054"/></filter><filter id="iN9VMbb" width="3.868" height="3.688" x="2.737" y="15.968" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_3054" stdDeviation=".125"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:sled" /></template>
<style>
.a84p2rb3l {
  stroke: var(--svg-color--f22e5b, #F22E5B);
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12.037 22.372v5.157");
}

.ah99qqcvh {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M24.318 22.372v5.157");
}

.awme95d2l {
  stop-color: var(--svg-color--ff4462, #FF4462);
  stop-opacity: 0;
}

.bdclkbxdi {
  d: path("M2.943 24.872v.157a3 3 0 0 0 3 3h22.906");
}

.bmgcb3dxv {
  stop-color: var(--svg-color--d02640, #D02640);
  stop-opacity: 0;
}

.bujplac7c {
  stop-color: var(--svg-color--f9b398, #F9B398);
}

.c92j1ybhk {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12.037 22.372v5.157");
}

.crv2xwbdt {
  stop-color: var(--svg-color--f7a29d, #F7A29D);
}

.d8af_jbct {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.ey9ovtlxh {
  stroke: var(--svg-color--ff455f, #FF455F);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M3.112 16.343c.03.979.696 2.937 3.119 2.937");
}

.fg956rssn {
  stop-color: var(--svg-color--ffb063, #FFB063);
}

.ft5dv1b6b {
  fill: none;
}

.g00hgc-gl {
  stop-color: var(--svg-color--ff449d, #FF449D);
}

.h859tdb5v {
  stop-color: var(--svg-color--c3305e, #C3305E);
  stop-opacity: 0;
}

.i8yhl7b1q {
  stop-color: var(--svg-color--c3305e, #C3305E);
}

.iuk_a1b5z {
  stroke: var(--svg-color--fe368a, #FE368A);
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M24.318 22.372v5.157");
}

.kwqd_0z_v {
  stop-color: var(--svg-color--f7a29d, #F7A29D);
  stop-opacity: 0;
}

.kz4r3qo0r {
  stop-color: var(--svg-color--ff4462, #FF4462);
}

.lees09bpy {
  stop-color: var(--svg-color--cf2738, #CF2738);
  stop-opacity: 0;
}

.mokbsrbmg {
  stop-color: var(--svg-color--cf2738, #CF2738);
}

.n03dx1biq {
  stop-color: var(--svg-color--d17979, #D17979);
  stop-opacity: 0;
}

.nkwuembyp {
  fill: var(--svg-color--df7590, #DF7590);
  d: path("M7.53 19.799v1.509c0 .69.56 1.25 1.25 1.25h18.933c.69 0 1.25-.56 1.25-1.25v-1.51c0 .69-.56 1.25-1.25 1.25H8.78c-.69 0-1.25-.56-1.25-1.25");
}

.nl42jtlgo {
  stop-color: var(--svg-color--ffc899, #FFC899);
}

.nt6ruob0m {
  stop-color: var(--svg-color--ffcb95, #FFCB95);
}

.o-c16gure {
  d: path("M2.943 16.466v.156a3 3 0 0 0 3 3h20");
}

.p8cu0eq5m {
  d: path("M7.53 18.318v-1.453h21.433v1.453z");
}

.q2bhaimkf {
  d: path("M7.53 19.799v1.509c0 .69.56 1.25 1.25 1.25h18.933c.69 0 1.25-.56 1.25-1.25v-1.51c0 .69-.56 1.25-1.25 1.25H8.78c-.69 0-1.25-.56-1.25-1.25");
}

.qqgm_bnmv {
  stop-color: var(--svg-color--df884f, #DF884F);
}

.r--zxkbgx {
  width: 21.434px;
  height: 11.558px;
  x: 7.529px;
  y: 11px;
  rx: 1.25px;
}

.re6vzs60c {
  stop-color: var(--svg-color--d17979, #D17979);
}

.rg81j723m {
  stop-color: var(--svg-color--f3984d, #F3984D);
}

.rx1lckolv {
  stop-color: var(--svg-color--ffae65, #FFAE65);
}

.ry77lkgfc {
  stop-color: var(--svg-color--ff449d, #FF449D);
  stop-opacity: 0;
}

.tdb14gbhf {
  stop-color: var(--svg-color--df884f, #DF884F);
  stop-opacity: 0;
}

.trjwl5b7e {
  stop-color: var(--svg-color--f9b398, #F9B398);
  stop-opacity: 0;
}

.uvqus6y_e {
  stop-color: var(--svg-color--e72268, #E72268);
}

.v_rt5kb-t {
  stop-color: var(--svg-color--ff579f, #FF579F);
  stop-opacity: 0;
}

.w4-1d3eyn {
  stop-color: var(--svg-color--ff4161, #FF4161);
}

.wiifu8bvh {
  stop-color: var(--svg-color--ff579f, #FF579F);
}

.wnk2vkbkn {
  stop-color: var(--svg-color--ff4d92, #FF4D92);
}

.x-qi9vboy {
  stop-color: var(--svg-color--ffb063, #FFB063);
  stop-opacity: 0;
}

.yvlra6byh {
  d: path("M7.53 14.997v-1.453h21.433v1.453z");
}

.znv03of5i {
  stop-color: var(--svg-color--d02640, #D02640);
}

.zr6--jigs {
  stop-color: var(--svg-color--ff4d92, #FF4D92);
  stop-opacity: 0;
}

</style>
