<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="akex1fi2m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:star-one-quarter-20-filled" /></template>
<style>
.akex1fi2m {
  fill: currentColor;
  d: path("M8 5.137L7.174 6.81l-4.317.627a1 1 0 0 0-.554 1.706l3.124 3.044l-.738 4.3a1.002 1.002 0 0 0 1.038 1.17a1 1 0 0 0 .414-.117L8 16.565z");
}

</style>
