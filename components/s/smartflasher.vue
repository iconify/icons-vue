<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="lr8as2bsj"/><path class="zxvreoboa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:smartflasher" /></template>
<style>
.lr8as2bsj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M21.66 4.5V24h-6.33l11.01 19.5V24h6.33z");
}

.zxvreoboa {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M26.34 36.55a12.76 12.76 0 0 0-.83-25.22m-3.85.12a12.76 12.76 0 0 0 .83 25.22");
}

</style>
