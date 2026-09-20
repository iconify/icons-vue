<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kd7u44b3p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:pinch-sharp" /></template>
<style>
.kd7u44b3p {
  fill: currentColor;
  d: path("M10.27 6.616V3.742L3.741 10.27h2.874v.885H2.23V6.769h.885v2.873l6.526-6.526H6.77V2.23h4.385v4.384zm2.767 15.153l-5.668-5.653l.922-.895l3.44.858v-8.81h1v7.77h1.827v-4.27h1v4.27h1.846v-3.27h1v3.27h1.827v-1.27h1v8z");
}

</style>
