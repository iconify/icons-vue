<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="lx0n4eb6z"/><path class="l3ly-jo2s"/><circle class="np6s29gah"/><path class="w9aytj-1f"/><rect class="j3s9ivbxi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:mijnsimpel" /></template>
<style>
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

.l3ly-jo2s {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M20.19 23.585a1.95 1.95 0 0 1 1.952-1.95h0a1.95 1.95 0 0 1 1.95 1.95v3.22");
}

.lx0n4eb6z {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M16.29 23.585a1.95 1.95 0 0 1 1.95-1.95h0a1.95 1.95 0 0 1 1.95 1.95v3.22m-3.901-5.171v5.17");
}

.np6s29gah {
  cx: 14.107px;
  cy: 19.245px;
  r: 0.75px;
  fill: currentColor;
}

.w9aytj-1f {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M14.107 21.634v5.17m-5.484-.436c.356.3.74.436 1.604.436h.438c.712 0 1.29-.578 1.29-1.292h0c0-.714-.578-1.293-1.29-1.293H9.79a1.29 1.29 0 0 1-1.29-1.292h0c0-.714.577-1.293 1.29-1.293h.437c.864 0 1.249.137 1.605.437M38.232 19v6.829c0 .539.437.975.975.975h.293m-3.603-.984a1.95 1.95 0 0 1-1.695.984h0a1.95 1.95 0 0 1-1.95-1.95v-1.269a1.95 1.95 0 0 1 1.95-1.95h0a1.95 1.95 0 0 1 1.951 1.95v.634h-3.902m-5.981.635a1.95 1.95 0 0 0 1.952 1.95h0a1.95 1.95 0 0 0 1.95-1.95v-1.269a1.95 1.95 0 0 0-1.95-1.95h0a1.95 1.95 0 0 0-1.951 1.95m0-1.951v7.804");
}

</style>
