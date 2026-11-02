<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y17db3bte"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:watch-fill-sharp" /></template>
<style>
.y17db3bte {
  fill: currentColor;
  d: path("M8 7.527V3a1 1 0 0 1 1-1h6a1 1 0 0 1 1 1v4.527a6 6 0 0 1 0 8.946V21a1 1 0 0 1-1 1H9a1 1 0 0 1-1-1v-4.527a6 6 0 0 1 0-8.946m2-1.186a6.03 6.03 0 0 1 4 0V4h-4ZM13 10a1 1 0 0 0-2 0v2a1 1 0 0 0 1 1h2a1 1 0 0 0 0-2h-1Zm-3 7.659V20h4v-2.341a6.03 6.03 0 0 1-4 0");
}

</style>
