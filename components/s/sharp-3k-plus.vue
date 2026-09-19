<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sv2yccc-d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-3k-plus" /></template>
<style>
.sv2yccc-d {
  fill: currentColor;
  d: path("M21 3H3v18h18zM10 9v6H5.5v-1.5h3v-1h-2v-1h2v-1h-3V9zm6 6h-1.75l-1.75-2.25V15H11V9h1.5v2.25L14.25 9H16l-2.25 3zm3-2.5h-1.5V14h-1v-1.5H15v-1h1.5V10h1v1.5H19z");
}

</style>
