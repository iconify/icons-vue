<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zb9ydcv-p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:starting-grid" /></template>
<style>
.zb9ydcv-p {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M8.75 2.25h-3.5q-2.5 0-2.5 2.5v5q0 1.036.732 1.768t1.768.732h3.5q2.5 0 2.5-2.5v-5q0-2.5-2.5-2.5m6.5 9.5h3.5q2.5 0 2.5 2.5v5q0 1.036-.732 1.768t-1.768.732h-3.5q-1.036 0-1.768-.732t-.732-1.768v-5q0-2.5 2.5-2.5");
}

</style>
