<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="f0a2sjbrg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:people-prohibited-48-filled" /></template>
<style>
.f0a2sjbrg {
  fill: currentColor;
  d: path("M34 24c6.075 0 11 4.925 11 11s-4.925 11-11 11s-11-4.925-11-11s4.925-11 11-11m-5.061 17.83a8.5 8.5 0 0 0 11.89-11.89zM34 26.5a8.5 8.5 0 0 0-6.83 13.562L39.063 28.17A8.46 8.46 0 0 0 34 26.5M25.25 25q.212 0 .417.023A12.97 12.97 0 0 0 21 35c0 1.156.151 2.276.435 3.343c-1.497.41-3.288.657-5.435.657c-13 0-13-9-13-9v-1.25A3.75 3.75 0 0 1 6.75 25zM16 6a8 8 0 1 1 0 16a8 8 0 0 1 0-16m18 4a6 6 0 1 1 0 12a6 6 0 0 1 0-12");
}

</style>
