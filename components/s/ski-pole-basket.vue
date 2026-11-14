<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yzg2f69eg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:ski-pole-basket" /></template>
<style>
.yzg2f69eg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 2.5zA1.5 1.5 0 0 1 13.5 4v1.5A1.5 1.5 0 0 1 12 7a1.5 1.5 0 0 1-1.5-1.5V4A1.5 1.5 0 0 1 12 2.5M12 7v13.5m-5-5a5 2 0 1 0 10 0a5 2 0 1 0-10 0m-4 5h18");
}

</style>
