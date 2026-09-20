<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="k_n70yhsc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:playlist-light" /></template>
<style>
.k_n70yhsc {
  fill: currentColor;
  d: path("M34 64a6 6 0 0 1 6-6h176a6 6 0 0 1 0 12H40a6 6 0 0 1-6-6m6 70h120a6 6 0 0 0 0-12H40a6 6 0 0 0 0 12m72 52H40a6 6 0 0 0 0 12h72a6 6 0 0 0 0-12m133.75-60.28a6 6 0 0 1-7.48 4L206 120.06V192a30 30 0 1 1-12-24v-56a6 6 0 0 1 7.72-5.75l40 12a6 6 0 0 1 4.03 7.47M194 192a18 18 0 1 0-18 18a18 18 0 0 0 18-18");
}

</style>
