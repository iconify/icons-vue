<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="j3s9ivbxi"/><path class="ofg8spboc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:nhk-world-japan" /></template>
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

.ofg8spboc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.5 13.209h37m-37 18.018h37M24 5.5v7.709m-8.777 20.783v3.461c0 .637-.547 1.154-1.221 1.154s-1.221-.517-1.221-1.154v-.383m9.204 1.537v-4.615h1.6c.903 0 1.636.694 1.636 1.55s-.733 1.55-1.637 1.55h-1.599m9.998 1.515v-4.615l3.236 4.615v-4.615m-15.533 3.087h-2.164m-.537 1.528l1.618-4.615l1.618 4.615m9.463-1.528H27.52m-.536 1.528l1.618-4.615l1.618 4.615M29.09 24.69v3.773h2.016m-7.433 0V24.69h1.32c.747 0 1.352.568 1.352 1.267s-.605 1.267-1.352 1.267h-1.32m1.32 0l1.321 1.239M15.508 24.69L14.5 28.463l-1.008-3.773l-1.008 3.773l-1.008-3.773m22.377 3.773V24.69h.907c.975 0 1.765.74 1.765 1.65v.473c0 .911-.79 1.65-1.765 1.65zM19.59 24.69c.738 0 1.336.56 1.336 1.25v1.273c0 .69-.598 1.25-1.336 1.25h0c-.738 0-1.336-.56-1.336-1.25V25.94c0-.69.598-1.25 1.336-1.25m-8.339-2.774l1.632-5.944l2.461 5.944l1.632-5.944m6.182.001l-1.632 5.944m5.726-5.944l-1.632 5.944m-3.275-2.984h4.093m6.995-2.95l-1.632 5.944m.57-2.071l4.379-3.854m-1.626 5.925l-1.725-2.972");
}

</style>
