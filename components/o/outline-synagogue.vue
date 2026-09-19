<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vyvdqab8m"/><circle class="o55lmib_i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:outline-synagogue" /></template>
<style>
.o55lmib_i {
  cx: 12px;
  cy: 10px;
  r: 1.5px;
  fill: currentColor;
}

.vyvdqab8m {
  fill: currentColor;
  d: path("M20 4c-1.66 0-3 1.34-3 3v.29L12 3L7 7.29V7c0-1.66-1.34-3-3-3S1 5.34 1 7v14h10v-5c0-.55.45-1 1-1s1 .45 1 1v5h10V7c0-1.66-1.34-3-3-3m0 2c.55 0 1 .45 1 1v1h-2V7c0-.55.45-1 1-1M4 6c.55 0 1 .45 1 1v1H3V7c0-.55.45-1 1-1M3 19v-9h2v9zm14 0h-2v-3c0-1.65-1.35-3-3-3s-3 1.35-3 3v3H7V9.92l5-4.29l5 4.29zm2 0v-9h2v9z");
}

</style>
