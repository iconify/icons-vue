<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h8yusjz4t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:view-carousel-outline-sharp" /></template>
<style>
.h8yusjz4t {
  fill: currentColor;
  d: path("M3 16V8h3.346v8zm4.73 2V6h8.54v12zm9.924-2V8H21v8zM8.73 17h6.538V7H8.731zM12 12");
}

</style>
