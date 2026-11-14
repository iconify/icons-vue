<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="trwqx6bhr"/><path class="mvufo0bgm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:stereo-camera" /></template>
<style>
.mvufo0bgm {
  d: path("M5.25 13a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0Zm8.5 0a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0Z");
}

.trwqx6bhr {
  d: path("M2.5 6.5h19v13h-19Zm7 0v-2h5v2");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
