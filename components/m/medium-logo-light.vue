<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="qax3gdcnu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:medium-logo-light" /></template>
<style>
.qax3gdcnu {
  fill: currentColor;
  d: path("M72 66a62 62 0 1 0 62 62a62.07 62.07 0 0 0-62-62m0 112a50 50 0 1 1 50-50a50.06 50.06 0 0 1-50 50M184 66c-17.1 0-30 26.65-30 62s12.9 62 30 62s30-26.65 30-62s-12.9-62-30-62m0 112c-7.34 0-18-19.48-18-50s10.66-50 18-50s18 19.48 18 50s-10.66 50-18 50m62-106v112a6 6 0 0 1-12 0V72a6 6 0 0 1 12 0");
}

</style>
