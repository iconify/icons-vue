<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="lgn4-fb8i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-monotone:waning-gibbous-moon" /></template>
<style>
.lgn4-fb8i {
  fill: currentColor;
  d: path("M32.001 2h.003h-.005C15.431 2 2 15.432 2 32s13.431 30 29.999 30h.005h-.003C48.568 62 62 48.568 62 32S48.568 2 32.001 2m-.002 58C16.537 60 4 47.463 4 32C4 16.536 16.537 4 31.999 4c2.569 0 5.056.353 7.42 1.001C45.091 9.863 49 20.125 49 32s-3.909 22.136-9.581 26.998A28 28 0 0 1 31.999 60");
}

</style>
