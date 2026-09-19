<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zbqu8obfp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:round-e-mobiledata" /></template>
<style>
.zbqu8obfp {
  fill: currentColor;
  d: path("M16 8c0-.55-.45-1-1-1H9c-.55 0-1 .45-1 1v8c0 .55.45 1 1 1h6c.55 0 1-.45 1-1s-.45-1-1-1h-5v-2h5c.55 0 1-.45 1-1s-.45-1-1-1h-5V9h5c.55 0 1-.45 1-1");
}

</style>
