<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iyecw4bpx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:view-comfy-alt-outline" /></template>
<style>
.iyecw4bpx {
  fill: currentColor;
  d: path("M3 10V3h7v7zm1-1h5V4H4zM3 21v-7h7v7zm1-1h5v-5H4zm10-10V3h7v7zm1-1h5V4h-5zm-1 12v-7h7v7zm1-1h5v-5h-5zm0-5");
}

</style>
