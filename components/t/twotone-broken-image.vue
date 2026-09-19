<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qqrqzz8db"/><path class="i23i5bbys"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-broken-image" /></template>
<style>
.i23i5bbys {
  fill: currentColor;
  d: path("M19 3H5c-1.1 0-2 .9-2 2v14c0 1.1.9 2 2 2h14c1.1 0 2-.9 2-2V5c0-1.1-.9-2-2-2m0 16H5v-4.58l.99.99l4-4l4 4l4-3.99L19 12.43zm0-9.41l-1.01-1.01l-4 4.01l-4-4l-4 4l-.99-1V5h14z");
}

.qqrqzz8db {
  fill: currentColor;
  d: path("m13.99 15.41l-4-4l-4 4l-.99-.99V19h14v-6.57l-1.01-1.01zM5 11.59l.99 1l4-4l4 4l4-4.01L19 9.59V5H5z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

</style>
