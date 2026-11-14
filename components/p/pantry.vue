<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cqrpnhb6n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:pantry" /></template>
<style>
.cqrpnhb6n {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 18.5h19m-17 0v3m15-3v3M3 9h5v9.5H3Zm0 2.75h5m2.75-6.25h3.5v13h-3.5Zm0 3h3.5m2.75 3h4v7h-4Zm0 2.5h4");
}

</style>
