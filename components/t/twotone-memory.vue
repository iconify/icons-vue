<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q58whgbes"/><path class="w5zqjzz7z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-memory" /></template>
<style>
.q58whgbes {
  fill: currentColor;
  d: path("M7 17h10V7H7zm2-8h6v6H9z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.w5zqjzz7z {
  fill: currentColor;
  d: path("M21 11V9h-2V7c0-1.1-.9-2-2-2h-2V3h-2v2h-2V3H9v2H7c-1.1 0-2 .9-2 2v2H3v2h2v2H3v2h2v2c0 1.1.9 2 2 2h2v2h2v-2h2v2h2v-2h2c1.1 0 2-.9 2-2v-2h2v-2h-2v-2zm-4 6H7V7h10zm-2-8H9v6h6zm-2 4h-2v-2h2z");
}

</style>
