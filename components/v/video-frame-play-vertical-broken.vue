<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="r_0pl6b2k"/><path class="txon6o65c"/><path class="j8dd61s2u"/><path class="wc-mzxdmm"/><path class="mrypp-g4i"/><path class="cfl3_9b4r"/><path class="js5h9bc7i"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:video-frame-play-vertical-broken" /></template>
<style>
.cfl3_9b4r {
  d: path("M14 12C14 11.4722 13.4704 11.1162 12.4112 10.4043C11.3375 9.68271 10.8006 9.3219 10.4003 9.58682C10 9.85174 10 10.5678 10 12C10 13.4322 10 14.1483 10.4003 14.4132C10.8006 14.6781 11.3375 14.3173 12.4112 13.5957C13.4704 12.8838 14 12.5278 14 12Z");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.j8dd61s2u {
  d: path("M2 12L7 12M22 12L17 12");
}

.js5h9bc7i {
  d: path("M2 12C2 7.28595 2 4.92893 3.46447 3.46447C4.92893 2 7.28595 2 12 2C16.714 2 19.0711 2 20.5355 3.46447C21.352 4.28094 21.7133 5.37486 21.8731 7M22 12C22 16.714 22 19.0711 20.5355 20.5355C19.0711 22 16.714 22 12 22C7.28595 22 4.92893 22 3.46447 20.5355C2.64799 19.7191 2.28672 18.6251 2.12687 17");
}

.mrypp-g4i {
  d: path("M2 17L7 17M21.5 17L17 17");
}

.r_0pl6b2k {
  d: path("M17 2.5L17 21.5");
}

.txon6o65c {
  d: path("M7 2.5L7 21.5");
}

.wc-mzxdmm {
  d: path("M2.5 7L7 7M21.5 7L17 7");
}

</style>
