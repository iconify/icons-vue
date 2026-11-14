<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="css1lzmra"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:sports-massage" /></template>
<style>
.css1lzmra {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12.5 4.5H18a3 3 0 0 1 3 3a3 3 0 0 1-3 3h-5.5a3 3 0 0 1-3-3a3 3 0 0 1 3-3m.5 6L11 21h4.5l2-10.5m-15-3a2 2 0 1 0 4 0a2 2 0 1 0-4 0m4 0h3");
}

</style>
