<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="f8rxl-pjd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:text-underline-20-regular" /></template>
<style>
.f8rxl-pjd {
  fill: currentColor;
  d: path("M6 3.5a.5.5 0 0 0-1 0v6.455C5 12.736 7.234 15 10 15s5-2.264 5-5.045V3.5a.5.5 0 0 0-1 0v6.455C14 12.194 12.204 14 10 14s-4-1.806-4-4.045zm-1 13a.5.5 0 0 1 .5-.5h9a.5.5 0 0 1 0 1h-9a.5.5 0 0 1-.5-.5");
}

</style>
