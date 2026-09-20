<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h-gmahbpw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:text-position-square-left-24-regular" /></template>
<style>
.h-gmahbpw {
  fill: currentColor;
  d: path("M3.75 4a.75.75 0 0 0 0 1.5h16.5a.75.75 0 0 0 0-1.5zm9.5 3.5a.75.75 0 0 0 0 1.5h7a.75.75 0 0 0 0-1.5zm-.75 7.75a.75.75 0 0 1 .75-.75h7a.75.75 0 0 1 0 1.5h-7a.75.75 0 0 1-.75-.75m.75-4.25a.75.75 0 0 0 0 1.5h7a.75.75 0 0 0 0-1.5zM3 18.75a.75.75 0 0 1 .75-.75h16.5a.75.75 0 0 1 0 1.5H3.75a.75.75 0 0 1-.75-.75M4.5 11a2.5 2.5 0 0 1 5 0v4.75a.75.75 0 0 0 1.5 0V11a4 4 0 1 0-8 0v4.75a.75.75 0 0 0 1.5 0z");
}

</style>
