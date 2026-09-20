<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="klinfuimz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:signal-cellular-connected-no-internet-4-bar-outline-sharp" /></template>
<style>
.klinfuimz {
  fill: currentColor;
  d: path("M2 22L22 2v6h-4v14zm18-4v-8h2v8zm0 4v-2h2v2z");
}

</style>
