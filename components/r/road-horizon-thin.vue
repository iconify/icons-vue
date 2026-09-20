<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="azw8ozb1t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:road-horizon-thin" /></template>
<style>
.azw8ozb1t {
  fill: currentColor;
  d: path("M235.49 190a4 4 0 0 1-1.53 5.45a4.07 4.07 0 0 1-2 .51a4 4 0 0 1-3.49-2L157.66 68H132v12a4 4 0 0 1-8 0V68H98.34L27.49 194a4 4 0 0 1-3.49 2a4.07 4.07 0 0 1-2-.51a4 4 0 0 1-1.49-5.49L89.16 68H24a4 4 0 0 1 0-8h208a4 4 0 0 1 0 8h-65.16ZM128 116a4 4 0 0 0-4 4v16a4 4 0 0 0 8 0v-16a4 4 0 0 0-4-4m0 56a4 4 0 0 0-4 4v16a4 4 0 0 0 8 0v-16a4 4 0 0 0-4-4");
}

</style>
