<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="h1err7b0o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:sticker-12-filled" /></template>
<style>
.h1err7b0o {
  fill: currentColor;
  d: path("M3 1h6a2 2 0 0 1 2 2v3H8c-.725 0-1.36.385-1.71.962a.9.9 0 0 1-.294.048c-.318 0-.572-.157-.768-.353a1.8 1.8 0 0 1-.281-.37a.5.5 0 0 0-.894.447v.002l.002.001l.002.005l.008.015a2 2 0 0 0 .113.187c.075.114.19.266.343.42c.303.304.797.646 1.475.646H6V11H3a2 2 0 0 1-2-2V3a2 2 0 0 1 2-2m1.5 4a.5.5 0 1 0 0-1a.5.5 0 0 0 0 1m3 0a.5.5 0 1 0 0-1a.5.5 0 0 0 0 1M11 7H8a1 1 0 0 0-1 1v3h.5a.5.5 0 0 0 .354-.146l3-3A.5.5 0 0 0 11 7.5z");
}

</style>
