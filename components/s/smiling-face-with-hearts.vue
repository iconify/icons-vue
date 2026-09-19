<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#ik9o6Ph)"><path fill="url(#iuezoob)" class="zannmacjr"/><path fill="url(#iE8QcEd)" class="zannmacjr"/><path fill="url(#ivEnSkc)" class="zannmacjr"/><path fill="url(#iWiImqb)" class="maobbcvxh"/><path fill="url(#ibBjvec)" class="zannmacjr"/><path fill="url(#ipSnfmL)" class="zannmacjr"/><path fill="url(#ilqJk5c)" class="zannmacjr"/><path fill="url(#i6j9Pab)" class="zannmacjr"/><path fill="url(#i3rRTnc)" class="qsiojnk9o"/><g filter="url(#ioH4HSv)" class="mc2zb0bvp"><path class="bo-hfpbkv"/></g><g filter="url(#ijfkAyc)" class="mc2zb0bvp"><path class="a79h18b3f"/></g><path class="kj167yb9b"/><g filter="url(#imzkHoe)" class="qfgt6tb2e"><path class="ca3x0hbrn"/></g><path class="ij5txvb3z"/><g filter="url(#i7jrvPc)" class="qfgt6tb2e"><path class="ti57i9b9x"/></g><path fill="url(#iu1OEMe)" class="ue7bszbtt"/><g filter="url(#itKZQzS)"><path class="v9q47-b0h"/></g><path fill="url(#iTjEujd)" class="bedqvbceq"/><path stroke="url(#iilSCJF)" class="jtgxwjbfa"/><g filter="url(#ipMIRze)" class="nctb2ac4r"><path class="t2mf32o-i"/></g><g filter="url(#irxXXhd)" class="nctb2ac4r"><path class="tw____1_c"/></g><g filter="url(#imTeMfe)"><circle class="cehiffbtf"/></g><g filter="url(#iVIYE6c)" class="z4n2hhy8u"><path class="jpaszwp2x"/></g><g filter="url(#ieRkkOc)"><path class="t6dt6vn2s"/></g><g filter="url(#iEfqWwe)"><path class="t16ln8bhn"/></g></g><defs><filter id="ioH4HSv" width="10" height="7" x="5" y="7" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20_194" stdDeviation=".75"/></filter><filter id="ijfkAyc" width="10.001" height="7" x="16" y="7" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20_194" stdDeviation=".75"/></filter><filter id="imzkHoe" width="8.75" height="5.75" x="6.375" y="6.875" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20_194" stdDeviation=".75"/></filter><filter id="i7jrvPc" width="8.75" height="5.75" x="17.375" y="6.875" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20_194" stdDeviation=".75"/></filter><filter id="itKZQzS" width="12.653" height="12.707" x="17.373" y="15.994" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20_194" stdDeviation="1"/></filter><filter id="ipMIRze" width="7.207" height="7.207" x="4.646" y=".146" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20_194" stdDeviation="1"/></filter><filter id="irxXXhd" width="9.274" height="8.111" x="22.616" y="16.18" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20_194" stdDeviation="1"/></filter><filter id="imTeMfe" width="6" height="6" x="5.5" y="21.5" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20_194" stdDeviation="1"/></filter><filter id="iVIYE6c" width="5.338" height="6.288" x="5.581" y="24.606" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20_194" stdDeviation=".5"/></filter><filter id="ieRkkOc" width="8.29" height="9.114" x="20.605" y="17.693" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20_194" stdDeviation="1"/></filter><filter id="iEfqWwe" width="7.207" height="7.207" x="3.146" y="3.646" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20_194" stdDeviation="1"/></filter><radialGradient id="iuezoob" cx="0" cy="0" r="1" gradientTransform="rotate(132.839 10.786 10.065)scale(37.5033)" gradientUnits="userSpaceOnUse"><stop class="qvxe_pbez"/><stop offset=".475" class="cjd26qb7f"/><stop offset="1" class="h13dd1l8r"/></radialGradient><radialGradient id="iE8QcEd" cx="0" cy="0" r="1" gradientTransform="rotate(131.878 10.74 10.193)scale(38.9487)" gradientUnits="userSpaceOnUse"><stop class="qvxe_pbez"/><stop offset=".475" class="cjd26qb7f"/><stop offset="1" class="h13dd1l8r"/></radialGradient><radialGradient id="ivEnSkc" cx="0" cy="0" r="1" gradientTransform="rotate(101.31 2.876 12.808)scale(17.8466 22.8581)" gradientUnits="userSpaceOnUse"><stop offset=".788" class="og2_-db3e"/><stop offset=".973" class="w5xp9scuu"/></radialGradient><radialGradient id="iWiImqb" cx="0" cy="0" r="1" gradientTransform="matrix(-29 29 -29 -29 18 14)" gradientUnits="userSpaceOnUse"><stop offset=".315" class="k05n1gbkm"/><stop offset="1"/></radialGradient><radialGradient id="ibBjvec" cx="0" cy="0" r="1" gradientTransform="rotate(77.692 -2.555 18.434)scale(28.1469)" gradientUnits="userSpaceOnUse"><stop offset=".508" class="zgcpgx8ap"/><stop offset="1" class="fqgjm_v0b"/></radialGradient><radialGradient id="ipSnfmL" cx="0" cy="0" r="1" gradientTransform="matrix(7.5 10.99996 -7.97335 5.4364 16.5 16.5)" gradientUnits="userSpaceOnUse"><stop class="g4z4xncfo"/><stop offset="1" class="k7y-44b1u"/></radialGradient><radialGradient id="ilqJk5c" cx="0" cy="0" r="1" gradientTransform="matrix(11.49998 2 -2 11.49998 20.5 18)" gradientUnits="userSpaceOnUse"><stop class="c1buurbbt"/><stop offset=".9" class="mqe6vbive"/></radialGradient><radialGradient id="i6j9Pab" cx="0" cy="0" r="1" gradientTransform="rotate(43.971 -9.827 29.173)scale(59.0529)" gradientUnits="userSpaceOnUse"><stop offset=".185" class="k05n1gbkm"/><stop offset="1" class="rw5c_lizo"/></radialGradient><radialGradient id="iilSCJF" cx="0" cy="0" r="1" gradientTransform="matrix(0 10.5 -6.42871 0 16 12)" gradientUnits="userSpaceOnUse"><stop offset=".556" class="d843lbc8v"/><stop offset=".74" class="dycszlbfj"/><stop offset="1" class="opsjn_43s"/><stop offset="1" class="hspwlpt0m"/></radialGradient><linearGradient id="i3rRTnc" x1="4.5" x2="8.136" y1="3.5" y2="8.277" gradientUnits="userSpaceOnUse"><stop class="sc-l0hbrp"/><stop offset="1" class="h13dd1l8r"/></linearGradient><linearGradient id="iu1OEMe" x1="6" x2="9.342" y1="24.5" y2="29.907" gradientUnits="userSpaceOnUse"><stop class="u1fm6pgvn"/><stop offset="1" class="h13dd1l8r"/></linearGradient><linearGradient id="iTjEujd" x1="29.099" x2="25.876" y1="18.037" y2="25.428" gradientUnits="userSpaceOnUse"><stop class="u1fm6pgvn"/><stop offset="1" class="h13dd1l8r"/></linearGradient><clipPath id="ik9o6Ph"><path class="wycjhibbk"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:smiling-face-with-hearts" /></template>
<style>
.a79h18b3f {
  stroke: var(--svg-color--9a4609, #9A4609);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M18.5 11.5s.5-2 2.5-2s2.5 2 2.5 2");
}

.bedqvbceq {
  d: path("M23 17.1c1.5-.5 3.167.9 3.5 1.4c.167-.5.9-1.5 2.5-1.5c2 0 2.557 2.107 2 3.5c-.73 1.826-3.06 4.136-4.264 5.25a.956.956 0 0 1-1.381-.09c-.963-1.126-2.73-3.222-3.355-4.16c-1-1.5-.897-3.767 1-4.4");
}

.bo-hfpbkv {
  stroke: var(--svg-color--9a4609, #9A4609);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M7.5 11.5s.25-2 2.5-2s2.5 2 2.5 2");
}

.c1buurbbt {
  stop-color: var(--svg-color--ffa64b, #FFA64B);
}

.ca3x0hbrn {
  stroke: var(--svg-color--fff, #fff);
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--0-75px, 0.75px);
  d: path("M8.25 10.75s.25-2 2.5-2s2.5 2 2.5 2");
}

.cehiffbtf {
  cx: 8.5px;
  cy: 24.5px;
  r: 1px;
  fill: var(--svg-color--fff, #fff);
}

.cjd26qb7f {
  stop-color: var(--svg-color--ffb02e, #FFB02E);
}

.d843lbc8v {
  stop-color: var(--svg-color--584343, #584343);
}

.dycszlbfj {
  stop-color: var(--svg-color--66525e, #66525E);
}

.fqgjm_v0b {
  stop-color: var(--svg-color--715b32, #715B32);
}

.ft5dv1b6b {
  fill: none;
}

.g4z4xncfo {
  stop-color: var(--svg-color--ffb849, #FFB849);
}

.h13dd1l8r {
  stop-color: var(--svg-color--f70a8d, #F70A8D);
}

.hspwlpt0m {
  stop-color: var(--svg-color--522c57, #522C57);
}

.ij5txvb3z {
  stroke: var(--svg-color--43273b, #43273B);
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M19 11s.5-2 2.5-2s2.5 2 2.5 2");
}

.jpaszwp2x {
  stroke: var(--svg-color--f944a5, #F944A5);
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M7.5 29.5L9 26");
}

.jtgxwjbfa {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 16c0 1.333.8 4 4 4s4-2.667 4-4");
}

.k05n1gbkm {
  stop-opacity: 0;
}

.k7y-44b1u {
  stop-color: var(--svg-color--ffb847, #FFB847);
  stop-opacity: 0;
}

.kj167yb9b {
  stroke: var(--svg-color--43273b, #43273B);
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M8 11s.25-2 2.5-2s2.5 2 2.5 2");
}

.maobbcvxh {
  fill-opacity: var(--svg-fill-opacity--0-6, 0.6);
  d: path("M15.999 29.998c9.334 0 13.999-6.268 13.999-14c0-7.73-4.665-13.998-14-13.998C6.665 2 2 8.268 2 15.999s4.664 13.999 13.999 13.999");
}

.mc2zb0bvp {
  opacity: var(--svg-opacity--0-5, 0.5);
}

.mqe6vbive {
  stop-color: var(--svg-color--ffae46, #FFAE46);
  stop-opacity: 0;
}

.nctb2ac4r {
  opacity: var(--svg-opacity--0-8, 0.8);
}

.og2_-db3e {
  stop-color: var(--svg-color--f59639, #F59639);
  stop-opacity: 0;
}

.opsjn_43s {
  stop-color: var(--svg-color--4e2553, #4E2553);
}

.qfgt6tb2e {
  opacity: var(--svg-opacity--0-26, 0.26);
}

.qsiojnk9o {
  d: path("M3 1.1c1.213-.36 2.5.4 3 .9c.5-.5 2.168-1.832 3.75-.25C11.025 3.025 10.5 5 9.5 6.5c-.589.883-2.116 2.272-3.347 3.21c-.644.49-1.54.345-2.086-.253C3.143 8.444 1.973 7.145 1.4 6c-1-2 0-4.425 1.6-4.9");
}

.qvxe_pbez {
  stop-color: var(--svg-color--fff478, #FFF478);
}

.rw5c_lizo {
  stop-opacity: 0.4;
}

.sc-l0hbrp {
  stop-color: var(--svg-color--dc2e50, #DC2E50);
}

.t16ln8bhn {
  stroke: var(--svg-color--f944a5, #F944A5);
  d: path("M5.5 8.5L8 6");
}

.t2mf32o-i {
  stroke: var(--svg-color--fff, #fff);
  d: path("M9.5 2.5L7 5");
}

.t6dt6vn2s {
  stroke: var(--svg-color--f944a5, #F944A5);
  d: path("M26.5 24.5L23 20");
}

.ti57i9b9x {
  stroke: var(--svg-color--fff, #fff);
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--0-75px, 0.75px);
  d: path("M19.25 10.75s.25-2 2.5-2s2.5 2 2.5 2");
}

.tw____1_c {
  stroke: var(--svg-color--fff, #fff);
  d: path("m25 18.5l2.5 3l2-2.5");
}

.u1fm6pgvn {
  stop-color: var(--svg-color--ca0b4a, #CA0B4A);
}

.ue7bszbtt {
  d: path("M4 28c-1.118-1.118-1.5-3-.5-4s3-.5 3-.5s.5-1.25 2-1c2 .25 2.25 2.5 1.75 4c-.382 1.146-1.307 2.369-1.98 3.156c-.431.506-1.167.58-1.717.204C5.628 29.23 4.316 28.316 4 28");
}

.v9q47-b0h {
  fill: var(--svg-color--e4694e, #E4694E);
  d: path("M21 18.1c1.5-.5 3.167.9 3.5 1.4c.167-.5.9-1.5 2.5-1.5c2 0 .557 2.107 0 3.5c-.625 1.562-1.64 3.48-2.314 4.698a.97.97 0 0 1-1.592.156C22.1 25.187 20.572 23.358 20 22.5c-1-1.5-.897-3.767 1-4.4");
}

.w5xp9scuu {
  stop-color: var(--svg-color--ff7dce, #FF7DCE);
}

.wycjhibbk {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h32v32H0z");
}

.z4n2hhy8u {
  opacity: var(--svg-opacity--0-6, 0.6);
}

.zannmacjr {
  d: path("M15.999 29.998c9.334 0 13.999-6.268 13.999-14c0-7.73-4.665-13.998-14-13.998C6.665 2 2 8.268 2 15.999s4.664 13.999 13.999 13.999");
}

.zgcpgx8ap {
  stop-color: var(--svg-color--7d6133, #7D6133);
  stop-opacity: 0;
}

</style>
