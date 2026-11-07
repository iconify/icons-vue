<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ddrrjpdcm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:spinner-rays-fill-sharp" /></template>
<style>
.ddrrjpdcm {
  fill: currentColor;
  d: path("M13 3v3a1 1 0 0 1-2 0V3a1 1 0 0 1 2 0M6.707 5.293l2 2a.999.999 0 1 1-1.414 1.414l-2-2a.999.999 0 1 1 1.414-1.414m12 1.414l-2 2a.999.999 0 1 1-1.414-1.414l2-2a.999.999 0 1 1 1.414 1.414M3 11h3a1 1 0 0 1 0 2H3a1 1 0 0 1 0-2m18 2h-3a1 1 0 0 1 0-2h3a1 1 0 0 1 0 2M5.293 17.293l2-2a.999.999 0 1 1 1.414 1.414l-2 2a.999.999 0 1 1-1.414-1.414m12 1.414l-2-2a.999.999 0 1 1 1.414-1.414l2 2a.999.999 0 1 1-1.414 1.414M11 21v-3a1 1 0 0 1 2 0v3a1 1 0 0 1-2 0");
}

</style>
