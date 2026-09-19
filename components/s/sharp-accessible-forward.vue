<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<circle class="mn9l6gbgf"/><path class="l7irhbbjm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-accessible-forward" /></template>
<style>
.l7irhbbjm {
  fill: currentColor;
  d: path("M15 17h-2c0 1.65-1.35 3-3 3s-3-1.35-3-3s1.35-3 3-3v-2c-2.76 0-5 2.24-5 5s2.24 5 5 5s5-2.24 5-5m5-3.5h-3.86l1.67-3.67C18.42 8.5 17.44 7 15.96 7h-5.2c-.81 0-1.54.47-1.87 1.2L8.22 10l1.92.53l.65-1.53H13l-3.12 7H18v5h2z");
}

.mn9l6gbgf {
  cx: 18px;
  cy: 4.54px;
  r: 2px;
  fill: currentColor;
}

</style>
