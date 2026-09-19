<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#ioGYGLe)" class="zmne6gb4t"/><path fill="url(#iE4eCod)" class="p_kzmdu-m"/><path fill="url(#iL7Njge)" class="a9bx0mzph"/><path fill="url(#ixmdPJe)" class="y4qo8nb1h"/><path stroke="url(#iNlalmc)" class="tium9eb7n"/><path fill="url(#iu2wnad)" class="j2c-q-b3h"/><path fill="url(#i37IFfe)" class="rh1h-9htm"/><path fill="url(#iGkhdKM)" class="jy83wpboe"/><path fill="url(#iUyzrbd)" class="h-_txvb1v"/><path stroke="url(#iFgZgte)" class="pp_-o2bzh"/><path fill="url(#iVAFQYc)" class="i-h5uew5t"/><rect fill="url(#ixZ76wt)" class="byh56mbdd"/><rect fill="url(#idl6nae)" class="fgrssg1eo"/><rect fill="url(#ixAHGHb)" class="fui3dmops"/><rect fill="url(#iYVh52d)" class="fui3dmops"/><path fill="url(#iXlBVsc)" class="eht_4mamr"/><rect fill="url(#iuNj3lb)" class="je8gyvble"/><rect fill="url(#iL4qXMd)" class="je8gyvble"/><rect fill="url(#iGpwfoe)" class="eoisbwjmw"/><rect fill="url(#iraFk1H)" class="eoisbwjmw"/><g filter="url(#icAtCpe)"><path stroke="url(#iS2btSc)" class="rye00fbbc"/></g><g filter="url(#iZuFTjc)"><path stroke="url(#i7jkKMb)" class="sa51-mbee"/></g><ellipse fill="url(#i8plZrc)" class="w-4qs4blz"/><ellipse fill="url(#i75jy3c)" class="b3vuvtb2m"/><path fill="url(#iNVOLdb)" clip-rule="evenodd" class="tdqwkbb_w"/><defs><linearGradient id="iE4eCod" x1="12" x2="4" y1="18" y2="18" gradientUnits="userSpaceOnUse"><stop class="rp8e12b0j"/><stop offset="1" class="msqtyubfv"/></linearGradient><linearGradient id="iL7Njge" x1="16" x2="16" y1="27" y2="31" gradientUnits="userSpaceOnUse"><stop class="m0dzvbb9i"/><stop offset="1" class="nd9spcwqz"/></linearGradient><linearGradient id="iNlalmc" x1="4" x2="4" y1="3.95" y2="13.05" gradientUnits="userSpaceOnUse"><stop class="pmdf6wn4g"/><stop offset="1" class="ioeu_cesb"/></linearGradient><linearGradient id="iu2wnad" x1="3" x2="3" y1="12" y2="23" gradientUnits="userSpaceOnUse"><stop class="mjwqwable"/><stop offset="1" class="qiivd6bsw"/></linearGradient><linearGradient id="i37IFfe" x1="15.998" x2="15.998" y1="17.701" y2="11.391" gradientUnits="userSpaceOnUse"><stop offset=".006" class="mw_4e64bb"/><stop offset="1" class="u3t5zknmy"/></linearGradient><linearGradient id="iGkhdKM" x1="15.998" x2="15.998" y1="25.686" y2="22.889" gradientUnits="userSpaceOnUse"><stop offset=".006" class="k610nrb0l"/><stop offset="1" class="m1sfvcbof"/></linearGradient><linearGradient id="iFgZgte" x1="29" x2="29" y1="4" y2="13.09" gradientUnits="userSpaceOnUse"><stop class="pmdf6wn4g"/><stop offset="1" class="ioeu_cesb"/></linearGradient><linearGradient id="ixAHGHb" x1="16" x2="14.5" y1="3" y2="6.5" gradientUnits="userSpaceOnUse"><stop class="iytes4csv"/><stop offset="1" class="n0hyftb9a"/></linearGradient><linearGradient id="iXlBVsc" x1="29" x2="29" y1="11.93" y2="22.94" gradientUnits="userSpaceOnUse"><stop class="g1pgvxl9g"/><stop offset="1" class="g6xod4boe"/></linearGradient><linearGradient id="iuNj3lb" x1="11.5" x2="9" y1="14" y2="14" gradientUnits="userSpaceOnUse"><stop class="l3r4zvnkw"/><stop offset="1" class="o18oq7b3q"/></linearGradient><linearGradient id="iGpwfoe" x1="23" x2="20.5" y1="14" y2="14" gradientUnits="userSpaceOnUse"><stop class="l3r4zvnkw"/><stop offset="1" class="o18oq7b3q"/></linearGradient><linearGradient id="iS2btSc" x1="3.5" x2="3.5" y1="7" y2="9" gradientUnits="userSpaceOnUse"><stop class="mdao7pyzi"/><stop offset="1" class="k3mijzbbm"/></linearGradient><linearGradient id="i7jkKMb" x1="28.5" x2="28.5" y1="7" y2="9" gradientUnits="userSpaceOnUse"><stop class="mdao7pyzi"/><stop offset="1" class="k3mijzbbm"/></linearGradient><radialGradient id="ioGYGLe" cx="0" cy="0" r="1" gradientTransform="rotate(141.911 10.515 10.065)scale(23.5053)" gradientUnits="userSpaceOnUse"><stop class="pk2b6-b5c"/><stop offset=".493" class="r7l84nlqf"/><stop offset="1" class="uo3ygebks"/></radialGradient><radialGradient id="ixmdPJe" cx="0" cy="0" r="1" gradientTransform="matrix(5 -.5 1.9111 19.11108 25 13.5)" gradientUnits="userSpaceOnUse"><stop class="cx5l0-bkm"/><stop offset="1" class="osd6sugsf"/></radialGradient><radialGradient id="iUyzrbd" cx="0" cy="0" r="1" gradientTransform="matrix(-.5 2 -2 -.5 4 3)" gradientUnits="userSpaceOnUse"><stop class="kkodhj6gc"/><stop offset=".441" class="i4pz_yfdt"/><stop offset="1" class="pgx2fdbvo"/></radialGradient><radialGradient id="iVAFQYc" cx="0" cy="0" r="1" gradientTransform="rotate(104.036 13.324 12.844)scale(2.13027)" gradientUnits="userSpaceOnUse"><stop class="kkodhj6gc"/><stop offset=".441" class="i4pz_yfdt"/><stop offset="1" class="pgx2fdbvo"/></radialGradient><radialGradient id="ixZ76wt" cx="0" cy="0" r="1" gradientTransform="matrix(-2.5 .5 -.68428 -3.42136 9.5 15)" gradientUnits="userSpaceOnUse"><stop class="bym35o1cy"/><stop offset="1" class="a3tidbb5i"/></radialGradient><radialGradient id="idl6nae" cx="0" cy="0" r="1" gradientTransform="matrix(-2.5 .5 -.68428 -3.42136 21 15)" gradientUnits="userSpaceOnUse"><stop class="bym35o1cy"/><stop offset="1" class="a3tidbb5i"/></radialGradient><radialGradient id="iYVh52d" cx="0" cy="0" r="1" gradientTransform="matrix(0 3 -10 0 16 4)" gradientUnits="userSpaceOnUse"><stop offset=".431" class="kqwmrcq8y"/><stop offset="1" class="jjpfxcbqn"/></radialGradient><radialGradient id="iL4qXMd" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.5 -1.14393 0 11 13.5)" gradientUnits="userSpaceOnUse"><stop class="l0a1wrz0y"/><stop offset="1" class="c2sc_b0gt"/></radialGradient><radialGradient id="iraFk1H" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.5 -1.14393 0 22.5 13.5)" gradientUnits="userSpaceOnUse"><stop class="l0a1wrz0y"/><stop offset="1" class="c2sc_b0gt"/></radialGradient><radialGradient id="i8plZrc" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.5 -1 0 29 13.5)" gradientUnits="userSpaceOnUse"><stop class="uugccrbmx"/><stop offset="1" class="eahycobqp"/></radialGradient><radialGradient id="i75jy3c" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.5 -.55944 0 29 16.5)" gradientUnits="userSpaceOnUse"><stop class="m4i23fbav"/><stop offset="1" class="hr3id03ds"/></radialGradient><radialGradient id="iNVOLdb" cx="0" cy="0" r="1" gradientTransform="rotate(90 8 12)" gradientUnits="userSpaceOnUse"><stop class="y8sgdz7kk"/><stop offset="1" class="o88ynsbhc"/></radialGradient><filter id="icAtCpe" width="1.25" height="7" x="3" y="4.5" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_31_1501" stdDeviation=".25"/></filter><filter id="iZuFTjc" width="1.25" height="7" x="28" y="4.5" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_31_1501" stdDeviation=".25"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:robot" /></template>
<style>
.a3tidbb5i {
  stop-color: var(--svg-color--342950, #342950);
  stop-opacity: 0;
}

.a9bx0mzph {
  d: path("M4 24h24a6 6 0 0 1-6 6H10a6 6 0 0 1-6-6");
}

.b3vuvtb2m {
  cx: 29px;
  cy: 16.5px;
  rx: 1px;
  ry: 4.5px;
}

.byh56mbdd {
  width: 4.5px;
  height: 6px;
  x: 7px;
  y: 12px;
  rx: 2px;
}

.bym35o1cy {
  stop-color: var(--svg-color--322649, #322649);
}

.c2sc_b0gt {
  stop-color: var(--svg-color--54c8ff, #54C8FF);
  stop-opacity: 0;
}

.cx5l0-bkm {
  stop-color: var(--svg-color--f0eaf6, #F0EAF6);
}

.eahycobqp {
  stop-color: var(--svg-color--ff6ebf, #FF6EBF);
  stop-opacity: 0;
}

.eht_4mamr {
  d: path("M28 22.94V11.93c1.1 0 2 .9 2 2v7.01c0 1.1-.9 2-2 2");
}

.eoisbwjmw {
  width: 2.5px;
  height: 5px;
  x: 20.5px;
  y: 12px;
  rx: 1.25px;
}

.fgrssg1eo {
  width: 4.5px;
  height: 6px;
  x: 18.5px;
  y: 12px;
  rx: 2px;
}

.ft5dv1b6b {
  fill: none;
}

.fui3dmops {
  width: 10px;
  height: 3px;
  x: 11px;
  y: 3px;
  rx: 1.5px;
}

.g1pgvxl9g {
  stop-color: var(--svg-color--ff30aa, #FF30AA);
}

.g6xod4boe {
  stop-color: var(--svg-color--ff2353, #FF2353);
}

.h-_txvb1v {
  d: path("M3.5 5a1.5 1.5 0 1 0 0-3a1.5 1.5 0 0 0 0 3");
}

.hr3id03ds {
  stop-color: var(--svg-color--ff73c1, #FF73C1);
  stop-opacity: 0;
}

.i-h5uew5t {
  d: path("M28.5 5.1a1.55 1.55 0 1 0 0-3.1a1.55 1.55 0 0 0 0 3.1");
}

.i4pz_yfdt {
  stop-color: var(--svg-color--ff2455, #FF2455);
}

.ioeu_cesb {
  stop-color: var(--svg-color--df2232, #DF2232);
}

.iytes4csv {
  stop-color: var(--svg-color--ffce2b, #FFCE2B);
}

.j2c-q-b3h {
  d: path("M4 12v11c-1.1 0-2-.9-2-1.998v-7.004C2 12.9 2.9 12 4 12");
}

.je8gyvble {
  width: 2.5px;
  height: 5px;
  x: 9px;
  y: 12px;
  rx: 1.25px;
}

.jjpfxcbqn {
  stop-color: var(--svg-color--673f13, #673F13);
}

.jy83wpboe {
  d: path("M18.528 26h-5.056C12.66 26 12 25.326 12 24.5s.66-1.5 1.472-1.5h5.056c.811 0 1.472.674 1.472 1.5s-.66 1.5-1.472 1.5");
}

.k3mijzbbm {
  stop-color: var(--svg-color--ff6db7, #FF6DB7);
  stop-opacity: 0;
}

.k610nrb0l {
  stop-color: var(--svg-color--39325e, #39325E);
}

.kkodhj6gc {
  stop-color: var(--svg-color--ff6c82, #FF6C82);
}

.kqwmrcq8y {
  stop-color: var(--svg-color--ca7e29, #CA7E29);
  stop-opacity: 0;
}

.l0a1wrz0y {
  stop-color: var(--svg-color--54c8ff, #54C8FF);
}

.l3r4zvnkw {
  stop-color: var(--svg-color--29b6fe, #29B6FE);
}

.m0dzvbb9i {
  stop-color: var(--svg-color--b17edb, #B17EDB);
  stop-opacity: 0;
}

.m1sfvcbof {
  stop-color: var(--svg-color--2b1831, #2B1831);
}

.m4i23fbav {
  stop-color: var(--svg-color--ff4b9c, #FF4B9C);
}

.mdao7pyzi {
  stop-color: var(--svg-color--ff96cb, #FF96CB);
}

.mjwqwable {
  stop-color: var(--svg-color--e93273, #E93273);
}

.msqtyubfv {
  stop-color: var(--svg-color--b4878d, #B4878D);
}

.mw_4e64bb {
  stop-color: var(--svg-color--443e75, #443E75);
}

.n0hyftb9a {
  stop-color: var(--svg-color--d9862d, #D9862D);
}

.nd9spcwqz {
  stop-color: var(--svg-color--a56bd6, #A56BD6);
}

.o18oq7b3q {
  stop-color: var(--svg-color--1769a8, #1769A8);
}

.o88ynsbhc {
  stop-color: var(--svg-color--ffef66, #FFEF66);
  stop-opacity: 0;
}

.osd6sugsf {
  stop-color: var(--svg-color--e7e0ef, #E7E0EF);
  stop-opacity: 0;
}

.p_kzmdu-m {
  d: path("M4 12a6 6 0 0 1 6-6h2v24h-2a6 6 0 0 1-6-6z");
}

.pgx2fdbvo {
  stop-color: var(--svg-color--d9206c, #D9206C);
}

.pk2b6-b5c {
  stop-color: var(--svg-color--eeebf0, #EEEBF0);
}

.pmdf6wn4g {
  stop-color: var(--svg-color--ea248a, #EA248A);
}

.pp_-o2bzh {
  stroke-miterlimit: 10;
  d: path("M28.5 4v9.09");
}

.qiivd6bsw {
  stop-color: var(--svg-color--d21844, #D21844);
}

.r7l84nlqf {
  stop-color: var(--svg-color--d1bee3, #D1BEE3);
}

.rh1h-9htm {
  d: path("M22.753 18.5H9.247A4.257 4.257 0 0 1 5 14.25A4.257 4.257 0 0 1 9.247 10h13.506A4.257 4.257 0 0 1 27 14.25c0 2.331-1.918 4.25-4.247 4.25");
}

.rp8e12b0j {
  stop-color: var(--svg-color--d5b2c0, #D5B2C0);
  stop-opacity: 0;
}

.rye00fbbc {
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M3.625 5v6");
}

.sa51-mbee {
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M28.625 5v6");
}

.tdqwkbb_w {
  fill-rule: evenodd;
  d: path("M19.776 3.025a1.5 1.5 0 0 1 1.199 1.2a1 1 0 1 1-1.2-1.2");
}

.tium9eb7n {
  stroke-miterlimit: 10;
  d: path("M3.5 3.95v9.1");
}

.u3t5zknmy {
  stop-color: var(--svg-color--2f1a3b, #2F1A3B);
}

.uo3ygebks {
  stop-color: var(--svg-color--d0bce2, #D0BCE2);
}

.uugccrbmx {
  stop-color: var(--svg-color--ff72c1, #FF72C1);
}

.w-4qs4blz {
  cx: 29px;
  cy: 13.5px;
  rx: 1px;
  ry: 1.5px;
}

.y4qo8nb1h {
  d: path("M20 6h2a6 6 0 0 1 6 6v12a6 6 0 0 1-6 6h-2z");
}

.y8sgdz7kk {
  stop-color: var(--svg-color--ffea60, #FFEA60);
}

.zmne6gb4t {
  d: path("M22.05 30H9.95C6.66 30 4 27.34 4 24.05V12.03C4 8.7 6.7 6 10.03 6h11.95C25.3 6 28 8.7 28 12.03v12.03c0 3.28-2.66 5.94-5.95 5.94");
}

</style>
