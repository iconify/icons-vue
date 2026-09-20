<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ccb2iyuxs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:split-scene-down-sharp" /></template>
<style>
.ccb2iyuxs {
  fill: currentColor;
  d: path("M5 9.116V4h14v5.116zM5 20v-7.5H3v-1h18v1h-2V20z");
}

</style>
