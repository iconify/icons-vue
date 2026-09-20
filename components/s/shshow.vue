<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="cpk0fnbgt"/><path class="j-sm20b8e"/><rect class="j9kp9bcik"/><path class="dh95m0b0y"/><rect class="u7m6ow2rr"/><path class="lh55bybau"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:shshow" /></template>
<style>
.cpk0fnbgt {
  cx: 24px;
  cy: 24px;
  r: 21.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.dh95m0b0y {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m19.121 27.903l-2.586-2.555");
}

.j-sm20b8e {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M35.483 27.048c.479.623 1.079.855 1.914.855h1.156a1.947 1.947 0 0 0 1.947-1.947v-.009A1.947 1.947 0 0 0 38.553 24h-1.275a1.95 1.95 0 0 1-1.95-1.95c0-1.079.875-1.953 1.954-1.953h1.15c.835 0 1.435.232 1.913.855m-19.202-.855v5.22a2.586 2.586 0 0 0 5.171 0v-5.22");
}

.j9kp9bcik {
  width: 5.172px;
  height: 7.806px;
  x: 28.331px;
  y: 20.097px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 2.586px;
  ry: 2.586px;
}

.lh55bybau {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M11.815 25.317H8.357M7.5 27.903l2.586-7.806l2.586 7.806");
}

.u7m6ow2rr {
  width: 5.172px;
  height: 7.806px;
  x: 13.949px;
  y: 20.097px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 2.586px;
  ry: 2.586px;
}

</style>
