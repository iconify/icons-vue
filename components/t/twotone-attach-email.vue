<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s-3f8l-od"/><path class="rmmgaxxhs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-attach-email" /></template>
<style>
.rmmgaxxhs {
  fill: currentColor;
  d: path("M21 14v4c0 1.1-.9 2-2 2s-2-.9-2-2v-4.5c0-.28.22-.5.5-.5s.5.22.5.5V18h2v-4.5a2.5 2.5 0 0 0-5 0V18c0 2.21 1.79 4 4 4s4-1.79 4-4v-4z");
}

.s-3f8l-od {
  fill: currentColor;
  d: path("m3 6l8 5l8-5v3h2V4c0-1.1-.9-2-2-2H3c-1.1 0-1.99.9-1.99 2L1 16c0 1.1.9 2 2 2h10v-2H3zm16-2l-8 5l-8-5z");
}

</style>
