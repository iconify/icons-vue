<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="u9c6ii1vp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:square-shadow-12-filled" /></template>
<style>
.u9c6ii1vp {
  fill: currentColor;
  d: path("M3 1a2 2 0 0 0-2 2v4a2 2 0 0 0 2 2a2 2 0 0 0 2 2h3.5A2.5 2.5 0 0 0 11 8.5V5a2 2 0 0 0-2-2a2 2 0 0 0-2-2zm-.5 2a.5.5 0 0 1 .5-.5h4a.5.5 0 0 1 .5.5v4a.5.5 0 0 1-.5.5H3a.5.5 0 0 1-.5-.5z");
}

</style>
