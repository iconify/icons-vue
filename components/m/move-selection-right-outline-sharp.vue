<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ctau_ebvj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:move-selection-right-outline-sharp" /></template>
<style>
.ctau_ebvj {
  fill: currentColor;
  d: path("M10 18V6h12v12zm2-2h8V8h-8zm-6 2v-2h2v2zM6 8V6h2v2zM2 18v-2h2v2zm0-5v-2h2v2zm0-5V6h2v2zm14 4");
}

</style>
