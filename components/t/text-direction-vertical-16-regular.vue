<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="j0da_7b-n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:text-direction-vertical-16-regular" /></template>
<style>
.j0da_7b-n {
  fill: currentColor;
  d: path("M4.5 2a.5.5 0 0 1 .5.5v9.793l1.146-1.146a.5.5 0 1 1 .707.707l-2 2a.5.5 0 0 1-.707 0l-2-2a.5.5 0 1 1 .707-.707L4 12.293V2.5a.5.5 0 0 1 .5-.5m6 7.5a.5.5 0 0 1 .5.5v2.293l1.146-1.146a.5.5 0 1 1 .707.707l-2 2a.5.5 0 0 1-.707 0l-2-2a.5.5 0 1 1 .707-.707L10 12.293V10a.5.5 0 0 1 .5-.5m0-7.5a.5.5 0 0 1 .467.32l2.5 6.5a.5.5 0 0 1-.934.36L11.695 7h-2.39l-.838 2.18a.5.5 0 0 1-.934-.36l2.5-6.5l.033-.069A.5.5 0 0 1 10.5 2m-.81 4h1.62l-.81-2.107z");
}

</style>
