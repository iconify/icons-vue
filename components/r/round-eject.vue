<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m1crl4bvu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:round-eject" /></template>
<style>
.m1crl4bvu {
  fill: currentColor;
  d: path("M6 17h12c.55 0 1 .45 1 1s-.45 1-1 1H6c-.55 0-1-.45-1-1s.45-1 1-1m5.17-10.75l-4.8 7.2c-.45.66.03 1.55.83 1.55h9.6c.8 0 1.28-.89.83-1.55l-4.8-7.2a.99.99 0 0 0-1.66 0");
}

</style>
