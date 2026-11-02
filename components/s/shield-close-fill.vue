<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k_ezrmbpy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:shield-close-fill" /></template>
<style>
.k_ezrmbpy {
  fill: currentColor;
  d: path("M6 2h12a3 3 0 0 1 3 3v5c-.001 5.712-3.495 9.647-8.594 11.914a1 1 0 0 1-.812 0C6.495 19.647 3.001 15.712 3 10V5a3 3 0 0 1 3-3m4.707 6.293a.999.999 0 1 0-1.414 1.414L10.586 11l-1.293 1.293a.999.999 0 1 0 1.414 1.414L12 12.414l1.293 1.293a.999.999 0 1 0 1.414-1.414L13.414 11l1.293-1.293a.999.999 0 1 0-1.414-1.414L12 9.586Z");
}

</style>
