<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="poi7ksbht"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:person-subtract-16-filled" /></template>
<style>
.poi7ksbht {
  fill: currentColor;
  d: path("M9.626 5.07a5.5 5.5 0 0 0-3.299 1.847A2.751 2.751 0 1 1 9.626 5.07M5.6 8c-.384.75-.6 1.6-.6 2.5c0 1.31.458 2.512 1.222 3.457C3.555 13.653 2 11.803 2 10v-.5A1.5 1.5 0 0 1 3.5 8zm4.9 7a4.5 4.5 0 1 0 0-9a4.5 4.5 0 0 0 0 9m-2.121-5h4.242a.5.5 0 1 1 0 1H8.38a.5.5 0 0 1 0-1");
}

</style>
