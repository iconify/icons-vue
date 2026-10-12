<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vhk3dufaj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:mouth-stick" /></template>
<style>
.vhk3dufaj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.15 14.75v-2.12c-.88-.88-1.4-2.16-1.4-3.68c0-3.4 2.28-6.2 5.2-6.2c2.16 0 3.52 1.4 3.8 3.4l1.12 2.08q.2.52-.32.52h-.6v2q0 1.6-1.4 1.6h-1v2.4Zm12.54-2.6l2.89.77q1.45.39 1.06 1.84l-1.29 4.83q-.39 1.45-1.84 1.06l-2.89-.77q-1.45-.39-1.06-1.84l1.29-4.83q.39-1.45 1.84-1.06m-.95 5.45l1.94.52M12.95 10l3.3 3.25");
}

</style>
