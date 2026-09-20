<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wjhos3p_o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:rate-review-outline-sharp" /></template>
<style>
.wjhos3p_o {
  fill: currentColor;
  d: path("M6.385 13.616h2.204l5.89-5.891l-2.167-2.221l-5.928 5.908zm6.846-5.902l-.925-.945zM7.269 12.73v-.95l3.448-3.448l.462.488l.469.481l-3.429 3.429zm3.91-3.91l.469.481l-.93-.97zm.63 4.795h5.807v-1H12.81zM3 20.077V3h18v14H6.077zM5.65 16H20V4H4v13.644zM4 16V4z");
}

</style>
