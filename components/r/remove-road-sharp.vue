<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m48_frbqq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:remove-road-sharp" /></template>
<style>
.m48_frbqq {
  fill: currentColor;
  d: path("M18 13V4h2v9zM4 20V4h2v16zm7-12V4h2v4zm0 6v-4h2v4zm0 6v-4h2v4zm4.425.575l2.125-2.125l-2.125-2.1l1.425-1.425l2.125 2.125l2.125-2.125l1.4 1.425l-2.125 2.125l2.1 2.125L21.1 22l-2.15-2.125L16.825 22z");
}

</style>
