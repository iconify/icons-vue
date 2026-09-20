<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<defs><linearGradient id="SVGA3G7hdNW" x1="55.271%" x2="39.509%" y1="73.825%" y2="35.404%"><stop offset="0%" class="bp5yk2bov"/><stop offset="6%" class="de6tj9u0b"/><stop offset="33%" class="zx0ei7d-u"/><stop offset="58%" class="kiioodymg"/><stop offset="81%" class="uq8fqgjso"/><stop offset="100%" class="hri_srbgw"/></linearGradient><linearGradient id="SVGVIG0uefO" x1="19.047%" x2="50.141%" y1="2.917%" y2="36.328%"><stop offset="0%" class="gp61sbbkt"/><stop offset="100%" class="bp5yk2bov"/></linearGradient><linearGradient id="SVGcUl1Wb6S" x1="9.775%" x2="73.277%" y1="8%" y2="97.512%"><stop offset="0%" class="gp61sbbkt"/><stop offset="30%" class="bp5yk2bov"/><stop offset="63%" class="bp5yk2bov"/><stop offset="64%" class="de6tj9u0b"/><stop offset="70%" class="zx0ei7d-u"/><stop offset="76%" class="kiioodymg"/><stop offset="81%" class="uq8fqgjso"/><stop offset="85%" class="hri_srbgw"/></linearGradient></defs><path fill="url(#SVGA3G7hdNW)" class="nv483-2db"/><path fill="url(#SVGVIG0uefO)" class="c1mpd3rei"/><path fill="url(#SVGcUl1Wb6S)" class="eo1k9obfr"/><path class="dkwhibcnh"/><path class="io3rz4bjx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:rubymine" /></template>
<style>
.bp5yk2bov {
  stop-color: var(--svg-color--fe2857, #fe2857);
}

.c1mpd3rei {
  d: path("M210.72 91.867L93.733 22.533l116.987 137.12z");
}

.de6tj9u0b {
  stop-color: var(--svg-color--fe3052, #fe3052);
}

.dkwhibcnh {
  d: path("M50.667 48h160v160h-160z");
}

.eo1k9obfr {
  d: path("m106.56 249.333l95.68-12.746l-14.853-28.56h23.333v-48.374L93.707 22.32L0 45.333l.107 134.4L53.973 256l52.294-6.64l.24-.027z");
}

.gp61sbbkt {
  stop-color: var(--svg-color--6b57ff, #6b57ff);
}

.hri_srbgw {
  stop-color: var(--svg-color--fc801d, #fc801d);
}

.io3rz4bjx {
  fill: var(--svg-color--fff, #fff);
  d: path("M70.613 177.76h60v10h-60zm59.28-109.84h14.267l15.813 25.44l15.814-25.44h14.266v60.133h-13.146V88.8l-16.934 25.68h-.346L142.88 89.067v38.986h-12.987zM70.667 68h27.466q11.414 0 17.494 6.08a18.67 18.67 0 0 1 5.146 13.733V88a18.67 18.67 0 0 1-3.573 11.867a20.64 20.64 0 0 1-9.307 6.746l14.694 21.334H107.12L94.667 109.52H83.76v18.453H70.667zm26.666 29.093a11 11 0 0 0 7.387-2.426a8 8 0 0 0 2.667-6.187v-.16a7.6 7.6 0 0 0-2.667-6.427a12.08 12.08 0 0 0-7.627-2.16h-13.28v17.254z");
}

.kiioodymg {
  stop-color: var(--svg-color--fc6c2a, #fc6c2a);
}

.nv483-2db {
  d: path("m212.907 0l-73.254 26.24L81.92 0L62.907 47.893H50.613V189.28l177.787 1.547l27.6-140.8z");
}

.uq8fqgjso {
  stop-color: var(--svg-color--fc7b20, #fc7b20);
}

.zx0ei7d-u {
  stop-color: var(--svg-color--fd533b, #fd533b);
}

</style>
