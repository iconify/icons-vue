<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jo2qx522z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:scene-party" /></template>
<style>
.jo2qx522z {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m4.107 17.68l1.498-4.494a1.75 1.75 0 0 1 2.897-.684l2.996 2.996a1.75 1.75 0 0 1-.684 2.897L6.32 19.893a1.75 1.75 0 0 1-2.213-2.213M9.5 8c1.5-1.5 0-3 1.5-4.5m3 8h.01m.99 2c1.5-1 3 .5 4.5-.5m-.97-8.905l.348.554a1.5 1.5 0 0 0 .473.473l.554.348a.626.626 0 0 1 0 1.06l-.554.348a1.5 1.5 0 0 0-.473.473l-.348.554a.626.626 0 0 1-1.06 0l-.348-.554a1.5 1.5 0 0 0-.473-.473l-.554-.348a.626.626 0 0 1 0-1.06l.554-.348a1.5 1.5 0 0 0 .473-.473l.348-.554a.626.626 0 0 1 1.06 0");
}

</style>
