<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="jpaw8wden"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:person-error-16-filled" /></template>
<style>
.jpaw8wden {
  fill: currentColor;
  d: path("M10.5 6a4.5 4.5 0 1 1 0 9a4.5 4.5 0 0 1 0-9M5.6 8c-.384.75-.6 1.6-.6 2.5c0 1.31.458 2.512 1.222 3.457C3.555 13.653 2 11.803 2 10v-.5A1.5 1.5 0 0 1 3.5 8zm4.9 3.875a.625.625 0 1 0 0 1.25a.625.625 0 0 0 0-1.25M10.5 8a.5.5 0 0 0-.5.5v2a.5.5 0 0 0 1 0v-2a.5.5 0 0 0-.5-.5M7 1.5a2.75 2.75 0 0 1 2.626 3.57a5.5 5.5 0 0 0-3.299 1.847A2.751 2.751 0 0 1 7 1.5");
}

</style>
