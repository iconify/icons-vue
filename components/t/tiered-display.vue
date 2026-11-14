<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qijx-fb9a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:tiered-display" /></template>
<style>
.qijx-fb9a {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 4v14.5m-9.5.5a9.5 2.5 0 1 0 19 0a9.5 2.5 0 1 0-19 0ZM5 13a7 2 0 1 0 14 0a7 2 0 1 0-14 0Zm2.5-5.5a4.5 1.75 0 1 0 9 0a4.5 1.75 0 1 0-9 0Zm4.5-5h.01");
}

</style>
