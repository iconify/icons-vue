<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u2z6kohcf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:round-carpenter" /></template>
<style>
.u2z6kohcf {
  fill: currentColor;
  d: path("M19.73 14.23L7.71 2.21a.996.996 0 0 0-1.41 0L3.7 4.8a1 1 0 0 0-.11 1.28l7.65 10.98c-.78.78-.78 2.05 0 2.83l1.41 1.41c.78.78 2.05.78 2.83 0l4.24-4.24c.79-.78.79-2.05.01-2.83m-5.66 5.65l-1.41-1.41l4.24-4.24l1.41 1.41z");
}

</style>
