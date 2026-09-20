<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="apehpubwk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:tv-outline-sharp" /></template>
<style>
.apehpubwk {
  fill: currentColor;
  d: path("M9 20v-2H3V4h18v14h-6v2zm-5-3h16V5H4zm0 0V5z");
}

</style>
