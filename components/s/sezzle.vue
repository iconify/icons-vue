<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="y9tr6bcfx"><path class="njm3sx09s"/><path class="dp7x5abqh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:sezzle" /></template>
<style>
.dp7x5abqh {
  d: path("M24 30.919s1.327-4.62 0-6.918s0-6.917 0-6.917");
}

.njm3sx09s {
  d: path("M24 3.5L10.614 16.876c-5.05 4.893-3.968 11.113-.536 14.545c3.282 3.283 8.968 3.271 13.922-.502c-6.803 6.798 0 13.581 0 13.581l13.386-13.376c5.05-4.893 3.968-11.111.536-14.543C34.64 13.3 28.954 13.31 24 17.084C30.803 10.285 24 3.5 24 3.5m0 13.584L9.869 31.205M24 30.919l14.131-14.122");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
