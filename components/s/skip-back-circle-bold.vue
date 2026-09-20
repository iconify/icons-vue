<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="y6tp-_fus"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:skip-back-circle-bold" /></template>
<style>
.y6tp-_fus {
  fill: currentColor;
  d: path("M128 20a108 108 0 1 0 108 108A108.12 108.12 0 0 0 128 20m0 192a84 84 0 1 1 84-84a84.09 84.09 0 0 1-84 84m37.82-134.5a12 12 0 0 0-12.18.32L108 106.35V88a12 12 0 0 0-24 0v80a12 12 0 0 0 24 0v-18.35l45.64 28.53A12 12 0 0 0 172 168V88a12 12 0 0 0-6.18-10.5M148 146.35L118.64 128L148 109.65Z");
}

</style>
