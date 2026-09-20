<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y4-xg2b4b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:network-locked-sharp" /></template>
<style>
.y4-xg2b4b {
  fill: currentColor;
  d: path("M16.23 21v-4.538h1v-1q0-.748.511-1.259t1.259-.51t1.259.51t.51 1.259v1h.981V21zM18 16.462h2v-1q0-.425-.288-.713T19 14.461t-.712.288t-.288.713zM3 21L21 3v8.462h-2q-2.075 0-3.537 1.462T14 16.462V21z");
}

</style>
