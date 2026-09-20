<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="xy4nxac_e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:train-simple-light" /></template>
<style>
.xy4nxac_e {
  fill: currentColor;
  d: path("M184 26H72a30 30 0 0 0-30 30v128a30 30 0 0 0 30 30h12l-16.8 22.4a6 6 0 1 0 9.6 7.2L99 214h58l22.2 29.6a6 6 0 0 0 9.6-7.2L172 214h12a30 30 0 0 0 30-30V56a30 30 0 0 0-30-30M72 38h112a18 18 0 0 1 18 18v66H54V56a18 18 0 0 1 18-18m112 164H72a18 18 0 0 1-18-18v-50h148v50a18 18 0 0 1-18 18m-2-30a10 10 0 1 1-10-10a10 10 0 0 1 10 10m-88 0a10 10 0 1 1-10-10a10 10 0 0 1 10 10");
}

</style>
