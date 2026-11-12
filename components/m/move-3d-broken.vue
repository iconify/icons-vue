<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="qim-6bkwl"/><path class="h4koblh4d"/><path class="n_9rn8bax"/><path class="znspvb6ko"/><path class="x3o6axbse"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:move-3d-broken" /></template>
<style>
.h4koblh4d {
  stroke-linejoin: round;
  d: path("M4.16258 15.3467L4.16264 19.8379L8.65373 19.838");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.n_9rn8bax {
  stroke-linejoin: round;
  d: path("M16.6623 17.3376L19.8379 14.1621L16.6623 10.9868");
}

.qim-6bkwl {
  stroke-linejoin: round;
  d: path("M13.0137 7.3381L9.83785 4.16235L6.66215 7.33801");
}

.x3o6axbse {
  d: path("M12 14.1621H9.83755M9.83755 14.1621L4.1626 19.8379M9.83755 14.1621L9.83776 4.16235");
}

.znspvb6ko {
  d: path("M19.8376 14.1623L15.9965 14.1622");
}

</style>
