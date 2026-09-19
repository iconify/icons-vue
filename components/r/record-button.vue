<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="gvj983b0x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-monotone:record-button" /></template>
<style>
.gvj983b0x {
  fill: currentColor;
  d: path("M32 2C15.432 2 2 15.432 2 32c0 16.569 13.432 30 30 30s30-13.431 30-30C62 15.432 48.568 2 32 2m0 45c-8.283 0-15-6.716-15-15s6.717-15 15-15c8.285 0 15 6.716 15 15s-6.715 15-15 15");
}

</style>
