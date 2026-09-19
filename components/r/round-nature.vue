<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x8v1dib3v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:round-nature" /></template>
<style>
.x8v1dib3v {
  fill: currentColor;
  d: path("M13 16.12c3.37-.4 6.01-3.19 6.16-6.64c.17-3.87-3.02-7.25-6.89-7.31c-3.92-.05-7.1 3.1-7.1 7A6.98 6.98 0 0 0 11 16.06V20H6c-.55 0-1 .45-1 1s.45 1 1 1h12c.55 0 1-.45 1-1s-.45-1-1-1h-5z");
}

</style>
