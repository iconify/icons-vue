<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ayg-oyf_t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:text-ad-outline-sharp" /></template>
<style>
.ayg-oyf_t {
  fill: currentColor;
  d: path("M2 20V4h20v16zm2-2h16V6H4zm0 0V6zm1-1h14v-2H5zm0-4h14v-2H5zm0-4h10V7H5z");
}

</style>
