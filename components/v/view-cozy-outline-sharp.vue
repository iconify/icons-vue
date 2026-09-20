<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tj3m3nbvo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:view-cozy-outline-sharp" /></template>
<style>
.tj3m3nbvo {
  fill: currentColor;
  d: path("M4 10.5V4h6.5v6.5zm1-1h4.5V5H5zM4 20v-6.5h6.5V20zm1-1h4.5v-4.5H5zm8.5-8.5V4H20v6.5zm1-1H19V5h-4.5zm-1 10.5v-6.5H20V20zm1-1H19v-4.5h-4.5zm0-4.5");
}

</style>
