<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j96mtrbnx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:video-template-sharp" /></template>
<style>
.j96mtrbnx {
  fill: currentColor;
  d: path("M3 23v-3h18v3zm-1-5V6h20v12zm8-3l5-3l-5-3zM3 4V1h18v3z");
}

</style>
