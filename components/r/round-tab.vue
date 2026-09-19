<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u1bylabmm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:round-tab" /></template>
<style>
.u1bylabmm {
  fill: currentColor;
  d: path("M21 3H3c-1.1 0-2 .9-2 2v14c0 1.1.9 2 2 2h18c1.1 0 2-.9 2-2V5c0-1.1-.9-2-2-2m-1 16H4c-.55 0-1-.45-1-1V6c0-.55.45-1 1-1h9v3c0 .55.45 1 1 1h7v9c0 .55-.45 1-1 1");
}

</style>
