<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fc-n39buv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:splitscreen-right-outline-sharp" /></template>
<style>
.fc-n39buv {
  fill: currentColor;
  d: path("M13.385 20V4h6v16zm-8.77 0V4h6v16zm1-15v14h4V5z");
}

</style>
