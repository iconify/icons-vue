<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xxhhelj_u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:network-locked" /></template>
<style>
.xxhhelj_u {
  fill: currentColor;
  d: path("M17.12 21q-.35 0-.62-.27t-.27-.618v-2.8q0-.35.27-.6t.62-.25h.11v-1q0-.749.511-1.259t1.259-.51t1.259.51t.51 1.258v1h.112q.358 0 .613.25q.256.25.256.6v2.8q0 .35-.256.62q-.255.269-.613.269zm.88-4.538h2v-1q0-.425-.288-.713T19 14.461t-.712.288t-.288.713zM3 21L21 3v8.462h-2q-2.075 0-3.537 1.462T14 16.462V21z");
}

</style>
