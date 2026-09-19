<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<defs><path id="iAhm1Cb" class="wycjhibbk"/></defs><g class="ft5dv1b6b"><g clip-path="url(#izIOyGZ)"><g clip-path="url(#izIOyGZ)"><g class="z4n2hhy8u"><path fill="url(#igD8Twm)" class="vdvfwlbgz"/><path fill="url(#iXjnbHb)" class="vdvfwlbgz"/><path fill="url(#ivYSpJb)" class="vdvfwlbgz"/><path fill="url(#iqwX6bE)" class="qdlmj3w0x"/><path fill="url(#iXIbQdb)" class="vdvfwlbgz"/><path fill="url(#iPlM5Ss)" class="vdvfwlbgz"/><path fill="url(#iiXrj0b)" class="vdvfwlbgz"/><path fill="url(#iERenLb)" class="vdvfwlbgz"/></g><g class="z4n2hhy8u"><path fill="url(#iMNaqnb)" class="ms0lv279h"/><path fill="url(#ixZESCe)" class="ms0lv279h"/><path fill="url(#iOdhW3a)" class="ms0lv279h"/><path fill="url(#ijlpLZc)" class="bev6p3fmc"/><path fill="url(#ixOTBEy)" class="ms0lv279h"/><path fill="url(#iVSnSvc)" class="ms0lv279h"/><path fill="url(#i0vlGqb)" class="ms0lv279h"/><path fill="url(#iVHPE9D)" class="ms0lv279h"/></g><path fill="url(#iGcuGSc)" clip-rule="evenodd" class="t_9wdbypg"/><path fill="url(#iBUmmwc)" clip-rule="evenodd" class="ivl8n5b8u"/><path fill="url(#iMNaqnb)" clip-rule="evenodd" class="uiv4j_gix"/><path fill="url(#ixZESCe)" clip-rule="evenodd" class="uiv4j_gix"/><path fill="url(#iOdhW3a)" clip-rule="evenodd" class="uiv4j_gix"/><path fill="url(#ijlpLZc)" clip-rule="evenodd" class="t5s0gbc0c"/><path fill="url(#ixOTBEy)" clip-rule="evenodd" class="uiv4j_gix"/><path fill="url(#iVSnSvc)" clip-rule="evenodd" class="uiv4j_gix"/><path fill="url(#i0vlGqb)" clip-rule="evenodd" class="uiv4j_gix"/><path fill="url(#iVHPE9D)" clip-rule="evenodd" class="uiv4j_gix"/><circle fill="url(#i9Pb7WL)" class="oy9phebil"/><circle fill="url(#idvAimb)" class="unvjvgbso"/><path class="kwysvy96i"/><path class="c713-nflz"/><path class="f5tq5acha"/><path fill="url(#iWtfBkd)" class="agv7a6b9h"/><path fill="url(#iWtfBkd)" class="pvay9aclv"/><path fill="url(#ibP05he)" clip-rule="evenodd" class="f9h751bpd"/><path fill="url(#ivsKlHA)" clip-rule="evenodd" class="ia8_kfbnx"/><path fill="url(#ivOYSAd)" class="zli26-lya"/></g></g><defs><radialGradient id="igD8Twm" cx="0" cy="0" r="1" gradientTransform="rotate(132.839 9.786 9.629)scale(37.5033)" gradientUnits="userSpaceOnUse"><stop class="qvxe_pbez"/><stop offset=".475" class="cjd26qb7f"/><stop offset="1" class="h13dd1l8r"/></radialGradient><radialGradient id="iXjnbHb" cx="0" cy="0" r="1" gradientTransform="rotate(131.878 9.74 9.746)scale(38.9487)" gradientUnits="userSpaceOnUse"><stop class="qvxe_pbez"/><stop offset=".475" class="cjd26qb7f"/><stop offset="1" class="h13dd1l8r"/></radialGradient><radialGradient id="ivYSpJb" cx="0" cy="0" r="1" gradientTransform="rotate(101.31 1.876 11.989)scale(17.8466 22.8581)" gradientUnits="userSpaceOnUse"><stop offset=".788" class="og2_-db3e"/><stop offset=".973" class="w5xp9scuu"/></radialGradient><radialGradient id="iqwX6bE" cx="0" cy="0" r="1" gradientTransform="matrix(-29 29 -29 -29 16 14)" gradientUnits="userSpaceOnUse"><stop offset=".315" class="k05n1gbkm"/><stop offset="1"/></radialGradient><radialGradient id="iXIbQdb" cx="0" cy="0" r="1" gradientTransform="rotate(77.692 -3.555 17.192)scale(28.1469)" gradientUnits="userSpaceOnUse"><stop offset=".508" class="zgcpgx8ap"/><stop offset="1" class="fqgjm_v0b"/></radialGradient><radialGradient id="iPlM5Ss" cx="0" cy="0" r="1" gradientTransform="matrix(7.5 10.99996 -7.97335 5.4364 14.5 16.5)" gradientUnits="userSpaceOnUse"><stop class="g4z4xncfo"/><stop offset="1" class="k7y-44b1u"/></radialGradient><radialGradient id="iiXrj0b" cx="0" cy="0" r="1" gradientTransform="matrix(11.49998 2 -2 11.49998 18.5 18)" gradientUnits="userSpaceOnUse"><stop class="c1buurbbt"/><stop offset=".9" class="mqe6vbive"/></radialGradient><radialGradient id="iERenLb" cx="0" cy="0" r="1" gradientTransform="rotate(43.971 -10.827 26.696)scale(59.0529)" gradientUnits="userSpaceOnUse"><stop offset=".185" class="k05n1gbkm"/><stop offset="1" class="rw5c_lizo"/></radialGradient><radialGradient id="iMNaqnb" cx="0" cy="0" r="1" gradientTransform="rotate(132.839 11.786 10.502)scale(37.5033)" gradientUnits="userSpaceOnUse"><stop class="qvxe_pbez"/><stop offset=".475" class="cjd26qb7f"/><stop offset="1" class="h13dd1l8r"/></radialGradient><radialGradient id="ixZESCe" cx="0" cy="0" r="1" gradientTransform="rotate(131.878 11.74 10.64)scale(38.9487)" gradientUnits="userSpaceOnUse"><stop class="qvxe_pbez"/><stop offset=".475" class="cjd26qb7f"/><stop offset="1" class="h13dd1l8r"/></radialGradient><radialGradient id="iOdhW3a" cx="0" cy="0" r="1" gradientTransform="rotate(101.31 3.876 13.628)scale(17.8466 22.8581)" gradientUnits="userSpaceOnUse"><stop offset=".788" class="og2_-db3e"/><stop offset=".973" class="w5xp9scuu"/></radialGradient><radialGradient id="ijlpLZc" cx="0" cy="0" r="1" gradientTransform="matrix(-29 29 -29 -29 20 14)" gradientUnits="userSpaceOnUse"><stop offset=".315" class="k05n1gbkm"/><stop offset="1"/></radialGradient><radialGradient id="ixOTBEy" cx="0" cy="0" r="1" gradientTransform="rotate(77.692 -1.555 19.675)scale(28.1469)" gradientUnits="userSpaceOnUse"><stop offset=".508" class="zgcpgx8ap"/><stop offset="1" class="fqgjm_v0b"/></radialGradient><radialGradient id="iVSnSvc" cx="0" cy="0" r="1" gradientTransform="matrix(7.5 10.99996 -7.97335 5.4364 18.5 16.5)" gradientUnits="userSpaceOnUse"><stop class="g4z4xncfo"/><stop offset="1" class="k7y-44b1u"/></radialGradient><radialGradient id="i0vlGqb" cx="0" cy="0" r="1" gradientTransform="matrix(11.49998 2 -2 11.49998 22.5 18)" gradientUnits="userSpaceOnUse"><stop class="c1buurbbt"/><stop offset=".9" class="mqe6vbive"/></radialGradient><radialGradient id="iVHPE9D" cx="0" cy="0" r="1" gradientTransform="rotate(43.971 -8.827 31.65)scale(59.0529)" gradientUnits="userSpaceOnUse"><stop offset=".185" class="k05n1gbkm"/><stop offset="1" class="rw5c_lizo"/></radialGradient><radialGradient id="i9Pb7WL" cx="0" cy="0" r="1" gradientTransform="rotate(135 3.936 8.725)scale(9.74236 5.04232)" gradientUnits="userSpaceOnUse"><stop class="d3wf5jb8r"/><stop offset="1" class="fqac_w1ss"/></radialGradient><radialGradient id="idvAimb" cx="0" cy="0" r="1" gradientTransform="matrix(-5.75 5.75 -3.24597 -3.24597 23 13)" gradientUnits="userSpaceOnUse"><stop class="d3wf5jb8r"/><stop offset="1" class="fqac_w1ss"/></radialGradient><radialGradient id="ivOYSAd" cx="0" cy="0" r="1" gradientTransform="rotate(-90 22.167 6.167)scale(7.33333)" gradientUnits="userSpaceOnUse"><stop class="h13dd1l8r"/><stop offset="1" class="di9ro-btr"/></radialGradient><linearGradient id="iGcuGSc" x1="3.833" x2="3.833" y1="10.4" y2="8.6" gradientUnits="userSpaceOnUse"><stop offset=".03" class="ii_r00eab"/><stop offset="1" class="zg8znn0_h"/></linearGradient><linearGradient id="iBUmmwc" x1="28.166" x2="28.166" y1="10.4" y2="8.6" gradientUnits="userSpaceOnUse"><stop offset=".03" class="ii_r00eab"/><stop offset="1" class="zg8znn0_h"/></linearGradient><linearGradient id="iWtfBkd" x1="20.615" x2="19.927" y1="13" y2="17.03" gradientUnits="userSpaceOnUse"><stop class="ehgdi7b0u"/><stop offset="1" class="kiu9e17zs"/></linearGradient><linearGradient id="ibP05he" x1="6.833" x2="6.833" y1="10.4" y2="8.6" gradientUnits="userSpaceOnUse"><stop offset=".03" class="ii_r00eab"/><stop offset="1" class="zg8znn0_h"/></linearGradient><linearGradient id="ivsKlHA" x1="25.166" x2="25.166" y1="10.4" y2="8.6" gradientUnits="userSpaceOnUse"><stop offset=".03" class="ii_r00eab"/><stop offset="1" class="zg8znn0_h"/></linearGradient><clipPath id="izIOyGZ"><use href="#iAhm1Cb"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:shaking-face" /></template>
<style>
.agv7a6b9h {
  d: path("M12 17a2 2 0 1 0 0-4a2 2 0 0 0 0 4");
}

