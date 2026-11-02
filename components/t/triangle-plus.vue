<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eba16pb2a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:triangle-plus" /></template>
<style>
.eba16pb2a {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("m13.728 4.992l7 12C21.505 18.326 20.544 20 19 20H5c-1.544 0-2.505-1.674-1.728-3.008l7-12c.772-1.323 2.684-1.323 3.456 0M9 14h6m-3-3v6");
}

</style>
