<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qpe9macaf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-tv-off" /></template>
<style>
.qpe9macaf {
  fill: currentColor;
  d: path("M21 7v10.88l2 2V5h-9.58l3.29-3.3L16 1l-4 4l-4-4l-.7.7L10.58 5H8.12l2 2zM2.41 2.13l-.14.14L1 3.54l1.53 1.53H1V21h17.46l1.99 1.99l1.26-1.26l.15-.15zM3 19V7h1.46l12 12z");
}

</style>
