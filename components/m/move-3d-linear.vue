<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="qim-6bkwl"/><path class="qlvg9o9nq"/><path class="mcf4dis3x"/><path class="l_z-b8vui"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:move-3d-linear" /></template>
<style>
.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.l_z-b8vui {
  d: path("M9.83776 4.16235L9.83755 14.1621M9.83755 14.1621L19.8376 14.1622M9.83755 14.1621L4.1626 19.8379");
}

.mcf4dis3x {
  stroke-linejoin: round;
  d: path("M16.662 17.3376L19.8376 14.1621L16.662 10.9868");
}

.qim-6bkwl {
  stroke-linejoin: round;
  d: path("M13.0137 7.3381L9.83785 4.16235L6.66215 7.33801");
}

.qlvg9o9nq {
  stroke-linejoin: round;
  d: path("M4.16234 15.3467L4.1624 19.8379L8.65348 19.838");
}

</style>
