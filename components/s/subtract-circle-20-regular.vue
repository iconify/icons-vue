<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="nyturbybz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:subtract-circle-20-regular" /></template>
<style>
.nyturbybz {
  fill: currentColor;
  d: path("M6 10a.5.5 0 0 1 .5-.5h7a.5.5 0 0 1 0 1h-7A.5.5 0 0 1 6 10m4 8a8 8 0 1 0 0-16a8 8 0 0 0 0 16m0-1a7 7 0 1 1 0-14a7 7 0 0 1 0 14");
}

</style>
