<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hd7ul2biy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:shield-warning" /></template>
<style>
.hd7ul2biy {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 3h6a2 2 0 0 1 2 2v5c0 5.5-3.5 9-8 11c-4.5-2-8-5.5-8-11V5a2 2 0 0 1 2-2zm0 5v4m0 3h.01");
}

</style>
