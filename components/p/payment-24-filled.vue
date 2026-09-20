<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oz9okqbdd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:payment-24-filled" /></template>
<style>
.oz9okqbdd {
  fill: currentColor;
  d: path("M5.25 5A3.25 3.25 0 0 0 2 8.25V9.5h20V8.25A3.25 3.25 0 0 0 18.75 5zM22 11H2v4.75A3.25 3.25 0 0 0 5.25 19h13.5A3.25 3.25 0 0 0 22 15.75zm-6.25 3.5h2.5a.75.75 0 0 1 0 1.5h-2.5a.75.75 0 0 1 0-1.5");
}

</style>
