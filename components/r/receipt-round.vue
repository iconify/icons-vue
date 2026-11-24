<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j9-tkvb9y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:receipt-round" /></template>
<style>
.j9-tkvb9y {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 3h4a4 4 0 0 1 4 4v14l-4-2l-4 2l-4-2l-4 2V7a4 4 0 0 1 4-4zM8 7h8m-8 4h8m-8 4h4");
}

</style>
