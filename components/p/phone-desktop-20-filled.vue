<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="k0e5pke-a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:phone-desktop-20-filled" /></template>
<style>
.k0e5pke-a {
  fill: currentColor;
  d: path("M6 2a2 2 0 0 0-2 2v3h2.5A2.5 2.5 0 0 1 9 9.5V13h3v2H9v1h5.5a.5.5 0 0 0 0-1H13v-2h3a2 2 0 0 0 2-2V4a2 2 0 0 0-2-2zM3.5 8A1.5 1.5 0 0 0 2 9.5v7A1.5 1.5 0 0 0 3.5 18h3A1.5 1.5 0 0 0 8 16.5v-7A1.5 1.5 0 0 0 6.5 8zm.5 7.5a.5.5 0 0 1 .5-.5h1a.5.5 0 0 1 0 1h-1a.5.5 0 0 1-.5-.5");
}

</style>
