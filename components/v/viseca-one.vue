<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="y9tr6bcfx"><rect class="ccyn2rwlc"/><path class="krbacubzh"/><circle class="ovk5o1vio"/></g><circle class="cpk0fnbgt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:viseca-one" /></template>
<style>
.ccyn2rwlc {
  width: 6.617px;
  height: 8.768px;
  x: 10.5px;
  y: 27.213px;
  rx: 3.309px;
  ry: 3.309px;
}

.cpk0fnbgt {
  cx: 24px;
  cy: 24px;
  r: 21.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.krbacubzh {
  d: path("M27.304 35.981v-5.46a3.31 3.31 0 0 0-3.308-3.308h0a3.31 3.31 0 0 0-3.309 3.309m0 5.459v-8.768m16.379 7.099a3.31 3.31 0 0 1-2.875 1.67h0a3.31 3.31 0 0 1-3.308-3.31v-2.15a3.31 3.31 0 0 1 3.308-3.309h0a3.31 3.31 0 0 1 3.309 3.309v1.075h-6.617");
}

.ovk5o1vio {
  cx: 29.62px;
  cy: 16.959px;
  r: 4.94px;
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
