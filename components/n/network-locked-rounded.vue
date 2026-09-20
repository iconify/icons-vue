<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ays2otb0q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:network-locked-rounded" /></template>
<style>
.ays2otb0q {
  fill: currentColor;
  d: path("M17.12 21q-.35 0-.62-.27t-.27-.618v-2.8q0-.35.27-.6t.62-.25h.11v-1q0-.749.511-1.259t1.259-.51t1.259.51t.51 1.258v1h.112q.358 0 .613.25q.256.25.256.6v2.8q0 .35-.256.62q-.255.269-.613.269zm.88-4.538h2v-1q0-.425-.288-.713T19 14.461t-.712.288t-.288.713zM4.944 21q-.534 0-.742-.497t.171-.876L19.627 4.373q.379-.379.876-.171t.497.742v5.71q0 .343-.232.575t-.576.233H19q-2.075 0-3.537 1.462T14 16.462v3.73q0 .344-.232.576t-.576.232z");
}

</style>
