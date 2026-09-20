<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mgisxui8f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:scan-outline-sharp" /></template>
<style>
.mgisxui8f {
  fill: currentColor;
  d: path("M5 21v-4.5h1V20h12v-3.5h1V21zm0-9.5V3h9.5L19 7.5v4h-1V8h-4V4H6v7.5zm-3.423 3v-1h20.846v1zM12 16.5");
}

</style>
