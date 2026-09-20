<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ok3ggdc_m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:potted-plant-sharp" /></template>
<style>
.ok3ggdc_m {
  fill: currentColor;
  d: path("m7 22l-1.5-6h13L17 22zm5-14q0-2.5 1.75-4.25T18 2q0 2.25-1.425 3.9T13 7.9V10h8v5H3v-5h8V7.9q-2.15-.35-3.575-2T6 2q2.5 0 4.25 1.75T12 8");
}

</style>
