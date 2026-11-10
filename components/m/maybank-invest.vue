<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="qtivdlggg"/><path class="g2wj9jbhp"/><path class="y2ubdachr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:maybank-invest" /></template>
<style>
.g2wj9jbhp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M9.5 5.5h29c2.216 0 4 1.784 4 4v29c0 2.216-1.784 4-4 4h-29c-2.216 0-4-1.784-4-4v-29c0-2.216 1.784-4 4-4");
}

.qtivdlggg {
  fill: currentColor;
  d: path("M37.311 19.095a.75.75 0 0 1-1.5 0a.75.75 0 0 1 1.5 0");
}

.y2ubdachr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M11.644 29.186V18.802l5.198 10.396l5.198-10.38v10.38m14.521-6.92v6.887M30.426 24a2.599 2.599 0 1 1 0 5.198h-4.288V18.802h4.288a2.599 2.599 0 1 1 0 5.198m0 0h-4.288");
}

</style>
