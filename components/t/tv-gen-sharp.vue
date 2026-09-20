<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h7-rv1l8d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:tv-gen-sharp" /></template>
<style>
.h7-rv1l8d {
  fill: currentColor;
  d: path("M4.616 19.462V18H3V5h18v13h-1.616v1.462h-.5L18.37 18H5.675l-.56 1.462z");
}

</style>
