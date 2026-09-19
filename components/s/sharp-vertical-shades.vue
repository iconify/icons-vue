<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yvc_kgbsu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-vertical-shades" /></template>
<style>
.yvc_kgbsu {
  fill: currentColor;
  d: path("M20 19V3H4v16H2v2h20v-2zm-10 0V5h4v14z");
}

</style>
