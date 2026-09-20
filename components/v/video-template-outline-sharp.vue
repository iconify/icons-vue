<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pu9_2ctog"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:video-template-outline-sharp" /></template>
<style>
.pu9_2ctog {
  fill: currentColor;
  d: path("M3 23v-3h2v1h14v-1h2v3zm-1-5V6h20v12zm8-3l5-3l-5-3zM3 4V1h18v3h-2V3H5v1zm1 12h16V8H4zm8-4");
}

</style>
