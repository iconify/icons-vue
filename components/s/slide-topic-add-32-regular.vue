<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="sdmk_luyx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:slide-topic-add-32-regular" /></template>
<style>
.sdmk_luyx {
  fill: currentColor;
  d: path("M23.5 16a7.5 7.5 0 1 1 0 15a7.5 7.5 0 0 1 0-15m.25 2a.75.75 0 0 0-.75.75v3.75h-3.75a.75.75 0 0 0 0 1.5H23v3.75a.75.75 0 0 0 1.5 0V24h3.75a.75.75 0 0 0 0-1.5H24.5v-3.75a.75.75 0 0 0-.75-.75m1.75-8a4.5 4.5 0 0 1 4.5 4.5v2.777a9 9 0 0 0-2-1.57V14.5a2.5 2.5 0 0 0-2.5-2.5h-19A2.5 2.5 0 0 0 4 14.5v10A2.5 2.5 0 0 0 6.5 27h8.706a9 9 0 0 0 1.173 2H6.5A4.5 4.5 0 0 1 2 24.5v-10A4.5 4.5 0 0 1 6.5 10zM13 20a1 1 0 1 1 0 2H7a1 1 0 1 1 0-2zm3-5a1 1 0 1 1 0 2H7a1 1 0 1 1 0-2zM27.5 3a2.5 2.5 0 0 1 0 5h-23a2.5 2.5 0 0 1 0-5z");
}

</style>
