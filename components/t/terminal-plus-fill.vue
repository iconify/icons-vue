<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="thhqrkbic"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:terminal-plus-fill" /></template>
<style>
.thhqrkbic {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M2 5L8.5571 10.6204C8.7899 10.8199 8.7899 11.1801 8.5571 11.3796L2 17M18 19H11M19 5L19 11M16 8L22 8");
}

</style>
