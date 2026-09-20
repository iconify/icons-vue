<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="kkq279dol"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:person-arrow-left-16-filled" /></template>
<style>
.kkq279dol {
  fill: currentColor;
  d: path("M9.626 5.07a5.5 5.5 0 0 0-3.299 1.847A2.751 2.751 0 1 1 9.626 5.07M5.6 8c-.384.75-.6 1.6-.6 2.5c0 1.31.458 2.512 1.222 3.457C3.555 13.653 2 11.803 2 10v-.5A1.5 1.5 0 0 1 3.5 8zm9.4 2.5a4.5 4.5 0 1 1-9 0a4.5 4.5 0 0 1 9 0m-6.853-.354l-.003.003a.5.5 0 0 0-.144.348v.006a.5.5 0 0 0 .146.35l2 2a.5.5 0 0 0 .708-.707L9.707 11H12.5a.5.5 0 0 0 0-1H9.707l1.147-1.146a.5.5 0 0 0-.708-.708z");
}

</style>
