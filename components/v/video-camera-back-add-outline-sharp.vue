<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o9rrh7g1n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:video-camera-back-add-outline-sharp" /></template>
<style>
.o9rrh7g1n {
  fill: currentColor;
  d: path("M2 20v-8h2v6h12V6h-6V4h8v6.5l4-4v11l-4-4V20zm3-4h10l-3.375-4.5L9 15l-1.625-2.175zm-1-6V8H2V6h2V4h2v2h2v2H6v2z");
}

</style>
