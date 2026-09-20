<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lojp-cbdw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:space-dashboard-outline-sharp" /></template>
<style>
.lojp-cbdw {
  fill: currentColor;
  d: path("M4 20V4h16v16zm1-1h6.5V5H5zm7.5 0H19v-7h-6.5zm0-8H19V5h-6.5z");
}

</style>
