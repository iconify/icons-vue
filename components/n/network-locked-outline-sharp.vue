<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c59xlfbvx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:network-locked-outline-sharp" /></template>
<style>
.c59xlfbvx {
  fill: currentColor;
  d: path("M3 21L21 3v8.462h-1V5.426L5.421 20H14v1zm13.23 0v-4.538h1v-1q0-.748.511-1.259t1.259-.51t1.259.51t.51 1.259v1h.981V21zM18 16.462h2v-1q0-.425-.288-.713T19 14.461t-.712.288t-.288.713zM5.421 20L20 5.427l-7.29 7.287z");
}

</style>
