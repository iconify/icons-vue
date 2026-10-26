<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="vacubtbfy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:nextflow-icon" /></template>
<style>
.vacubtbfy {
  fill: var(--svg-color--0dc09d, #0dc09d);
  d: path("M0 47.186c40.397 2.683 72.765 35.133 75.305 75.571h47.176C119.859 56.238 66.488 2.765 0 0zm75.571 86.334C72.888 173.917 40.438 206.285 0 208.824V256c66.519-2.62 119.992-55.992 122.757-122.48zm104.858-11.04c2.683-40.396 35.133-72.765 75.571-75.304V0c-66.52 2.621-119.992 55.992-122.757 122.48zM256 208.815c-40.397-2.683-72.765-35.134-75.304-75.571H133.52C136.14 199.762 189.512 253.235 256 256z");
}

</style>
