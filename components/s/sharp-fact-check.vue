<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rzckwb-ds"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-fact-check" /></template>
<style>
.rzckwb-ds {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M2 3v18h20V3zm8 14H5v-2h5zm0-4H5v-2h5zm0-4H5V7h5zm4.82 6L12 12.16l1.41-1.41l1.41 1.42L17.99 9l1.42 1.42z");
}

</style>
