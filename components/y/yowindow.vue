<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="kr3akubvu"/><path class="j55wabb3t"/><circle class="e5g_xy0rn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:yowindow" /></template>
<style>
.e5g_xy0rn {
  cx: 24px;
  cy: 24px;
  r: 15.75px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.j55wabb3t {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m24 2.5l3.077 6.033l5.151-4.396l.533 6.751l6.442-2.091l-2.091 6.442l6.751.533l-4.396 5.151L45.5 24l-6.033 3.077l4.396 5.151l-6.751.533l2.091 6.442l-6.442-2.091l-.533 6.751l-5.151-4.396L24 45.5l-3.077-6.033l-5.151 4.396l-.533-6.751l-6.442 2.091l2.091-6.442l-6.751-.533l4.396-5.151L2.5 24l6.033-3.077l-4.396-5.151l6.751-.533l-2.091-6.442l6.442 2.091l.533-6.751l5.151 4.396z");
}

.kr3akubvu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M29.93 18.6c0 .949-.49 1.717-1.095 1.717s-1.094-.769-1.094-1.717s.49-1.716 1.094-1.717c.604 0 1.095.77 1.095 1.718m-12.665.232c.522-.564 1.343-.895 2.214-.895c.87 0 1.69.331 2.214.895m10.638 7.793c-1.456 2.729-4.723 4.49-8.332 4.49c-3.607 0-6.874-1.76-8.33-4.489");
}

</style>
