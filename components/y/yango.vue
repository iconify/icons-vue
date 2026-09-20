<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="g2wj9jbhp"/><path class="u4vh1fb3f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:yango" /></template>
<style>
.g2wj9jbhp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M9.5 5.5h29c2.216 0 4 1.784 4 4v29c0 2.216-1.784 4-4 4h-29c-2.216 0-4-1.784-4-4v-29c0-2.216 1.784-4 4-4");
}

.u4vh1fb3f {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M20.553 27.71v-7.42l4.949 7.42v-7.42m-11.858 0L11.216 24L8.79 20.29m2.426 7.42V24m25.476 3.71za2.403 2.403 0 0 1-2.428-2.411v-2.505c0-1.391 1.12-2.505 2.428-2.505c1.4 0 2.52 1.114 2.52 2.505v2.412a2.5 2.5 0 0 1-2.52 2.505m-4.251-4.917a2.5 2.5 0 0 0-2.52-2.504a2.5 2.5 0 0 0-2.522 2.504V25.3c0 1.391 1.12 2.412 2.521 2.412s2.521-1.114 2.521-2.412h-2.52m-12.031-.094h-3.362m-.84 2.504l2.521-7.42l2.521 7.42");
}

</style>
