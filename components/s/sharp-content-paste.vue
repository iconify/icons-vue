<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o-kjx9blo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-content-paste" /></template>
<style>
.o-kjx9blo {
  fill: currentColor;
  d: path("M21 2h-6.18C14.4.84 13.3 0 12 0S9.6.84 9.18 2H3v20h18zm-9 0c.55 0 1 .45 1 1s-.45 1-1 1s-1-.45-1-1s.45-1 1-1m7 18H5V4h2v3h10V4h2z");
}

</style>
