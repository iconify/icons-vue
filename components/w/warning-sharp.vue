<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xg41-gd_j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:warning-sharp" /></template>
<style>
.xg41-gd_j {
  fill: currentColor;
  d: path("M2.73 20L12 4l9.27 16zm9.704-2.566q.182-.182.182-.434t-.182-.434t-.434-.181t-.434.181t-.181.434t.181.434t.434.181t.434-.181m-.934-2.05h1v-5h-1z");
}

</style>
