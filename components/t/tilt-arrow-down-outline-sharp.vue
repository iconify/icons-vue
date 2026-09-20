<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o5z78ibxb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:tilt-arrow-down-outline-sharp" /></template>
<style>
.o5z78ibxb {
  fill: currentColor;
  d: path("M5 20V4h14.02v16zm1-1h12.02V5H6zm5.52-5.536L9.4 11.35l-.708.708l3.327 3.327l3.289-3.289l-.708-.713l-2.08 2.08V8.77h-1zM18.02 19H6z");
}

</style>
