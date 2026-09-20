<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="hgwt8qbxp"/><radialGradient id="SVGwAkjOd5Y" cx="52.551" cy="68.978" r="47.532" gradientTransform="matrix(1 0 0 -1.1901 0 141.11)" gradientUnits="userSpaceOnUse"><stop offset=".794" class="qpo2vg_rh"/><stop offset="1" class="g00j4bcaa"/></radialGradient><path fill="url(#SVGwAkjOd5Y)" class="c29oxcbxn"/><radialGradient id="SVGq5B17bfp" cx="53.328" cy=".282" r="68.219" gradientTransform="matrix(1 0 0 -.6035 0 127.888)" gradientUnits="userSpaceOnUse"><stop offset=".559" class="sl8ua6bht"/><stop offset="1" class="l_ukgm8gc"/></radialGradient><path fill="url(#SVGq5B17bfp)" class="etru7qb7k"/><linearGradient id="SVGS1G9qeUd" x1="87.922" x2="102.38" y1="13.052" y2="11.137" gradientTransform="matrix(1 0 0 -1 0 128)" gradientUnits="userSpaceOnUse"><stop offset="0" class="sed7b7o5x"/><stop offset=".788" class="hunkxc7oa"/></linearGradient><path fill="url(#SVGS1G9qeUd)" class="bt4rg9b-v"/><path class="c0kv8bc1k"/><linearGradient id="SVGc8VwAd3S" x1="52.21" x2="52.21" y1="22.296" y2="3.267" gradientTransform="matrix(1 0 0 -1 0 128)" gradientUnits="userSpaceOnUse"><stop offset=".003" class="mo-c96pwm"/><stop offset=".333" class="zx1i4kjds"/><stop offset=".941" class="qumfb1b0t"/><stop offset="1" class="tux77cbot"/></linearGradient><path fill="url(#SVGc8VwAd3S)" class="yp7cy6bww"/><linearGradient id="SVGfc3mnsUu" x1="38.665" x2="38.665" y1="10.657" y2="30.86" gradientTransform="matrix(1 0 0 -1 0 128)" gradientUnits="userSpaceOnUse"><stop offset=".335" class="ohm06yblq"/><stop offset=".668" class="nmuty9thj"/><stop offset=".987" class="ip0ngccya"/></linearGradient><path fill="url(#SVGfc3mnsUu)" class="vvbr19b8e"/><linearGradient id="SVGOehQpbvA" x1="38.553" x2="38.553" y1="10.657" y2="30.86" gradientTransform="matrix(-1 0 0 -1 104.157 128)" gradientUnits="userSpaceOnUse"><stop offset=".335" class="ohm06yblq"/><stop offset=".668" class="nmuty9thj"/><stop offset=".987" class="ip0ngccya"/></linearGradient><path fill="url(#SVGOehQpbvA)" class="hrrajob-b"/><path class="upryfqb8e"/><linearGradient id="SVGoypXtcAD" x1="97.973" x2="123.716" y1="22.785" y2="19.374" gradientTransform="matrix(1 0 0 -1 0 128)" gradientUnits="userSpaceOnUse"><stop offset=".437" class="sl8ua6bht"/><stop offset="1" class="l_ukgm8gc"/></linearGradient><path fill="url(#SVGoypXtcAD)" class="xlu291pqg"/><linearGradient id="SVGGoJxjs1m" x1="118.567" x2="96.091" y1="75.431" y2="22.72" gradientTransform="matrix(1 0 0 -1 0 128)" gradientUnits="userSpaceOnUse"><stop offset="0" class="ebvzorzlx"/><stop offset=".083" class="pz8rxab8d"/><stop offset=".674" class="du2ie8b3s"/><stop offset="1" class="ibo9lk-wv"/></linearGradient><path fill="url(#SVGGoJxjs1m)" class="r40lp11ju"/><radialGradient id="SVGwIJVedkX" cx="112.423" cy="39.875" r="25.366" gradientTransform="rotate(193.308 1.935 51.896)scale(-1 1)" gradientUnits="userSpaceOnUse"><stop offset="0" class="hw4z69b5r"/><stop offset=".205" class="feqh3t37a"/><stop offset=".537" class="qld3g178y"/><stop offset=".95" class="b58bblbnd"/><stop offset="1" class="wpq-rwbig"/></radialGradient><path fill="url(#SVGwIJVedkX)" class="dt-2yrx8m"/><path class="qi5nomb4d"/><path class="o1rmzfb-y"/><path class="gh3y5--hr"/><ellipse transform="rotate(-68.482 95.976 105.65)" class="zzi8bib0e"/><ellipse transform="rotate(-68.507 118.369 49.348)" class="jf20fw4ar"/><path class="h-hxa7bnz"/><path class="yekff7b3b"/><path class="y_66tmbiq"/><g class="d2ol71wkq"><ellipse class="upfqbpb1l"/><ellipse class="jlznpebxq"/></g><linearGradient id="SVG6BNvad4g" x1="51.654" x2="51.654" y1="83.691" y2="59.498" gradientTransform="matrix(1 0 0 -1 0 128)" gradientUnits="userSpaceOnUse"><stop offset=".203" class="uqm7_ibdb"/><stop offset="1" class="rfr131bdw"/></linearGradient><path fill="url(#SVG6BNvad4g)" class="vl8d6sxdn"/><linearGradient id="SVGAghE0b2o" x1="80.209" x2="80.209" y1="72.219" y2="84.847" gradientTransform="matrix(1 0 0 -1 0 128)" gradientUnits="userSpaceOnUse"><stop offset="0" class="ip0ngccya"/><stop offset="1" class="ohm06yblq"/></linearGradient><path fill="url(#SVGAghE0b2o)" class="bl4v7gbum"/><linearGradient id="SVG7J9M4dul" x1="24.041" x2="24.041" y1="72.386" y2="84.508" gradientTransform="matrix(1 0 0 -1 0 128)" gradientUnits="userSpaceOnUse"><stop offset="0" class="ip0ngccya"/><stop offset="1" class="ohm06yblq"/></linearGradient><path fill="url(#SVG7J9M4dul)" class="gn75d7bjr"/><radialGradient id="SVGAefTnexY" cx="52.111" cy="71.87" r="22.896" gradientTransform="matrix(0 1 1.4084 0 -49.11 4.017)" gradientUnits="userSpaceOnUse"><stop offset="0" class="sl8ua6bht"/><stop offset=".676" class="rwhk7-m5g"/><stop offset="1" class="ohm06yblq"/></radialGradient><path fill="url(#SVGAefTnexY)" class="q69_7qjno"/><path class="k2d0blbzn"/><radialGradient id="SVG77oYEd3c" cx="52.885" cy="64.954" r="49.788" gradientTransform="matrix(1 0 0 -1.2135 0 141.87)" gradientUnits="userSpaceOnUse"><stop offset=".794" class="qpo2vg_rh"/><stop offset="1" class="g00j4bcaa"/></radialGradient><path fill="url(#SVG77oYEd3c)" class="ua7n5pbsq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto:woman-scientist-dark-skin-tone" /></template>
<style>
.b58bblbnd {
  stop-color: var(--svg-color--ad4cbe, #ad4cbe);
}

.bl4v7gbum {
  d: path("M88.28 54.76c.01.67-.19 1.32-.57 1.87l-5.47 8.05c-2.06 2.85-9.3 4.43-9.3 4.43l8.18-9.14l-1.56-11.5l-7.43-5.8s3.07.3 5.24.3s4.33 1.39 5.44 2.16l4.02 2.77c.88.61 1.4 1.6 1.41 2.67z");
}

.bt4rg9b-v {
  d: path("m90.03 105.14l-5.82 19.41h15.83v-3.04c0-7.05-3.87-12.43-10.01-16.37");
}

.c0kv8bc1k {
  fill: var(--svg-color--3c2b24, #3c2b24);
  d: path("M52 92.53h-9.08v9.98c0 4.51 3.7 8.17 8.26 8.17h1.65c4.56 0 8.26-3.66 8.26-8.17v-9.98z");
}

.c29oxcbxn {
  d: path("M53.12 3.45c-41.01 0-40.68 37.92-40.68 38.52c0 24.56 1.88 59.25 11.71 72.9c3.9 5.41 11.43 5.71 11.43 5.71l16.97-.03l16.97.03s7.54-.3 11.43-5.71c9.83-13.65 11.71-48.34 11.71-72.9c0-.6 1.47-38.52-39.54-38.52");
}

.d2ol71wkq {
  fill: var(--svg-color--1a1717, #1a1717);
}

.dt-2yrx8m {
  d: path("M106.89 111.57c-5.64-2.2-17.38-6.85-23.03-9.14c-1.53-.63-1.93-2.6-.77-3.77l7.43-7.49l19.51-.94v19.19c.01 1.62-1.62 2.74-3.14 2.15");
  opacity: var(--svg-opacity--0-8, 0.8);
}

.du2ie8b3s {
  stop-color: var(--svg-color--8dd8fa, #8dd8fa);
  stop-opacity: 0.935;
}

.ebvzorzlx {
  stop-color: var(--svg-color--b3e5fc, #b3e5fc);
  stop-opacity: 0.8;
}

.etru7qb7k {
  d: path("M51.92 96.45c-23.62.07-48.11 7.33-48.11 25.05v3.04h96.23v-3.04c0-17.72-24.5-24.98-48.12-25.05");
}

.feqh3t37a {
  stop-color: var(--svg-color--ca8ad5, #ca8ad5);
}

.g00j4bcaa {
  stop-color: var(--svg-color--444140, #444140);
}

.gh3y5--hr {
  fill: var(--svg-color--26a69a, #26a69a);
  d: path("M99.61 71.23c-.72.13-1.28.71-1.44 1.43l-.07.31l4.18-1.43c-.98-.46-1.95-.44-2.67-.31m5.08-4.81c-.57-.63-1.23-.99-1.82-1.2c-.94-.33-1.98.07-2.5.92zm3.29-6.05c-.73-.29-1.6-.07-2.04.58c-.01.02-.02.04-.03.05c1.78.22 4.45 1.34 4.45 1.34c-.54-1.06-1.56-1.65-2.38-1.97");
}

.gn75d7bjr {
  d: path("M15.97 54.76c-.01.67.19 1.32.57 1.87L22 64.68c2.06 2.85 9.3 4.43 9.3 4.43l-8.18-9.14l1.56-11.5l7.43-5.8s-3.07.3-5.24.3s-4.33 1.39-5.44 2.16l-4.02 2.77c-.88.61-1.4 1.6-1.41 2.67z");
}

.h-hxa7bnz {
  fill: var(--svg-color--70534a, #70534a);
  d: path("M52.11 16.04c-17.2 0-33.13 12.79-33.13 39.91c0 21.78 13.49 34.67 25.23 38.83c2.8.99 5.5 1.49 7.9 1.49c2.38 0 5.07-.49 7.85-1.47c11.76-4.14 25.28-17.03 25.28-38.84c0-27.13-15.93-39.92-33.13-39.92");
}

.hgwt8qbxp {
  fill: var(--svg-color--232020, #232020);
  d: path("M53.12 3.45c-41.01 0-40.68 37.92-40.68 38.52c0 24.56 1.88 59.25 11.71 72.9c3.9 5.41 11.43 5.71 11.43 5.71l16.97-.03l16.97.03s7.54-.3 11.43-5.71c9.83-13.65 11.71-48.34 11.71-72.9c0-.6 1.47-38.52-39.54-38.52");
}

.hrrajob-b {
  d: path("M61.22 96.77c5.92.43 8.69.94 8.69.94l3.13 7.3l-5.25 4.39l4.88 6.15l-7.12 9h-7.38z");
}

.hunkxc7oa {
  stop-color: var(--svg-color--9e9e9e, #9e9e9e);
}

.hw4z69b5r {
  stop-color: var(--svg-color--ce93d8, #ce93d8);
}

.ibo9lk-wv {
  stop-color: var(--svg-color--81d4fa, #81d4fa);
}

.ip0ngccya {
  stop-color: var(--svg-color--bdbdbd, #bdbdbd);
}

.jf20fw4ar {
  cx: 118.37px;
  cy: 49.35px;
  fill: var(--svg-color--81d4fa, #81d4fa);
  rx: 3.09px;
  ry: 5.73px;
}

.jlznpebxq {
  cx: 67.68px;
  cy: 59.02px;
  rx: 4.93px;
  ry: 5.1px;
}

.k2d0blbzn {
  fill: var(--svg-color--232020, #232020);
  d: path("M53.12 3.45c-41.01 0-40.68 37.92-40.68 38.52c0 7.76.19 16.53.75 25.32l6.72-.02c-.06-2.92 1.99-20.97 8.08-22.34C50.35 39.9 63 28.04 63 28.04c3.29 7.18 13.58 14.19 17.27 16.86c3.03 2.19 3.96 18.55 3.9 22.38h7.71c0-.05.02-.1.02-.16c.56-8.75.74-17.46.74-25.17c.02-.58 1.49-38.5-39.52-38.5");
}

.l_ukgm8gc {
  stop-color: var(--svg-color--c6c6c6, #c6c6c6);
}

.mo-c96pwm {
  stop-color: var(--svg-color--80cbc4, #80cbc4);
}

.nmuty9thj {
  stop-color: var(--svg-color--d0d0d0, #d0d0d0);
}

.o1rmzfb-y {
  fill: var(--svg-color--80cbc4, #80cbc4);
  d: path("M98.74 80.1s-2.53-2.14-2.52-4.09c.01-1.56 1.89-3.04 1.89-3.04s-1.8-2.77-1.14-4.28c.94-2.14 3.41-2.55 3.41-2.55s-1.12-2.79.65-4.43c1.26-1.17 4.9-.68 4.9-.68s.36-4.58 4.82-3.43c1.74.45 7.91 3.99 10.21 11.46c1.44 4.67 2 6.06 1.54 13.06c-.2 2.97-7.71 2.97-10.54 1.95c-7.05-2.54-9.05-5.64-10.02-5.62c-.98.01-3.2 1.65-3.2 1.65");
}

.ohm06yblq {
  stop-color: var(--svg-color--e0e0e0, #e0e0e0);
}

.pz8rxab8d {
  stop-color: var(--svg-color--aee3fc, #aee3fc);
  stop-opacity: 0.817;
}

.q69_7qjno {
  d: path("M71.58 45.63c1.1 0 2.93.35 4.48 1.34c2.1 1.34 2.16 2.89 2.18 3.4c.03.77.06 1.51.1 2.25c.1 2.31.2 4.49.2 6.61c0 4.35-3.91 7.38-9.5 7.38c-3.95 0-8.42-3.33-10.46-5.57c-1.6-1.75-3.96-2.76-6.48-2.76s-4.88 1.01-6.48 2.76c-2.04 2.24-6.51 5.57-10.46 5.57c-5.59 0-9.5-3.03-9.5-7.38c0-2.13.1-4.31.2-6.61c.03-.74.07-1.49.1-2.25c.02-.51.08-2.06 2.18-3.4c1.55-.99 3.38-1.34 4.48-1.34zm0-3H32.64c-3.58 0-9.44 2.3-9.66 7.62c-.13 3.2-.3 6.1-.3 8.99c0 6 5.21 10.38 12.5 10.38c5 0 10.15-3.78 12.67-6.55c1.08-1.18 2.67-1.78 4.26-1.78s3.19.6 4.26 1.78c2.53 2.77 7.67 6.55 12.67 6.55c7.29 0 12.5-4.38 12.5-10.38c0-2.88-.17-5.79-.3-8.99c-.21-5.32-6.07-7.62-9.66-7.62");
}

.qi5nomb4d {
  fill: var(--svg-color--fff, #fff);
  d: path("m96.85 100.28l.773-1.845l6.272 2.626l-.772 1.845zm2.015-5.444l.773-1.845l6.272 2.626l-.772 1.845zm2.035-5.439l.772-1.845l6.273 2.626l-.773 1.845zm2.02-5.437l.773-1.845l6.272 2.626l-.772 1.845zm2.016-5.445l.773-1.844l6.272 2.626l-.772 1.845zm2.024-5.435l.772-1.846l6.273 2.626l-.772 1.845zm2.024-5.44l.772-1.846l6.273 2.626l-.772 1.845zm2.504-6.325l.772-1.845l6.273 2.625l-.772 1.845zm2.025-5.444l.772-1.845l6.273 2.626l-.772 1.845z");
}

.qld3g178y {
  stop-color: var(--svg-color--bf73cc, #bf73cc);
}

.qpo2vg_rh {
  stop-color: var(--svg-color--444140, #444140);
  stop-opacity: 0;
}

.qumfb1b0t {
  stop-color: var(--svg-color--51b8ae, #51b8ae);
}

.r40lp11ju {
  d: path("M110.49 113.13c-2.27 1.4-9.11.12-15.75-2.25c-5.12-1.83-9.23-4.16-9.27-4.17c-.53-.25-5.5-2.95-5.5-5.74c0-2.32 1.96-3.89 2.44-4.43l.1-.1l17.46-17.59l13.14-31.8l.02-.01s2.36-.81 5.67.49s5.01 3.46 5.01 3.46l-.02.01l-11.85 32.62s.03 23.38 0 25.39c-.04 2.72-.36 3.45-1.45 4.12");
  opacity: var(--svg-opacity--0-86, 0.86);
}

.rfr131bdw {
  stop-color: var(--svg-color--b3e5fc, #b3e5fc);
  stop-opacity: 0.2;
}

.rwhk7-m5g {
  stop-color: var(--svg-color--eee, #eee);
}

.sed7b7o5x {
  stop-color: var(--svg-color--9e9e9e, #9e9e9e);
  stop-opacity: 0;
}

.sl8ua6bht {
  stop-color: var(--svg-color--f5f5f5, #f5f5f5);
}

.tux77cbot {
  stop-color: var(--svg-color--4db6ac, #4db6ac);
}

.ua7n5pbsq {
  d: path("M53.12 3.45c-41.01 0-40.68 37.92-40.68 38.52c0 7.76.19 16.53.75 25.32l6.72-.02c-.06-2.92 1.99-20.97 8.08-22.34C50.35 39.9 63 28.04 63 28.04c3.29 7.18 13.58 14.19 17.27 16.86c3.03 2.19 3.96 18.55 3.9 22.38h7.71c0-.05.02-.1.02-.16c.56-8.75.74-17.46.74-25.17c.02-.58 1.49-38.5-39.52-38.5");
}

.upfqbpb1l {
  cx: 36.54px;
  cy: 59.02px;
  rx: 4.93px;
  ry: 5.1px;
}

.upryfqb8e {
  fill: var(--svg-color--80cbc4, #80cbc4);
  d: path("M122.32 74.01c1.14 7.79-.11 16.87-.11 16.87l-10.26-.9s-.39-5.91 0-5.92z");
}

.uqm7_ibdb {
  stop-color: var(--svg-color--b3e5fc, #b3e5fc);
  stop-opacity: 0.5;
}

.vl8d6sxdn {
  d: path("M31.1 44.31h42.65l5.79 5.1v15.03s-3.94 5.5-13.44 3.19s-8.23-8.05-13.88-8.05s-8.25 9.17-20.62 8.92c0 0-6.38-.56-7.56-4.56l-.27-16.61z");
}

.vvbr19b8e {
  d: path("M43.05 96.77c-5.92.43-8.69.94-8.69.94l-3.13 7.3l5.25 4.39l-4.88 6.15l7.12 9h7.38z");
}

.wpq-rwbig {
  stop-color: var(--svg-color--ab47bc, #ab47bc);
}

.xlu291pqg {
  d: path("M111.99 88.35c-6.66-.81-9.59-1.6-9.59-1.6l-11.34 37.8h28.19l4.14-36.21s-3.15 1.01-11.4.01");
}

.y_66tmbiq {
  fill: var(--svg-color--1a1717, #1a1717);
  d: path("M60.53 76.35c-3.19 1.89-13.63 1.89-16.81 0c-1.83-1.09-3.7.58-2.94 2.24c.75 1.63 6.44 5.42 11.37 5.42s10.55-3.79 11.3-5.42c.75-1.67-1.09-3.33-2.92-2.24M43.77 49.97c-.93-1.23-3.07-3.01-7.23-3.01s-6.31 1.79-7.23 3.01c-.41.54-.31 1.17-.02 1.55c.26.35 1.04.68 1.9.39s2.54-1.16 5.35-1.18c2.81.02 4.49.89 5.35 1.18s1.64-.03 1.9-.39c.29-.37.39-1-.02-1.55m31.15 0c-.93-1.23-3.07-3.01-7.23-3.01s-6.31 1.79-7.23 3.01c-.41.54-.31 1.17-.02 1.55c.26.35 1.04.68 1.9.39s2.54-1.16 5.35-1.18c2.81.02 4.49.89 5.35 1.18s1.64-.03 1.9-.39c.28-.37.38-1-.02-1.55");
}

.yekff7b3b {
  fill: var(--svg-color--33251f, #33251f);
  d: path("M55.86 68.26c-.11-.04-.21-.07-.32-.08h-7.08c-.11.01-.22.04-.32.08c-.64.26-.99.92-.69 1.63s1.71 2.69 4.55 2.69s4.25-1.99 4.55-2.69s-.05-1.37-.69-1.63");
}

.yp7cy6bww {
  d: path("M62.78 105.7H41.64l2.42 18.85h16.56z");
}

.zx1i4kjds {
  stop-color: var(--svg-color--73c6be, #73c6be);
}

.zzi8bib0e {
  cx: 95.98px;
  cy: 105.65px;
  fill: var(--svg-color--8f5d9b, #8f5d9b);
  rx: 3.35px;
  ry: 14.43px;
}

</style>
