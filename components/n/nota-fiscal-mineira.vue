<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="b2464oroe"/><path class="rm-3y4yek"/><path class="u9_tlbbnt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:nota-fiscal-mineira" /></template>
<style>
.b2464oroe {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m5.93 15.612l2.33-4.035a12.155 12.155 0 0 1 21.054 0l5.28 9.145a5.065 5.065 0 0 1-4.387 7.597H14.97");
}

.rm-3y4yek {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m38.112 13.65l2.33 4.034a12.155 12.155 0 0 1-10.528 18.232H19.355a5.065 5.065 0 0 1-4.386-7.596l7.619-13.196");
}

.u9_tlbbnt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M23.722 42.5h-4.66A12.156 12.156 0 0 1 8.537 24.268l5.28-9.145a5.065 5.065 0 0 1 8.772 0l7.618 13.196");
}

</style>
