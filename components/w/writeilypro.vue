<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="xridcacut"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:writeilypro" /></template>
<style>
.xridcacut {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M37.31 15.93L12.24 41L5.5 42.5L7 35.76l.51-.51l28-28l.51-.51l1.76 1.76l.55-.5l2.46-2.5l1.71 1.71L40 9.68l-.52.51l1.8 1.81l-3 3l1.41 1.42l1.45 1.44l-4.88 4.88m1.55-14.26l1.71 1.71m-1.21 4.74l-1 1M7 35.76L12.24 41");
}

</style>
