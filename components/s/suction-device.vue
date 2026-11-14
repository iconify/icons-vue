<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="zbgj3r9mg"/><path class="hn0nwvbgg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:suction-device" /></template>
<style>
.hn0nwvbgg {
  d: path("M12.5 4.5c0-2 3-2.5 4.75-1C19.5 5.5 18 9 20 11l1.5 1.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.zbgj3r9mg {
  d: path("M4 7.5h11v14H4Zm-1-3h13v3H3Zm1 10h11");
}

</style>
