<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l2esorb9m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:open-in-new-down-outline-sharp" /></template>
<style>
.l2esorb9m {
  fill: currentColor;
  d: path("M3 21V3h18v9h-2V5H5v14h7v2zm11 0v-2h3.6L8.3 9.7l1.4-1.4l9.3 9.275V14h2v7z");
}

</style>
