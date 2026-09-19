<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="cpk0fnbgt"/><path class="zl8bwf-4t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:ripio" /></template>
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

.zl8bwf-4t {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m30.693 27.848l-13.225 6.093a.63.63 0 0 1-.895-.572V21.298a1.26 1.26 0 0 1 .734-1.146l13.225-6.093a.63.63 0 0 1 .895.572v12.071a1.26 1.26 0 0 1-.734 1.146");
}

</style>
