<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hmfcf6bfg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:uppercase-outline" /></template>
<style>
.hmfcf6bfg {
  fill: currentColor;
  d: path("M16.5 18v-6.2l-1.6 1.6l-1.4-1.4l4-4l4 4l-1.4 1.4l-1.6-1.6V18zM3 18L7.125 7H9.1l4.125 11h-1.9l-.975-2.825H5.9L4.9 18zm3.475-4.425H9.75l-1.625-4.55h-.1z");
}

</style>
