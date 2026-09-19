<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wvdkjvbab"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-tap-and-play" /></template>
<style>
.wvdkjvbab {
  fill: currentColor;
  d: path("M2 16v2c2.76 0 5 2.24 5 5h2c0-3.87-3.13-7-7-7m0 4v3h3c0-1.66-1.34-3-3-3m0-8v2a9 9 0 0 1 9 9h2c0-6.08-4.92-11-11-11M5 1v9.37c.69.16 1.36.37 2 .64V5h10v13h-3.03c.52 1.25.84 2.59.95 4H19V1z");
}

</style>
