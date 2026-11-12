<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="hyvc97btq"/><path class="ck53_x6oq"/><path class="yklwhpb-j"/><path class="cm4zj5gvq"/><path class="xvjk-cbox"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:sheet-linear" /></template>
<style>
.ck53_x6oq {
  d: path("M2.02881 8.6665L21.9711 8.6665");
}

.cm4zj5gvq {
  d: path("M8.6665 8.66589L8.6665 21.971");
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

.xvjk-cbox {
  d: path("M12 22C7.28595 22 4.92893 22 3.46447 20.5355C2 19.0711 2 16.714 2 12C2 7.28595 2 4.92893 3.46447 3.46447C4.92893 2 7.28595 2 12 2C16.714 2 19.0711 2 20.5355 3.46447C22 4.92893 22 7.28595 22 12C22 16.714 22 19.0711 20.5355 20.5355C19.0711 22 16.714 22 12 22Z");
}

.yklwhpb-j {
  d: path("M15.333 8.66565L15.333 21.9708");
}

</style>
