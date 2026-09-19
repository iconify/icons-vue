<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iTDJVMc)" class="ax0p23jlx"/><path fill="url(#i96LLLd)" class="ax0p23jlx"/><path fill="url(#il99dwb)" class="b70pu6beb"/><path fill="url(#i0krond)" class="b70pu6beb"/><rect fill="url(#i69wp6b)" class="dvvbp0b-e"/><rect fill="url(#iaRAXQk)" class="cihs65bhu"/><path fill="url(#ihLpMke)" class="cbaujwuoi"/><path fill="url(#iAuWV4d)" class="cbaujwuoi"/><path fill="url(#iN92xOd)" class="cbaujwuoi"/><g clip-rule="evenodd" filter="url(#i3fSExd)" class="d2kvgvbvc"><path fill="url(#iJRasrb)" class="ilw5-9niw"/><path fill="url(#icdbOpc)" class="ilw5-9niw"/></g><g filter="url(#iShGM4b)"><circle stroke="url(#iZG8B2c)" class="e0q9hv3xv"/></g><g filter="url(#isfeDtd)"><path class="r4fheydmg"/></g><path fill="url(#i6CJ37z)" class="y7knbxfad"/><path fill="url(#i42Qhac)" class="y7knbxfad"/><path fill="url(#iGiQApz)" class="y7knbxfad"/><path fill="url(#ilzMSve)" class="y7knbxfad"/><path fill="url(#i3p4QLd)" class="y7knbxfad"/><path fill="url(#ieuKHbe)" class="y7knbxfad"/><rect fill="url(#ifJbj7y)" class="ffusvn22m"/><rect fill="url(#inVE5qd)" class="ffusvn22m"/><rect fill="url(#iywXmWb)" class="ffusvn22m"/><rect fill="url(#iBfUUDN)" class="jcn3kzb_i"/><rect fill="url(#iZ4jLvb)" class="jcn3kzb_i"/><rect fill="url(#ixFnfXc)" class="jcn3kzb_i"/><rect fill="url(#iAF1G4b)" class="jcn3kzb_i"/><rect fill="url(#iiq8Owz)" class="y53avr0xw"/><rect fill="url(#ihEoynd)" class="y53avr0xw"/><rect fill="url(#iLlns7q)" class="y53avr0xw"/><circle fill="url(#iX6izgH)" class="uewe3cb4i"/><circle fill="url(#isHYord)" class="uewe3cb4i"/><circle fill="url(#iCPOw2Q)" class="uewe3cb4i"/><circle fill="url(#iRxbN1c)" class="si6dx8buo"/><circle fill="url(#iqgsmze)" class="si6dx8buo"/><circle fill="url(#i3YgE9d)" class="si6dx8buo"/><g filter="url(#iiHywpb)"><rect fill="url(#iQ1Czgd)" class="c1xej2b5a"/><rect fill="url(#isOUued)" class="c1xej2b5a"/></g><g filter="url(#ivyfWqd)"><path fill="url(#iXjFYGb)" class="ss7z6rb_x"/></g><defs><radialGradient id="iTDJVMc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.60938 1.375 0 14.375 29.364)" gradientUnits="userSpaceOnUse"><stop class="z10pod_vo"/><stop offset=".892" class="lqcsddcgp"/></radialGradient><radialGradient id="i96LLLd" cx="0" cy="0" r="1" gradientTransform="matrix(0 3.00781 -2.66406 0 13.867 27.552)" gradientUnits="userSpaceOnUse"><stop offset=".613" class="xbda6nmpf"/><stop offset="1" class="d4afa3raj"/></radialGradient><radialGradient id="il99dwb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.60938 1.375 0 17.219 29.364)" gradientUnits="userSpaceOnUse"><stop class="yqvvqqblc"/><stop offset=".892" class="dzqyulbzv"/></radialGradient><radialGradient id="i0krond" cx="0" cy="0" r="1" gradientTransform="matrix(0 3.00781 -2.66406 0 16.71 27.552)" gradientUnits="userSpaceOnUse"><stop offset=".613" class="xbda6nmpf"/><stop offset="1" class="d4afa3raj"/></radialGradient><radialGradient id="iN92xOd" cx="0" cy="0" r="1" gradientTransform="matrix(4.23438 0 0 1.39062 6.063 22.661)" gradientUnits="userSpaceOnUse"><stop class="d18zxh7pv"/><stop offset="1" class="x1tmhjbjd"/></radialGradient><radialGradient id="iJRasrb" cx="0" cy="0" r="1" gradientTransform="rotate(28.467 -21.231 25.283)scale(10.9488 19.636)" gradientUnits="userSpaceOnUse"><stop class="w1jt_2imm"/><stop offset="1" class="bbk6060zu"/></radialGradient><radialGradient id="icdbOpc" cx="0" cy="0" r="1" gradientTransform="matrix(-2.6875 -2.65626 1.39798 -1.41442 21.172 10.927)" gradientUnits="userSpaceOnUse"><stop class="qr2vjmbwl"/><stop offset="1" class="o613ltb1h"/></radialGradient><radialGradient id="i6CJ37z" cx="0" cy="0" r="1" gradientTransform="matrix(5.13953 4.70788 -7.85584 8.57611 17.602 2.712)" gradientUnits="userSpaceOnUse"><stop class="dk9c7xbwd"/><stop offset="1" class="d1rjm5bhm"/></radialGradient><radialGradient id="i42Qhac" cx="0" cy="0" r="1" gradientTransform="rotate(142.275 13.381 6.562)scale(6.62283 9.89663)" gradientUnits="userSpaceOnUse"><stop class="vzfdnobzy"/><stop offset="1" class="nhodafbbh"/></radialGradient><radialGradient id="ilzMSve" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.11192 -5.31497 0 24.422 3.22)" gradientUnits="userSpaceOnUse"><stop offset=".16" class="hrh81ggug"/><stop offset="1" class="vk7qt4bxa"/></radialGradient><radialGradient id="i3p4QLd" cx="0" cy="0" r="1" gradientTransform="rotate(69.179 7.224 13.745)scale(1.87693 4.06515)" gradientUnits="userSpaceOnUse"><stop offset=".284" class="p45q9rbpx"/><stop offset="1" class="i_d37i_0z"/></radialGradient><radialGradient id="iywXmWb" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.23437 -.67188 0 14.188 22.192)" gradientUnits="userSpaceOnUse"><stop offset=".154" class="d5t3omb3z"/><stop offset="1" class="fhloi5biw"/></radialGradient><radialGradient id="iAF1G4b" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.23437 -.67188 0 15.61 22.192)" gradientUnits="userSpaceOnUse"><stop offset=".154" class="d5t3omb3z"/><stop offset="1" class="fhloi5biw"/></radialGradient><radialGradient id="iLlns7q" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.23437 -.67188 0 17.031 22.192)" gradientUnits="userSpaceOnUse"><stop offset=".154" class="d5t3omb3z"/><stop offset="1" class="fhloi5biw"/></radialGradient><radialGradient id="isHYord" cx="0" cy="0" r="1" gradientTransform="matrix(-.49219 0 0 -.47656 14.36 25.974)" gradientUnits="userSpaceOnUse"><stop offset=".365" class="api3no8gv"/><stop offset="1" class="mplhlnb_w"/></radialGradient><radialGradient id="iCPOw2Q" cx="0" cy="0" r="1" gradientTransform="matrix(-.71875 0 0 -.17188 14.242 26.708)" gradientUnits="userSpaceOnUse"><stop offset=".261" class="q8ithybjt"/><stop offset="1" class="mfpu7cb_z"/></radialGradient><radialGradient id="iqgsmze" cx="0" cy="0" r="1" gradientTransform="matrix(-.49219 0 0 -.47656 17.203 25.974)" gradientUnits="userSpaceOnUse"><stop offset=".365" class="api3no8gv"/><stop offset="1" class="mplhlnb_w"/></radialGradient><radialGradient id="i3YgE9d" cx="0" cy="0" r="1" gradientTransform="matrix(-.71875 0 0 -.17188 17.086 26.708)" gradientUnits="userSpaceOnUse"><stop offset=".261" class="q8ithybjt"/><stop offset="1" class="mfpu7cb_z"/></radialGradient><radialGradient id="isOUued" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.875 -.78125 0 5.688 22.536)" gradientUnits="userSpaceOnUse"><stop class="mxr1xib8e"/><stop offset="1" class="qatfftbgu"/></radialGradient><linearGradient id="i69wp6b" x1="13.873" x2="13.873" y1="24.646" y2="25.751" gradientUnits="userSpaceOnUse"><stop class="hj38uqgsc"/><stop offset="1" class="lgixovb3w"/></linearGradient><linearGradient id="iaRAXQk" x1="16.717" x2="16.717" y1="24.646" y2="25.751" gradientUnits="userSpaceOnUse"><stop class="hj38uqgsc"/><stop offset="1" class="lgixovb3w"/></linearGradient><linearGradient id="ihLpMke" x1="9.897" x2="9.897" y1="22.052" y2="24.214" gradientUnits="userSpaceOnUse"><stop class="rj12m6bbf"/><stop offset="1" class="c48wqgbcf"/></linearGradient><linearGradient id="iAuWV4d" x1="9.897" x2="9.897" y1="24.427" y2="23.833" gradientUnits="userSpaceOnUse"><stop class="ot9w6jbjv"/><stop offset="1" class="pjv7p5bhx"/></linearGradient><linearGradient id="iZG8B2c" x1="8.703" x2="17.984" y1="19.302" y2="11.177" gradientUnits="userSpaceOnUse"><stop class="vgsof8qrz"/><stop offset=".239" class="pl6zczb5o"/><stop offset="1" class="xr9lt30fe"/></linearGradient><linearGradient id="iGiQApz" x1="20.873" x2="20.873" y1="2.712" y2="4.504" gradientUnits="userSpaceOnUse"><stop offset=".294" class="ts_s70ell"/><stop offset="1" class="jm33hibyf"/></linearGradient><linearGradient id="ieuKHbe" x1="20.873" x2="20.873" y1="2.575" y2="2.888" gradientUnits="userSpaceOnUse"><stop class="m0dpivaud"/><stop offset="1" class="z9l7jjcan"/></linearGradient><linearGradient id="ifJbj7y" x1="13.867" x2="13.867" y1="20.513" y2="24.755" gradientUnits="userSpaceOnUse"><stop class="tbr27ebag"/><stop offset="1" class="z_-z14u5s"/></linearGradient><linearGradient id="inVE5qd" x1="14.703" x2="14.219" y1="23.083" y2="23.083" gradientUnits="userSpaceOnUse"><stop offset=".452" class="q06ngzf1w"/><stop offset="1" class="o91pafsek"/></linearGradient><linearGradient id="iBfUUDN" x1="15.289" x2="15.289" y1="20.513" y2="24.755" gradientUnits="userSpaceOnUse"><stop class="tbr27ebag"/><stop offset="1" class="z_-z14u5s"/></linearGradient><linearGradient id="iZ4jLvb" x1="16.125" x2="15.641" y1="23.083" y2="23.083" gradientUnits="userSpaceOnUse"><stop offset=".452" class="q06ngzf1w"/><stop offset="1" class="o91pafsek"/></linearGradient><linearGradient id="ixFnfXc" x1="14" x2="14.938" y1="23.083" y2="23.083" gradientUnits="userSpaceOnUse"><stop offset=".452" class="q06ngzf1w"/><stop offset="1" class="o91pafsek"/></linearGradient><linearGradient id="iiq8Owz" x1="16.711" x2="16.711" y1="20.513" y2="24.755" gradientUnits="userSpaceOnUse"><stop class="tbr27ebag"/><stop offset="1" class="z_-z14u5s"/></linearGradient><linearGradient id="ihEoynd" x1="15.719" x2="16.438" y1="23.083" y2="23.083" gradientUnits="userSpaceOnUse"><stop offset=".302" class="q06ngzf1w"/><stop offset="1" class="o91pafsek"/></linearGradient><linearGradient id="iX6izgH" x1="13.867" x2="13.867" y1="25.521" y2="26.771" gradientUnits="userSpaceOnUse"><stop class="e0nfo0slh"/><stop offset="1" class="m3wetvbhw"/></linearGradient><linearGradient id="iRxbN1c" x1="16.711" x2="16.711" y1="25.521" y2="26.771" gradientUnits="userSpaceOnUse"><stop class="e0nfo0slh"/><stop offset="1" class="m3wetvbhw"/></linearGradient><linearGradient id="iQ1Czgd" x1="5.123" x2="5.123" y1="21.083" y2="25.151" gradientUnits="userSpaceOnUse"><stop class="v6zpkabsk"/><stop offset="1" class="karos6bsz"/></linearGradient><linearGradient id="iXjFYGb" x1="22.531" x2="22.531" y1="8.177" y2="15.896" gradientUnits="userSpaceOnUse"><stop offset=".765" class="p7yy0k8-f"/><stop offset="1" class="vdmdmqblj"/></linearGradient><filter id="i3fSExd" width="16.193" height="16.693" x="7.092" y="7.497" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.886275 0 0 0 0 0.498039 0 0 0 0 0.305882 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_17915"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.15"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.85098 0 0 0 0 0.486275 0 0 0 0 0.403922 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_17915" result="effect2_innerShadow_18_17915"/></filter><filter id="iShGM4b" width="15.646" height="15.646" x="7.578" y="8.177" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_17915" stdDeviation=".375"/></filter><filter id="isfeDtd" width="13.412" height="21.679" x="14.667" y="2.512" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.945098 0 0 0 0 0.619608 0 0 0 0 0.180392 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_17915"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.905882 0 0 0 0 0.541176 0 0 0 0 0.466667 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_17915" result="effect2_innerShadow_18_17915"/></filter><filter id="iiHywpb" width="1.967" height="4.614" x="4.239" y="20.537" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.25"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.827451 0 0 0 0 0.52549 0 0 0 0 0.486275 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_17915"/></filter><filter id="ivyfWqd" width="2.319" height="10.037" x="21.372" y="7.377" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_17915" stdDeviation=".4"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:postal-horn" /></template>
<style>
.api3no8gv {
  stop-color: var(--svg-color--d54a76, #D54A76);
}

.ax0p23jlx {
  d: path("M14.496 27.08a.655.655 0 0 0-1.265.027l-.538 1.988a1.203 1.203 0 1 0 2.296-.174z");
}

.b70pu6beb {
  d: path("M17.34 27.08a.655.655 0 0 0-1.265.027l-.539 1.988a1.203 1.203 0 1 0 2.296-.174z");
}

.bbk6060zu {
  stop-color: var(--svg-color--eb943b, #EB943B);
}

.c1xej2b5a {
  width: 1.767px;
  height: 4.364px;
  x: 4.239px;
  y: 20.787px;
  rx: 0.883px;
}

.c48wqgbcf {
  stop-color: var(--svg-color--db734f, #DB734F);
}

.cbaujwuoi {
  d: path("M5.649 21.655h8.497v2.559H5.649z");
}

.cihs65bhu {
  width: 0.395px;
  height: 1.496px;
  x: 16.52px;
  y: 24.255px;
  rx: 0.197px;
}

.d18zxh7pv {
  stop-color: var(--svg-color--f7a443, #F7A443);
}

.d1rjm5bhm {
  stop-color: var(--svg-color--e58940, #E58940);
  stop-opacity: 0;
}

.d2kvgvbvc {
  fill-rule: evenodd;
}

.d4afa3raj {
  stop-color: var(--svg-color--cf2a87, #CF2A87);
}

.d5t3omb3z {
  stop-color: var(--svg-color--d84e7b, #D84E7B);
}

.dk9c7xbwd {
  stop-color: var(--svg-color--e58940, #E58940);
}

.dvvbp0b-e {
  width: 0.395px;
  height: 1.496px;
  x: 13.676px;
  y: 24.255px;
  rx: 0.197px;
}

.dzqyulbzv {
  stop-color: var(--svg-color--d11967, #D11967);
}

.e0nfo0slh {
  stop-color: var(--svg-color--c91c51, #C91C51);
}

.e0q9hv3xv {
  cx: 15.401px;
  cy: 16px;
  r: 6.698px;
  stroke-width: var(--svg-stroke-width--0-75px, 0.75px);
}

.ffusvn22m {
  width: 1.422px;
  height: 4.242px;
  x: 13.156px;
  y: 20.513px;
  rx: 0.711px;
}

.fhloi5biw {
  stop-color: var(--svg-color--d84e7b, #D84E7B);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.hj38uqgsc {
  stop-color: var(--svg-color--c72a59, #C72A59);
}

.hrh81ggug {
  stop-color: var(--svg-color--ffde61, #FFDE61);
}

.i_d37i_0z {
  stop-color: var(--svg-color--d6a148, #D6A148);
  stop-opacity: 0;
}

.ilw5-9niw {
  d: path("M15.188 10.557a5.537 5.537 0 1 0 0 11.074a5.537 5.537 0 0 0 0-11.074m-8.096 5.537a8.097 8.097 0 1 1 16.193 0a8.097 8.097 0 0 1-16.193 0");
}

.jcn3kzb_i {
  width: 1.422px;
  height: 4.242px;
  x: 14.578px;
  y: 20.513px;
  rx: 0.711px;
}

.jm33hibyf {
  stop-color: var(--svg-color--ffb529, #FFB529);
  stop-opacity: 0;
}

.karos6bsz {
  stop-color: var(--svg-color--e3914a, #E3914A);
}

.lgixovb3w {
  stop-color: var(--svg-color--cc355b, #CC355B);
}

.lqcsddcgp {
  stop-color: var(--svg-color--d0395a, #D0395A);
}

.m0dpivaud {
  stop-color: var(--svg-color--deae54, #DEAE54);
}

.m3wetvbhw {
  stop-color: var(--svg-color--d2226c, #D2226C);
}

.mfpu7cb_z {
  stop-color: var(--svg-color--d63f67, #D63F67);
  stop-opacity: 0;
}

.mplhlnb_w {
  stop-color: var(--svg-color--d54a76, #D54A76);
  stop-opacity: 0;
}

.mxr1xib8e {
  stop-color: var(--svg-color--feba43, #FEBA43);
}

.nhodafbbh {
  stop-color: var(--svg-color--e1a152, #E1A152);
  stop-opacity: 0;
}

.o613ltb1h {
  stop-color: var(--svg-color--ffc252, #FFC252);
  stop-opacity: 0;
}

.o91pafsek {
  stop-color: var(--svg-color--c30354, #C30354);
  stop-opacity: 0;
}

.ot9w6jbjv {
  stop-color: var(--svg-color--d77177, #D77177);
}

.p45q9rbpx {
  stop-color: var(--svg-color--d6a148, #D6A148);
}

.p7yy0k8-f {
  stop-color: var(--svg-color--ffd452, #FFD452);
}

.pjv7p5bhx {
  stop-color: var(--svg-color--d77177, #D77177);
  stop-opacity: 0;
}

.pl6zczb5o {
  stop-color: var(--svg-color--ffd15b, #FFD15B);
  stop-opacity: 0.973;
}

.q06ngzf1w {
  stop-color: var(--svg-color--c30354, #C30354);
}

.q8ithybjt {
  stop-color: var(--svg-color--d63f67, #D63F67);
}

.qatfftbgu {
  stop-color: var(--svg-color--feba43, #FEBA43);
  stop-opacity: 0;
}

.qr2vjmbwl {
  stop-color: var(--svg-color--ffc252, #FFC252);
}

.r4fheydmg {
  fill: var(--svg-color--ffb940, #FFB940);
  d: path("M17.757 2.712a.826.826 0 0 0-.398 1.549c1.17.815 3.364 2.957 3.364 5.383h.002v6.517a5.47 5.47 0 0 1-5.47 5.47h-.588v2.56h.588a8.03 8.03 0 0 0 8.03-8.03V9.644c0-2.421 2.184-4.559 3.356-5.378a.825.825 0 0 0-.388-1.554z");
}

.rj12m6bbf {
  stop-color: var(--svg-color--e69b2c, #E69B2C);
}

.si6dx8buo {
  cx: 16.711px;
  cy: 26.046px;
  r: 0.725px;
}

.ss7z6rb_x {
  d: path("M22.172 8.177h.719v8.438h-.719z");
}

.tbr27ebag {
  stop-color: var(--svg-color--ce3057, #CE3057);
}

.ts_s70ell {
  stop-color: var(--svg-color--ffb529, #FFB529);
}

.uewe3cb4i {
  cx: 13.867px;
  cy: 26.046px;
  r: 0.725px;
}

.v6zpkabsk {
  stop-color: var(--svg-color--ebb13c, #EBB13C);
}

.vdmdmqblj {
  stop-color: var(--svg-color--ffd452, #FFD452);
  stop-opacity: 0;
}

.vgsof8qrz {
  stop-color: var(--svg-color--ffd15b, #FFD15B);
}

.vk7qt4bxa {
  stop-color: var(--svg-color--ffc433, #FFC433);
  stop-opacity: 0;
}

.vzfdnobzy {
  stop-color: var(--svg-color--e1a152, #E1A152);
}

.w1jt_2imm {
  stop-color: var(--svg-color--f4b12a, #F4B12A);
}

.x1tmhjbjd {
  stop-color: var(--svg-color--ea9223, #EA9223);
  stop-opacity: 0;
}

.xbda6nmpf {
  stop-color: var(--svg-color--cf2a87, #CF2A87);
  stop-opacity: 0;
}

.xr9lt30fe {
  stop-color: var(--svg-color--ffd15b, #FFD15B);
  stop-opacity: 0;
}

.y53avr0xw {
  width: 1.422px;
  height: 4.242px;
  x: 16px;
  y: 20.513px;
  rx: 0.711px;
}

.y7knbxfad {
  d: path("M17.757 2.712a.826.826 0 0 0-.398 1.549c1.17.815 3.364 2.957 3.364 5.383h.002v6.517a5.47 5.47 0 0 1-5.47 5.47h-.588v2.56h.588a8.03 8.03 0 0 0 8.03-8.03V9.644c0-2.421 2.184-4.559 3.356-5.378a.825.825 0 0 0-.388-1.554z");
}

.yqvvqqblc {
  stop-color: var(--svg-color--e64991, #E64991);
}

.z_-z14u5s {
  stop-color: var(--svg-color--c51776, #C51776);
}

.z10pod_vo {
  stop-color: var(--svg-color--df437f, #DF437F);
}

.z9l7jjcan {
  stop-color: var(--svg-color--deae54, #DEAE54);
  stop-opacity: 0;
}

</style>
