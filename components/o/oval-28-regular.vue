<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="e28qtbvrc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:oval-28-regular" /></template>
<style>
.e28qtbvrc {
  fill: currentColor;
  d: path("M2 14a9 9 0 0 1 9-9h6a9 9 0 1 1 0 18h-6a9 9 0 0 1-9-9m9-7.5a7.5 7.5 0 1 0 0 15h6a7.5 7.5 0 0 0 0-15z");
}

</style>
