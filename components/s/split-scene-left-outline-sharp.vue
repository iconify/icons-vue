<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gq-eiyboc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:split-scene-left-outline-sharp" /></template>
<style>
.gq-eiyboc {
  fill: currentColor;
  d: path("M15 20v-2h4V6h-4V4h6v16zm-4 2v-2H3V4h8V2h2v20zm8-16v12z");
}

</style>
