<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="fe_k65rsf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:text-align-justify-low-rotate-90-20-filled" /></template>
<style>
.fe_k65rsf {
  fill: currentColor;
  d: path("M15.5 9a.75.75 0 0 1 .75.75v7.5a.75.75 0 0 1-1.5 0v-7.5A.75.75 0 0 1 15.5 9m-5 0a.75.75 0 0 1 .75.75v7.5a.75.75 0 0 1-1.5 0v-7.5A.75.75 0 0 1 10.5 9M6.25 2.75a.75.75 0 0 0-1.5 0v14.5a.75.75 0 0 0 1.5 0z");
}

</style>
