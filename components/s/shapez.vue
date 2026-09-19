<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="snqmvj41f"/><path class="a_1wniu1a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:shapez" /></template>
<style>
.a_1wniu1a {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M13 24h11v11H13z");
}

.snqmvj41f {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M42.5 24h-37C5.5 13.783 13.783 5.5 24 5.5h18.5zc0 10.217-8.283 18.5-18.5 18.5v-37");
}

</style>
