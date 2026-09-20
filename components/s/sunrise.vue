<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<radialGradient id="SVGwgpsubmf" cx="63.542" cy="78.723" r="88.912" gradientUnits="userSpaceOnUse"><stop offset=".275" class="hicm65bps"/><stop offset=".372" class="dcbsbeb8j"/><stop offset=".529" class="tqcegvbsx"/><stop offset=".631" class="b_dh6kngo"/><stop offset=".702" class="m1ymtwgod"/><stop offset=".79" class="lefuc8-zh"/><stop offset=".865" class="hak101bml"/><stop offset=".928" class="fb36z6-hf"/><stop offset=".987" class="hvwh6jp9j"/><stop offset="1" class="dezlefbvn"/></radialGradient><path fill="url(#SVGwgpsubmf)" class="qe7gt5x_i"/><path class="zlm_1ibun"/><path class="w6izaf4ew"/><radialGradient id="SVGjHY0zcvS" cx="35.001" cy="77.736" r="32.437" gradientUnits="userSpaceOnUse"><stop offset="0" class="bha333bzu"/><stop offset=".046" class="rp49j1b3r"/><stop offset=".155" class="oe9pdrcad"/><stop offset=".261" class="p8gnkub1w"/><stop offset=".36" class="kzluesggu"/><stop offset=".452" class="gydximp-r"/><stop offset=".528" class="s32q1nast"/><stop offset=".975" class="du7tgj6nn"/><stop offset="1" class="v44hmrg_j"/></radialGradient><path fill="url(#SVGjHY0zcvS)" class="rd_o8_bga"/><radialGradient id="SVGegJO5b0C" cx="34.733" cy="70.686" r="36.905" gradientUnits="userSpaceOnUse"><stop offset="0" class="bha333bzu"/><stop offset=".046" class="rp49j1b3r"/><stop offset=".155" class="oe9pdrcad"/><stop offset=".261" class="p8gnkub1w"/><stop offset=".36" class="kzluesggu"/><stop offset=".452" class="gydximp-r"/><stop offset=".528" class="s32q1nast"/><stop offset=".906" class="v44hmrg_j"/></radialGradient><path fill="url(#SVGegJO5b0C)" class="v6rh9ccaf"/><radialGradient id="SVGFuCfjcWj" cx="38.928" cy="59.148" r="44.193" gradientUnits="userSpaceOnUse"><stop offset="0" class="bha333bzu"/><stop offset=".046" class="rp49j1b3r"/><stop offset=".155" class="oe9pdrcad"/><stop offset=".261" class="p8gnkub1w"/><stop offset=".36" class="kzluesggu"/><stop offset=".452" class="gydximp-r"/><stop offset=".528" class="s32q1nast"/><stop offset=".897" class="v44hmrg_j"/></radialGradient><path fill="url(#SVGFuCfjcWj)" class="r1v-bqb5s"/><radialGradient id="SVGuhSjEb2n" cx="41.779" cy="49.682" r="51.324" gradientUnits="userSpaceOnUse"><stop offset="0" class="bha333bzu"/><stop offset=".033" class="rp49j1b3r"/><stop offset=".111" class="oe9pdrcad"/><stop offset=".186" class="p8gnkub1w"/><stop offset=".258" class="kzluesggu"/><stop offset=".324" class="gydximp-r"/><stop offset=".378" class="s32q1nast"/><stop offset=".757" class="v44hmrg_j"/></radialGradient><path fill="url(#SVGuhSjEb2n)" class="xe06vnb_v"/><radialGradient id="SVGcecwKeec" cx="44.695" cy="50.914" r="50.513" gradientUnits="userSpaceOnUse"><stop offset="0" class="bha333bzu"/><stop offset=".046" class="rp49j1b3r"/><stop offset=".155" class="oe9pdrcad"/><stop offset=".261" class="p8gnkub1w"/><stop offset=".36" class="kzluesggu"/><stop offset=".452" class="gydximp-r"/><stop offset=".528" class="s32q1nast"/><stop offset=".854" class="v44hmrg_j"/></radialGradient><path fill="url(#SVGcecwKeec)" class="a7p87f1qo"/><radialGradient id="SVGMXKZwdDP" cx="56.16" cy="45.789" r="42.264" gradientUnits="userSpaceOnUse"><stop offset="0" class="bha333bzu"/><stop offset=".046" class="rp49j1b3r"/><stop offset=".155" class="oe9pdrcad"/><stop offset=".261" class="p8gnkub1w"/><stop offset=".36" class="kzluesggu"/><stop offset=".452" class="gydximp-r"/><stop offset=".528" class="s32q1nast"/><stop offset=".976" class="v44hmrg_j"/></radialGradient><path fill="url(#SVGMXKZwdDP)" class="rywfembgm"/><radialGradient id="SVG2qwiGd8v" cx="64.665" cy="45.167" r="41.283" gradientUnits="userSpaceOnUse"><stop offset="0" class="bha333bzu"/><stop offset=".046" class="rp49j1b3r"/><stop offset=".155" class="oe9pdrcad"/><stop offset=".261" class="p8gnkub1w"/><stop offset=".36" class="kzluesggu"/><stop offset=".452" class="gydximp-r"/><stop offset=".528" class="s32q1nast"/><stop offset=".975" class="du7tgj6nn"/><stop offset="1" class="v44hmrg_j"/></radialGradient><path fill="url(#SVG2qwiGd8v)" class="byq_3obpg"/><radialGradient id="SVGOCu6le8O" cx="73.378" cy="46.619" r="44.476" gradientUnits="userSpaceOnUse"><stop offset="0" class="bha333bzu"/><stop offset=".04" class="rp49j1b3r"/><stop offset=".133" class="oe9pdrcad"/><stop offset=".224" class="p8gnkub1w"/><stop offset=".309" class="kzluesggu"/><stop offset=".388" class="gydximp-r"/><stop offset=".453" class="s32q1nast"/><stop offset=".959" class="v44hmrg_j"/></radialGradient><path fill="url(#SVGOCu6le8O)" class="ndvmx7gdk"/><radialGradient id="SVGoySTxcXk" cx="81.468" cy="49.523" r="47.227" gradientUnits="userSpaceOnUse"><stop offset="0" class="bha333bzu"/><stop offset=".046" class="rp49j1b3r"/><stop offset=".155" class="oe9pdrcad"/><stop offset=".261" class="p8gnkub1w"/><stop offset=".36" class="kzluesggu"/><stop offset=".452" class="gydximp-r"/><stop offset=".528" class="s32q1nast"/><stop offset=".926" class="v44hmrg_j"/></radialGradient><path fill="url(#SVGoySTxcXk)" class="r2mw7qbcv"/><radialGradient id="SVGW92DxbKa" cx="85.311" cy="52.263" r="49.025" gradientUnits="userSpaceOnUse"><stop offset="0" class="bha333bzu"/><stop offset=".037" class="rp49j1b3r"/><stop offset=".126" class="oe9pdrcad"/><stop offset=".212" class="p8gnkub1w"/><stop offset=".293" class="kzluesggu"/><stop offset=".368" class="gydximp-r"/><stop offset=".43" class="s32q1nast"/><stop offset=".832" class="v44hmrg_j"/></radialGradient><path fill="url(#SVGW92DxbKa)" class="cpf0ejb9h"/><radialGradient id="SVGe98HWc5r" cx="92.896" cy="62.144" r="35.226" gradientUnits="userSpaceOnUse"><stop offset="0" class="bha333bzu"/><stop offset=".046" class="rp49j1b3r"/><stop offset=".155" class="oe9pdrcad"/><stop offset=".261" class="p8gnkub1w"/><stop offset=".36" class="kzluesggu"/><stop offset=".452" class="gydximp-r"/><stop offset=".528" class="s32q1nast"/><stop offset="1" class="v44hmrg_j"/></radialGradient><path fill="url(#SVGe98HWc5r)" class="osvdgkofv"/><radialGradient id="SVGic6isdCp" cx="94.17" cy="70.686" r="35.972" gradientUnits="userSpaceOnUse"><stop offset="0" class="bha333bzu"/><stop offset=".046" class="rp49j1b3r"/><stop offset=".155" class="oe9pdrcad"/><stop offset=".261" class="p8gnkub1w"/><stop offset=".36" class="kzluesggu"/><stop offset=".452" class="gydximp-r"/><stop offset=".528" class="s32q1nast"/><stop offset="1" class="v44hmrg_j"/></radialGradient><path fill="url(#SVGic6isdCp)" class="xu9971fab"/><radialGradient id="SVG4SUBqbAa" cx="94.537" cy="82.092" r="31.836" gradientUnits="userSpaceOnUse"><stop offset="0" class="bha333bzu"/><stop offset=".046" class="rp49j1b3r"/><stop offset=".155" class="oe9pdrcad"/><stop offset=".261" class="p8gnkub1w"/><stop offset=".36" class="kzluesggu"/><stop offset=".452" class="gydximp-r"/><stop offset=".528" class="s32q1nast"/><stop offset=".942" class="v44hmrg_j"/></radialGradient><path fill="url(#SVG4SUBqbAa)" class="dzz1dhb9l"/><radialGradient id="SVGeucxncCH" cx="65.226" cy="68.515" r="54.923" gradientTransform="matrix(.00617 1 -2.3771 .0147 227.692 2.285)" gradientUnits="userSpaceOnUse"><stop offset=".246" class="ooguuacjb"/><stop offset=".34" class="hv3mg6_af"/><stop offset=".457" class="lc6ji8bxp"/><stop offset=".587" class="mhfzbjbzp"/><stop offset=".724" class="qygju2kff"/><stop offset=".867" class="xh--b9bua"/><stop offset=".997" class="d2g15lbnt"/></radialGradient><path fill="url(#SVGeucxncCH)" class="k299pucdb"/><path class="plmdxcgjz"/><path class="qddz71b9l"/><path class="gjj_9_smk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto:sunrise" /></template>
<style>
.a7p87f1qo {
  d: path("M29.96 3.89c-6.29 0-10.78.02-12.17.08c-.52.02-1.05.05-1.58.1l29.12 46.27a29 29 0 0 1 4.94-3.03z");
}

