<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><rect transform="rotate(-45 17.969 10.906)" class="ssjlrox8h"/><rect fill="url(#iYPke4n)" transform="rotate(-45 17.969 10.906)" class="d8k-deb1f"/><rect fill="url(#inymKfe)" transform="rotate(-45 17.969 10.906)" class="d8k-deb1f"/><rect fill="url(#iJy9EQb)" transform="rotate(-45 17.969 10.906)" class="d8k-deb1f"/><rect fill="url(#iffmqIb)" transform="rotate(-45 17.969 10.906)" class="d8k-deb1f"/><g filter="url(#iyYtSQd)"><path fill="url(#iLCXDkb)" transform="rotate(45 27.856 3.919)" class="v_ohmz__l"/></g><path fill="url(#ijKGTFn)" class="atch1o9yu"/><g filter="url(#i7wKcIe)"><path class="nb_lm-4cg"/><path fill="url(#ipYop4b)" class="jwmhe_btd"/></g><g filter="url(#i2jbFjc)"><path class="hz6oeacqc"/><path fill="url(#iZU008W)" class="k_l1dmb2b"/></g><g filter="url(#iXihXZA)"><path class="rihc9ibve"/><path fill="url(#iRneocd)" class="gl_kqqbgr"/></g><path fill="url(#iUr1FSd)" class="t8oyk1b2o"/><path fill="url(#ioos6lb)" class="t8oyk1b2o"/><path fill="url(#iE9tRmO)" class="t8oyk1b2o"/><path fill="url(#iGynaUd)" class="t8oyk1b2o"/><path fill="url(#imQM1Rd)" class="t8oyk1b2o"/><g filter="url(#isROXXq)"><path fill="url(#iQn7Iwc)" class="s9ayvuo6u"/></g><path fill="url(#iMUAyTd)" class="s9ayvuo6u"/><path fill="url(#ihGoWKc)" class="s9ayvuo6u"/><g filter="url(#iwdr6td)"><rect transform="rotate(45 9.882 9.333)" class="al4pe7bes"/></g><g filter="url(#i6ITl2d)"><rect transform="rotate(45.861 7.391 17.303)" class="s-mov5b3t"/></g><g filter="url(#iYv6w4k)"><rect transform="rotate(45.861 10.794 20.833)" class="wqkigebjp"/></g><g filter="url(#iQN2BSd)"><rect transform="rotate(45.861 14.369 24.315)" class="bc6ll9b1f"/></g><defs><linearGradient id="iYPke4n" x1="27.139" x2="27.139" y1="16.143" y2="14.199" gradientUnits="userSpaceOnUse"><stop class="nmh68yz-i"/><stop offset="1" class="qnie2pb1o"/></linearGradient><linearGradient id="inymKfe" x1="26.542" x2="26.476" y1="10.508" y2="13.315" gradientUnits="userSpaceOnUse"><stop class="fjvlpbcfk"/><stop offset="1" class="sjitiy62y"/></linearGradient><linearGradient id="iJy9EQb" x1="32.265" x2="29.57" y1="13.447" y2="13.447" gradientUnits="userSpaceOnUse"><stop class="kt__1405u"/><stop offset="1" class="vjemq_cin"/></linearGradient><linearGradient id="iLCXDkb" x1="29.133" x2="29.275" y1="9.536" y2="3.497" gradientUnits="userSpaceOnUse"><stop class="uk0oujenw"/><stop offset="1" class="ut1klz98a"/></linearGradient><linearGradient id="ipYop4b" x1="2.75" x2="4.156" y1="22.75" y2="21.281" gradientUnits="userSpaceOnUse"><stop class="dpkzbnbyd"/><stop offset="1" class="myiy0ln4s"/></linearGradient><linearGradient id="iZU008W" x1="6.23" x2="7.637" y1="26.23" y2="24.762" gradientUnits="userSpaceOnUse"><stop class="dpkzbnbyd"/><stop offset="1" class="myiy0ln4s"/></linearGradient><linearGradient id="iRneocd" x1="9.687" x2="11.094" y1="29.719" y2="28.25" gradientUnits="userSpaceOnUse"><stop class="dpkzbnbyd"/><stop offset="1" class="myiy0ln4s"/></linearGradient><linearGradient id="imQM1Rd" x1="17.312" x2="18.152" y1="16.063" y2="15.219" gradientUnits="userSpaceOnUse"><stop offset=".292" class="xt9ggsumx"/><stop offset="1" class="lu2n6cbnj"/></linearGradient><linearGradient id="iQn7Iwc" x1="16.594" x2="12.156" y1="15.25" y2="19.438" gradientUnits="userSpaceOnUse"><stop class="miyj2_bix"/><stop offset="1" class="h_cqc_bac"/></linearGradient><linearGradient id="iMUAyTd" x1="18.515" x2="15.987" y1="15.936" y2="18.531" gradientUnits="userSpaceOnUse"><stop offset=".031" class="r2ahyobge"/><stop offset="1" class="n70uf6bde"/></linearGradient><linearGradient id="ihGoWKc" x1="5.841" x2="8.635" y1="8.917" y2="11.811" gradientUnits="userSpaceOnUse"><stop offset=".03" class="c3cs8dbhw"/><stop offset="1" class="kmdorcbsg"/></linearGradient><filter id="iyYtSQd" width="5.876" height="5.876" x="22.974" y="3.419" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_25869" stdDeviation=".25"/></filter><filter id="i7wKcIe" width="6.336" height="6.336" x="2.277" y="16.621" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.2 0 0 0 0 0.352941 0 0 0 0 0.858824 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_25869"/></filter><filter id="i2jbFjc" width="6.336" height="6.336" x="5.758" y="20.102" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.2 0 0 0 0 0.352941 0 0 0 0 0.858824 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_25869"/></filter><filter id="iXihXZA" width="6.336" height="6.336" x="9.215" y="23.59" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.2 0 0 0 0 0.352941 0 0 0 0 0.858824 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_25869"/></filter><filter id="isROXXq" width="18.342" height="18.842" x="6.019" y="7.737" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.552941 0 0 0 0 0.482353 0 0 0 0 0.666667 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_25869"/></filter><filter id="iwdr6td" width="16.845" height="16.845" x="7.578" y="8.166" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_25869" stdDeviation=".75"/></filter><filter id="i6ITl2d" width="5.686" height="5.594" x="2.969" y="16.77" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_25869" stdDeviation=".375"/></filter><filter id="iYv6w4k" width="5.686" height="5.594" x="6.372" y="20.301" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_25869" stdDeviation=".375"/></filter><filter id="iQN2BSd" width="5.686" height="5.594" x="9.946" y="23.782" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_25869" stdDeviation=".375"/></filter><radialGradient id="iffmqIb" cx="0" cy="0" r="1" gradientTransform="matrix(2.58536 1.10486 -.59281 1.38718 30.564 13.69)" gradientUnits="userSpaceOnUse"><stop class="fybcjlhmq"/><stop offset="1" class="tm5jv7bjm"/></radialGradient><radialGradient id="ijKGTFn" cx="0" cy="0" r="1" gradientTransform="rotate(135 10.28 9.036)scale(3.93328 2.86477)" gradientUnits="userSpaceOnUse"><stop offset=".247" class="e4kh69bzx"/><stop offset="1" class="l5f7q9bdm"/></radialGradient><radialGradient id="iUr1FSd" cx="0" cy="0" r="1" gradientTransform="rotate(135.562 8.908 10.433)scale(9.5979 10.8918)" gradientUnits="userSpaceOnUse"><stop offset=".167" class="y2863tbls"/><stop offset="1" class="p7cvtbcwg"/></radialGradient><radialGradient id="ioos6lb" cx="0" cy="0" r="1" gradientTransform="matrix(-7.75111 -7.88429 6.54322 -6.4327 20.079 15.97)" gradientUnits="userSpaceOnUse"><stop offset=".795" class="qwfi8obtf"/><stop offset="1" class="ioxwe5x6r"/></radialGradient><radialGradient id="iE9tRmO" cx="0" cy="0" r="1" gradientTransform="matrix(3.8257 12.80773 -16.42223 4.90536 19.546 8.85)" gradientUnits="userSpaceOnUse"><stop offset=".718" class="c0kjxibpc"/><stop offset=".952" class="p6fmy1b4q"/></radialGradient><radialGradient id="iGynaUd" cx="0" cy="0" r="1" gradientTransform="matrix(4.92348 -2.89036 1.97299 3.36082 19.247 14.469)" gradientUnits="userSpaceOnUse"><stop class="nw6pt4bpo"/><stop offset="1" class="tjzsambum"/></radialGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:shower" /></template>
<style>
.al4pe7bes {
  width: 18.913px;
  height: 1.609px;
  x: 9.882px;
  y: 9.333px;
  fill: var(--svg-color--dfdde1, #DFDDE1);
  rx: 0.805px;
}

.atch1o9yu {
  d: path("M19.666 9.209a2.4 2.4 0 1 0 3.395 3.395l3.037-3.038l-3.395-3.394z");
}

.bc6ll9b1f {
  width: 1.05px;
  height: 5.42px;
  x: 14.369px;
  y: 24.315px;
  fill: var(--svg-color--498cff, #498CFF);
  rx: 0.525px;
}

.c0kjxibpc {
  stop-color: var(--svg-color--aca3b7, #ACA3B7);
  stop-opacity: 0;
}

.c3cs8dbhw {
  stop-color: var(--svg-color--a6a6a7, #A6A6A7);
}

.d8k-deb1f {
  width: 13.855px;
  height: 4.801px;
  x: 17.969px;
  y: 10.906px;
  rx: 2.4px;
}

.dpkzbnbyd {
  stop-color: var(--svg-color--354fd8, #354FD8);
}

.e4kh69bzx {
  stop-color: var(--svg-color--979697, #979697);
}

.fjvlpbcfk {
  stop-color: var(--svg-color--9f9f9f, #9F9F9F);
}

.ft5dv1b6b {
  fill: none;
}

.fybcjlhmq {
  stop-color: var(--svg-color--dddcde, #DDDCDE);
}

.gl_kqqbgr {
  d: path("M9.687 29.453a1.613 1.613 0 0 1 0-2.281l3.11-3.11a1.613 1.613 0 1 1 2.281 2.282l-3.11 3.11c-.63.63-1.65.63-2.28 0");
}

.h_cqc_bac {
  stop-color: var(--svg-color--a7a0b0, #A7A0B0);
}

.hz6oeacqc {
  fill: var(--svg-color--3379ff, #3379FF);
  d: path("M6.23 25.965a1.613 1.613 0 0 1 0-2.281l3.11-3.11a1.613 1.613 0 1 1 2.281 2.281l-3.11 3.11c-.63.63-1.65.63-2.28 0");
}

.ioxwe5x6r {
  stop-color: var(--svg-color--a1a1a1, #A1A1A1);
}

.jwmhe_btd {
  d: path("M2.75 22.484a1.613 1.613 0 0 1 0-2.28l3.11-3.11a1.613 1.613 0 0 1 2.28 2.281l-3.109 3.11c-.63.63-1.651.63-2.281 0");
}

.k_l1dmb2b {
  d: path("M6.23 25.965a1.613 1.613 0 0 1 0-2.281l3.11-3.11a1.613 1.613 0 1 1 2.281 2.281l-3.11 3.11c-.63.63-1.65.63-2.28 0");
}

.kmdorcbsg {
  stop-color: var(--svg-color--a6a6a7, #A6A6A7);
  stop-opacity: 0;
}

.kt__1405u {
  stop-color: var(--svg-color--ccc, #CCC);
}

.l5f7q9bdm {
  stop-color: var(--svg-color--7b7581, #7B7581);
}

.lu2n6cbnj {
  stop-color: var(--svg-color--b5b5b5, #B5B5B5);
  stop-opacity: 0;
}

.miyj2_bix {
  stop-color: var(--svg-color--cecece, #CECECE);
}

.myiy0ln4s {
  stop-color: var(--svg-color--354fd8, #354FD8);
  stop-opacity: 0;
}

.n70uf6bde {
  stop-color: var(--svg-color--c1bec4, #C1BEC4);
  stop-opacity: 0;
}

.nb_lm-4cg {
  fill: var(--svg-color--3379ff, #3379FF);
  d: path("M2.75 22.484a1.613 1.613 0 0 1 0-2.28l3.11-3.11a1.613 1.613 0 0 1 2.28 2.281l-3.109 3.11c-.63.63-1.651.63-2.281 0");
}

.nmh68yz-i {
  stop-color: var(--svg-color--a6a1ad, #A6A1AD);
}

.nw6pt4bpo {
  stop-color: var(--svg-color--e0dfe1, #E0DFE1);
}

.p6fmy1b4q {
  stop-color: var(--svg-color--aca3b7, #ACA3B7);
}

.p7cvtbcwg {
  stop-color: var(--svg-color--aeaeae, #AEAEAE);
}

.qnie2pb1o {
  stop-color: var(--svg-color--bbb7c0, #BBB7C0);
  stop-opacity: 0;
}

.qwfi8obtf {
  stop-color: var(--svg-color--b0b0b0, #B0B0B0);
  stop-opacity: 0;
}

.r2ahyobge {
  stop-color: var(--svg-color--d3d2d3, #D3D2D3);
}

.rihc9ibve {
  fill: var(--svg-color--3379ff, #3379FF);
  d: path("M9.687 29.453a1.613 1.613 0 0 1 0-2.281l3.11-3.11a1.613 1.613 0 1 1 2.281 2.282l-3.11 3.11c-.63.63-1.65.63-2.28 0");
}

.s-mov5b3t {
  width: 1.05px;
  height: 5.42px;
  x: 7.391px;
  y: 17.303px;
  fill: var(--svg-color--498cff, #498CFF);
  rx: 0.525px;
}

.s9ayvuo6u {
  d: path("M6.957 9.176a3.204 3.204 0 0 1 4.532 0l11.933 11.933a3.204 3.204 0 1 1-4.532 4.531L6.957 13.707a3.204 3.204 0 0 1 0-4.531");
}

.sjitiy62y {
  stop-color: var(--svg-color--b4b3b5, #B4B3B5);
  stop-opacity: 0;
}

.ssjlrox8h {
  width: 13.855px;
  height: 4.801px;
  x: 17.969px;
  y: 10.906px;
  fill: var(--svg-color--c8c7c8, #C8C7C8);
  rx: 2.4px;
}

.t8oyk1b2o {
  d: path("M23.425 21.112A8.734 8.734 0 0 0 11.091 8.778l-.443.398L22.031 22.39z");
}

.tjzsambum {
  stop-color: var(--svg-color--e0dfe1, #E0DFE1);
  stop-opacity: 0;
}

.tm5jv7bjm {
  stop-color: var(--svg-color--cccbcc, #CCCBCC);
  stop-opacity: 0;
}

.uk0oujenw {
  stop-color: var(--svg-color--cfcfcf, #CFCFCF);
}

.ut1klz98a {
  stop-color: var(--svg-color--cfcfcf, #CFCFCF);
  stop-opacity: 0;
}

.v_ohmz__l {
  d: path("M27.856 3.919h.699v6.197h-.699z");
}

.vjemq_cin {
  stop-color: var(--svg-color--ccc, #CCC);
  stop-opacity: 0;
}

.wqkigebjp {
  width: 1.05px;
  height: 5.42px;
  x: 10.794px;
  y: 20.833px;
  fill: var(--svg-color--498cff, #498CFF);
  rx: 0.525px;
}

.xt9ggsumx {
  stop-color: var(--svg-color--b5b5b5, #B5B5B5);
}

.y2863tbls {
  stop-color: var(--svg-color--d6d6d7, #D6D6D7);
}

</style>
