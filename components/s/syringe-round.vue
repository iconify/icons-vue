<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pi41d3bzj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:syringe-round" /></template>
<style>
.pi41d3bzj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("m13 7l-5 5a2.828 2.828 0 1 0 4 4l5-5m-5-5l6 6M8 16l-4 4m5-9l4 4m2-6l3-3m-2-2l4 4");
}

</style>
