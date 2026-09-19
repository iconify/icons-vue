<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m23b6h8ct"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-sim-card" /></template>
<style>
.m23b6h8ct {
  fill: currentColor;
  d: path("M19.99 2H10L4 8v14h16zM9 19H7v-2h2zm8 0h-2v-2h2zm-8-4H7v-4h2zm4 4h-2v-4h2zm0-6h-2v-2h2zm4 2h-2v-4h2z");
}

</style>
