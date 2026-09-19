<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="j3s9ivbxi"/><path class="g-r6rob0s"/><path class="kr512cbiw"/><circle class="vg7f0wbkj"/><path class="uxqpwpb4p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:mister-donut" /></template>
<style>
.g-r6rob0s {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M10.83 19.914a1.794 1.794 0 1 1 3.588 0v2.961m-3.588-4.756v4.756");
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

.kr512cbiw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M14.418 19.914a1.794 1.794 0 1 1 3.588 0v2.961m17.37-2.961c0-.991.803-1.795 1.794-1.795m-1.794 0v4.756");
}

.uxqpwpb4p {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M19.799 18.119v4.756m1.907-.401c.328.275.681.401 1.475.401h.403c.655 0 1.186-.532 1.186-1.189s-.531-1.189-1.186-1.189h-.805a1.187 1.187 0 0 1-1.186-1.189c0-.656.531-1.189 1.186-1.189h.402c.795 0 1.148.126 1.476.402m2.378-1.882v5.34c0 .495.402.897.897.897h.269m-2.108-4.757h1.883m5.371 3.851a1.793 1.793 0 0 1-3.353-.889v-1.167a1.794 1.794 0 1 1 3.588 0v.584h-3.588m-1.082 6.953v2.961a1.794 1.794 0 1 0 3.588 0v-2.961m0 2.962v1.794m2.734-6.236v5.34c0 .495.402.897.897.897h.269m-2.107-4.756h1.883m-9.058 4.755v-2.961a1.794 1.794 0 1 0-3.588 0m0 2.961v-4.756m-10.315 4.757h-1.614v-6.281h1.614a3.14 3.14 0 0 1 0 6.281m4.934-2.962a1.794 1.794 0 1 1 3.588 0v1.167a1.794 1.794 0 1 1-3.588 0z");
}

.vg7f0wbkj {
  cx: 19.799px;
  cy: 15.921px;
  r: 0.75px;
  fill: currentColor;
}

</style>
