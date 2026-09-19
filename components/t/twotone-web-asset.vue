<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h332xx0in"/><path class="m_gsnq25f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-web-asset" /></template>
<style>
.h332xx0in {
  fill: currentColor;
  d: path("M5 8h14v10H5z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.m_gsnq25f {
  fill: currentColor;
  d: path("M19 4H5a2 2 0 0 0-2 2v12a2 2 0 0 0 2 2h14c1.1 0 2-.9 2-2V6a2 2 0 0 0-2-2m0 14H5V8h14z");
}

</style>
