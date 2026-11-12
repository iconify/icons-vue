<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m_pxpplcy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:touchpad-fill-sharp" /></template>
<style>
.m_pxpplcy {
  fill: currentColor;
  d: path("M2 13V5a1 1 0 0 1 1-1h18a1 1 0 0 1 1 1v8Zm0 2h9v5H3a1 1 0 0 1-1-1Zm20 0v4a1 1 0 0 1-1 1h-8v-5Z");
}

</style>
