<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="w34osu__y"><path class="ilutk442e"/><path class="h87_01bsp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:wordweb" /></template>
<style>
.h87_01bsp {
  stroke-linecap: round;
  d: path("m22.3 14.2l2.6 10.9m0 0l3.4-10.9m0 0l3.4 10.9m0 0l2.6-10.9");
}

.ilutk442e {
  d: path("M28.3 5.6c-7.7 0-13.9 6.1-13.9 13.7c0 8 6.1 14.2 13.9 14.2s14.1-6.2 14.1-13.9c-.1-7.7-6.4-13.9-14.1-14zM5.4 39.3c.1 1.3.9 2.4 2.3 3s2.6.2 3.6-.8c.5-.5.9-1 1.3-1.6c1.9-2.5 1.6-2.7 3.8-5c2.6-2.8 2-1.9-.1-4.3c-.5-.6-1-.5-1.5 0c-3.1 3-4.3 3.3-7.8 5.7c-1.1.7-1.6 1.7-1.6 3z");
}

.w34osu__y {
  fill: none;
  stroke: currentColor;
  stroke-miterlimit: 10;
}

</style>
