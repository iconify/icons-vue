<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jtpp63bpy"/><path class="u8ekscbfk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-filter-none" /></template>
<style>
.jtpp63bpy {
  fill: currentColor;
  d: path("M7 3h14v14H7z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.u8ekscbfk {
  fill: currentColor;
  d: path("M3 23h16v-2H3V5H1v16c0 1.1.9 2 2 2M21 1H7c-1.1 0-2 .9-2 2v14c0 1.1.9 2 2 2h14c1.1 0 2-.9 2-2V3c0-1.1-.9-2-2-2m0 16H7V3h14z");
}

</style>
