<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="cpk0fnbgt"/><path class="ou1_3ubkq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:wikiloc" /></template>
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

.ou1_3ubkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M35.061 5.563c2.232 5.962-1.247 12.37-6.262 15.266c-3.778 2.182-7.786 6.797-7.786 13.47c0 3.968 1.614 8.941 5.31 11.075m2.83-42.247c1.39 5.19-4.019 9.463-6.314 10.079c-4.527 1.213-10.977 4.532-13.98 11.549c-2.193 4.74-1.587 11.05.896 15.349");
}

</style>
