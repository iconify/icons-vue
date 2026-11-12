<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e7f_21bdw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:text-direction-ltr-fill-sharp" /></template>
<style>
.e7f_21bdw {
  fill: currentColor;
  d: path("M11 2h6a1 1 0 0 1 0 2v7a1 1 0 0 1-2 0V4h-2v7a1 1 0 0 1-2 0v-1a4 4 0 0 1 0-8m0 2a2 2 0 1 0 0 4Zm6.293 16.293L18.586 19H3a1 1 0 0 1 0-2h15.586l-1.293-1.293a1 1 0 0 1 1.414-1.414l3 3a1 1 0 0 1 0 1.414l-3 3a.999.999 0 1 1-1.414-1.414");
}

</style>
