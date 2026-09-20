<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="l3rpquehn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:person-home-32-regular" /></template>
<style>
.l3rpquehn {
  fill: currentColor;
  d: path("M21.374 16.1a2.5 2.5 0 0 1 3.252 0l5 4.284a2.5 2.5 0 0 1 .874 1.898V29a1.5 1.5 0 0 1-1.5 1.5h-2a1.5 1.5 0 0 1-1.5-1.5v-3.5A1.5 1.5 0 0 0 24 24h-2a1.5 1.5 0 0 0-1.5 1.5V29a1.5 1.5 0 0 1-1.5 1.5h-2a1.5 1.5 0 0 1-1.5-1.5v-6.718c0-.73.32-1.423.874-1.898zm-5.976 3.145a4 4 0 0 0-.681.755H7.5A1.5 1.5 0 0 0 6 21.5v.5c0 1.473.94 2.949 2.759 4.106c1.375.876 3.186 1.514 5.241 1.77V29c0 .314.056.618.157.906c-2.477-.25-4.723-1-6.472-2.113C5.523 26.417 4 24.393 4 22v-.5A3.5 3.5 0 0 1 7.5 18h9.35zM16 2a7 7 0 1 1 0 14a7 7 0 0 1 0-14m0 2a5 5 0 1 0 0 10a5 5 0 0 0 0-10");
}

</style>
