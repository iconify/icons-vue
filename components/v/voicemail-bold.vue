<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="jc3xp1agn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:voicemail-bold" /></template>
<style>
.jc3xp1agn {
  fill: currentColor;
  d: path("M196 68a60 60 0 0 0-48 96h-40a60 60 0 1 0-48 24h136a60 60 0 0 0 0-120M24 128a36 36 0 1 1 36 36a36 36 0 0 1-36-36m172 36a36 36 0 1 1 36-36a36 36 0 0 1-36 36");
}

</style>
