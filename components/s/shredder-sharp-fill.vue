<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path clip-rule="evenodd" class="udgqy7bss"/><path class="vcg_lradd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:shredder-sharp-fill" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.udgqy7bss {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M3 12L3 2C3 1.4477 3.4477 1 4 1L14 1C14.2652 1 14.5196 1.1054 14.7071 1.2929L20.7071 7.2929C20.8946 7.4804 21 7.7348 21 8L21 12C21 12.5523 20.5523 13 20 13L4 13C3.4477 13 3 12.5523 3 12ZM14 8L18.5858 8L14 3.4142L14 8Z");
  stroke: none;
}

.vcg_lradd {
  d: path("M1 12L23 12M6 15L6 23M10 15L10 21M14 15L14 23M18 15L18 21");
}

</style>
