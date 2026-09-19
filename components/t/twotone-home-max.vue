<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ky_i47i0m"/><path class="ky-sfcbyw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-home-max" /></template>
<style>
.ky_i47i0m {
  fill: currentColor;
  d: path("M19 7H5c-1.1 0-2 .9-2 2v5c0 1.1.9 2 2 2h14c1.1 0 2-.9 2-2V9c0-1.1-.9-2-2-2");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.ky-sfcbyw {
  fill: currentColor;
  d: path("M19 5H5C2.79 5 1 6.79 1 9v5c0 2.21 1.79 4 4 4h2v1h10v-1h2c2.21 0 4-1.79 4-4V9c0-2.21-1.79-4-4-4m2 9c0 1.1-.9 2-2 2H5c-1.1 0-2-.9-2-2V9c0-1.1.9-2 2-2h14c1.1 0 2 .9 2 2z");
}

</style>
