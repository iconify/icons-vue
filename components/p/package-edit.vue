<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g-ud9-4zw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:package-edit" /></template>
<style>
.g-ud9-4zw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M5 6c.613-1.226 1.387-2 2-2h10c.613 0 1.387.774 2 2l1 2v10a2 2 0 0 1-2 2H6a2 2 0 0 1-2-2V8zM4 8h16M9 17v-2l4-4l2 2l-4 4Z");
}

</style>
