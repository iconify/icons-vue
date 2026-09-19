<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="skgal-bib"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:white-medium-square" /></template>
<style>
.skgal-bib {
  fill: var(--svg-color--d0d0d0, #d0d0d0);
  d: path("M8 8h48v48H8z");
}

</style>
