<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="i1cg6ugju"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:navigation-person-20-filled" /></template>
<style>
.i1cg6ugju {
  fill: currentColor;
  d: path("M2 4.75A.75.75 0 0 1 2.75 4h14.5a.75.75 0 0 1 0 1.5H2.75A.75.75 0 0 1 2 4.75m0 5A.75.75 0 0 1 2.75 9h14.5a.75.75 0 0 1 .526 1.284A3 3 0 0 0 16.5 10c-.613 0-1.184.184-1.659.5H2.75A.75.75 0 0 1 2 9.75m12.273 5.26a3 3 0 0 1-.602-1.01H2.75a.75.75 0 0 0 0 1.5H13a2.5 2.5 0 0 1 1.273-.49M18.5 13a2 2 0 1 1-4 0a2 2 0 0 1 4 0m1.5 4.5c0 1.245-1 2.5-3.5 2.5S13 18.75 13 17.5a1.5 1.5 0 0 1 1.5-1.5h4a1.5 1.5 0 0 1 1.5 1.5");
}

</style>
