<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="bt-_gdbmz"/><circle class="hnp-a-bsc"/><rect class="k1qs_h7jn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:touch-the-notch" /></template>
<style>
.bt-_gdbmz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m22.825 37.342l-.039-3.235l-2.31-2.497s.096-3.829-1.78-5.574c-1.878-1.746.894-1.228 1.316-.283c.423.944 1.749 1.21 1.987 3.154s.282-10.276.282-10.276s.854-1.673 2.013-.059l.19 7.376s.709-2.24 1.89-.104c0 0 1.16-1.542 2.092.134c0 0 1.616-.433 1.475 1.556c0 0 .153 3.377-.889 4.63c0 0-.846.774-.353 5.336");
}

.hnp-a-bsc {
  cx: 23.297px;
  cy: 15.147px;
  r: 1.183px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.k1qs_h7jn {
  width: 39px;
  height: 27px;
  x: 4.5px;
  y: 10.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 4px;
  ry: 4px;
}

</style>
