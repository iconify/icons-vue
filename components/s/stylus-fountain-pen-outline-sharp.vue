<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dbygz5bmw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:stylus-fountain-pen-outline-sharp" /></template>
<style>
.dbygz5bmw {
  fill: currentColor;
  d: path("M7.675 16L5.5 7L12 1l6.5 6l-2.175 9zm1.575-2h5.5l1.525-6.325L13 4.65V7.3q.35.25.55.625t.2.825q0 .725-.513 1.238T12 10.5t-1.237-.513t-.513-1.237q0-.45.2-.825T11 7.3V4.65L7.725 7.675zM4 21l1-3h14l1 3z");
}

</style>
