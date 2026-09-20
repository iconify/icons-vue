<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qu65vzbqw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:missed-video-call-sharp" /></template>
<style>
.qu65vzbqw {
  fill: currentColor;
  d: path("M2 20V4h16v6.5l4-4v11l-4-4V20zm8.7-4l4.5-4.55l-1.4-1.4l-3.1 3.1L8.5 11H10V9H5v5h2v-1.7z");
}

</style>
