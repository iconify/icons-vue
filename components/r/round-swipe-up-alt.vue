<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o0gbttbzj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:round-swipe-up-alt" /></template>
<style>
.o0gbttbzj {
  fill: currentColor;
  d: path("m13 5.41l.88.88a.996.996 0 1 0 1.41-1.41L12.7 2.29a.996.996 0 0 0-1.41 0L8.71 4.88a.996.996 0 1 0 1.41 1.41l.88-.88v4.27a5 5 0 1 0 2 0z");
}

</style>
