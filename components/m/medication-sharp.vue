<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pqs25-xvj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:medication-sharp" /></template>
<style>
.pqs25-xvj {
  fill: currentColor;
  d: path("M11.385 16.5h1.23V14h2.5v-1.23h-2.5v-2.5h-1.23v2.5h-2.5V14h2.5zM6 19.885v-13h12v13zm.462-14.77v-1h11.077v1z");
}

</style>
