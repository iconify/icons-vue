<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="y8noz6bcy"/><path class="g2wj9jbhp"/><circle class="vdrlog67y"/><path class="rcy8j3bdu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:murglar-2" /></template>
<style>
.g2wj9jbhp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M9.5 5.5h29c2.216 0 4 1.784 4 4v29c0 2.216-1.784 4-4 4h-29c-2.216 0-4-1.784-4-4v-29c0-2.216 1.784-4 4-4");
}

.rcy8j3bdu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M16.041 16h3.225c.43 0 .78.35.78.78v1.97c0 .43-.35.78-.78.78H15.26v-2.75c0-.43.35-.78.78-.78m-.779 3.53v9.288");
}

.vdrlog67y {
  cx: 12.079px;
  cy: 28.818px;
  r: 3.182px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.y8noz6bcy {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M19.392 5.501L31.766 42.5m-7.879-24.948H35.7m-10.305 4.505H35.7m-8.798 4.505h4.16m2.508 1.973l2.203 2.203l2.203-2.203m-2.204-2.866v5.062m-3.614 2.138h7.23");
}

</style>
