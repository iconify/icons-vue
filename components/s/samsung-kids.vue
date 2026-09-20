<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="vikk5kbwk"/><path class="h1cz7lbig"/><circle class="a8n2576sn"/><circle class="zvh7ah41t"/><path class="it2zdyrrn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:samsung-kids" /></template>
<style>
.a8n2576sn {
  cx: 17.484px;
  cy: 20.93px;
  r: 1.068px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.h1cz7lbig {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M14.613 15.066c5.193.568 9.814.065 13.301-2.565c1.826 3.286 3.65 4.264 5.476 5.103m-2.297 8.87c1.32-.268 1.453.607 1.335 1.122c-1.978 8.635-13.625 7.991-15.972 1.122c-.321-.94.334-1.515 1.362-1.362c4.382.648 8.822.021 13.275-.882");
}

.it2zdyrrn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M21.733 23.549a1.602 1.602 0 1 1 3.204 0z");
}

.vikk5kbwk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M11.034 7.853c1.452 3.078 3.757 2.091 6.784 1.175c11.81-3.574 20.776 3.291 21.635 12.13c1.407-.605 3.11.595 3.045 1.923s-1.2 2.498-3.045 2.084c.015 2.976-3.529 6.249 2.671 8.71c-1.953 1.199-3.738 2.817-6.784 1.282c-4.174 4.74-9.92 6.325-16.988 3.794c-7.318-2.621-9.616-9.714-10.043-14.694c-1.348-.172-2.743-.89-2.807-2.57c-.064-1.678 1.714-2.748 3.234-1.465c.16-2.516 1.71-4.825 3.26-7.133c-2.04-1.827-1.899-3.55-.962-5.236");
}

.zvh7ah41t {
  cx: 29.714px;
  cy: 20.771px;
  r: 1.068px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
