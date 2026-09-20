<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="fc9hqjb7r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:table-picnic-16-regular" /></template>
<style>
.fc9hqjb7r {
  fill: currentColor;
  d: path("M2.957 12.703a.5.5 0 0 1-.914-.406L3.063 10h1.095zm11-.406a.5.5 0 1 1-.914.406L11.842 10h1.095zM5.047 8h5.906L9.62 5h1.095l1.334 3H14.5a.5.5 0 0 1 0 1h-13a.5.5 0 0 1 0-1h2.452l1.334-3h1.095zM12.5 3a.5.5 0 0 1 0 1h-9a.5.5 0 0 1 0-1z");
}

</style>
