<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ggyhkw-uf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:rectangle-add-sharp" /></template>
<style>
.ggyhkw-uf {
  fill: currentColor;
  d: path("M11 16h2v-3h3v-2h-3V8h-2v3H8v2h3zm-9 4V4h20v16z");
}

</style>
