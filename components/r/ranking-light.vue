<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="ze_h8xbxi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:ranking-light" /></template>
<style>
.ze_h8xbxi {
  fill: currentColor;
  d: path("M114.31 101.9a6 6 0 0 1 3.79-7.59l12-4A6 6 0 0 1 138 96v40a6 6 0 0 1-12 0v-31.68l-4.1 1.37a6 6 0 0 1-7.59-3.79M246 208a6 6 0 0 1-6 6H16a6 6 0 0 1 0-12h10v-98a14 14 0 0 1 14-14h42V56a14 14 0 0 1 14-14h64a14 14 0 0 1 14 14v74h42a14 14 0 0 1 14 14v58h10a6 6 0 0 1 6 6m-72-66v60h44v-58a2 2 0 0 0-2-2Zm-80 60h68V56a2 2 0 0 0-2-2H96a2 2 0 0 0-2 2Zm-56 0h44V102H40a2 2 0 0 0-2 2Z");
}

</style>
