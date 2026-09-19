<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="j3s9ivbxi"/><path class="cq871m_tk"/><g class="y9tr6bcfx"><path class="w-uprwc1s"/><path class="weckg6brc"/></g><path class="ooar_bbyw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:star-sports" /></template>
<style>
.cq871m_tk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m19.936 18.291l1.417-.772v5.669m13.391-3.792a1.88 1.88 0 0 1 3.745-.212c.059.594-.13 1.18-.54 1.54c-.759.666-3.205 2.463-3.205 2.463H38.5");
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

.ooar_bbyw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M37.787 38.452v-5.669l-3.043 3.808H38.5M18.883 20.613L15.3 18.221l-3.57 2.414l1.168-4.148L9.5 13.84l4.305-.172l1.469-4.05l1.493 4.041l4.306.146l-3.382 2.669zm14.353-.069l-3.583-2.392l-3.57 2.413l1.168-4.147l-3.398-2.649l4.305-.171l1.469-4.05l1.493 4.04l4.306.146l-3.382 2.67zM18.883 35.91L15.3 33.516l-3.57 2.414l1.168-4.147l-3.398-2.65l4.305-.17l1.469-4.05l1.493 4.04l4.306.146l-3.382 2.669l1.193 4.14Zm14.353 0l-3.583-2.393l-3.57 2.414l1.168-4.147l-3.398-2.65l4.305-.17l1.469-4.05l1.493 4.04l4.306.146l-3.382 2.669z");
}

.w-uprwc1s {
  d: path("M19.816 37.974c.392.328.814.478 1.763.478h.221c.783 0 1.417-.634 1.417-1.417h0c0-.782-.634-1.417-1.417-1.417");
}

.weckg6brc {
  d: path("M19.816 33.257c.392-.327.815-.476 1.764-.473h.22c.783 0 1.417.635 1.417 1.418h0c0 .782-.634 1.417-1.417 1.417m-1.089-.001H21.8");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
