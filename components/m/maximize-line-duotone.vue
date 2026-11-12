<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="j-eh52bdl"/><path class="sxv1zyb9f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:maximize-line-duotone" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.j-eh52bdl {
  d: path("M9 15L2 22M2 16.1429V22H7.85714");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.sxv1zyb9f {
  d: path("M15 9L22 2M22 7.85714V2H16.1429");
}

</style>
