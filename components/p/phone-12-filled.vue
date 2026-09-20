<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="n_r09abgv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:phone-12-filled" /></template>
<style>
.n_r09abgv {
  fill: currentColor;
  d: path("M3 2.5A1.5 1.5 0 0 1 4.5 1h3A1.5 1.5 0 0 1 9 2.5v7A1.5 1.5 0 0 1 7.5 11h-3A1.5 1.5 0 0 1 3 9.5zM5.5 8a.5.5 0 0 0 0 1h1a.5.5 0 0 0 0-1z");
}

</style>
