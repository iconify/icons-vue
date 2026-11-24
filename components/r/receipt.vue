<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wqm4ov5zx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:receipt" /></template>
<style>
.wqm4ov5zx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 3h6a2 2 0 0 1 2 2v16l-4-2l-4 2l-4-2l-4 2V5a2 2 0 0 1 2-2zM8 7h8m-8 4h8m-8 4h4");
}

</style>
