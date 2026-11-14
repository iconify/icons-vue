<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b3rwd2brh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:skydive-drop-zone" /></template>
<style>
.b3rwd2brh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7 7.5a5 5 0 0 1 10 0Zm0 0l5 5m5-5l-5 5m-9.5 6a9.5 3 0 1 0 19 0a9.5 3 0 1 0-19 0Zm9.5 0h.01");
}

</style>
