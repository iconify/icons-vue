<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y7swppq1c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:trending-up-duotone" /></template>
<style>
.y7swppq1c {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("m3 17l5-5a1.414 1.414 0 0 1 2 0l2 2a1.414 1.414 0 0 0 2 0l7-7m-6 0h6v6");
}

</style>
