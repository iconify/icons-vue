<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="sfnpq3o8l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:towel-bold" /></template>
<style>
.sfnpq3o8l {
  fill: currentColor;
  d: path("M197.16 20H72a28 28 0 0 0-28 28v168a20 20 0 0 0 20 20h104a20 20 0 0 0 20-20V52a8 8 0 0 1 8-8h.35a8.33 8.33 0 0 1 7.7 8.48V148a12 12 0 0 0 24 0V52.48A32.13 32.13 0 0 0 197.16 20M72 44h93a32.2 32.2 0 0 0-1 8v120H68V48a4 4 0 0 1 4-4m-4 168v-16h96v16Z");
}

</style>
