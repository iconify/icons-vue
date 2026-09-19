<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#ik9o6Ph)"><path stroke="url(#iiw9xec)" class="uhbhukbkz"/><path stroke="url(#imZTwqe)" class="uhbhukbkz"/><path fill="url(#iuezoob)" class="zannmacjr"/><path fill="url(#iE8QcEd)" class="zannmacjr"/><path fill="url(#ivEnSkc)" class="zannmacjr"/><path fill="url(#iWiImqb)" class="maobbcvxh"/><path fill="url(#ibBjvec)" class="zannmacjr"/><path fill="url(#ipSnfmL)" class="zannmacjr"/><path fill="url(#ilqJk5c)" class="zannmacjr"/><path fill="url(#i6j9Pab)" class="zannmacjr"/><g filter="url(#iK0QbPe)" class="mc2zb0bvp"><path class="m37yj46mo"/></g><g filter="url(#iNhejlb)" class="mc2zb0bvp"><path class="my6_9i-8p"/></g><path class="h_dza0b0h"/><g filter="url(#iWdjYfc)" class="qfgt6tb2e"><path class="txbfq0sbl"/></g><path class="tcrp4vblf"/><g filter="url(#icBF2Ee)" class="qfgt6tb2e"><path class="etqf_4fbs"/></g><path stroke="url(#iatMmub)" class="nfmntmf-p"/><path fill="url(#iGWcxve)" clip-rule="evenodd" class="qgne59bev"/><path fill="url(#i2klytr)" clip-rule="evenodd" class="o7pg5ob8v"/><path fill="url(#i4tPMie)" clip-rule="evenodd" class="o7pg5ob8v"/></g><defs><radialGradient id="imZTwqe" cx="0" cy="0" r="1" gradientTransform="rotate(-105.945 7.579 .167)scale(7.28011 11.995)" gradientUnits="userSpaceOnUse"><stop offset=".482" class="u_qh28yjw"/><stop offset=".735" class="jqsfp_b9j"/><stop offset=".988" class="vmr2y_bes"/></radialGradient><radialGradient id="iuezoob" cx="0" cy="0" r="1" gradientTransform="rotate(132.839 10.786 10.065)scale(37.5033)" gradientUnits="userSpaceOnUse"><stop class="qvxe_pbez"/><stop offset=".475" class="cjd26qb7f"/><stop offset="1" class="h13dd1l8r"/></radialGradient><radialGradient id="iE8QcEd" cx="0" cy="0" r="1" gradientTransform="rotate(131.878 10.74 10.193)scale(38.9487)" gradientUnits="userSpaceOnUse"><stop class="qvxe_pbez"/><stop offset=".475" class="cjd26qb7f"/><stop offset="1" class="h13dd1l8r"/></radialGradient><radialGradient id="ivEnSkc" cx="0" cy="0" r="1" gradientTransform="rotate(101.31 2.876 12.808)scale(17.8466 22.8581)" gradientUnits="userSpaceOnUse"><stop offset=".788" class="og2_-db3e"/><stop offset=".973" class="w5xp9scuu"/></radialGradient><radialGradient id="iWiImqb" cx="0" cy="0" r="1" gradientTransform="matrix(-29 29 -29 -29 18 14)" gradientUnits="userSpaceOnUse"><stop offset=".315" class="k05n1gbkm"/><stop offset="1"/></radialGradient><radialGradient id="ibBjvec" cx="0" cy="0" r="1" gradientTransform="rotate(77.692 -2.555 18.434)scale(28.1469)" gradientUnits="userSpaceOnUse"><stop offset=".508" class="zgcpgx8ap"/><stop offset="1" class="fqgjm_v0b"/></radialGradient><radialGradient id="ipSnfmL" cx="0" cy="0" r="1" gradientTransform="matrix(7.5 10.99996 -7.97335 5.4364 16.5 16.5)" gradientUnits="userSpaceOnUse"><stop class="g4z4xncfo"/><stop offset="1" class="k7y-44b1u"/></radialGradient><radialGradient id="ilqJk5c" cx="0" cy="0" r="1" gradientTransform="matrix(11.49998 2 -2 11.49998 20.5 18)" gradientUnits="userSpaceOnUse"><stop class="c1buurbbt"/><stop offset=".9" class="mqe6vbive"/></radialGradient><radialGradient id="i6j9Pab" cx="0" cy="0" r="1" gradientTransform="rotate(43.971 -9.827 29.173)scale(59.0529)" gradientUnits="userSpaceOnUse"><stop offset=".185" class="k05n1gbkm"/><stop offset="1" class="rw5c_lizo"/></radialGradient><radialGradient id="iatMmub" cx="0" cy="0" r="1" gradientTransform="matrix(0 10.5 -6.42871 0 16 15)" gradientUnits="userSpaceOnUse"><stop offset=".556" class="d843lbc8v"/><stop offset=".74" class="dycszlbfj"/><stop offset="1" class="opsjn_43s"/><stop offset="1" class="hspwlpt0m"/></radialGradient><radialGradient id="iGWcxve" cx="0" cy="0" r="1" gradientTransform="matrix(0 3.5 -19.4266 0 14.5 6.5)" gradientUnits="userSpaceOnUse"><stop class="d3wf5jb8r"/><stop offset="1" class="fqac_w1ss"/></radialGradient><radialGradient id="i2klytr" cx="0" cy="0" r="1" gradientTransform="matrix(0 33 -38.8902 0 16.5 -23)" gradientUnits="userSpaceOnUse"><stop offset=".843" class="fi04u18ez"/><stop offset=".898" class="ex5w2u-ri"/><stop offset=".958" class="yj44frptj"/></radialGradient><radialGradient id="i4tPMie" cx="0" cy="0" r="1" gradientTransform="matrix(14 0 0 16.4989 6.5 3.5)" gradientUnits="userSpaceOnUse"><stop class="vl3pcabcm"/><stop offset="1" class="fmpd25b6q"/></radialGradient><filter id="iK0QbPe" width="10" height="7" x="5" y="10" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_23_441" stdDeviation=".75"/></filter><filter id="iNhejlb" width="10.001" height="7" x="16" y="10" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_23_441" stdDeviation=".75"/></filter><filter id="iWdjYfc" width="8.75" height="5.75" x="6.375" y="9.875" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_23_441" stdDeviation=".75"/></filter><filter id="icBF2Ee" width="8.75" height="5.75" x="17.375" y="9.875" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_23_441" stdDeviation=".75"/></filter><linearGradient id="iiw9xec" x1="16" x2="16" y1="1" y2="4.5" gradientUnits="userSpaceOnUse"><stop class="odfe3h_ck"/><stop offset="1" class="hdwlm8q1h"/></linearGradient><clipPath id="ik9o6Ph"><path class="wycjhibbk"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:smiling-face-with-halo" /></template>
<style>
.c1buurbbt {
  stop-color: var(--svg-color--ffa64b, #FFA64B);
}

.cjd26qb7f {
  stop-color: var(--svg-color--ffb02e, #FFB02E);
}

.d3wf5jb8r {
  stop-color: var(--svg-color--392108, #392108);
}

.d843lbc8v {
  stop-color: var(--svg-color--584343, #584343);
}

.dycszlbfj {
  stop-color: var(--svg-color--66525e, #66525E);
}

.etqf_4fbs {
  stroke: var(--svg-color--fff, #fff);
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--0-75px, 0.75px);
  d: path("M19.25 13.75s.25-2 2.5-2s2.5 2 2.5 2");
}

.ex5w2u-ri {
  stop-color: var(--svg-color--508fff, #508FFF);
}

.fi04u18ez {
  stop-color: var(--svg-color--425bff, #425BFF);
}

.fmpd25b6q {
  stop-color: var(--svg-color--4457ff, #4457FF);
  stop-opacity: 0;
}

.fqac_w1ss {
  stop-color: var(--svg-color--c87928, #C87928);
  stop-opacity: 0;
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

.h_dza0b0h {
  stroke: var(--svg-color--43273b, #43273B);
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M8 14s.25-2 2.5-2s2.5 2 2.5 2");
}

.h13dd1l8r {
  stop-color: var(--svg-color--f70a8d, #F70A8D);
}

.hdwlm8q1h {
  stop-color: var(--svg-color--3a54e1, #3A54E1);
}

.hspwlpt0m {
  stop-color: var(--svg-color--522c57, #522C57);
}

.jqsfp_b9j {
  stop-color: var(--svg-color--5292ff, #5292FF);
}

.k05n1gbkm {
  stop-opacity: 0;
}

.k7y-44b1u {
  stop-color: var(--svg-color--ffb847, #FFB847);
  stop-opacity: 0;
}

.m37yj46mo {
  stroke: var(--svg-color--9a4609, #9A4609);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M7.5 14.5s.25-2 2.5-2s2.5 2 2.5 2");
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

.my6_9i-8p {
  stroke: var(--svg-color--9a4609, #9A4609);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M18.5 14.5s.5-2 2.5-2s2.5 2 2.5 2");
}

.nfmntmf-p {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 19c0 1.333.8 4 4 4s4-2.667 4-4");
}

.o7pg5ob8v {
  fill-rule: evenodd;
  d: path("M3.123 3.295C3.853 4.187 7.6 5 8.5 5h.071c1.981.308 4.57.5 7.429.5c2.922 0 5.563-.2 7.56-.52C24.93 4.83 28.5 3.915 28.5 3v-.029q.141.102.27.22c.326.298.73.821.73 1.559s-.404 1.26-.73 1.56c-.33.3-.73.52-1.105.687c-.762.338-1.772.606-2.903.818c-2.288.43-5.385.685-8.762.685s-6.474-.256-8.762-.685c-1.131-.212-2.14-.48-2.903-.818c-.376-.167-.776-.386-1.105-.688c-.325-.298-.73-.821-.73-1.559c0-.659.322-1.146.623-1.455");
}

.odfe3h_ck {
  stop-color: var(--svg-color--3173ec, #3173EC);
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

.qgne59bev {
  fill-rule: evenodd;
  d: path("M3.585 8.873c.184.157.373.292.55.405c.789.506 1.832.905 2.988 1.218c2.332.632 5.47 1.004 8.877 1.004s6.545-.372 8.878-1.004c1.155-.313 2.198-.712 2.988-1.218c.176-.113.364-.247.547-.404a12.1 12.1 0 0 0-2.526-3.39c-.633.183-1.274.328-1.789.417c1.014.275 1.726.576 2.15.847l.003.002l-.003.002c-.425.272-1.139.573-2.155.848c-2.01.545-4.872.9-8.093.9s-6.082-.355-8.093-.9c-1.016-.275-1.73-.576-2.155-.848l-.003-.002l.003-.002c.41-.262 1.088-.551 2.047-.819a18 18 0 0 1-1.767-.37a12.1 12.1 0 0 0-2.447 3.314M5.441 7l.009-.012zm21.118 0l-.008-.012zm-.008-.486l.009-.012l-.01.012m-21.101 0l-.01-.012q.002 0 .01.012");
}

.qvxe_pbez {
  stop-color: var(--svg-color--fff478, #FFF478);
}

.rw5c_lizo {
  stop-opacity: 0.4;
}

.tcrp4vblf {
  stroke: var(--svg-color--43273b, #43273B);
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M19 14s.5-2 2.5-2s2.5 2 2.5 2");
}

.txbfq0sbl {
  stroke: var(--svg-color--fff, #fff);
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--0-75px, 0.75px);
  d: path("M8.25 13.75s.25-2 2.5-2s2.5 2 2.5 2");
}

.u_qh28yjw {
  stop-color: var(--svg-color--5468db, #5468DB);
}

.uhbhukbkz {
  stroke-miterlimit: 10;
  stroke-width: var(--svg-stroke-width--3px, 3px);
  d: path("M16 7c6.627 0 12-1.007 12-2.25S22.627 2.5 16 2.5S4 3.507 4 4.75S9.373 7 16 7Z");
}

.vl3pcabcm {
  stop-color: var(--svg-color--5664d2, #5664D2);
}

.vmr2y_bes {
  stop-color: var(--svg-color--486fff, #486FFF);
  stop-opacity: 0;
}

.w5xp9scuu {
  stop-color: var(--svg-color--ff7dce, #FF7DCE);
}

.wycjhibbk {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h32v32H0z");
}

.yj44frptj {
  stop-color: var(--svg-color--4457ff, #4457FF);
}

.zannmacjr {
  d: path("M15.999 29.998c9.334 0 13.999-6.268 13.999-14c0-7.73-4.665-13.998-14-13.998C6.665 2 2 8.268 2 15.999s4.664 13.999 13.999 13.999");
}

.zgcpgx8ap {
  stop-color: var(--svg-color--7d6133, #7D6133);
  stop-opacity: 0;
}

</style>
