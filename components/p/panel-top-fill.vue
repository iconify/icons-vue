<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="csamymbpu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:panel-top-fill" /></template>
<style>
.csamymbpu {
  fill: currentColor;
  d: path("M21 18a3 3 0 0 1-3 3H6a3.004 3.004 0 0 1-3-3V6a3 3 0 0 1 3-3h12a3 3 0 0 1 3 3ZM5 18a1 1 0 0 0 1 1h12a1 1 0 0 0 1-1v-8H5Z");
}

</style>
