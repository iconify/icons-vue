<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ij9f0_xdj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:outdoor-garden-rounded" /></template>
<style>
.ij9f0_xdj {
  fill: currentColor;
  d: path("M3.73 20.5h5V6.135l-2.5-2.5l-2.5 2.5zm5.77 0h5V6.135l-2.5-2.5l-2.5 2.5zm5.77 0h5V6.135l-2.5-2.5l-2.5 2.5z");
}

</style>
