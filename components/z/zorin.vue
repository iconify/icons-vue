<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="vbd893b6t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:zorin" /></template>
<style>
.vbd893b6t {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m10.333 35.863l3.409 5.904h20.516l3.409-5.904zM44.5 24l-3.438 5.959H19.244L41.062 18.04zm-41 0l3.438-5.959h21.818L6.938 29.96zm6.833-11.863l3.409-5.904h20.516l3.409 5.904z");
}

</style>
