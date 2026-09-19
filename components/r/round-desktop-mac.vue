<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nalzoobbm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:round-desktop-mac" /></template>
<style>
.nalzoobbm {
  fill: currentColor;
  d: path("M21 2H3c-1.1 0-2 .9-2 2v12c0 1.1.9 2 2 2h7l-1.63 2.45c-.44.66.03 1.55.83 1.55h5.6c.8 0 1.28-.89.83-1.55L14 18h7c1.1 0 2-.9 2-2V4c0-1.1-.9-2-2-2m0 12H3V5c0-.55.45-1 1-1h16c.55 0 1 .45 1 1z");
}

</style>
