<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="hyvc97btq"/><path class="hm_s1kx4n"/><path class="y8umtvvdr"/><path class="z_9yqfbzq"/><path class="x1r8oybfd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:sheet-broken" /></template>
<style>
.hm_s1kx4n {
  d: path("M2.02881 8.66602L21.9711 8.66602");
}

.hyvc97btq {
  d: path("M2.02886 15.333L21.9713 15.333");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.x1r8oybfd {
  d: path("M21.9946 9.98076C21.9651 6.5798 21.774 4.70296 20.5355 3.46447C19.0711 2 16.714 2 12 2C7.28595 2 4.92893 2 3.46447 3.46447C2 4.92893 2 7.28595 2 12C2 16.714 2 19.0711 3.46447 20.5355C4.92893 22 7.28595 22 12 22C16.714 22 19.0711 22 20.5355 20.5355C21.774 19.297 21.9651 17.4202 21.9946 14.0191");
}

.y8umtvvdr {
  d: path("M15.333 8.66602L15.333 21.9711");
}

.z_9yqfbzq {
  d: path("M8.6665 8.66602L8.6665 21.9711");
}

</style>
