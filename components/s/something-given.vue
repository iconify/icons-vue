<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="j3s9ivbxi"/><path class="lec_tezmo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:something-given" /></template>
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

.lec_tezmo {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M32.47 27.553c.365.307.76.447 1.645.447h.449c.73 0 1.322-.593 1.322-1.325s-.592-1.325-1.322-1.325h-.898c-.73 0-1.322-.593-1.322-1.325s.592-1.325 1.322-1.325h.449c.885 0 1.28.14 1.645.447M12.115 24h2.6m-2.6 4v-8h4m12.972 1.83V20m0 1.83l-1.101 1.37m-.5-2.375l1.601 1.005m0 0l1.11 1.37m.489-2.375l-1.599 1.005m-4.858 0V20m0 1.83l-1.1 1.37m-.5-2.375l1.6 1.005m0 0l1.11 1.37m.49-2.375l-1.6 1.005m-4.857 0V20m0 1.83l-1.1 1.37m-.5-2.375l1.6 1.005m0 0l1.11 1.37m.49-2.375l-1.6 1.005");
}

</style>
