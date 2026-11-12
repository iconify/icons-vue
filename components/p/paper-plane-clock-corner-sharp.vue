<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xr1c5w-bp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:paper-plane-clock-corner-sharp" /></template>
<style>
.xr1c5w-bp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 3L3 6l4 2l2 4zM7 8l1-1m4 10a5 5 0 1 0 10 0a5 5 0 0 0-10 0m5-2v2h2");
}

</style>
