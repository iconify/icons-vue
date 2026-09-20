<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="em9o_c-lg"/><path class="b5n032bas"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:xp-investimentos" /></template>
<style>
.b5n032bas {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M31.51 33.619a3.78 3.78 0 1 0 7.558 0v-2.457a3.78 3.78 0 1 0-7.558 0m0-3.779V42.5");
}

.em9o_c-lg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 5.5h-29a4 4 0 0 0-4 4v29a4 4 0 0 0 4 4h29a4 4 0 0 0 4-4v-29a4 4 0 0 0-4-4M27.715 27.383l-7.558 10.015m7.558 0l-7.558-10.015");
}

</style>
