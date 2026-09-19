<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="j3s9ivbxi"/><path class="fwpk76buz"/><path class="o19merwfs"/><path class="b4mq_jiix"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:youme-app" /></template>
<style>
.b4mq_jiix {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M16.272 12.082v5.138a3.114 3.114 0 1 1-6.228 0v-5.138");
}

.fwpk76buz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M22.5 12.082a3.107 3.107 0 0 1 3.114 3.114v2.024c0 1.726-1.389 3.115-3.114 3.115s-3.114-1.39-3.114-3.115v-2.024a3.107 3.107 0 0 1 3.114-3.114m6.228 0v5.138a3.114 3.114 0 1 0 6.228 0v-5.138m0 5.139v3.114M16.111 30.779a3.114 3.114 0 1 1 6.228 0v5.138m-6.228-8.252v8.252");
}

.j3s9ivbxi {
  width: 37px;
  height: 37px;
  x: 5.5px;
  y: 5.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 4px;
  ry: 4px;
}

.o19merwfs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M22.339 30.779a3.114 3.114 0 1 1 6.228 0v5.138m8.981-1.571a3.113 3.113 0 0 1-5.82-1.543V30.78a3.114 3.114 0 1 1 6.228 0v1.012h-6.228M16.272 17.221v4.204a3.114 3.114 0 0 1-5.316 2.202");
}

</style>
