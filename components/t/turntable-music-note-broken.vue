<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="yaxzcyw0z"/><path class="hl5jo5b4t"/><circle class="b-v3dtbhs"/><path class="fc4f7w-7u"/><path class="dlp9kybon"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:turntable-music-note-broken" /></template>
<style>
.b-v3dtbhs {
  cx: 17px;
  cy: 20px;
  r: 2px;
}

.dlp9kybon {
  d: path("M12 15C10.3431 15 9 13.6569 9 12C9 10.3431 10.3431 9 12 9C13.6569 9 15 10.3431 15 12C15 13.6569 13.6569 15 12 15Z");
}

.fc4f7w-7u {
  d: path("M22 15C20.3431 15 19 13.6569 19 12");
}

.hl5jo5b4t {
  d: path("M19 20V16V12");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.yaxzcyw0z {
  d: path("M12 22C7.28595 22 4.92893 22 3.46447 20.5355C2 19.0711 2 16.714 2 12M21.9948 10C21.9658 6.58687 21.7764 4.70529 20.5355 3.46447C19.0711 2 16.714 2 12 2C7.28595 2 4.92893 2 3.46447 3.46447C2.49073 4.43821 2.16444 5.80655 2.0551 8");
}

</style>
