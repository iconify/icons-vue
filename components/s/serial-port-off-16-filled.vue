<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="o0c5n9b2y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:serial-port-off-16-filled" /></template>
<style>
.o0c5n9b2y {
  fill: currentColor;
  d: path("M1.146 1.147a.5.5 0 0 1 .708 0l13 13a.5.5 0 0 1-.707.707L11.293 12H3.749a2 2 0 0 1-1.944-1.53l-.725-3A2 2 0 0 1 3.024 5h1.269L1.146 1.854a.5.5 0 0 1 0-.707M12.994 5a2 2 0 0 1 1.944 2.47l-.726 3a2 2 0 0 1-.607 1.014L9.48 7.357a.5.5 0 0 0-.335-.335L7.12 5zM6.002 9a.5.5 0 1 0 0 1a.5.5 0 0 0 0-1m2 0a.5.5 0 1 0 0 1a.5.5 0 0 0 0-1m-3-2a.5.5 0 1 0 0 1a.5.5 0 0 0 0-1m1.559.268a.496.496 0 0 0 .672.672zM11.002 7a.5.5 0 1 0 0 1a.5.5 0 0 0 0-1");
}

</style>
