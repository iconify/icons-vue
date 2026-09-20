<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="v5q9ozizi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:pin-28-regular" /></template>
<style>
.v5q9ozizi {
  fill: currentColor;
  d: path("M13.804 4.385c.962-2.031 3.646-2.496 5.235-.907l5.483 5.483c1.589 1.59 1.124 4.273-.907 5.235l-5.39 2.553a1.75 1.75 0 0 0-.884.954l-1.589 4.13a1.75 1.75 0 0 1-2.87.609L9.75 19.31L4.06 25H3v-1.06l5.69-5.69l-3.132-3.132a1.75 1.75 0 0 1 .609-2.87l4.13-1.59c.42-.16.761-.477.953-.883zm4.174.154a1.75 1.75 0 0 0-2.819.488l-2.553 5.39a3.25 3.25 0 0 1-1.77 1.642l-4.13 1.588a.25.25 0 0 0-.088.41l7.324 7.324a.25.25 0 0 0 .41-.087l1.589-4.13a3.25 3.25 0 0 1 1.642-1.77l5.39-2.553a1.75 1.75 0 0 0 .488-2.82z");
}

</style>
