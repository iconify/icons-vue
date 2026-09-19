<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l0yp1jb4e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-archive" /></template>
<style>
.l0yp1jb4e {
  fill: currentColor;
  d: path("M18.71 3H5.29L3 5.79V21h18V5.79zM12 17.5L6.5 12H10v-2h4v2h3.5zM5.12 5l.81-1h12l.94 1z");
}

</style>
