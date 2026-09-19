<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oy-kh2bzw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-mobile-friendly" /></template>
<style>
.oy-kh2bzw {
  fill: currentColor;
  d: path("M19 1H9c-1.1 0-2 .9-2 2v3h2V4h10v16H9v-2H7v3c0 1.1.9 2 2 2h10c1.1 0 2-.9 2-2V3c0-1.1-.9-2-2-2M7.01 13.47l-2.55-2.55l-1.27 1.27L7 16l7.19-7.19l-1.27-1.27z");
}

</style>
