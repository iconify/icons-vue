<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="u1mgzq3ix"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:shuffles" /></template>
<style>
.u1mgzq3ix {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M39.39 5.5L6.229 9.362l1.078 9.252V29.34h19.356L7.338 31.59L8.61 42.5l33.161-3.862l-1.08-9.298l.002-10.984H23.947l16.714-1.947z");
}

</style>
