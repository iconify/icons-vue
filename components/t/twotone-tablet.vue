<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g_4e9kbbs"/><path class="c236umbfu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-tablet" /></template>
<style>
.c236umbfu {
  fill: currentColor;
  d: path("M21 4H3c-1.1 0-2 .9-2 2v12c0 1.1.9 2 2 2h18c1.1 0 1.99-.9 1.99-2L23 6c0-1.1-.9-2-2-2m-2 14H5V6h14z");
}

.g_4e9kbbs {
  fill: currentColor;
  d: path("M5 6h14v12H5z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

</style>
