<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gb9v9obyb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:move-diagonal-flip-fill" /></template>
<style>
.gb9v9obyb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M4.6 4.6L19.4 19.4M20 14L20 19.5C20 19.7761 19.7761 20 19.5 20L14 20M4 10L4 4.5C4 4.2239 4.2239 4 4.5 4L10 4");
}

</style>
