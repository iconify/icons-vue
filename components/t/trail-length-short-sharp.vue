<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yv_g7jbfe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:trail-length-short-sharp" /></template>
<style>
.yv_g7jbfe {
  fill: currentColor;
  d: path("M15 16.5q-1.748 0-3.005-1.137T10.523 12.5H4.5v-1h6.023q.087-.806.51-1.623q.425-.818 1.217-1.377H6.5v-1H15q1.868 0 3.184 1.316Q19.5 10.13 19.5 11.997t-1.316 3.185T15 16.5m-7.5 0v-1h2v1z");
}

</style>
