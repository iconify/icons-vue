<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pzmr-rg_b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:tamper-detection-off-sharp" /></template>
<style>
.pzmr-rg_b {
  fill: currentColor;
  d: path("M3.625 23L0 19.4L1.4 18L3 19.6v-8.1h1.5V16h1v-6H7v6h1v-5h1.5v5h1v-4H12v11zm16.925.35L17.2 20H14v-3.2L6.2 9H2V4.8L.65 3.45l1.4-1.4l19.9 19.9zM22 17.5l-4-4v1.7L6.8 4H18v6.5l4-4z");
}

</style>
