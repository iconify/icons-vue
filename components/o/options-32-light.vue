<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="x64-geblu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:options-32-light" /></template>
<style>
.x64-geblu {
  fill: currentColor;
  d: path("M11.5 19a4.5 4.5 0 0 1 4.473 4H29.5a.5.5 0 0 1 0 1H15.973a4.5 4.5 0 0 1-8.946 0H2.5a.5.5 0 0 1 0-1h4.527a4.5 4.5 0 0 1 4.473-4m0 1a3.5 3.5 0 1 0 0 7a3.5 3.5 0 0 0 0-7m9-16a4.5 4.5 0 0 1 4.473 4H29.5a.5.5 0 0 1 0 1h-4.527a4.5 4.5 0 0 1-8.946 0H2.5a.5.5 0 0 1 0-1h13.527A4.5 4.5 0 0 1 20.5 4m0 1a3.5 3.5 0 1 0 0 7a3.5 3.5 0 0 0 0-7");
}

</style>
