<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hodjzcbue"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-crop-din" /></template>
<style>
.hodjzcbue {
  fill: currentColor;
  d: path("M21 3H3v18h18zm-2 16H5V5h14z");
}

</style>
