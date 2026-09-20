<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h09mfibom"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:settings-input-hdmi-outline-sharp" /></template>
<style>
.h09mfibom {
  fill: currentColor;
  d: path("M9 21v-2.346l-3-6.038V7.212h1V3h10v4.212h1v5.404l-3 6.038V21zM8 7.212h2.116V5.077h.769v2.135h2.23V5.077h.77v2.135H16V4H8zM10 20h4v-1.616l3-6.038V8.211H7v4.135l3 6.038zm2-7.654");
}

</style>
