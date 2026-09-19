<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rjgbvp0zx"/><path class="sdtrjc_hj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-thumb-down-off-alt" /></template>
<style>
.rjgbvp0zx {
  fill: currentColor;
  d: path("M3 12v2h9l-1.34 5.34L15 15V5H6z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.sdtrjc_hj {
  fill: currentColor;
  d: path("M19 3h4v12h-4zm-4 0H6c-.83 0-1.54.5-1.84 1.22l-3.02 7.05c-.09.23-.14.47-.14.73v2c0 1.1.9 2 2 2h6.31l-.95 4.57l-.03.32c0 .41.17.79.44 1.06L9.83 23l6.59-6.59c.36-.36.58-.86.58-1.41V5c0-1.1-.9-2-2-2m0 12l-4.34 4.34L12 14H3v-2l3-7h9z");
}

</style>
