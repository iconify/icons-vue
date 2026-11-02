<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zak4g-l0z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:shirt-bulk" /></template>
<style>
.zak4g-l0z {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M8.629 3.072A.998.998 0 0 1 10 4a2 2 0 1 0 4 0a1 1 0 0 1 1.371-.928l5 2C21.177 5.394 22 6.056 22 7v3a2 2 0 0 1-2 2h-1v6a3 3 0 0 1-3 3H8a3 3 0 0 1-3-3v-6H4a2 2 0 0 1-2-2V7c0-.944.823-1.606 1.629-1.928Z");
}

</style>
