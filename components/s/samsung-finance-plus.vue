<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="j3s9ivbxi"/><path class="ofx04gbtg"/><circle class="l07usix7z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:samsung-finance-plus" /></template>
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

.l07usix7z {
  cx: 29.647px;
  cy: 24px;
  r: 0.75px;
  fill: currentColor;
}

.ofx04gbtg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M12.368 28.964c.764 1.015 1.723 1.393 3.056 1.393h1.845c1.718 0 3.11-1.42 3.11-3.172v-.013c0-1.752-1.392-3.172-3.11-3.172h-2.035c-1.72 0-3.113-1.421-3.113-3.175c0-1.757 1.397-3.181 3.12-3.181h1.835c1.333 0 2.291.378 3.056 1.393m5.464 11.319V17.643h6.232m.935 3.178v6.357m0-3.178h3.116");
}

</style>
