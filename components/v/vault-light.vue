<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="z7hhwqb8y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:vault-light" /></template>
<style>
.z7hhwqb8y {
  fill: currentColor;
  d: path("M216 42H40a14 14 0 0 0-14 14v136a14 14 0 0 0 14 14h18v18a6 6 0 0 0 12 0v-18h116v18a6 6 0 0 0 12 0v-18h18a14 14 0 0 0 14-14V56a14 14 0 0 0-14-14m0 152H40a2 2 0 0 1-2-2V56a2 2 0 0 1 2-2h176a2 2 0 0 1 2 2v66h-20.4a46 46 0 1 0 0 12H218v58a2 2 0 0 1-2 2m-51.37-72a14 14 0 1 0 0 12h20.83a34 34 0 1 1 0-12Z");
}

</style>
