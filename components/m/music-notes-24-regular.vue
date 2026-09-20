<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wkv04yget"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:music-notes-24-regular" /></template>
<style>
.wkv04yget {
  fill: currentColor;
  d: path("M19.698 2.148A.75.75 0 0 1 20 2.75v13.5l-.004.079q.004.086.004.171a3.5 3.5 0 1 1-1.5-2.873V7.758l-8.5 2.55v7.942l-.004.079q.004.085.004.171a3.5 3.5 0 1 1-1.5-2.873V5.75a.75.75 0 0 1 .534-.718l10-3a.75.75 0 0 1 .664.116M10 8.742l8.5-2.55V3.758L10 6.308zM6.5 16.5a2 2 0 1 0 0 4a2 2 0 0 0 0-4m8 0a2 2 0 1 0 4 0a2 2 0 0 0-4 0");
}

</style>
