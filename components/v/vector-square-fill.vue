<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sp_34smiy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:vector-square-fill" /></template>
<style>
.sp_34smiy {
  fill: currentColor;
  d: path("M2 4a2 2 0 0 1 2-2h2a2 2 0 0 1 2 2h8a2 2 0 0 1 2-2h2a2 2 0 0 1 2 2v2a2 2 0 0 1-2 2v8a2 2 0 0 1 2 2v2a2 2 0 0 1-2 2h-2a2 2 0 0 1-2-2H8a2 2 0 0 1-2 2H4a2 2 0 0 1-2-2v-2a2 2 0 0 1 2-2V8a2 2 0 0 1-2-2Zm4 4v8a2 2 0 0 1 2 2h8a2 2 0 0 1 2-2V8a2 2 0 0 1-2-2H8a2 2 0 0 1-2 2");
}

</style>
