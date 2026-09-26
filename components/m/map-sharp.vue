<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tmy4j9b0h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:map-sharp" /></template>
<style>
.tmy4j9b0h {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 6L9 3L15 6L21 3L21 18L15 21L9 18L3 21L3 6ZM9 3L9 18.4871M15 5.5129L15 21");
}

</style>
