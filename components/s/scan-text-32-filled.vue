<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="eur3p9aub"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:scan-text-32-filled" /></template>
<style>
.eur3p9aub {
  fill: currentColor;
  d: path("M3.25 21c.69 0 1.25.56 1.25 1.25v3.25a2 2 0 0 0 2 2h3.25a1.25 1.25 0 1 1 0 2.5H6.5A4.5 4.5 0 0 1 2 25.5v-3.25c0-.69.56-1.25 1.25-1.25m25.5 0c.69 0 1.25.56 1.25 1.25v3.25a4.5 4.5 0 0 1-4.5 4.5h-3.25a1.25 1.25 0 1 1 0-2.5h3.25a2 2 0 0 0 2-2v-3.25c0-.69.56-1.25 1.25-1.25m-12 0a1.25 1.25 0 1 1 0 2.5h-6.5a1.25 1.25 0 1 1 0-2.5zm5-6a1.25 1.25 0 1 1 0 2.5h-11.5a1.25 1.25 0 1 1 0-2.5zm0-6a1.25 1.25 0 1 1 0 2.5h-11.5a1.25 1.25 0 1 1 0-2.5zm-12-7a1.25 1.25 0 1 1 0 2.5H6.5a2 2 0 0 0-2 2v3.25a1.25 1.25 0 1 1-2.5 0V6.5A4.5 4.5 0 0 1 6.5 2zM25.5 2A4.5 4.5 0 0 1 30 6.5v3.25a1.25 1.25 0 1 1-2.5 0V6.5a2 2 0 0 0-2-2h-3.25a1.25 1.25 0 1 1 0-2.5z");
}

</style>
