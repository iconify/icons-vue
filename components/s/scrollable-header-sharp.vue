<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fi6d5ja8h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:scrollable-header-sharp" /></template>
<style>
.fi6d5ja8h {
  fill: currentColor;
  d: path("M4 20V4h16v16zm1-1h14v-5.384H5z");
}

</style>
