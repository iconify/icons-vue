<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ylzkncbsg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:memorial-poppy" /></template>
<style>
.ylzkncbsg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M14.75 5.75a2.75 2.75 0 0 1 0 5.5a2.75 2.75 0 0 1-5.5 0a2.75 2.75 0 0 1 0-5.5a2.75 2.75 0 0 1 5.5 0M12 14v7.5m0-2.5c2-3 5-3 6-2.5c-.5 2-3 3-6 2.5m0-10.5h.01");
}

</style>
