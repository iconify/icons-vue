<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="jhgd45kxd"/><rect class="j3s9ivbxi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:moorepay" /></template>
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

.jhgd45kxd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M13.5 28.061V22.83a3.171 3.171 0 0 1 6.342 0v5.232m0-5.232a3.171 3.171 0 1 1 6.342 0v5.231m1.974-3.171a3.171 3.171 0 0 0 6.342 0v-2.06a3.171 3.171 0 1 0-6.342 0m0-.001v9.513");
}

</style>
