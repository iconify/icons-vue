<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k5jf7jbvw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:space-station-sharp" /></template>
<style>
.k5jf7jbvw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 7.25h4.5v9.5h-4.5zm14 0h4.5v9.5h-4.5zM2.75 12h4.5m9.5 0h4.5M9.75 8.25h4.5v7.5h-4.5zM7.25 12h2.5m4.5 0h2.5M12 8.25v-4m0 11.5v4");
}

</style>