.bev6p3fmc {
  fill-opacity: var(--svg-fill-opacity--0-6, 0.6);
  d: path("M17.999 29.998c9.334 0 13.999-6.268 13.999-14c0-7.73-4.665-13.998-14-13.998C8.665 2 4 8.268 4 15.999s4.664 13.999 13.999 13.999");
}

.c1buurbbt {
  stop-color: var(--svg-color--ffa64b, #FFA64B);
}

.c713-nflz {
  fill: var(--svg-color--fff, #fff);
  d: path("M8.5 19a4.5 4.5 0 1 0 0-9a4.5 4.5 0 0 0 0 9m15 0a4.5 4.5 0 1 0 0-9a4.5 4.5 0 0 0 0 9");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.cjd26qb7f {
  stop-color: var(--svg-color--ffb02e, #FFB02E);
}

.d3wf5jb8r {
  stop-color: var(--svg-color--392108, #392108);
}

.di9ro-btr {
  stop-color: var(--svg-color--89029c, #89029C);
}

.ehgdi7b0u {
  stop-color: var(--svg-color--553b3e, #553B3E);
}

.f5tq5acha {
  fill: var(--svg-color--fff, #fff);
  d: path("M10.5 19a4.5 4.5 0 1 0 0-9a4.5 4.5 0 0 0 0 9m11 0a4.5 4.5 0 1 0 0-9a4.5 4.5 0 0 0 0 9");
}

.f9h751bpd {
  fill-rule: evenodd;
  d: path("M8.07 7.988c-.594.562-.952 1.24-1.096 1.67a.5.5 0 1 1-.948-.316c.19-.57.631-1.392 1.355-2.08C8.113 6.567 9.148 6 10.5 6a.5.5 0 1 1 0 1c-1.049 0-1.847.433-2.432.988");
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

.ia8_kfbnx {
  fill-rule: evenodd;
  d: path("M23.93 7.988c.593.562.952 1.24 1.096 1.67a.5.5 0 1 0 .948-.316c-.19-.57-.631-1.392-1.355-2.08C23.887 6.567 22.852 6 21.5 6a.5.5 0 1 0 0 1c1.049 0 1.847.433 2.432.988");
}

.ii_r00eab {
  stop-color: var(--svg-color--524049, #524049);
}

.ivl8n5b8u {
  fill-rule: evenodd;
  d: path("M26.93 7.988c.593.562.952 1.24 1.096 1.67a.5.5 0 1 0 .948-.316c-.19-.57-.631-1.392-1.355-2.08C26.887 6.567 25.852 6 24.5 6a.5.5 0 1 0 0 1c1.049 0 1.847.433 2.432.988");
  opacity: var(--svg-opacity--0-6, 0.6);
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

.kwysvy96i {
  fill: var(--svg-color--fff, #fff);
  d: path("M6.5 19a4.5 4.5 0 1 0 0-9a4.5 4.5 0 0 0 0 9m19 0a4.5 4.5 0 1 0 0-9a4.5 4.5 0 0 0 0 9");
  opacity: var(--svg-opacity--0-4, 0.4);
}

.mqe6vbive {
  stop-color: var(--svg-color--ffae46, #FFAE46);
  stop-opacity: 0;
}

.ms0lv279h {
  d: path("M17.999 29.998c9.334 0 13.999-6.268 13.999-14c0-7.73-4.665-13.998-14-13.998C8.665 2 4 8.268 4 15.999s4.664 13.999 13.999 13.999");
}

.og2_-db3e {
  stop-color: var(--svg-color--f59639, #F59639);
  stop-opacity: 0;
}

.oy9phebil {
  cx: 9px;
  cy: 16px;
  r: 5px;
}

.pvay9aclv {
  d: path("M20 17a2 2 0 1 0 0-4a2 2 0 0 0 0 4");
}

.qdlmj3w0x {
  fill-opacity: var(--svg-fill-opacity--0-6, 0.6);
  d: path("M13.999 29.998c9.334 0 13.999-6.268 13.999-14c0-7.73-4.665-13.998-14-13.998C4.665 2 0 8.268 0 15.999s4.664 13.999 13.999 13.999");
}

.qvxe_pbez {
  stop-color: var(--svg-color--fff478, #FFF478);
}

.rw5c_lizo {
  stop-opacity: 0.4;
}

.t_9wdbypg {
  fill-rule: evenodd;
  d: path("M5.07 7.988c-.594.562-.952 1.24-1.096 1.67a.5.5 0 1 1-.948-.316c.19-.57.631-1.392 1.355-2.08C5.113 6.567 6.148 6 7.5 6a.5.5 0 0 1 0 1c-1.049 0-1.847.433-2.432.988");
  opacity: var(--svg-opacity--0-6, 0.6);
}

.t5s0gbc0c {
  fill-opacity: var(--svg-fill-opacity--0-6, 0.6);
  fill-rule: evenodd;
  d: path("M15.999 2.102C7.999 2.938 4 8.84 4 15.999S7.998 29.06 15.999 29.896c8-.836 11.999-6.74 11.999-13.897c0-7.158-3.998-13.061-12-13.897");
}

.uiv4j_gix {
  fill-rule: evenodd;
  d: path("M15.999 2.102C7.999 2.938 4 8.84 4 15.999S7.998 29.06 15.999 29.896c8-.836 11.999-6.74 11.999-13.897c0-7.158-3.998-13.061-12-13.897");
}

.unvjvgbso {
  cx: 19.5px;
  cy: 16.5px;
  r: 4.5px;
}

.vdvfwlbgz {
  d: path("M13.999 29.998c9.334 0 13.999-6.268 13.999-14c0-7.73-4.665-13.998-14-13.998C4.665 2 0 8.268 0 15.999s4.664 13.999 13.999 13.999");
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

.zg8znn0_h {
  stop-color: var(--svg-color--4a2c42, #4A2C42);
}

.zgcpgx8ap {
  stop-color: var(--svg-color--7d6133, #7D6133);
  stop-opacity: 0;
}

.zli26-lya {
  d: path("M13 24a3 3 0 1 1 6 0a3 3 0 0 1-6 0");
}

</style>
