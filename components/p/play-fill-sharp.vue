<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nnhdqmt5c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:play-fill-sharp" /></template>
<style>
.nnhdqmt5c {
  fill: currentColor;
  d: path("M20.496 11.132a.999.999 0 0 1 0 1.736l-14 8A1 1 0 0 1 5 20V4a1 1 0 0 1 1.496-.868Z");
}

</style>
