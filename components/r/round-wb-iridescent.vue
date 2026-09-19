<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tzst_db8j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:round-wb-iridescent" /></template>
<style>
.tzst_db8j {
  fill: currentColor;
  d: path("M6 15h12c.55 0 1-.45 1-1v-3.95c0-.55-.45-1-1-1H6c-.55 0-1 .45-1 1V14c0 .55.45 1 1 1m5-13v1.05c0 .55.45.95 1 .95s1-.4 1-.95V2c0-.55-.45-1-1-1s-1 .45-1 1m7.34 2.3l-.38.38a.996.996 0 1 0 1.41 1.41l.38-.38a.996.996 0 1 0-1.41-1.41M13 22v-.96c0-.55-.45-1-1-1s-1 .45-1 1V22c0 .55.45 1 1 1s1-.45 1-1m6.74-3.61l-.39-.39a.996.996 0 1 0-1.41 1.41l.38.39c.39.39 1.02.39 1.41 0l.01-.01a.984.984 0 0 0 0-1.4M4.25 5.71l.39.39a.996.996 0 1 0 1.41-1.41l-.39-.39a.996.996 0 0 0-1.41 0c-.38.39-.38 1.03 0 1.41m1.42 14.08l.38-.38A.996.996 0 1 0 4.64 18l-.38.38a.996.996 0 1 0 1.41 1.41");
}

</style>
