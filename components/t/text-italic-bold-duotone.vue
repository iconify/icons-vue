<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="kx3fe_t0r"/><path class="rj_m6ufoq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:text-italic-bold-duotone" /></template>
<style>
.kx3fe_t0r {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M9 1.00002H14.9768C14.992 0.999669 15.0072 0.999667 15.0225 1.00002H21C21.5523 1.00002 22 1.44773 22 2.00002C22 2.5523 21.5523 3.00002 21 3.00002H15.744H13.656H9C8.44772 3.00002 8 2.5523 8 2.00002C8 1.44773 8.44772 1.00002 9 1.00002ZM8.25597 21H3C2.44772 21 2 21.4477 2 22C2 22.5523 2.44772 23 3 23H8.97753C8.99281 23.0004 9.00805 23.0004 9.02325 23H15C15.5523 23 16 22.5523 16 22C16 21.4477 15.5523 21 15 21H10.344H8.25597Z");
}

.rj_m6ufoq {
  fill: currentColor;
  d: path("M13.6559 3L8.25586 21H10.3439L15.7439 3H13.6559Z");
  opacity: var(--svg-opacity--0-5, 0.5);
}

</style>
