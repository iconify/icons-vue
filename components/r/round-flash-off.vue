<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="drgtggb8o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:round-flash-off" /></template>
<style>
.drgtggb8o {
  fill: currentColor;
  d: path("M16.12 11.5a.995.995 0 0 0-.86-1.5h-1.87l2.28 2.28zm.16-8.05c.33-.67-.15-1.45-.9-1.45H8c-.55 0-1 .45-1 1v.61l6.13 6.13zm2.16 14.43L4.12 3.56a.996.996 0 1 0-1.41 1.41L7 9.27V12c0 .55.45 1 1 1h2v7.15c0 .51.67.69.93.25l2.65-4.55l3.44 3.44c.39.39 1.02.39 1.41 0c.4-.39.4-1.02.01-1.41");
}

</style>
