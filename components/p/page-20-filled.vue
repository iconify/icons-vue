<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g class="ft5dv1b6b"><path class="z_167mxev"/><path class="vjiv5bbrn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:page-20-filled" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.vjiv5bbrn {
  d: path("M12 3.144V7.5a.5.5 0 0 0 .5.5h4.356a2.5 2.5 0 0 0-.588-.932l-3.336-3.336A2.5 2.5 0 0 0 12 3.144z");
  fill: currentColor;
}

.z_167mxev {
  d: path("M5.5 3A2.5 2.5 0 0 0 3 5.5v9A2.5 2.5 0 0 0 5.5 17h9a2.5 2.5 0 0 0 2.5-2.5V9h-4.5A1.5 1.5 0 0 1 11 7.5V3H5.5z");
  fill: currentColor;
}

</style>
