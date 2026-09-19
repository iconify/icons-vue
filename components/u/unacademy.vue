<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="hxwgknbss"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:unacademy" /></template>
<style>
.hxwgknbss {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M4.916 7.534h38.168m-38.584 0a19.5 19.5 0 0 0 39 0Zm28.914 32.932a9.414 9.414 0 0 0-18.828 0Z");
}

</style>
