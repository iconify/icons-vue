<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a-a4dmiub"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:syringe" /></template>
<style>
.a-a4dmiub {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("m13 7l-6 6a1.414 1.414 0 0 0 0 2l2 2a1.414 1.414 0 0 0 2 0l6-6m-5-5l6 6M8 16l-4 4m5-9l4 4m2-6l3-3m-2-2l4 4");
}

</style>
