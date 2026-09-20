<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="en5la8b_r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:pentagon-48-filled" /></template>
<style>
.en5la8b_r {
  fill: currentColor;
  d: path("M21.502 4.313a4.25 4.25 0 0 1 5 0l15.75 11.456a4.25 4.25 0 0 1 1.543 4.75l-6.018 18.54a4.25 4.25 0 0 1-4.042 2.938H14.268a4.25 4.25 0 0 1-4.042-2.938l-6.018-18.54a4.25 4.25 0 0 1 1.542-4.75z");
}

</style>
