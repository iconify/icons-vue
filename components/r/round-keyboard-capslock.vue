<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s2d2b-b_s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:round-keyboard-capslock" /></template>
<style>
.s2d2b-b_s {
  fill: currentColor;
  d: path("m12 8.41l3.89 3.89a.996.996 0 1 0 1.41-1.41L12.71 6.3a.996.996 0 0 0-1.41 0l-4.6 4.59a.996.996 0 1 0 1.41 1.41zM7 18h10c.55 0 1-.45 1-1s-.45-1-1-1H7c-.55 0-1 .45-1 1s.45 1 1 1");
}

</style>
