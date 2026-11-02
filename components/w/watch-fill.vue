<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f0l9d5bvd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:watch-fill" /></template>
<style>
.f0l9d5bvd {
  fill: currentColor;
  d: path("M8 7.527V5a3 3 0 0 1 3-3h2a3 3 0 0 1 3 3v2.527a6 6 0 0 1 0 8.946V19a3 3 0 0 1-3 3h-2a3 3 0 0 1-3-3v-2.527a6 6 0 0 1 0-8.946m2-1.186a6.03 6.03 0 0 1 4 0V5a.997.997 0 0 0-1-1h-2a.997.997 0 0 0-1 1ZM13 10a1 1 0 0 0-2 0v2a1 1 0 0 0 1 1h2a1 1 0 0 0 0-2h-1Zm-3 7.659V19a1 1 0 0 0 1 1h2a1 1 0 0 0 1-1v-1.341a6.03 6.03 0 0 1-4 0");
}

</style>
