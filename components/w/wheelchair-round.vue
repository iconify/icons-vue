<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g8qladuvv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:wheelchair-round" /></template>
<style>
.g8qladuvv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M8 4a1 1 0 1 0 2 0a1 1 0 0 0-2 0m1 4v4a2 2 0 0 0 2 2h3c.613 0 1.387.774 2 2l1 2c.613 1.226 1.387 2 2 2h1M9 10h5m-5 1a5 5 0 1 0 4 8");
}

</style>
