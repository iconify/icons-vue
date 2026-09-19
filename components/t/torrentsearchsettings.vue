<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="axzgyyerf"/><circle class="ivoeacboo"/><path class="ex537ziul"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:torrentsearchsettings" /></template>
<style>
.axzgyyerf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m24 2.5l3.05 2.24l3.594-1.188l2.209 3.073l3.784-.019l1.152 3.605l3.605 1.152l-.019 3.784l3.073 2.209l-1.188 3.594L45.5 24l-2.24 3.05l1.188 3.594l-3.073 2.209l.019 3.784l-3.605 1.152l-1.152 3.605l-3.784-.019l-2.209 3.073l-3.594-1.188L24 45.5l-3.05-2.24l-3.594 1.188l-2.209-3.073l-3.784.019l-1.152-3.605l-3.605-1.152l.019-3.784l-3.073-2.209L4.74 27.05L2.5 24l2.24-3.05l-1.188-3.594l3.073-2.209l-.019-3.784l3.605-1.152l1.152-3.605l3.784.019l2.209-3.073L20.95 4.74z");
}

.ex537ziul {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M17.249 22.757L24 29.508l6.751-6.751M24 29.508V11.5");
}

.ivoeacboo {
  cx: 24px;
  cy: 24px;
  r: 12.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
