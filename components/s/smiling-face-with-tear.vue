<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iuezoob)" class="zannmacjr"/><path fill="url(#iE8QcEd)" class="zannmacjr"/><path fill="url(#ivEnSkc)" class="zannmacjr"/><path fill="url(#iWiImqb)" class="maobbcvxh"/><path fill="url(#ibBjvec)" class="zannmacjr"/><path fill="url(#ipSnfmL)" class="zannmacjr"/><path fill="url(#ilqJk5c)" class="zannmacjr"/><path fill="url(#i6j9Pab)" class="zannmacjr"/><path fill="url(#isBWaZN)" class="zannmacjr"/><path fill="url(#iHqNsXd)" class="zannmacjr"/><path fill="url(#iPJHUOb)" class="zannmacjr"/><path fill="url(#igiKuOd)" class="zannmacjr"/><path fill="url(#inFaS5J)" class="zannmacjr"/><path class="z486gib-c"/><path fill="url(#ircvEob)" class="jo4k7lbns"/><path fill="url(#ircvEob)" class="fi3ygubsr"/><path fill="url(#ifVhWsc)" clip-rule="evenodd" class="a4iah7r8b"/><path fill="url(#iDUDAhe)" class="ut47l53gt"/><defs><radialGradient id="iuezoob" cx="0" cy="0" r="1" gradientTransform="rotate(132.839 10.786 10.065)scale(37.5033)" gradientUnits="userSpaceOnUse"><stop class="qvxe_pbez"/><stop offset=".475" class="cjd26qb7f"/><stop offset="1" class="h13dd1l8r"/></radialGradient><radialGradient id="iE8QcEd" cx="0" cy="0" r="1" gradientTransform="rotate(131.878 10.74 10.193)scale(38.9487)" gradientUnits="userSpaceOnUse"><stop class="qvxe_pbez"/><stop offset=".475" class="cjd26qb7f"/><stop offset="1" class="h13dd1l8r"/></radialGradient><radialGradient id="ivEnSkc" cx="0" cy="0" r="1" gradientTransform="rotate(101.31 2.876 12.808)scale(17.8466 22.8581)" gradientUnits="userSpaceOnUse"><stop offset=".788" class="og2_-db3e"/><stop offset=".973" class="w5xp9scuu"/></radialGradient><radialGradient id="iWiImqb" cx="0" cy="0" r="1" gradientTransform="matrix(-29 29 -29 -29 18 14)" gradientUnits="userSpaceOnUse"><stop offset=".315" class="k05n1gbkm"/><stop offset="1"/></radialGradient><radialGradient id="ibBjvec" cx="0" cy="0" r="1" gradientTransform="rotate(77.692 -2.555 18.434)scale(28.1469)" gradientUnits="userSpaceOnUse"><stop offset=".508" class="zgcpgx8ap"/><stop offset="1" class="fqgjm_v0b"/></radialGradient><radialGradient id="ipSnfmL" cx="0" cy="0" r="1" gradientTransform="matrix(7.5 10.99996 -7.97335 5.4364 16.5 16.5)" gradientUnits="userSpaceOnUse"><stop class="g4z4xncfo"/><stop offset="1" class="k7y-44b1u"/></radialGradient><radialGradient id="ilqJk5c" cx="0" cy="0" r="1" gradientTransform="matrix(11.49998 2 -2 11.49998 20.5 18)" gradientUnits="userSpaceOnUse"><stop class="c1buurbbt"/><stop offset=".9" class="mqe6vbive"/></radialGradient><radialGradient id="i6j9Pab" cx="0" cy="0" r="1" gradientTransform="rotate(43.971 -9.827 29.173)scale(59.0529)" gradientUnits="userSpaceOnUse"><stop offset=".185" class="k05n1gbkm"/><stop offset="1" class="rw5c_lizo"/></radialGradient><radialGradient id="isBWaZN" cx="0" cy="0" r="1" gradientTransform="rotate(133.727 1.51 9.661)scale(5.29073)" gradientUnits="userSpaceOnUse"><stop class="d3wf5jb8r"/><stop offset="1" class="fqac_w1ss"/></radialGradient><radialGradient id="iHqNsXd" cx="0" cy="0" r="1" gradientTransform="rotate(148.696 8.35 10.703)scale(4.91807)" gradientUnits="userSpaceOnUse"><stop class="d3wf5jb8r"/><stop offset="1" class="fqac_w1ss"/></radialGradient><radialGradient id="iPJHUOb" cx="0" cy="0" r="1" gradientTransform="rotate(26.381 -37.927 58.216)scale(3.68158)" gradientUnits="userSpaceOnUse"><stop class="a29a-0d3f"/><stop offset="1" class="fqac_w1ss"/></radialGradient><radialGradient id="igiKuOd" cx="0" cy="0" r="1" gradientTransform="matrix(2.5 -3.5 3.5 2.5 22.5 26)" gradientUnits="userSpaceOnUse"><stop class="lctctv22m"/><stop offset="1" class="fqac_w1ss"/></radialGradient><radialGradient id="inFaS5J" cx="0" cy="0" r="1" gradientTransform="matrix(0 3.39634 -1.85251 0 22.304 23.48)" gradientUnits="userSpaceOnUse"><stop class="lctctv22m"/><stop offset="1" class="fqac_w1ss"/></radialGradient><radialGradient id="ifVhWsc" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.14214 -5.61232 0 16 21.247)" gradientUnits="userSpaceOnUse"><stop offset=".348" class="xec7mnldh"/><stop offset=".628" class="ixywm0blw"/><stop offset="1" class="opsjn_43s"/><stop offset="1" class="z3hv7yb0c"/></radialGradient><radialGradient id="iDUDAhe" cx="0" cy="0" r="1" gradientTransform="matrix(-2.99998 10.45459 -4.24098 -1.21696 26 20.454)" gradientUnits="userSpaceOnUse"><stop class="flip35zyj"/><stop offset=".806" class="uospscb_d"/><stop offset=".962" class="mqyq9nueh"/></radialGradient><linearGradient id="ircvEob" x1="16.5" x2="15.5" y1="10.688" y2="17.688" gradientUnits="userSpaceOnUse"><stop class="ehgdi7b0u"/><stop offset="1" class="kiu9e17zs"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:smiling-face-with-tear" /></template>
<style>
.a29a-0d3f {
  stop-color: var(--svg-color--be5f45, #BE5F45);
}

.a4iah7r8b {
  fill-rule: evenodd;
  d: path("M12.257 22.331a1 1 0 0 1 1.412-.074c.517.465 1.377.755 2.331.755s1.814-.29 2.331-.755a1 1 0 0 1 1.338 1.486c-.983.885-2.373 1.27-3.669 1.27s-2.686-.385-3.669-1.27a1 1 0 0 1-.074-1.412");
}

.c1buurbbt {
  stop-color: var(--svg-color--ffa64b, #FFA64B);
}

.cjd26qb7f {
  stop-color: var(--svg-color--ffb02e, #FFB02E);
}

.d3wf5jb8r {
  stop-color: var(--svg-color--392108, #392108);
}

.ehgdi7b0u {
  stop-color: var(--svg-color--553b3e, #553B3E);
}

.fi3ygubsr {
  d: path("M21 17.688a3 3 0 1 0 0-6a3 3 0 0 0 0 6");
}

.flip35zyj {
  stop-color: var(--svg-color--5c98ff, #5C98FF);
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

.h13dd1l8r {
  stop-color: var(--svg-color--f70a8d, #F70A8D);
}

.ixywm0blw {
  stop-color: var(--svg-color--57444a, #57444A);
}

.jo4k7lbns {
  d: path("M11 17.688a3 3 0 1 0 0-6a3 3 0 0 0 0 6");
}

.k05n1gbkm {
  stop-opacity: 0;
}

.k7y-44b1u {
  stop-color: var(--svg-color--ffb847, #FFB847);
  stop-opacity: 0;
}

.kiu9e17zs {
  stop-color: var(--svg-color--3d2432, #3D2432);
}

.lctctv22m {
  stop-color: var(--svg-color--b3622e, #B3622E);
}

.maobbcvxh {
  fill-opacity: var(--svg-fill-opacity--0-6, 0.6);
  d: path("M15.999 29.998c9.334 0 13.999-6.268 13.999-14c0-7.73-4.665-13.998-14-13.998C6.665 2 2 8.268 2 15.999s4.664 13.999 13.999 13.999");
}

.mqe6vbive {
  stop-color: var(--svg-color--ffae46, #FFAE46);
  stop-opacity: 0;
}

.mqyq9nueh {
  stop-color: var(--svg-color--6065ca, #6065CA);
}

.og2_-db3e {
  stop-color: var(--svg-color--f59639, #F59639);
  stop-opacity: 0;
}

.opsjn_43s {
  stop-color: var(--svg-color--4e2553, #4E2553);
}

.qvxe_pbez {
  stop-color: var(--svg-color--fff478, #FFF478);
}

.rw5c_lizo {
  stop-opacity: 0.4;
}

.uospscb_d {
  stop-color: var(--svg-color--3d5bf1, #3D5BF1);
}

.ut47l53gt {
  d: path("M21 22.857C21 21.28 22.343 20 24 20s3 1.28 3 2.857v4.286C27 28.72 25.657 30 24 30s-3-1.28-3-2.857z");
}

.w5xp9scuu {
  stop-color: var(--svg-color--ff7dce, #FF7DCE);
}

.xec7mnldh {
  stop-color: var(--svg-color--4d3027, #4D3027);
}

.z3hv7yb0c {
  stop-color: var(--svg-color--502a56, #502A56);
}

.z486gib-c {
  fill: var(--svg-color--fff, #fff);
  d: path("M10.42 18.912a4.206 4.206 0 1 0 0-8.412a4.206 4.206 0 0 0 0 8.412m11.148.077a4.244 4.244 0 1 0 0-8.489a4.244 4.244 0 0 0 0 8.489");
}

.zannmacjr {
  d: path("M15.999 29.998c9.334 0 13.999-6.268 13.999-14c0-7.73-4.665-13.998-14-13.998C6.665 2 2 8.268 2 15.999s4.664 13.999 13.999 13.999");
}

.zgcpgx8ap {
  stop-color: var(--svg-color--7d6133, #7D6133);
  stop-opacity: 0;
}

</style>
