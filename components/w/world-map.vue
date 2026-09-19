<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#ivgyYkc)"><path fill="url(#ib61ngb)" class="ihlzqs0mj"/></g><g filter="url(#izG9wUe)"><path fill="url(#iBPuDPb)" class="ihlzqs0mj"/></g><path fill="url(#ieaHMJb)" class="b3qdgackj"/><path fill="url(#im5bRcb)" class="pxt4w7b7v"/><path fill="url(#iArwuFd)" class="jyhzjdsle"/><path fill="url(#iCww5Bb)" class="k0ow-5buu"/><path fill="url(#iam9jfA)" class="ajsvnnvhp"/><g filter="url(#idZsdre)"><path class="l2k_uzhkq"/></g><g filter="url(#igDQxKc)"><path class="vhuylzb_x"/></g><defs><linearGradient id="ib61ngb" x1="29.965" x2="2.055" y1="15.479" y2="15.479" gradientUnits="userSpaceOnUse"><stop class="wf6g6bgqd"/><stop offset=".238" class="t6sx6gnap"/><stop offset=".257" class="hf9qiaccp"/><stop offset=".488" class="krai7gx9m"/><stop offset=".508" class="ag3p06bvc"/><stop offset=".741" class="yn43prbwt"/><stop offset=".76" class="wexh2ybsf"/><stop offset="1" class="nlbw0ccjg"/></linearGradient><linearGradient id="iBPuDPb" x1="13.391" x2="13.391" y1="48.485" y2="2.895" gradientUnits="userSpaceOnUse"><stop class="ed7rrnb0p"/><stop offset="1" class="d1pmhhbow"/></linearGradient><linearGradient id="ieaHMJb" x1="28.505" x2="3.496" y1="16" y2="16.121" gradientUnits="userSpaceOnUse"><stop class="ms89rn_8a"/><stop offset=".206" class="xb4lzxbxh"/><stop offset=".225" class="kuslfhw3t"/><stop offset=".485" class="gvd91wb2w"/><stop offset=".509" class="jafxawbus"/><stop offset=".764" class="lp47vzbkj"/><stop offset=".788" class="vlgf8fbci"/><stop offset="1" class="rx9fr3e3p"/></linearGradient><linearGradient id="im5bRcb" x1="14.027" x2="26.024" y1="14.99" y2="14.99" gradientUnits="userSpaceOnUse"><stop class="aedw4owlx"/><stop offset=".142" class="aedw4owlx"/><stop offset=".19" class="rb4_kr3md"/><stop offset=".717" class="f4nt2acdv"/><stop offset=".777" class="cq8-9jbee"/></linearGradient><linearGradient id="iArwuFd" x1="4.029" x2="14.027" y1="15.49" y2="15.49" gradientUnits="userSpaceOnUse"><stop class="bs3hxrb8g"/><stop offset=".481" class="bs3hxrb8g"/><stop offset=".534" class="uc8b0bc6k"/><stop offset="1" class="uc8b0bc6k"/></linearGradient><linearGradient id="iCww5Bb" x1="22.025" x2="26.024" y1="18.563" y2="18.563" gradientUnits="userSpaceOnUse"><stop class="ccw4q1bab"/><stop offset=".32" class="ccw4q1bab"/><stop offset=".441" class="i7d3kqypz"/><stop offset="1" class="tfllu3bhs"/></linearGradient><linearGradient id="iam9jfA" x1="23.025" x2="26.024" y1="21.489" y2="21.489" gradientUnits="userSpaceOnUse"><stop class="x-jf43b9k"/><stop offset=".062" class="x-jf43b9k"/><stop offset=".119" class="dbxks3bxa"/></linearGradient><filter id="ivgyYkc" width="28.16" height="25.212" x="2.055" y="3.285" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.611765 0 0 0 0 0.564706 0 0 0 0 0.635294 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_4830"/></filter><filter id="izG9wUe" width="27.91" height="25.262" x="2.055" y="3.385" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.15"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.67451 0 0 0 0 0.513726 0 0 0 0 0.784314 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_4830"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".15"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.8 0 0 0 0 0.8 0 0 0 0 0.8 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_4830" result="effect2_innerShadow_18_4830"/></filter><filter id="idZsdre" width="6.988" height="2.441" x="16.156" y="3.656" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_4830" stdDeviation=".1"/></filter><filter id="igDQxKc" width="6.7" height="2.334" x="2.422" y="3.706" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_4830" stdDeviation=".1"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:world-map" /></template>
<style>
.aedw4owlx {
  stop-color: var(--svg-color--46bf86, #46BF86);
}

.ag3p06bvc {
  stop-color: var(--svg-color--c5b9cd, #C5B9CD);
}

.ajsvnnvhp {
  d: path("M23.025 21.325v.67c0 .28.22.5.5.5h2c.28 0 .5-.22.5-.5v-.95a.56.56 0 0 0-.56-.56h-1.61c-.46 0-.83.38-.83.84");
}

.b3qdgackj {
  d: path("M4.005 6.835L8.639 5.62a1.5 1.5 0 0 1 .79.009l6.158 1.749a1.5 1.5 0 0 0 .816 0l6.227-1.753a1.5 1.5 0 0 1 .792-.006l4.573 1.215c.3.08.51.35.51.66v18.172c0 .22-.114.516-.466.422l-4.598-1.463a1.5 1.5 0 0 0-.865-.013l-6.169 1.755a1.5 1.5 0 0 1-.824-.001L9.461 24.61a1.5 1.5 0 0 0-.858.009l-4.442 1.377c-.336.082-.666-.097-.666-.547V7.495c0-.31.21-.58.51-.66");
}

.bs3hxrb8g {
  stop-color: var(--svg-color--61e7a1, #61E7A1);
}

.ccw4q1bab {
  stop-color: var(--svg-color--4ec88c, #4EC88C);
}

.cq8-9jbee {
  stop-color: var(--svg-color--43be81, #43BE81);
}

.d1pmhhbow {
  stop-color: var(--svg-color--c5b2d4, #C5B2D4);
  stop-opacity: 0;
}

.dbxks3bxa {
  stop-color: var(--svg-color--43b385, #43B385);
}

.ed7rrnb0p {
  stop-color: var(--svg-color--c5b2d4, #C5B2D4);
}

.f4nt2acdv {
  stop-color: var(--svg-color--50cc8c, #50CC8C);
}

.ft5dv1b6b {
  fill: none;
}

.gvd91wb2w {
  stop-color: var(--svg-color--49a5f1, #49A5F1);
}

.hf9qiaccp {
  stop-color: var(--svg-color--ded3e5, #DED3E5);
}

.i7d3kqypz {
  stop-color: var(--svg-color--42b483, #42B483);
}

.ihlzqs0mj {
  d: path("m2.575 5.335l6.176-1.762a1 1 0 0 1 .548 0l6.457 1.842a1 1 0 0 0 .549 0l6.445-1.842a1 1 0 0 1 .55 0l6.155 1.762c.3.08.51.35.51.66v21.82c0 .44-.42.77-.85.66l-5.79-1.883a1 1 0 0 0-.584-.01l-6.43 1.834a1 1 0 0 1-.55 0L9.318 26.57a1 1 0 0 0-.585.01l-5.829 1.896a.684.684 0 0 1-.85-.66V5.995c0-.31.22-.58.52-.66");
}

.jafxawbus {
  stop-color: var(--svg-color--2484d0, #2484D0);
}

.jyhzjdsle {
  d: path("M10.525 22.485c.28 0 .5-.22.5-.5v-1.14c0-.22.12-.42.32-.52l1.23-.62c.27-.14.45-.42.45-.72c0-.31-.17-.59-.45-.72l-1.17-.58c-.25-.13-.53-.19-.81-.19h-.44a.3.3 0 0 1-.22-.09l-1.82-1.82a.3.3 0 0 1-.09-.22v-.56c0-.17.14-.31.31-.31h.38c.17 0 .31.14.31.31v.19c0 .28.22.5.5.5s.5-.22.5-.5v-.19c0-.17.14-.31.31-.31c.44 0 .87-.18 1.18-.49l.29-.29c.12-.12.12-.32 0-.44l-.69-.69a.3.3 0 0 1-.09-.22v-.37c0-.28-.22-.5-.5-.5s-.5.22-.5.5s-.22.5-.5.5s-.5-.22-.5-.5v-.19c0-.17.14-.31.31-.31c.18 0 .32-.15.31-.32l-.02-.35c-.01-.18.13-.32.31-.32h.78c.17 0 .31-.14.31-.31v-.19c0-.28.22-.5.5-.5s.5.22.5.5v2c0 .28.22.5.5.5s.5-.22.5-.5v-.37c0-.08.03-.16.09-.22l.41-.41c.32-.32.5-.75.5-1.2c0-.72-.58-1.3-1.3-1.3h-1.6c-.7 0-1.37.29-1.85.8l-.62.67c-.31.34-.75.53-1.21.53h-.1c-.17 0-.31-.14-.31-.31c0-.38-.31-.69-.69-.69h-.62c-.38 0-.69.31-.69.69v.37c0 .6-.24 1.18-.66 1.6l-.24.24a.3.3 0 0 0-.09.22v.13c0 .28.33.41.53.22l1.26-1.26c.13-.13.31-.21.5-.21c.39 0-.29.32-.29.71v2.36c0 .6 1.24 1.17 1.66 1.59l1.25 1.25c.06.06.09.14.09.22v1.12c0 .48.19.95.53 1.29l.38.38c.06.06.09.14.09.22v1.37c-.02.25.21.47.48.47");
}

.k0ow-5buu {
  d: path("M22.025 17.795v.21c0 .31.11.61.3.85l.21.25c.3.37.79.54 1.25.43a.31.31 0 0 0 .24-.3v-.37c0-.16.12-.29.27-.31l.15-.02c.31-.03.58.21.58.52c0 .24.17.46.41.51l.22.05c.19.04.37-.1.37-.3v-.84c0-.55-.45-1-1-1h-.86c-.09 0-.17.04-.23.1l-.37.41a.31.31 0 0 1-.54-.21c0-.17-.14-.31-.31-.31h-.38c-.17.02-.31.16-.31.33");
}

.krai7gx9m {
  stop-color: var(--svg-color--ebe1f1, #EBE1F1);
}

.kuslfhw3t {
  stop-color: var(--svg-color--4190db, #4190DB);
}

.l2k_uzhkq {
  stroke: var(--svg-color--eae4ee, #EAE4EE);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("m16.432 5.822l6.437-1.891");
}

.lp47vzbkj {
  stop-color: var(--svg-color--2488d4, #2488D4);
}

.ms89rn_8a {
  stop-color: var(--svg-color--257ac5, #257AC5);
}

.nlbw0ccjg {
  stop-color: var(--svg-color--e3d7e9, #E3D7E9);
}

.pxt4w7b7v {
  d: path("m14.905 15.605l-.53.53c-.23.23-.35.53-.35.85s.13.63.35.85l.53.53a.4.4 0 0 0 .29.12h.43c.22 0 .4.18.4.4v2.19c0 .22.18.4.4.4h.43a.4.4 0 0 0 .29-.12l.41-.41c.3-.3.47-.71.47-1.14v-1.24c0-.06.01-.12.04-.18l.91-1.83c.03-.06.04-.12.04-.18v-.5c0-.22.18-.4.4-.4h.19c.22 0 .4.18.4.4v.19c0 .22.18.4.4.4h.19c.22 0 .4-.18.4-.4v-.19c0-.22.18-.4.4-.4h.19c.22 0 .4.18.4.4v.19c0 .22.18.4.4.4h1.12c.16 0 .31-.1.37-.25l.88-2.19a.4.4 0 0 0-.37-.55c-.22 0-.4-.18-.4-.4v-1.19c0-.22.18-.4.4-.4h.19c.22 0 .4.18.4.4v.1c0 .28.22.5.5.5s.5-.22.5-.5v-1.94c0-.86-.7-1.55-1.55-1.55h-.04c-.22 0-.4.18-.4.4v.19c0 .22-.18.4-.4.4h-1.19c-.22 0-.4-.18-.4-.4c0-.33-.27-.6-.6-.6h-.4c-.55 0-1 .45-1 1v.03c0 .11-.05.22-.13.3l-1.75 1.57c-.07.07-.17.1-.27.1h-1.44c-.22 0-.4.18-.4.4v.19c0 .22-.18.4-.4.4h-.19c-.22 0-.4.18-.4.4v1.19c0 .22.18.4.4.4h.19c.22 0 .4.18.4.4v.19c0 .22-.18.4-.4.4h-.43c-.09.04-.19.08-.27.15");
}

.rb4_kr3md {
  stop-color: var(--svg-color--5ce09b, #5CE09B);
}

.rx9fr3e3p {
  stop-color: var(--svg-color--4babfc, #4BABFC);
}

.t6sx6gnap {
  stop-color: var(--svg-color--c3b5cd, #C3B5CD);
}

.tfllu3bhs {
  stop-color: var(--svg-color--45b683, #45B683);
}

.uc8b0bc6k {
  stop-color: var(--svg-color--46c687, #46C687);
}

.vhuylzb_x {
  stroke: var(--svg-color--eae4ee, #EAE4EE);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("m2.697 5.766l6.15-1.785");
}

.vlgf8fbci {
  stop-color: var(--svg-color--4aa6f6, #4AA6F6);
}

.wexh2ybsf {
  stop-color: var(--svg-color--efe3f3, #EFE3F3);
}

.wf6g6bgqd {
  stop-color: var(--svg-color--bfb1ca, #BFB1CA);
}

.x-jf43b9k {
  stop-color: var(--svg-color--4bbd8e, #4BBD8E);
}

.xb4lzxbxh {
  stop-color: var(--svg-color--237bc8, #237BC8);
}

.yn43prbwt {
  stop-color: var(--svg-color--c7bcce, #C7BCCE);
}

</style>
