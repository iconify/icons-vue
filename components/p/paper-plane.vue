<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z-xidnbrq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:paper-plane" /></template>
<style>
.z-xidnbrq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 6L6 8c-1.107.369-1.738 1.631-1 2l6 3l3 6c.369.738 1.631.107 2-1l4-12c.412-1.236-.764-2.412-2-2zm-1 7l3-3");
}

</style>
