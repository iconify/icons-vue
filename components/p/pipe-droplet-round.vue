<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gqhdk2n6e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:pipe-droplet-round" /></template>
<style>
.gqhdk2n6e {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 3h5l2 3l-2 3H3m18-6h-5l-2 3l2 3h5m-9 4l-3 4c0 4 6 4 6 0Z");
}

</style>
