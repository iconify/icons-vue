<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="varxkfibx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-monotone:stop-button" /></template>
<style>
.varxkfibx {
  fill: currentColor;
  d: path("M32 2C15.432 2 2 15.432 2 32c0 16.569 13.432 30 30 30s30-13.431 30-30C62 15.432 48.568 2 32 2m15 45H17V17h30z");
}

</style>
