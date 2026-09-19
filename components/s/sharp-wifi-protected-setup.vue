<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ysfczkbzl"/><path class="fea8x0b8c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-wifi-protected-setup" /></template>
<style>
.fea8x0b8c {
  fill: currentColor;
  d: path("M7.46 8.88c0-1.31.32-2.54.88-3.63a8.48 8.48 0 0 0-3.88 7.13c0 2.52 1.1 4.77 2.84 6.33L5 21h8v-8l-2.3 2.3c-1.96-1.46-3.24-3.78-3.24-6.42");
}

.ysfczkbzl {
  fill: currentColor;
  d: path("M16.71 5.29L19 3h-8v8l2.3-2.3c1.97 1.46 3.25 3.78 3.25 6.42c0 1.31-.32 2.54-.88 3.63c2.33-1.52 3.88-4.14 3.88-7.13c0-2.52-1.11-4.77-2.84-6.33");
}

</style>
