<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i0hptcb9r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:round-nightlight-round" /></template>
<style>
.i0hptcb9r {
  fill: currentColor;
  d: path("M15.5 22h.21c.84-.02 1.12-1.11.41-1.56a9.99 9.99 0 0 1-4.63-8.43c0-3.55 1.85-6.66 4.63-8.44c.7-.45.44-1.54-.39-1.56h-.13c-4.9-.05-9.21 3.53-9.98 8.37C4.64 16.61 9.45 22 15.5 22");
}

</style>
