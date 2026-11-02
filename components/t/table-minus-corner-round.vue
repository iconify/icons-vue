<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s1gj2m_4m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:table-minus-corner-round" /></template>
<style>
.s1gj2m_4m {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 4h4a4 4 0 0 1 4 4v1M9 20H8a4 4 0 0 1-4-4V8a4 4 0 0 1 4-4h4M4 9h16M4 15h5m3-11v5m1 7h8");
}

</style>
