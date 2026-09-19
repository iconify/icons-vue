<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h3smqkbnh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:round-straight" /></template>
<style>
.h3smqkbnh {
  fill: currentColor;
  d: path("m13 6.83l.88.88a.996.996 0 1 0 1.41-1.41L12.7 3.71a.996.996 0 0 0-1.41 0L8.71 6.29a.996.996 0 1 0 1.41 1.41l.88-.87V20c0 .55.45 1 1 1s1-.45 1-1z");
}

</style>
