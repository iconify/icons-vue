<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dfw50oy7i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:store-fill-sharp" /></template>
<style>
.dfw50oy7i {
  fill: currentColor;
  d: path("M3 2h5v8H6v10h3v-5a1 1 0 0 1 1-1h4a1 1 0 0 1 1 1v5h3V10h-2V2h5a1 1 0 0 1 1 1v6a1 1 0 0 1-1 1h-1v11a1 1 0 0 1-1 1H5a1 1 0 0 1-1-1V10H3a1 1 0 0 1-1-1V3a1 1 0 0 1 1-1m11 0v8h-4V2Zm-3 18h2v-4h-2Z");
}

</style>
