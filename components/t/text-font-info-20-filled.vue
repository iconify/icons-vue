<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="nrsuqbcrk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:text-font-info-20-filled" /></template>
<style>
.nrsuqbcrk {
  fill: currentColor;
  d: path("M8.193 3.754a.75.75 0 0 0-1.41-.02L2.8 14.234a.75.75 0 1 0 1.402.532l.86-2.266h3.03A5.5 5.5 0 0 1 8.6 11H5.63l1.824-4.805l1.476 4.244a5.5 5.5 0 0 1 1.154-1.25zm5.307 7.121a.625.625 0 1 0 0 1.25a.625.625 0 0 0 0-1.25m0 5.125a.5.5 0 0 0 .5-.5v-2a.5.5 0 0 0-1 0v2a.5.5 0 0 0 .5.5m0-7a4.5 4.5 0 1 0 0 9a4.5 4.5 0 0 0 0-9m0 8a3.5 3.5 0 1 1 0-7a3.5 3.5 0 0 1 0 7");
}

</style>
