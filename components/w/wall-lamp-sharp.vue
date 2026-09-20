<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jbjay1mqt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:wall-lamp-sharp" /></template>
<style>
.jbjay1mqt {
  fill: currentColor;
  d: path("M3.73 20v-5h1v5zm2.77-2v-1h6v-4H6.996L9.4 5h7.2l2.404 8H13.5v5z");
}

</style>