.b_dh6kngo {
  stop-color: var(--svg-color--ff9c97, #ff9c97);
}

.bha333bzu {
  stop-color: var(--svg-color--fff7b3, #fff7b3);
}

.byq_3obpg {
  d: path("M70.26 4.01c-3.82-.03-6.31-.09-10.16-.11l1.56 40.42c1.1-.08 2.23-.12 3.38-.1c1.1.02 2.19.09 3.25.22z");
}

.cpf0ejb9h {
  d: path("M124.13 23.3c.01-6.26.02-10.77.02-11.86c0-1.39-.45-2.56-1.41-3.52l-36.75 45a32.4 32.4 0 0 1 3.97 4.65z");
}

.d2g15lbnt {
  stop-color: var(--svg-color--1dc1e8, #1dc1e8);
}

.dcbsbeb8j {
  stop-color: var(--svg-color--ffc7ab, #ffc7ab);
}

.dezlefbvn {
  stop-color: var(--svg-color--e16870, #e16870);
}

.du7tgj6nn {
  stop-color: var(--svg-color--ffd525, #ffd525);
  stop-opacity: 0.052;
}

.dzz1dhb9l {
  d: path("M95.35 76.7c-.18 6.48-1.27 11.96-1.27 11.96l29.93-6.75s0-2.34.01-6.17z");
}

.fb36z6-hf {
  stop-color: var(--svg-color--f47e62, #f47e62);
}

.gjj_9_smk {
  fill: var(--svg-color--baf3fa, #baf3fa);
  d: path("M93.34 92.25c.09 1.86 1 2.93 4.15 3s6.15.07 7.5 0s2.84-.99 2.72-3c-.14-2.36-2.14-2.36-3.43-2.5s-6.86-.07-8.22-.07s-2.8 1.14-2.72 2.57m-76.48-1.64c0 2 1.64 2.43 3.57 2.5s5.07.07 6.36-.07s2.29-1.07 2.36-2.43s-1.29-2.22-3.07-2.22s-5.43.07-6.65.07c-1.21.01-2.57.94-2.57 2.15m12.22 4c-2.13.25-2.57 1.72-2.5 2.72s.86 2.22 2.64 2.22s6.22 0 7.5-.14c1.29-.14 1.72-1.36 1.79-2.57s-1-2.14-2.29-2.22c-1.28-.08-5.28-.22-7.14-.01");
}

.gydximp-r {
  stop-color: var(--svg-color--ffd62a, #ffd62a);
}

.hak101bml {
  stop-color: var(--svg-color--fc895c, #fc895c);
}

.hicm65bps {
  stop-color: var(--svg-color--ffd0af, #ffd0af);
}

.hv3mg6_af {
  stop-color: var(--svg-color--c5d6aa, #c5d6aa);
}

.hvwh6jp9j {
  stop-color: var(--svg-color--e56d6d, #e56d6d);
}

.k299pucdb {
  d: path("M124.15 79.02v37.72c0 4.15-3.37 7.52-7.52 7.52H11.32c-4.15 0-7.52-3.37-7.52-7.52V78.55z");
}

.kzluesggu {
  stop-color: var(--svg-color--ffda39, #ffda39);
}

.lc6ji8bxp {
  stop-color: var(--svg-color--b5d4b0, #b5d4b0);
}

.lefuc8-zh {
  stop-color: var(--svg-color--ff8c5a, #ff8c5a);
}

.m1ymtwgod {
  stop-color: var(--svg-color--ff947a, #ff947a);
}

.mhfzbjbzp {
  stop-color: var(--svg-color--9cd1b9, #9cd1b9);
}

.ndvmx7gdk {
  d: path("M90.45 4.21c-3.52-.03-7.37-.06-11.41-.09l-8.11 40.76c2.09.44 4.06 1.1 5.95 1.92z");
}

.oe9pdrcad {
  stop-color: var(--svg-color--ffe873, #ffe873);
}

.ooguuacjb {
  stop-color: var(--svg-color--cad7a8, #cad7a8);
}

.osvdgkofv {
  d: path("m124.08 48.54l.03-13.37l-32.79 24.52c1.05 1.79 1.89 3.68 2.55 5.62z");
}

.p8gnkub1w {
  stop-color: var(--svg-color--ffe051, #ffe051);
}

.plmdxcgjz {
  fill: var(--svg-color--fff, #fff);
  d: path("M35.72 85.04c-.12 2 1.5 3.43 4.5 3.5s46.6-.12 48.1-.07c2.36.07 4.29-1.07 4.15-3.43s-2.43-2.64-3.93-2.64c-1.01 0-18.44-.07-26.87-.07s-21.16.07-22.58.14s-3.23.21-3.37 2.57m4.51 9.5c-.09 2.43 1.93 2.86 4.5 2.93s12.79.07 19.8.07s18.3-.14 20.08-.14c1.5 0 3.14-1 3.07-2.93c-.06-1.51-.93-2.57-3.5-2.64s-22.37.07-29.02 0s-9.93 0-11.44 0c-1.49 0-3.42.85-3.49 2.71m8.44 8.33c.07 1.79 1.64 2.5 3.5 2.5s23.66.21 25.44.14c1.79-.07 2.93-1.29 3-2.72s-1.22-2.22-2.93-2.22s-24.66-.14-26.09-.07c-1.42.09-3 .66-2.92 2.37");
}

.qddz71b9l {
  fill: var(--svg-color--fff, #fff);
  d: path("M56.24 106.95c.16 1.43.71 2.5 3.29 2.57c2.57.07 10.29-.01 11.72-.07c1.57-.07 2.32-1.35 2.36-2.5c.07-1.93-1.72-2.36-1.72-2.36l-14.22.14s-1.57.93-1.43 2.22");
}

.qe7gt5x_i {
  d: path("M116.62 124.26H11.32c-4.15 0-7.52-3.37-7.52-7.52V11.44c0-4.15 3.37-7.52 7.52-7.52h105.3c4.15 0 7.52 3.37 7.52 7.52v105.3c.01 4.15-3.36 7.52-7.52 7.52");
}

.qygju2kff {
  stop-color: var(--svg-color--79cdc6, #79cdc6);
}

.r1v-bqb5s {
  d: path("M4.1 34.38c.01 4.07 0 8.5-.03 12.97l31.07 17.49c.63-1.92 1.45-3.74 2.42-5.47z");
}

.r2mw7qbcv {
  d: path("M111.37 4.59q-1.92-.135-4.17-.18c-1.68-.04-4.49-.07-8.1-.11L79.34 48.01c1.67.91 3.22 1.98 4.67 3.16z");
}

.rd_o8_bga {
  d: path("m3.85 74.01l-.08 6.88l30.82 2.55s-.97-3.21-1.09-7.67z");
}

.rp49j1b3r {
  stop-color: var(--svg-color--fff29e, #fff29e);
}

.rywfembgm {
  d: path("M51.45 3.95c-3.9-.02-7.69-.03-11.23-.04l12.63 42.3c1.92-.71 3.96-1.24 6.12-1.57z");
}

.s32q1nast {
  stop-color: var(--svg-color--ffd525, #ffd525);
}

.tqcegvbsx {
  stop-color: var(--svg-color--ffafa0, #ffafa0);
}

.v44hmrg_j {
  stop-color: var(--svg-color--ffd525, #ffd525);
  stop-opacity: 0;
}

.v6rh9ccaf {
  d: path("M4.02 56.26c-.03 3.98-.06 7.8-.1 11.19l29.65 5.34q.075-1.2.27-2.46c.13-.87.3-1.74.5-2.59z");
}

.w6izaf4ew {
  fill: var(--svg-color--fffdfa, #fffdfa);
  d: path("M55.64 57.24c-2.68-2.16-6.97.85-9.21 4.61c-2.02 3.39-2.95 7.77-.4 9.06c3.29 1.67 5.26-2.83 7.04-5.72c1.76-2.89 5.21-5.82 2.57-7.95");
}

.xe06vnb_v {
  d: path("M7.53 7.42C5.2 9.61 3.67 13.15 3.9 18.87c.02.61.05 1.32.07 2.1L39.2 56.74c1.17-1.68 2.53-3.22 4.03-4.62z");
}

.xh--b9bua {
  stop-color: var(--svg-color--4cc7d6, #4cc7d6);
}

.xu9971fab {
  d: path("m95.36 73.6l28.68-4.23c.01-3.27.01-6.98.02-10.93L94.6 67.87c.44 1.85.7 3.74.75 5.64c0 .03 0 .06.01.09");
}

.zlm_1ibun {
  fill: var(--svg-color--fff7b3, #fff7b3);
  d: path("M64.48 47.56c-14.65.06-27.84 12.2-27.66 28.21s11.47 27.83 28.16 27.64c17.13-.2 27.09-13.06 26.97-27.49c-.12-14.44-10.3-28.42-27.47-28.36");
}

</style>
