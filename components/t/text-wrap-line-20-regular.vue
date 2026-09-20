<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="xpy2l7b7b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:text-wrap-line-20-regular" /></template>
<style>
.xpy2l7b7b {
  fill: currentColor;
  d: path("M3.5 3a.5.5 0 0 0 0 1h13a.5.5 0 0 0 0-1zm0 12a.5.5 0 0 0 0 1h13a.5.5 0 0 0 0-1zm7.5-2.5a.5.5 0 0 1 .5-.5h5a.5.5 0 0 1 0 1h-5a.5.5 0 0 1-.5-.5m-7-4a2.5 2.5 0 0 1 5 0v5a.5.5 0 0 0 1 0v-5a3.5 3.5 0 1 0-7 0v5a.5.5 0 0 0 1 0z");
}

</style>
