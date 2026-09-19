<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="b8rvnc51q"/><path class="q8ro0ub9b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:sberbank" /></template>
<style>
.b8rvnc51q {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.21 7.85L16 20.62L5.21 14.39m29.13-7.83L16 17.13l-8.58-4.88m33.66-2.34L16 24.35L3.85 17.41");
}

.q8ro0ub9b {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M43.39 15.46A19.4 19.4 0 0 1 44.5 22a20.3 20.3 0 0 1-1.11 6.64l-.5 1.36a20.9 20.9 0 0 1-4.38 6.54A20.2 20.2 0 0 1 32 40.87a20.2 20.2 0 0 1-8 1.66a19.9 19.9 0 0 1-8-1.66a21 21 0 0 1-6.49-4.33A19.7 19.7 0 0 1 5.11 30a20.7 20.7 0 0 1-1.61-8v-1.36L16 27.73l26.29-15.09Z");
}

</style>
