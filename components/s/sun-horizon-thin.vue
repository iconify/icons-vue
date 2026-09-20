<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="a097dabjr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:sun-horizon-thin" /></template>
<style>
.a097dabjr {
  fill: currentColor;
  d: path("M240 156h-45.06A68 68 0 1 0 60 144a68.7 68.7 0 0 0 1.06 12H16a4 4 0 0 0 0 8h224a4 4 0 0 0 0-8M68 144a60 60 0 1 1 118.79 12H69.21A60 60 0 0 1 68 144m144 56a4 4 0 0 1-4 4H48a4 4 0 0 1 0-8h160a4 4 0 0 1 4 4M76.42 41.79a4 4 0 0 1 7.16-3.58l8 16a4 4 0 0 1-7.16 3.58Zm-56 52.42a4 4 0 0 1 5.37-1.79l16 8a4 4 0 0 1-3.58 7.16l-16-8a4 4 0 0 1-1.79-5.37m192 11.58a4 4 0 0 1 1.79-5.37l16-8a4 4 0 1 1 3.58 7.16l-16 8a4 4 0 0 1-5.37-1.79m-48-51.58l8-16a4 4 0 1 1 7.16 3.58l-8 16a4 4 0 0 1-7.16-3.58");
}

</style>
