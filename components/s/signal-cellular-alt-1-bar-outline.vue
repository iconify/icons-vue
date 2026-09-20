<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n35-htkzb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:signal-cellular-alt-1-bar-outline" /></template>
<style>
.n35-htkzb {
  fill: currentColor;
  d: path("M6 19v-4h1.616v4z");
}

</style>
