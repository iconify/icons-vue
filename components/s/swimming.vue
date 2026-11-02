<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u1gf5ddcd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:swimming" /></template>
<style>
.u1gf5ddcd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("m5 11l5-3l4 3l-2 2m-9 4q3-3 6 0t6 0t6 0m-4-9a1 1 0 1 0 2 0a1 1 0 0 0-2 0");
}

</style>
