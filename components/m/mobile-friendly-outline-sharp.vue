<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d53r80wzq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:mobile-friendly-outline-sharp" /></template>
<style>
.d53r80wzq {
  fill: currentColor;
  d: path("M4 23V1h14v6h-2V6H6v12h10v-1h2v6zm2-3v1h10v-1zM6 4h10V3H6zm0 0V3zm0 16v1zm8.95-4l-4.25-4.25l1.4-1.4l2.85 2.85l5.65-5.65l1.4 1.4z");
}

</style>
