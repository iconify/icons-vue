<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p9ejy_b4u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:space-dashboard-2-outline-sharp" /></template>
<style>
.p9ejy_b4u {
  fill: currentColor;
  d: path("M4 20V4h16v16zm1-1h8.5V5H5zm9.5 0H19v-6.5h-4.5zm0-7.5H19V5h-4.5z");
}

</style>
