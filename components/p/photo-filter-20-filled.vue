<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="zmwrk2blg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:photo-filter-20-filled" /></template>
<style>
.zmwrk2blg {
  fill: currentColor;
  d: path("M6.257 13.743a6 6 0 1 1 7.486-7.486a6 6 0 1 1-7.486 7.486M3.5 8A4.5 4.5 0 0 0 6 12.032V12a6 6 0 0 1 6.032-6A4.5 4.5 0 0 0 3.5 8m4.468 6A4.5 4.5 0 1 0 14 7.968V8a6 6 0 0 1-6 6z");
}

</style>
