<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="cpk0fnbgt"/><path class="q676ax9eo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:quoteunquote" /></template>
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

.q676ax9eo {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M13 29.75c2.21 0 4-2.686 4-6h-4v-9.5h8.7v9.5c0 5.523-3.895 10-8.7 10Zm13.3 0c2.21 0 4-2.686 4-6h-4v-9.5H35v9.5c0 5.523-3.895 10-8.7 10Z");
}

</style>
