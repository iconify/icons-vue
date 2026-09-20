<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ft756bbez"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:oval-16-regular" /></template>
<style>
.ft756bbez {
  fill: currentColor;
  d: path("M1 8a5 5 0 0 1 5-5h4a5 5 0 0 1 0 10H6a5 5 0 0 1-5-5m5-4a4 4 0 1 0 0 8h4a4 4 0 0 0 0-8z");
}

</style>
