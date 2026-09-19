<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g4dr2ectz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:round-u-turn-left" /></template>
<style>
.g4dr2ectz {
  fill: currentColor;
  d: path("M3.71 12.29a.996.996 0 0 1 1.41 0l.88.88V9c0-3.31 2.69-6 6-6s6 2.69 6 6v11c0 .55-.45 1-1 1s-1-.45-1-1V9c0-2.21-1.79-4-4-4S8 6.79 8 9v4.17l.88-.88a.996.996 0 1 1 1.41 1.41L7.7 16.29a.996.996 0 0 1-1.41 0L3.7 13.7c-.38-.38-.38-1.02.01-1.41");
}

</style>
