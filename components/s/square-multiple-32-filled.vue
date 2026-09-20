<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="uqz5jqbss"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:square-multiple-32-filled" /></template>
<style>
.uqz5jqbss {
  fill: currentColor;
  d: path("M8.113 5.5h2.097A2.5 2.5 0 0 1 12.502 4h11a4.5 4.5 0 0 1 4.5 4.5v11a2.5 2.5 0 0 1-1.502 2.293v2.096a4.5 4.5 0 0 0 3.502-4.389v-11a6.5 6.5 0 0 0-6.5-6.5h-11a4.5 4.5 0 0 0-4.389 3.5M6.5 7A4.5 4.5 0 0 0 2 11.5v14A4.5 4.5 0 0 0 6.5 30h14a4.5 4.5 0 0 0 4.5-4.5v-14A4.5 4.5 0 0 0 20.5 7z");
}

</style>
