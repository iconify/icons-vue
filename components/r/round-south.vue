<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q89odz03u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:round-south" /></template>
<style>
.q89odz03u {
  fill: currentColor;
  d: path("M18.3 14.29a.996.996 0 0 0-1.41 0L13 18.17V3c0-.55-.45-1-1-1s-1 .45-1 1v15.18L7.12 14.3a.996.996 0 1 0-1.41 1.41l5.59 5.59c.39.39 1.02.39 1.41 0l5.59-5.59c.38-.39.38-1.03 0-1.42");
}

</style>
