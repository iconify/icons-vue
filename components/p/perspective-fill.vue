<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="mzh3pccpk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:perspective-fill" /></template>
<style>
.mzh3pccpk {
  fill: currentColor;
  d: path("M248 136a8 8 0 0 1-8 8h-16v64a16 16 0 0 1-16 16a16.5 16.5 0 0 1-2.87-.26l-160-29.09A16 16 0 0 1 32 178.91V144H16a8 8 0 0 1 0-16h224a8 8 0 0 1 8 8M36 112h184a4 4 0 0 0 4-4V48.42a16.48 16.48 0 0 0-4.07-11.08a16 16 0 0 0-14.79-5.08l-160 29.09A16 16 0 0 0 32 77.09V108a4 4 0 0 0 4 4");
}

</style>
