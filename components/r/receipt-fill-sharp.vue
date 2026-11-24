<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ne3impssu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:receipt-fill-sharp" /></template>
<style>
.ne3impssu {
  fill: currentColor;
  d: path("M4 2h16a1 1 0 0 1 1 1v18a1 1 0 0 1-1.447.894L16 20.118l-3.553 1.776a1 1 0 0 1-.894 0L8 20.118l-3.553 1.776A1 1 0 0 1 3 21V3a1 1 0 0 1 1-1m4 4a1 1 0 0 0 0 2h8a1 1 0 0 0 0-2Zm0 4a1 1 0 0 0 0 2h8a1 1 0 0 0 0-2Zm0 4a1 1 0 0 0 0 2h4a1 1 0 0 0 0-2Z");
}

</style>
