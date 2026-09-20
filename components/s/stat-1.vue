<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sp4732bla"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:stat-1" /></template>
<style>
.sp4732bla {
  fill: currentColor;
  d: path("m7.4 14.702l-.708-.708L12 8.687l5.308 5.307l-.708.708l-4.6-4.594z");
}

</style>
