<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="skr-doe8g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:variables-outline" /></template>
<style>
.skr-doe8g {
  fill: currentColor;
  d: path("M3 17V7h18v10zm2-2h14V9H5zm0 0V9z");
}

</style>
