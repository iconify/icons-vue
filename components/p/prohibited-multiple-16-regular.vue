<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="g9q6xeu3j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:prohibited-multiple-16-regular" /></template>
<style>
.g9q6xeu3j {
  fill: currentColor;
  d: path("M3.464 3.464a5 5 0 0 1 6.7-.336l-7.036 7.037a5 5 0 0 1 .336-6.7m.371 7.408l7.037-7.037a5 5 0 0 1-7.037 7.037m7.408-8.115a6 6 0 1 0-8.486 8.486a6 6 0 0 0 8.486-8.486M14 7c0 1.217-.31 2.361-.857 3.358a5.02 5.02 0 0 1-2.785 2.785A7 7 0 0 1 7 14q-.553 0-1.084-.084a6 6 0 0 0 8-8Q14 6.446 14 7");
}

</style>
