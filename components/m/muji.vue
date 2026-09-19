<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="j3s9ivbxi"/><path class="ur36nxb2s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:muji" /></template>
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

.ur36nxb2s {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.385 19.45v9.1m-2.677-9.1v6.825c0 1.257-1.073 2.275-2.397 2.275s-2.398-1.018-2.398-2.275v-.755M9.615 28.54v-9.09l4.795 9.1l4.795-9.087v9.087m2.677-9.1v6.086c0 1.665 1.422 3.015 3.177 3.015s3.176-1.35 3.176-3.015V19.45");
}

</style>
