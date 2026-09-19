<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="lgcqmdbti"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:picooc" /></template>
<style>
.lgcqmdbti {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m42.5 42.5l-16-16m16-21l-16 16m-21 21l15.672-15.672a4 4 0 0 0 0-5.656L5.5 5.5");
}

</style>
