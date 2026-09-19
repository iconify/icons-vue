<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xjoh4447g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-restore-from-trash" /></template>
<style>
.xjoh4447g {
  fill: currentColor;
  d: path("M6 21h12V7H6zm6-11l4 4h-2v4h-4v-4H8zm3.5-6l-1-1h-5l-1 1H5v2h14V4z");
}

</style>
