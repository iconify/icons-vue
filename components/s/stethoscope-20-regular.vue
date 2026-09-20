<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="n9md46b8q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:stethoscope-20-regular" /></template>
<style>
.n9md46b8q {
  fill: currentColor;
  d: path("M2.5 2a.5.5 0 0 0-.5.5v5a4.5 4.5 0 0 0 4 4.473V13a5 5 0 0 0 10 0v-1.05a2.5 2.5 0 1 0-1 0V13a4 4 0 1 1-8 0v-1.027A4.5 4.5 0 0 0 11 7.5v-5a.5.5 0 0 0-.5-.5h-2a.5.5 0 0 0 0 1H10v4.5a3.5 3.5 0 0 1-7 0V3h1.5a.5.5 0 0 0 0-1zm13 6a1.5 1.5 0 1 1 0 3a1.5 1.5 0 0 1 0-3");
}

</style>
