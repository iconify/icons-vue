<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="og9negm3r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:round-grid-on" /></template>
<style>
.og9negm3r {
  fill: currentColor;
  d: path("M20 2H4c-1.1 0-2 .9-2 2v16c0 1.1.9 2 2 2h16c1.1 0 2-.9 2-2V4c0-1.1-.9-2-2-2M8 20H5c-.55 0-1-.45-1-1v-3h4zm0-6H4v-4h4zm0-6H4V5c0-.55.45-1 1-1h3zm6 12h-4v-4h4zm0-6h-4v-4h4zm0-6h-4V4h4zm5 12h-3v-4h4v3c0 .55-.45 1-1 1m1-6h-4v-4h4zm0-6h-4V4h3c.55 0 1 .45 1 1z");
}

</style>
