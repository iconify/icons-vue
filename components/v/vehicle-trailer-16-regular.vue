<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="f3fvl467a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:vehicle-trailer-16-regular" /></template>
<style>
.f3fvl467a {
  fill: currentColor;
  d: path("M10.5 2A2.5 2.5 0 0 1 13 4.5V11h1V9.5a.5.5 0 0 1 1 0v4a.5.5 0 0 1-1 0V12H7a2 2 0 1 1-4 0l.001-.036A2.39 2.39 0 0 1 1 9.605C1 5.405 4.405 2 8.605 2zM5 11a1 1 0 1 0 0 2a1 1 0 0 0 0-2m3.605-8A6.606 6.606 0 0 0 2 9.605c0 .73.56 1.327 1.272 1.39A1.998 1.998 0 0 1 6.73 11H12V4.5A1.5 1.5 0 0 0 10.5 3zM10 4a1 1 0 0 1 1 1v2a1 1 0 0 1-1 1H8a1 1 0 0 1-1-1V5a1 1 0 0 1 1-1zM8 7h2V5H8z");
}

</style>
