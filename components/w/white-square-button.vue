<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="lu1px_bac"/><path class="z79lwxbrh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-monotone:white-square-button" /></template>
<style>
.lu1px_bac {
  fill: currentColor;
  d: path("M2 2v60h60V2zm58 58H4V4h56z");
}

.z79lwxbrh {
  fill: currentColor;
  d: path("M10 10h44v44H10z");
}

</style>
