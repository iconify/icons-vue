<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ablhl1bfc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:window-new-rotate-180-32-filled" /></template>
<style>
.ablhl1bfc {
  fill: currentColor;
  d: path("M7.5 29A4.5 4.5 0 0 1 3 24.5v-13a4.5 4.5 0 0 1 4.025-4.475A4.5 4.5 0 0 1 11.5 3h10a7.5 7.5 0 0 1 7.5 7.5v10a4.5 4.5 0 0 1-4.024 4.476A4.5 4.5 0 0 1 20.5 29zM25 22.95a2.5 2.5 0 0 0 2-2.45v-10A5.5 5.5 0 0 0 21.5 5h-10a2.5 2.5 0 0 0-2.45 2H20.5a4.5 4.5 0 0 1 4.5 4.5zM17 24a1 1 0 1 0 0-2h-5.586l8.293-8.293a1 1 0 1 0-1.414-1.414L10 20.586V15a1 1 0 1 0-2 0v8a1 1 0 0 0 1 1z");
}

</style>
