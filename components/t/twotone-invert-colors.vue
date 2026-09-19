<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="samojxqew"/><path class="twi9gbbzn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-invert-colors" /></template>
<style>
.samojxqew {
  fill: currentColor;
  d: path("M7.75 8.99A5.77 5.77 0 0 0 6 13.13C6 16.37 8.69 19 12 19V4.81z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.twi9gbbzn {
  fill: currentColor;
  d: path("M17.65 7.56L12 2L6.35 7.56C4.9 8.99 4 10.96 4 13.13C4 17.48 7.58 21 12 21s8-3.52 8-7.87c0-2.17-.9-4.14-2.35-5.57M6 13.13c0-1.56.62-3.03 1.75-4.14L12 4.81V19c-3.31 0-6-2.63-6-5.87");
}

</style>
