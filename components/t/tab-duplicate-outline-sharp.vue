<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p-qs12buz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:tab-duplicate-outline-sharp" /></template>
<style>
.p-qs12buz {
  fill: currentColor;
  d: path("M6.712 17.308V3H21v14.308zm1-1H20V7.192h-6.615V4H7.712zM7.712 4v12.308zm-1.02 17v-1.23h1.231V21zM4.231 6.23H3V5h1.23zM10.385 21v-1.23h1.23V21zm3.692 0v-1.23h1.23V21zM3 21v-1.23h1.23V21zm0-3.692v-1.231h1.23v1.23zm0-3.693v-1.23h1.23v1.23zm0-3.692v-1.23h1.23v1.23zm14.77 9.846H19V21h-1.23z");
}

</style>
