<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="tzfzvrh5s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:prohibited-smoking-20-filled" /></template>
<style>
.tzfzvrh5s {
  fill: currentColor;
  d: path("M10 2a8 8 0 1 1 0 16a8 8 0 0 1 0-16m1.06 8h3.44a.5.5 0 0 1 .5.5v1a.5.5 0 0 1-.5.5H9.06l-3.095 3.096a6.5 6.5 0 0 0 9.13-9.13zM10 3.5a6.5 6.5 0 0 0-5.096 10.535L7 11.94V10h1.94l5.095-5.096A6.47 6.47 0 0 0 10 3.5M6 12h-.5a.5.5 0 0 1-.5-.5v-1a.5.5 0 0 1 .5-.5H6zm0-6.364c0-.159.213-.21.284-.068l.394.787A1 1 0 0 1 6.49 7.51l-.197.197A1 1 0 0 0 6 8.414v1.027c0 .264-.356.348-.474.112l-.407-.816a1.57 1.57 0 0 1 .532-2.005a.78.78 0 0 0 .349-.65z");
}

</style>
