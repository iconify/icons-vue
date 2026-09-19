<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ayyoft3nl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:mysynchrony" /></template>
<style>
.ayyoft3nl {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M20.375 4.5h7.5v39h-7.5zm10.5 0h7.5v19h-7.5zm-21.25 20h7.5v19h-7.5z");
}

</style>
