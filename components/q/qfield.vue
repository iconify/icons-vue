<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="iju9thr2k"/><path class="ktt07xbjl"/><path class="jd_j27qta"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:qfield" /></template>
<style>
.iju9thr2k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m36.063 22.575l-2.586 10.517l-10.683 2.503l19.85 6.637z");
}

.jd_j27qta {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M29.665 37.893A15 15 0 0 1 24 39c-8.284 0-15-6.716-15-15S15.716 9 24 9s15 6.716 15 15c0 1.716-.288 3.364-.819 4.9");
}

.ktt07xbjl {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M37.692 40.577A21.4 21.4 0 0 1 24 45.5C12.126 45.5 2.5 35.874 2.5 24S12.126 2.5 24 2.5S45.5 12.126 45.5 24a21.4 21.4 0 0 1-4.537 13.212");
}

</style>
