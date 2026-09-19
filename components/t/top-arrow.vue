<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="z11826rpt"/><path class="olg5kkbzt"/><path fill="url(#ih4pZdb)" class="t0zb6mb2n"/><path fill="url(#inv1cdc)" class="t0zb6mb2n"/><path fill="url(#icWiC7c)" class="t0zb6mb2n"/><path fill="url(#ilODXeb)" class="t0zb6mb2n"/><path fill="url(#iH7TbPc)" class="t0zb6mb2n"/><path fill="url(#iirXYnd)" class="t0zb6mb2n"/><path fill="url(#iUziqZt)" class="t0zb6mb2n"/><path fill="url(#iFKxCGd)" class="t0zb6mb2n"/><path fill="url(#i0vekEc)" class="t0zb6mb2n"/><path fill="url(#ixZ9Zwd)" class="t0zb6mb2n"/><path class="ry44macla"/><path fill="url(#iPFqLre)" class="a8xpxkz-y"/><path fill="url(#iNDLbXb)" class="a8xpxkz-y"/><path fill="url(#i1Hlywc)" class="a8xpxkz-y"/><path class="qoxhjrbsc"/><path fill="url(#iHWL7Qc)" class="pvb5yvbob"/><path fill="url(#iCMbWLd)" class="pvb5yvbob"/><path fill="url(#ieDXh5M)" class="pvb5yvbob"/><path fill="url(#iR9kfod)" class="pvb5yvbob"/><path fill="url(#ietuXpd)" class="pvb5yvbob"/><path fill="url(#igulile)" class="pvb5yvbob"/><path fill="url(#iiieCQd)" class="pvb5yvbob"/><path fill="url(#iNgopLc)" class="pvb5yvbob"/><path fill="url(#isWHzPe)" class="pvb5yvbob"/><path fill="url(#izUbPjd)" class="pvb5yvbob"/><path fill="url(#iOKEXkh)" class="pvb5yvbob"/><defs><radialGradient id="iirXYnd" cx="0" cy="0" r="1" gradientTransform="matrix(-5.15451 0 0 -1.07456 23.557 22.117)" gradientUnits="userSpaceOnUse"><stop class="sm1teyw2a"/><stop offset="0" class="wkxmqun6p"/><stop offset="1" class="t7qqt9byh"/></radialGradient><radialGradient id="iUziqZt" cx="0" cy="0" r="1" gradientTransform="matrix(5.8262 0 0 1.21459 7.608 22.453)" gradientUnits="userSpaceOnUse"><stop class="sm1teyw2a"/><stop offset="0" class="wkxmqun6p"/><stop offset="1" class="t7qqt9byh"/></radialGradient><radialGradient id="ixZ9Zwd" cx="0" cy="0" r="1" gradientTransform="matrix(-2.112 0 0 -3.45616 23.848 11.135)" gradientUnits="userSpaceOnUse"><stop class="vbayesb1n"/><stop offset="1" class="faivd0u6z"/></radialGradient><radialGradient id="iPFqLre" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.125 25.4904 0 16.222 19.5)" gradientUnits="userSpaceOnUse"><stop offset=".25" class="s72f_cuwl"/><stop offset=".544" class="frbc-ac5p"/><stop offset="1" class="zr_jwubcu"/></radialGradient><radialGradient id="iNDLbXb" cx="0" cy="0" r="1" gradientTransform="rotate(87.624 -2.056 13.7)scale(7.63156 2.47732)" gradientUnits="userSpaceOnUse"><stop offset=".523" class="oq43-dbkc"/><stop offset=".923" class="q-ss4xxck"/></radialGradient><radialGradient id="i1Hlywc" cx="0" cy="0" r="1" gradientTransform="rotate(91.766 2.684 17.366)scale(7.09712 2.30383)" gradientUnits="userSpaceOnUse"><stop offset=".292" class="oq43-dbkc"/><stop offset=".923" class="q-ss4xxck"/></radialGradient><radialGradient id="iHWL7Qc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.53124 1.37501 -25.36614 -28.2482 19.813 5.656)" gradientUnits="userSpaceOnUse"><stop offset=".285" class="ycoup5wdj"/><stop offset=".537" class="tpnkh7byy"/><stop offset="1" class="grhr04bhy"/></radialGradient><radialGradient id="iCMbWLd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.25 4.60366 0 8.875 12)" gradientUnits="userSpaceOnUse"><stop offset=".159" class="tj0dpwb0x"/><stop offset=".983" class="ybngzjbnp"/></radialGradient><radialGradient id="ieDXh5M" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.8125 3.44764 0 22.781 11.75)" gradientUnits="userSpaceOnUse"><stop offset=".159" class="vjuvqsbnt"/><stop offset=".983" class="ybngzjbnp"/></radialGradient><radialGradient id="iR9kfod" cx="0" cy="0" r="1" gradientTransform="matrix(-1.25001 1.14062 -20.7876 -22.7813 20.625 5.422)" gradientUnits="userSpaceOnUse"><stop offset=".538" class="qayttb7vd"/><stop offset="1" class="vlztjhb3c"/><stop offset="1" class="jedx2ccyq"/></radialGradient><radialGradient id="ietuXpd" cx="0" cy="0" r="1" gradientTransform="matrix(2.15626 2.03124 -21.12732 22.4276 10.562 5.156)" gradientUnits="userSpaceOnUse"><stop offset=".458" class="ad3ffbcvf"/><stop offset="1" class="yhyazbcky"/></radialGradient><radialGradient id="igulile" cx="0" cy="0" r="1" gradientTransform="matrix(1.32813 -.76562 .92023 1.59633 12.344 13.14)" gradientUnits="userSpaceOnUse"><stop offset=".3" class="p5q0swb7e"/><stop offset=".935" class="l2nczpxka"/></radialGradient><radialGradient id="iiieCQd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.76562 .23436 -.28169 -2.12218 19.938 13.25)" gradientUnits="userSpaceOnUse"><stop offset=".171" class="p5q0swb7e"/><stop offset=".935" class="l2nczpxka"/></radialGradient><radialGradient id="iNgopLc" cx="0" cy="0" r="1" gradientTransform="matrix(.0625 1.0625 -4.66218 .2742 8.75 12.72)" gradientUnits="userSpaceOnUse"><stop offset=".557" class="yaidseblk"/><stop offset="1" class="eybtlsl6i"/></radialGradient><radialGradient id="isWHzPe" cx="0" cy="0" r="1" gradientTransform="matrix(-.15625 1.125 -4.53031 -.62921 23.563 12.719)" gradientUnits="userSpaceOnUse"><stop offset=".349" class="yaidseblk"/><stop offset="1" class="eybtlsl6i"/></radialGradient><radialGradient id="izUbPjd" cx="0" cy="0" r="1" gradientTransform="matrix(-.65234 1.6875 -1.61342 -.6237 25.156 11.781)" gradientUnits="userSpaceOnUse"><stop offset=".365" class="a4z0mjz2l"/><stop offset="1" class="b6ib_x26e"/></radialGradient><radialGradient id="iOKEXkh" cx="0" cy="0" r="1" gradientTransform="matrix(1.5625 3.375 -2.28312 1.057 6.406 11.875)" gradientUnits="userSpaceOnUse"><stop offset=".3" class="kg25l4b7h"/><stop offset=".867" class="h3qjwlkcz"/></radialGradient><linearGradient id="ih4pZdb" x1="20.061" x2="17.558" y1="12.03" y2="12.03" gradientUnits="userSpaceOnUse"><stop offset=".237" class="lxsnoei1q"/><stop offset=".841" class="iwhihv9kc"/></linearGradient><linearGradient id="inv1cdc" x1="11.301" x2="14.492" y1="12.03" y2="12.03" gradientUnits="userSpaceOnUse"><stop offset=".294" class="lxsnoei1q"/><stop offset=".841" class="iwhihv9kc"/></linearGradient><linearGradient id="icWiC7c" x1="15.764" x2="15.764" y1="29.936" y2="2" gradientUnits="userSpaceOnUse"><stop offset=".61" class="t7qqt9byh"/><stop offset=".675" class="sm1teyw2a"/></linearGradient><linearGradient id="ilODXeb" x1="16.223" x2="16.223" y1="19.656" y2="17.594" gradientUnits="userSpaceOnUse"><stop offset=".181" class="lxsnoei1q"/><stop offset=".841" class="iwhihv9kc"/></linearGradient><linearGradient id="iH7TbPc" x1="22.066" x2="17.566" y1="4.28" y2="8.311" gradientUnits="userSpaceOnUse"><stop offset=".238" class="t7qqt9byh"/><stop offset=".628" class="b9l6s2bnr"/><stop offset="1" class="t7qqt9byh"/></linearGradient><linearGradient id="iFKxCGd" x1="10.557" x2="13.098" y1="4.401" y2="6.905" gradientUnits="userSpaceOnUse"><stop offset=".375" class="lxsnoei1q"/><stop offset=".919" class="iwhihv9kc"/></linearGradient><linearGradient id="i0vekEc" x1="22.428" x2="19.429" y1="3.871" y2="7.11" gradientUnits="userSpaceOnUse"><stop offset=".428" class="lxsnoei1q"/><stop offset=".906" class="iwhihv9kc"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:top-arrow" /></template>
<style>
.a4z0mjz2l {
  stop-color: var(--svg-color--5f48a9, #5F48A9);
}

.a8xpxkz-y {
  d: path("M19.904 12.236c-.35 0-.64.29-.64.64V17.8c.01.65-.53 1.18-1.18 1.18h-4.22c-.66 0-1.19-.53-1.19-1.19v-4.923c0-.35-.29-.64-.64-.64z");
}

.ad3ffbcvf {
  stop-color: var(--svg-color--483f6e, #483F6E);
}

.b6ib_x26e {
  stop-color: var(--svg-color--5f48a9, #5F48A9);
  stop-opacity: 0;
}

.b9l6s2bnr {
  stop-color: var(--svg-color--8176bb, #8176BB);
  stop-opacity: 0.5;
}

.eybtlsl6i {
  stop-color: var(--svg-color--623bbd, #623BBD);
  stop-opacity: 0;
}

.faivd0u6z {
  stop-color: var(--svg-color--584e86, #584E86);
  stop-opacity: 0;
}

.frbc-ac5p {
  stop-color: var(--svg-color--9150f4, #9150F4);
}

.ft5dv1b6b {
  fill: none;
}

.grhr04bhy {
  stop-color: var(--svg-color--7f6dc5, #7F6DC5);
  stop-opacity: 0;
}

.h3qjwlkcz {
  stop-color: var(--svg-color--534297, #534297);
  stop-opacity: 0;
}

.iwhihv9kc {
  stop-color: var(--svg-color--403966, #403966);
  stop-opacity: 0;
}

.jedx2ccyq {
  stop-color: var(--svg-color--7062a8, #7062A8);
  stop-opacity: 0;
}

.kg25l4b7h {
  stop-color: var(--svg-color--534297, #534297);
}

.l2nczpxka {
  stop-color: var(--svg-color--5d49a1, #5D49A1);
  stop-opacity: 0;
}

.lxsnoei1q {
  stop-color: var(--svg-color--403966, #403966);
}

.olg5kkbzt {
  fill: var(--svg-color--7e6cc3, #7E6CC3);
  d: path("m16.683 2.316l7.57 8.32c.56.62.12 1.6-.71 1.6h-3.64c-.35 0-.64.29-.64.64V17.8c.01.65-.53 1.18-1.18 1.18h-4.22c-.66 0-1.19-.53-1.19-1.19v-4.923c0-.35-.29-.64-.64-.64h-3.64c-.83 0-1.27-.99-.71-1.6l7.57-8.32a.977.977 0 0 1 1.43.01");
}

.oq43-dbkc {
  stop-color: var(--svg-color--4d3c86, #4D3C86);
}

.p5q0swb7e {
  stop-color: var(--svg-color--4d3c87, #4D3C87);
}

.pvb5yvbob {
  d: path("m16.684 2.316l7.57 8.32c.56.62.12 1.6-.71 1.6h-3.64c-.35 0-.64.29-.64.64l-6.59-.01c0-.35-.29-.64-.64-.64h-3.64c-.83 0-1.27-.99-.71-1.6l7.57-8.32a.977.977 0 0 1 1.43.01");
}

.q-ss4xxck {
  stop-color: var(--svg-color--604ca4, #604CA4);
  stop-opacity: 0;
}

.qayttb7vd {
  stop-color: var(--svg-color--6e60a6, #6E60A6);
}

.qoxhjrbsc {
  fill: var(--svg-color--7f6dc4, #7F6DC4);
  d: path("m16.684 2.316l7.57 8.32c.56.62.12 1.6-.71 1.6h-3.64c-.35 0-.64.29-.64.64l-6.59-.01c0-.35-.29-.64-.64-.64h-3.64c-.83 0-1.27-.99-.71-1.6l7.57-8.32a.977.977 0 0 1 1.43.01");
}

.ry44macla {
  fill: var(--svg-color--7f6dc4, #7F6DC4);
  d: path("M19.904 12.236c-.35 0-.64.29-.64.64V17.8c.01.65-.53 1.18-1.18 1.18h-4.22c-.66 0-1.19-.53-1.19-1.19v-4.923c0-.35-.29-.64-.64-.64z");
}

.s72f_cuwl {
  stop-color: var(--svg-color--653ac7, #653AC7);
}

.sm1teyw2a {
  stop-color: var(--svg-color--635994, #635994);
}

.t0zb6mb2n {
  d: path("m16.683 2.316l7.57 8.32c.56.62.12 1.6-.71 1.6h-3.64c-.35 0-.64.29-.64.64V17.8c.01.65-.53 1.18-1.18 1.18h-4.22c-.66 0-1.19-.53-1.19-1.19v-4.923c0-.35-.29-.64-.64-.64h-3.64c-.83 0-1.27-.99-.71-1.6l7.57-8.32a.977.977 0 0 1 1.43.01");
}

.t7qqt9byh {
  stop-color: var(--svg-color--635994, #635994);
  stop-opacity: 0;
}

.tj0dpwb0x {
  stop-color: var(--svg-color--8955e1, #8955E1);
}

.tpnkh7byy {
  stop-color: var(--svg-color--998ed2, #998ED2);
}

.vbayesb1n {
  stop-color: var(--svg-color--584e86, #584E86);
}

.vjuvqsbnt {
  stop-color: var(--svg-color--8b52e6, #8B52E6);
}

.vlztjhb3c {
  stop-color: var(--svg-color--8677c6, #8677C6);
  stop-opacity: 0;
}

.wkxmqun6p {
  stop-color: var(--svg-color--8176bb, #8176BB);
}

.yaidseblk {
  stop-color: var(--svg-color--623bbd, #623BBD);
}

.ybngzjbnp {
  stop-color: var(--svg-color--8b52e6, #8B52E6);
  stop-opacity: 0;
}

.ycoup5wdj {
  stop-color: var(--svg-color--9d92d4, #9D92D4);
}

.yhyazbcky {
  stop-color: var(--svg-color--5f5395, #5F5395);
  stop-opacity: 0;
}

.z11826rpt {
  fill: var(--svg-color--7763bb, #7763BB);
  d: path("M12.44 20.817H6c-.55 0-1 .45-1 1s.45 1 1 1h2.22v6.17c0 .55.45 1 1 1s1-.45 1-1v-6.17h2.22c.55 0 1-.45 1-1c0-.56-.45-1-1-1m9.39.01h2.77c1.51 0 2.74 1.23 2.74 2.74s-1.23 2.74-2.74 2.74h-1.77v2.69c0 .55-.45 1-1 1s-1-.45-1-1v-7.17c0-.55.45-1 1-1m1 3.48h1.77c.41 0 .74-.33.74-.74s-.33-.74-.74-.74h-1.77zm-9.39 2.55c0 1.73 1.41 3.14 3.15 3.14c1.73 0 3.15-1.41 3.15-3.14v-2.88c0-1.73-1.41-3.14-3.15-3.14s-3.15 1.41-3.15 3.14zm2-2.88a1.15 1.15 0 0 1 2.3 0v2.88c0 .64-.52 1.15-1.15 1.15s-1.15-.52-1.15-1.15z");
}

.zr_jwubcu {
  stop-color: var(--svg-color--914ef5, #914EF5);
  stop-opacity: 0;
}

</style>
