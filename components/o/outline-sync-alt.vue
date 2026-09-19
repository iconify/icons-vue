<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h9dyyxs0l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:outline-sync-alt" /></template>
<style>
.h9dyyxs0l {
  fill: currentColor;
  d: path("M7.41 13.41L6 12l-4 4l4 4l1.41-1.41L5.83 17H21v-2H5.83zm9.18-2.82L18 12l4-4l-4-4l-1.41 1.41L18.17 7H3v2h15.17z");
}

</style>
