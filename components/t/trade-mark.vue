<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#igA1L2d)" class="gbl0fgdri"/><path fill="url(#ikQVQ5f)" class="gbl0fgdri"/><path fill="url(#izZQjtC)" class="gbl0fgdri"/><path fill="url(#iWPXJob)" class="gbl0fgdri"/><path fill="url(#i25EvGd)" class="gbl0fgdri"/><path fill="url(#ix5v2qc)" class="ttge9qbbr"/><path fill="url(#id3bCZc)" class="ttge9qbbr"/><path fill="url(#ibHXXYc)" class="ttge9qbbr"/><path fill="url(#i8C1drt)" class="ttge9qbbr"/><path fill="url(#iulejRd)" class="ttge9qbbr"/><path fill="url(#itqK1pe)" class="ttge9qbbr"/><path fill="url(#iXly8Ke)" class="fs6wjvb2v"/><path fill="url(#iwu083b)" class="ttge9qbbr"/><path class="rqx193p1u"/><path fill="url(#iArnkPb)" class="o7ze1ybns"/><path fill="url(#iOyvfMb)" class="o7ze1ybns"/><path fill="url(#i9ekRXb)" class="o7ze1ybns"/><path fill="url(#i8MPUKM)" class="o7ze1ybns"/><path fill="url(#if3ckBd)" class="o7ze1ybns"/><path fill="url(#iCBnjsb)" class="o7ze1ybns"/><path fill="url(#iUboQ5c)" class="o7ze1ybns"/><path fill="url(#irDwaGe)" class="o7ze1ybns"/><path fill="url(#iKpaiae)" class="o7ze1ybns"/><path fill="url(#ioVTwpe)" class="o7ze1ybns"/><path fill="url(#ixVm6ge)" class="ome1r60wv"/><path fill="url(#ihNNvzw)" class="ome1r60wv"/><path fill="url(#i6OLIgd)" class="ome1r60wv"/><path fill="url(#izkQFOU)" class="ome1r60wv"/><path fill="url(#ifU0vzb)" class="o7ze1ybns"/><path fill="url(#i3Ietue)" class="o7ze1ybns"/><path fill="url(#iSR6lKc)" class="o7ze1ybns"/><path fill="url(#iAwqgGc)" class="o7ze1ybns"/><path fill="url(#iGebQab)" class="e-dwiybif"/><path fill="url(#i15wpsc)" class="e-dwiybif"/><path fill="url(#i1thVre)" class="e-dwiybif"/><path fill="url(#is6lEdb)" class="n32m7gb3j"/><path fill="url(#iJrbA3b)" class="n32m7gb3j"/><path fill="url(#i99w1Je)" class="n32m7gb3j"/><defs><radialGradient id="ikQVQ5f" cx="0" cy="0" r="1" gradientTransform="matrix(-.27762 5.2583 -8.2472 -.43542 7.107 3.421)" gradientUnits="userSpaceOnUse"><stop offset=".609" class="tcoi14v6o"/><stop offset=".704" class="haogwie1v"/></radialGradient><radialGradient id="izZQjtC" cx="0" cy="0" r="1" gradientTransform="matrix(-.41485 .47522 -.47712 -.41651 11.505 2.946)" gradientUnits="userSpaceOnUse"><stop class="wk-y_-1qb"/><stop offset="1" class="cypk33s0r"/></radialGradient><radialGradient id="iWPXJob" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.11022 -1.30249 0 8.482 4.294)" gradientUnits="userSpaceOnUse"><stop offset=".295" class="k5iz2mdcj"/><stop offset="1" class="dzw1vnaey"/><stop offset="1" class="ceocqpb2t"/></radialGradient><radialGradient id="i25EvGd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .61593 -1.40783 0 9.04 4.716)" gradientUnits="userSpaceOnUse"><stop offset=".295" class="igh9qd20m"/><stop offset="1" class="dzw1vnaey"/><stop offset="1" class="ceocqpb2t"/></radialGradient><radialGradient id="id3bCZc" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.46502 -2.67888 0 6.874 3.76)" gradientUnits="userSpaceOnUse"><stop offset=".239" class="txiyth_cn"/><stop offset=".678" class="zo8vm2lqz"/></radialGradient><radialGradient id="ibHXXYc" cx="0" cy="0" r="1" gradientTransform="rotate(90 1.994 6.088)scale(.85655)" gradientUnits="userSpaceOnUse"><stop offset=".295" class="k5iz2mdcj"/><stop offset="1" class="dzw1vnaey"/><stop offset="1" class="ceocqpb2t"/></radialGradient><radialGradient id="i8C1drt" cx="0" cy="0" r="1" gradientTransform="rotate(75.473 .1 5.698)scale(.6949)" gradientUnits="userSpaceOnUse"><stop offset=".295" class="k5iz2mdcj"/><stop offset="1" class="dzw1vnaey"/><stop offset="1" class="ceocqpb2t"/></radialGradient><radialGradient id="itqK1pe" cx="0" cy="0" r="1" gradientTransform="matrix(1.37552 0 0 2.6814 6.972 4.375)" gradientUnits="userSpaceOnUse"><stop class="m_96fhbiq"/><stop offset=".688" class="k4ebrxg2z"/></radialGradient><radialGradient id="iXly8Ke" cx="0" cy="0" r="1" gradientTransform="matrix(0 .94206 -1.38697 0 6.876 11.604)" gradientUnits="userSpaceOnUse"><stop offset=".096" class="yv0g24i-p"/><stop offset=".846" class="yr8_8rbhe"/></radialGradient><radialGradient id="iwu083b" cx="0" cy="0" r="1" gradientTransform="matrix(0 23.1981 -11.5301 0 6.94 -3.728)" gradientUnits="userSpaceOnUse"><stop offset=".653" class="tcoi14v6o"/><stop offset=".715" class="haogwie1v"/></radialGradient><radialGradient id="irDwaGe" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.8662 -2.98026 0 20.83 3.834)" gradientUnits="userSpaceOnUse"><stop offset=".594" class="ic9nshbiv"/><stop offset=".796" class="cjsgmyb7h"/></radialGradient><radialGradient id="ioVTwpe" cx="0" cy="0" r="1" gradientTransform="matrix(0 -24.4222 19.205 0 18.103 17.933)" gradientUnits="userSpaceOnUse"><stop offset=".653" class="tcoi14v6o"/><stop offset=".715" class="haogwie1v"/></radialGradient><radialGradient id="ixVm6ge" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.07922 -1.64229 0 13.782 11.52)" gradientUnits="userSpaceOnUse"><stop offset=".096" class="yv0g24i-p"/><stop offset=".846" class="yr8_8rbhe"/></radialGradient><radialGradient id="ihNNvzw" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.16377 -1.53918 0 21.996 11.796)" gradientUnits="userSpaceOnUse"><stop offset=".096" class="yv0g24i-p"/><stop offset=".846" class="yr8_8rbhe"/></radialGradient><radialGradient id="i6OLIgd" cx="0" cy="0" r="1" gradientTransform="rotate(78.957 3.778 12.084)scale(.88482)" gradientUnits="userSpaceOnUse"><stop offset=".096" class="yv0g24i-p"/><stop offset=".846" class="yr8_8rbhe"/></radialGradient><radialGradient id="izkQFOU" cx="0" cy="0" r="1" gradientTransform="rotate(137.01 9.232 7.012)scale(.71614)" gradientUnits="userSpaceOnUse"><stop offset=".096" class="yv0g24i-p"/><stop offset=".846" class="yr8_8rbhe"/></radialGradient><radialGradient id="ifU0vzb" cx="0" cy="0" r="1" gradientTransform="matrix(0 25.4473 -28.4453 0 18.12 -5.268)" gradientUnits="userSpaceOnUse"><stop offset=".677" class="tcoi14v6o"/><stop offset=".724" class="haogwie1v"/></radialGradient><radialGradient id="i3Ietue" cx="0" cy="0" r="1" gradientTransform="matrix(-.7199 0 0 -3.06676 15.13 10.484)" gradientUnits="userSpaceOnUse"><stop class="q8ei0-1mi"/><stop offset=".743" class="mp9-eubjy"/></radialGradient><radialGradient id="iSR6lKc" cx="0" cy="0" r="1" gradientTransform="matrix(-.54442 -.3725 1.58681 -2.31921 15.171 11.428)" gradientUnits="userSpaceOnUse"><stop class="q8ei0-1mi"/><stop offset=".743" class="mp9-eubjy"/></radialGradient><radialGradient id="iAwqgGc" cx="0" cy="0" r="1" gradientTransform="matrix(.36834 -.47668 2.03063 1.56911 21.116 12.048)" gradientUnits="userSpaceOnUse"><stop class="q8ei0-1mi"/><stop offset=".743" class="mp9-eubjy"/></radialGradient><radialGradient id="i1thVre" cx="0" cy="0" r="1" gradientTransform="rotate(90 9.596 12.605)scale(.62727)" gradientUnits="userSpaceOnUse"><stop class="wk-y_-1qb"/><stop offset="1" class="cypk33s0r"/></radialGradient><radialGradient id="i99w1Je" cx="0" cy="0" r="1" gradientTransform="matrix(.08189 -1.33195 2.43668 .1498 17.77 8.887)" gradientUnits="userSpaceOnUse"><stop offset=".161" class="q8ei0-1mi"/><stop offset=".402" class="mp9-eubjy"/></radialGradient><linearGradient id="igA1L2d" x1="6.829" x2="6.829" y1="2.25" y2="4.593" gradientUnits="userSpaceOnUse"><stop class="uw6ct3bwa"/><stop offset=".214" class="uzo543nom"/><stop offset=".335" class="lkeurab-x"/><stop offset=".523" class="i8hjxcl1d"/><stop offset=".863" class="gt6rl0ltw"/><stop offset="1" class="d_6xy98jp"/></linearGradient><linearGradient id="ix5v2qc" x1="10.298" x2="3.095" y1="7.996" y2="7.996" gradientUnits="userSpaceOnUse"><stop offset=".282" class="jf_d_hb7h"/><stop offset=".397" class="vlavj0bhr"/><stop offset=".426" class="vlavj0bhr"/><stop offset=".552" class="phf07y5lf"/><stop offset=".663" class="wbbnthoze"/></linearGradient><linearGradient id="iulejRd" x1="6.876" x2="6.876" y1="3.134" y2="4.046" gradientUnits="userSpaceOnUse"><stop class="cf4cu5bqe"/><stop offset=".267" class="zn4jy973r"/><stop offset=".448" class="p9sc3pp2n"/><stop offset=".647" class="qpto43zmj"/><stop offset="1" class="illn__i5j"/></linearGradient><linearGradient id="iArnkPb" x1="10.667" x2="16.276" y1="6.117" y2="6.117" gradientUnits="userSpaceOnUse"><stop offset=".513" class="ckjl5rtnx"/><stop offset=".589" class="m46f8vz9c"/><stop offset=".632" class="m46f8vz9c"/><stop offset=".717" class="u-3vz3bjc"/></linearGradient><linearGradient id="iOyvfMb" x1="12.392" x2="16.276" y1="6.117" y2="6.117" gradientUnits="userSpaceOnUse"><stop offset=".532" class="l34mbi91h"/><stop offset=".632" class="xeoab1-yu"/><stop offset=".681" class="u-3vz3bjc"/></linearGradient><linearGradient id="i9ekRXb" x1="16.988" x2="15.752" y1="4.673" y2="7.629" gradientUnits="userSpaceOnUse"><stop offset=".629" class="z_afiqklu"/><stop offset=".804" class="b9y6si0ar"/></linearGradient><linearGradient id="i8MPUKM" x1="17.036" x2="14.188" y1="2.25" y2="4.896" gradientUnits="userSpaceOnUse"><stop offset=".526" class="rbon7fb2e"/><stop offset=".596" class="nor3wl3_h"/><stop offset=".686" class="nor3wl3_h"/><stop offset=".863" class="mf0352b6e"/></linearGradient><linearGradient id="if3ckBd" x1="21.774" x2="15.729" y1="11.184" y2="5.139" gradientUnits="userSpaceOnUse"><stop offset=".629" class="z_afiqklu"/><stop offset=".804" class="b9y6si0ar"/></linearGradient><linearGradient id="iCBnjsb" x1="22.454" x2="19.964" y1="6.117" y2="6.117" gradientUnits="userSpaceOnUse"><stop offset=".046" class="l34mbi91h"/><stop offset=".642" class="xeoab1-yu"/><stop offset=".745" class="u-3vz3bjc"/></linearGradient><linearGradient id="iUboQ5c" x1="20.859" x2="23.04" y1="6.117" y2="6.117" gradientUnits="userSpaceOnUse"><stop offset=".401" class="ckjl5rtnx"/><stop offset=".589" class="m46f8vz9c"/><stop offset=".632" class="m46f8vz9c"/><stop offset=".854" class="u-3vz3bjc"/></linearGradient><linearGradient id="iKpaiae" x1="10.667" x2="16.276" y1="6.117" y2="6.117" gradientUnits="userSpaceOnUse"><stop offset=".387" class="q8ei0-1mi"/><stop offset=".6" class="jwp58ixzd"/></linearGradient><linearGradient id="iGebQab" x1="22.454" x2="18.658" y1="6.117" y2="2.25" gradientUnits="userSpaceOnUse"><stop offset=".4" class="l34mbi91h"/><stop offset=".517" class="lvkaobcon"/><stop offset=".679" class="xeoab1-yu"/><stop offset=".814" class="u-3vz3bjc"/></linearGradient><linearGradient id="i15wpsc" x1="24.684" x2="20.706" y1="6.117" y2="6.117" gradientUnits="userSpaceOnUse"><stop offset=".387" class="q8ei0-1mi"/><stop offset=".6" class="jwp58ixzd"/></linearGradient><linearGradient id="is6lEdb" x1="16.917" x2="15.422" y1="6.256" y2="7.751" gradientUnits="userSpaceOnUse"><stop offset=".248" class="l34mbi91h"/><stop offset=".464" class="zb7eih-wp"/><stop offset=".702" class="xeoab1-yu"/><stop offset=".86" class="u-3vz3bjc"/></linearGradient><linearGradient id="iJrbA3b" x1="17.965" x2="19.572" y1="6.745" y2="8.351" gradientUnits="userSpaceOnUse"><stop offset=".248" class="l34mbi91h"/><stop offset=".464" class="zb7eih-wp"/><stop offset=".702" class="xeoab1-yu"/><stop offset=".86" class="u-3vz3bjc"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:trade-mark" /></template>
<style>
.b9y6si0ar {
  stop-color: var(--svg-color--7b6bb9, #7B6BB9);
  stop-opacity: 0;
}

.ceocqpb2t {
  stop-color: var(--svg-color--844edf, #844EDF);
  stop-opacity: 0;
}

.cf4cu5bqe {
  stop-color: var(--svg-color--8577c1, #8577C1);
}

.cjsgmyb7h {
  stop-color: var(--svg-color--7b6bb7, #7B6BB7);
  stop-opacity: 0;
}

.ckjl5rtnx {
  stop-color: var(--svg-color--796ab5, #796AB5);
  stop-opacity: 0;
}

.cypk33s0r {
  stop-color: var(--svg-color--9d93d3, #9D93D3);
  stop-opacity: 0;
}

.d_6xy98jp {
  stop-color: var(--svg-color--6035be, #6035BE);
}

.dzw1vnaey {
  stop-color: var(--svg-color--7c6abe, #7C6ABE);
  stop-opacity: 0;
}

.e-dwiybif {
  d: path("m17.709 8.647l.024-.002c.305.016.618-.093.857-.333l2.22-2.31v5.077c0 .644.508 1.171 1.126 1.171c.62 0 1.104-.535 1.104-1.178V3.428c0-.644-.507-1.17-1.126-1.17c-.356 0-.759.053-1.036.333l-3.16 3.287l-.01-.01z");
}

.fs6wjvb2v {
  fill-opacity: var(--svg-fill-opacity--0-8, 0.8);
  d: path("M6.876 3.134c.71 0 1.285.575 1.285 1.285v6.652c0 .644-.572 1.179-1.28 1.179c-.71 0-1.29-.527-1.29-1.171v-6.66c0-.71.575-1.285 1.285-1.285");
}

.ft5dv1b6b {
  fill: none;
}

.gbl0fgdri {
  d: path("M11.04 2.25H2.619c-.71 0-1.29.528-1.29 1.171c0 .644.58 1.172 1.29 1.172h8.42c.71 0 1.29-.528 1.29-1.172s-.58-1.171-1.29-1.171");
}

.gt6rl0ltw {
  stop-color: var(--svg-color--8842ec, #8842EC);
}

.haogwie1v {
  stop-color: var(--svg-color--41366a, #41366A);
}

.i8hjxcl1d {
  stop-color: var(--svg-color--7966c1, #7966C1);
}

.ic9nshbiv {
  stop-color: var(--svg-color--7b6bb7, #7B6BB7);
}

.igh9qd20m {
  stop-color: var(--svg-color--6537c4, #6537C4);
}

.illn__i5j {
  stop-color: var(--svg-color--7e5cce, #7E5CCE);
  stop-opacity: 0;
}

.jf_d_hb7h {
  stop-color: var(--svg-color--645599, #645599);
}

.jwp58ixzd {
  stop-color: var(--svg-color--7c6cba, #7C6CBA);
  stop-opacity: 0;
}

.k4ebrxg2z {
  stop-color: var(--svg-color--7c6fbc, #7C6FBC);
  stop-opacity: 0;
}

.k5iz2mdcj {
  stop-color: var(--svg-color--844edf, #844EDF);
}

.l34mbi91h {
  stop-color: var(--svg-color--8779c2, #8779C2);
  stop-opacity: 0;
}

.lkeurab-x {
  stop-color: var(--svg-color--897ec1, #897EC1);
}

.lvkaobcon {
  stop-color: var(--svg-color--7d70b3, #7D70B3);
}

.m_96fhbiq {
  stop-color: var(--svg-color--7a6bb7, #7A6BB7);
}

.m46f8vz9c {
  stop-color: var(--svg-color--8779c2, #8779C2);
}

.mf0352b6e {
  stop-color: var(--svg-color--a49ad8, #A49AD8);
  stop-opacity: 0;
}

.mp9-eubjy {
  stop-color: var(--svg-color--473c84, #473C84);
  stop-opacity: 0;
}

.n32m7gb3j {
  d: path("M14.895 6.252v-3.31l2.823 2.936l3.09-3.215v3.341L18.59 8.312c-.239.24-.552.349-.857.333a1.08 1.08 0 0 1-.858-.333z");
}

.nor3wl3_h {
  stop-color: var(--svg-color--a49ad8, #A49AD8);
}

.o7ze1ybns {
  d: path("M21.914 2.257c.619 0 1.126.527 1.126 1.17v7.645c0 .643-.485 1.178-1.104 1.178c-.618 0-1.125-.527-1.125-1.17V6.001l-2.221 2.31c-.239.24-.552.349-.857.333a1.08 1.08 0 0 1-.858-.333L14.893 6.25v4.822c0 .643-.507 1.17-1.126 1.17s-1.125-.527-1.125-1.17V3.436c0-.31.104-.613.328-.845c.327-.35.82-.427 1.23-.248c.134.054.253.14.357.248l3.16 3.287l3.161-3.287c.277-.28.68-.334 1.036-.334");
}

.ome1r60wv {
  fill-opacity: var(--svg-fill-opacity--0-8, 0.8);
  d: path("M21.914 2.257c.619 0 1.126.527 1.126 1.17v7.645c0 .643-.485 1.178-1.104 1.178c-.618 0-1.125-.527-1.125-1.17V6.001l-2.221 2.31c-.239.24-.552.349-.857.333a1.08 1.08 0 0 1-.858-.333L14.893 6.25v4.822c0 .643-.507 1.17-1.126 1.17s-1.125-.527-1.125-1.17V3.436c0-.31.104-.613.328-.845c.327-.35.82-.427 1.23-.248c.134.054.253.14.357.248l3.16 3.287l3.161-3.287c.277-.28.68-.334 1.036-.334");
}

.p9sc3pp2n {
  stop-color: var(--svg-color--7a66c3, #7A66C3);
}

.phf07y5lf {
  stop-color: var(--svg-color--6151a1, #6151A1);
}

.q8ei0-1mi {
  stop-color: var(--svg-color--473c84, #473C84);
}

.qpto43zmj {
  stop-color: var(--svg-color--7e5cce, #7E5CCE);
}

.rbon7fb2e {
  stop-color: var(--svg-color--7264a9, #7264A9);
}

.rqx193p1u {
  fill: var(--svg-color--8472c6, #8472C6);
  d: path("M21.914 2.257c.619 0 1.126.527 1.126 1.17v7.645c0 .643-.485 1.178-1.104 1.178c-.618 0-1.125-.527-1.125-1.17V6.001l-2.221 2.31c-.239.24-.552.349-.857.333a1.08 1.08 0 0 1-.858-.333L14.893 6.25v4.822c0 .643-.507 1.17-1.126 1.17s-1.125-.527-1.125-1.17V3.436c0-.31.104-.613.328-.845c.327-.35.82-.427 1.23-.248c.134.054.253.14.357.248l3.16 3.287l3.161-3.287c.277-.28.68-.334 1.036-.334");
}

.tcoi14v6o {
  stop-color: var(--svg-color--423473, #423473);
  stop-opacity: 0;
}

.ttge9qbbr {
  d: path("M6.876 3.134c.71 0 1.285.575 1.285 1.285v6.652c0 .644-.572 1.179-1.28 1.179c-.71 0-1.29-.527-1.29-1.171v-6.66c0-.71.575-1.285 1.285-1.285");
}

.txiyth_cn {
  stop-color: var(--svg-color--7c6cbc, #7C6CBC);
}

.u-3vz3bjc {
  stop-color: var(--svg-color--7e6ebc, #7E6EBC);
  stop-opacity: 0;
}

.uw6ct3bwa {
  stop-color: var(--svg-color--655898, #655898);
}

.uzo543nom {
  stop-color: var(--svg-color--8276bd, #8276BD);
}

.vlavj0bhr {
  stop-color: var(--svg-color--8778c2, #8778C2);
}

.wbbnthoze {
  stop-color: var(--svg-color--44357b, #44357B);
}

.wk-y_-1qb {
  stop-color: var(--svg-color--9c92d2, #9C92D2);
}

.xeoab1-yu {
  stop-color: var(--svg-color--483d85, #483D85);
}

.yr8_8rbhe {
  stop-color: var(--svg-color--9447fe, #9447FE);
  stop-opacity: 0;
}

.yv0g24i-p {
  stop-color: var(--svg-color--9447fe, #9447FE);
}

.z_afiqklu {
  stop-color: var(--svg-color--7b6bb9, #7B6BB9);
}

.zb7eih-wp {
  stop-color: var(--svg-color--9447fe, #9447FE);
  stop-opacity: 0.485;
}

.zn4jy973r {
  stop-color: var(--svg-color--7e6dc1, #7E6DC1);
}

.zo8vm2lqz {
  stop-color: var(--svg-color--7c6cbc, #7C6CBC);
  stop-opacity: 0;
}

</style>
