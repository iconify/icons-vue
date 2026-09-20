<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tpdp5nb1m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:sd-card-alert-outline-sharp" /></template>
<style>
.tpdp5nb1m {
  fill: currentColor;
  d: path("M11.5 16.23h1v-1.384h-1zm0-2.807h1V8.769h-1zM19 21H5V8.423L10.423 3H19zm-1-1V4h-7.15L6 8.85V20zm0 0V4z");
}

</style>
