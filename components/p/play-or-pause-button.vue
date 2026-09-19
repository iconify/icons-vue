<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="e_b1m_4mu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-monotone:play-or-pause-button" /></template>
<style>
.e_b1m_4mu {
  fill: currentColor;
  d: path("M53.213 10.788c-11.715-11.717-30.711-11.717-42.426 0c-11.716 11.715-11.716 30.711 0 42.426s30.711 11.715 42.426 0s11.716-30.711 0-42.426M13 47.999v-32l19 16zm28.5 0h-5.7v-32h5.7zm9.5 0h-5.7v-32H51z");
}

</style>
