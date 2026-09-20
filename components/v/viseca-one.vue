<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="y9tr6bcfx"><rect class="ccyn2rwlc"/><path class="x2-itlu0g"/><circle class="ovk5o1vio"/></g><circle class="cpk0fnbgt"/>`;
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

.ovk5o1vio {
  cx: 29.62px;
  cy: 16.959px;
  r: 4.94px;
}

.x2-itlu0g {
  d: path("M27.304 35.981v-5.46a3.309 3.309 0 0 0-6.617 0m0 5.46v-8.768m16.379 7.099a3.309 3.309 0 0 1-6.184-1.639v-2.151a3.309 3.309 0 0 1 6.617 0v1.075h-6.616");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
