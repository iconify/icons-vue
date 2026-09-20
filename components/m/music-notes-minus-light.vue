<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="qi7ojzz1l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:music-notes-minus-light" /></template>
<style>
.qi7ojzz1l {
  fill: currentColor;
  d: path("M230 48a6 6 0 0 1-6 6h-48a6 6 0 0 1 0-12h48a6 6 0 0 1 6 6m-16 40v76a34.06 34.06 0 1 1-12-25.89V88a6 6 0 0 1 12 0m-12 76a22 22 0 1 0-22 22a22 22 0 0 0 22-22M86 108.69V196a34.06 34.06 0 1 1-12-25.89V56a6 6 0 0 1 4.54-5.82l56-14a6 6 0 1 1 2.92 11.64L86 60.68v35.63l72.54-18.13a6 6 0 1 1 2.92 11.64ZM74 196a22 22 0 1 0-22 22a22 22 0 0 0 22-22");
}

</style>
