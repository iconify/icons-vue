<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="b23t9yb4z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:parallelogram-bold" /></template>
<style>
.b23t9yb4z {
  fill: currentColor;
  d: path("M248.78 45.14A19.92 19.92 0 0 0 232 36H88.81a20 20 0 0 0-18.24 11.79l-64.8 144A20 20 0 0 0 24 220h143.19a20 20 0 0 0 18.24-11.79l64.8-144a19.9 19.9 0 0 0-1.45-19.07M164.6 196H30.2L91.4 60h134.4Z");
}

</style>
