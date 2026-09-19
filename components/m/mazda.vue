<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ht09gubuv"/><path class="r8ku54bsr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:mazda" /></template>
<style>
.ht09gubuv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M39.748 13.264c-3.102-3.332-8.109-4.86-15.75-4.867c-7.637.008-12.644 1.534-15.746 4.865C5.946 15.733 4.5 19.154 4.5 23.795c0 2.566.634 9.1 5.792 12.474c3.087 2.018 7.075 3.324 13.707 3.334c6.634-.01 10.62-1.316 13.71-3.334c5.156-3.374 5.791-9.91 5.791-12.474c0-4.628-1.457-8.073-3.754-10.535z");
}

.r8ku54bsr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M41.427 15.496c.334.934-1.32 2.638-4.16 3.559C29.22 21.664 25.88 23.525 24 29.577c-1.88-6.051-5.22-7.913-13.266-10.522c-2.84-.921-4.494-2.625-4.16-3.56");
}

</style>
