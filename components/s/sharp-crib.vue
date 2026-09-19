<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o2ba046wl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-crib" /></template>
<style>
.o2ba046wl {
  fill: currentColor;
  d: path("M20 9h-8V4H8C5.79 4 4 5.79 4 8v8h4v2.93c-.61-.35-1.16-.78-1.65-1.27l-1.42 1.42C6.74 20.88 9.24 22 12 22s5.26-1.12 7.07-2.93l-1.42-1.42c-.49.49-1.05.92-1.65 1.27V16h4zm-6 10.75c-.64.16-1.31.25-2 .25s-1.36-.09-2-.25V16h4z");
}

</style>
