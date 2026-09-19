<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="h7r3fibgy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-monotone:up-down-arrow" /></template>
<style>
.h7r3fibgy {
  fill: currentColor;
  d: path("M53.213 10.787c-11.715-11.715-30.711-11.715-42.426 0s-11.716 30.71 0 42.426s30.711 11.717 42.426 0c11.716-11.716 11.716-30.712 0-42.426M48 36.487L32 51.999L16 36.487h11.372v-8.974H16L32 12l16 15.514H36.628v8.974z");
}

</style>
