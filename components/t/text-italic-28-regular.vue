<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="pwwrd419d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:text-italic-28-regular" /></template>
<style>
.pwwrd419d {
  fill: currentColor;
  d: path("M22.251 4a.75.75 0 0 1 0 1.5h-4.233l-6.432 17h4.665a.75.75 0 0 1 0 1.5H5.754a.75.75 0 0 1 0-1.5h4.228l6.432-17h-4.66a.75.75 0 0 1 0-1.5z");
}

</style>
