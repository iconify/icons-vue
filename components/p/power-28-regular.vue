<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="rdqqf9clu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:power-28-regular" /></template>
<style>
.rdqqf9clu {
  fill: currentColor;
  d: path("M10.69 5.267a.75.75 0 0 1-.397.983A9.5 9.5 0 0 0 4.5 15a9.5 9.5 0 0 0 19 0a9.5 9.5 0 0 0-5.793-8.75a.75.75 0 0 1 .586-1.38A11 11 0 0 1 25 15c0 6.075-4.925 11-11 11S3 21.075 3 15A11 11 0 0 1 9.707 4.87a.75.75 0 0 1 .983.397M14 2a.75.75 0 0 1 .75.75v9.5a.75.75 0 0 1-1.5 0v-9.5A.75.75 0 0 1 14 2");
}

</style>
