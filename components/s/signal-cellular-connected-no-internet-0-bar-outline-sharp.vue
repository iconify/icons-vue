<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qerl4db3i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:signal-cellular-connected-no-internet-0-bar-outline-sharp" /></template>
<style>
.qerl4db3i {
  fill: currentColor;
  d: path("M2 22L22 2v6h-2V6.825L6.825 20H18v2zm18-4v-8h2v8zm2 2v2h-2v-2z");
}

</style>
