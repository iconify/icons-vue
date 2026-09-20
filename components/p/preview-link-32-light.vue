<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="icfuh7rxo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:preview-link-32-light" /></template>
<style>
.icfuh7rxo {
  fill: currentColor;
  d: path("M25.5 4A4.5 4.5 0 0 1 30 8.5v15a4.5 4.5 0 0 1-4.5 4.5h-19A4.5 4.5 0 0 1 2 23.5v-15A4.5 4.5 0 0 1 6.5 4zm-19 1A3.5 3.5 0 0 0 3 8.5v15A3.5 3.5 0 0 0 6.5 27h19a3.5 3.5 0 0 0 3.5-3.5v-15A3.5 3.5 0 0 0 25.5 5zm8 18a.5.5 0 0 1 0 1h-8a.5.5 0 0 1 0-1zM25 19a1 1 0 0 1 1 1v3a1 1 0 0 1-1 1h-7a1 1 0 0 1-1-1v-3a1 1 0 0 1 1-1zm-7 4h7v-3h-7zm-3.5-4a.5.5 0 0 1 0 1h-8a.5.5 0 0 1 0-1zM25 8a1 1 0 0 1 1 1v6a1 1 0 0 1-1 1H7a1 1 0 0 1-1-1V9a1 1 0 0 1 1-1zM7 15h18V9H7z");
}

</style>
