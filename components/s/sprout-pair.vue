<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hmm-9hbns"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:sprout-pair" /></template>
<style>
.hmm-9hbns {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 20.5V10m0 0c0-4-2.5-6.5-7.5-6.5c0 4 3 6.5 7.5 6.5Zm0 0c0-4 2.5-6.5 7.5-6.5c0 4-3 6.5-7.5 6.5Z");
}

</style>
