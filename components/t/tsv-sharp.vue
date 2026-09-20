<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="slamsgb_b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:tsv-sharp" /></template>
<style>
.slamsgb_b {
  fill: currentColor;
  d: path("M3 19V5h18v14zm3.558-4.308h.884v-4.5h1.25v-.884H5.308v.884h1.25zm3.25 0h3.384v-3.111h-2.5v-1.389h2.5v-.884H9.808v3.1h2.5v1.4h-2.5zm6.096 0h1.192l1.558-5.384h-.923L16.5 13.566l-1.23-4.258h-.924z");
}

</style>
