<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="z5b7j00zl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:text-position-square-left-16-regular" /></template>
<style>
.z5b7j00zl {
  fill: currentColor;
  d: path("M2.5 2a.5.5 0 0 0 0 1h11a.5.5 0 0 0 0-1zM10 4.5a.5.5 0 0 0 0 1h3.5a.5.5 0 0 0 0-1zm-.5 3A.5.5 0 0 1 10 7h3.5a.5.5 0 0 1 0 1H10a.5.5 0 0 1-.5-.5m.5 2a.5.5 0 0 0 0 1h3.5a.5.5 0 0 0 0-1zm-8 3a.5.5 0 0 1 .5-.5h11a.5.5 0 0 1 0 1h-11a.5.5 0 0 1-.5-.5M3 7a2 2 0 1 1 4 0v3.5a.5.5 0 0 0 1 0V7a3 3 0 0 0-6 0v3.5a.5.5 0 0 0 1 0z");
}

</style>
