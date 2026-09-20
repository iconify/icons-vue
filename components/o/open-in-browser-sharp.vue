<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r-v-4lmni"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:open-in-browser-sharp" /></template>
<style>
.r-v-4lmni {
  fill: currentColor;
  d: path("M3 21V3h18v18h-6v-2h4V7H5v12h4v2zm8 0v-6.15l-1.6 1.6L8 15l4-4l4 4l-1.4 1.45l-1.6-1.6V21z");
}

</style>
