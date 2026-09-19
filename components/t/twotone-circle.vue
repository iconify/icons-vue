<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<circle class="zyojugbos"/><path class="lephsccca"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-circle" /></template>
<style>
.lephsccca {
  fill: currentColor;
  d: path("M12 2C6.47 2 2 6.47 2 12s4.47 10 10 10s10-4.47 10-10S17.53 2 12 2m0 18c-4.42 0-8-3.58-8-8s3.58-8 8-8s8 3.58 8 8s-3.58 8-8 8");
}

.zyojugbos {
  cx: 12px;
  cy: 12px;
  r: 8px;
  fill: currentColor;
  opacity: var(--svg-opacity--0-3, 0.3);
}

</style>
