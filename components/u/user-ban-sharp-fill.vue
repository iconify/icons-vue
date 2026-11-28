<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="b1j2n9x2n"/><path class="jivej8b3q"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:user-ban-sharp-fill" /></template>
<style>
.b1j2n9x2n {
  fill: currentColor;
  d: path("M11 22H2C1.44772 22 1 21.5523 1 21V19C1 15.134 4.13402 12 8 12H11V22ZM9 2C11.2092 2 13 3.7908 13 6C13 8.2092 11.2092 10 9 10C6.7909 10 5 8.2092 5 6C5 3.7908 6.7909 2 9 2Z");
  stroke: none;
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.jivej8b3q {
  d: path("M15.1716 14.1716L20.8284 19.8284M18 13C20.2092 13 22 14.7908 22 17C22 19.2092 20.2092 21 18 21C15.7908 21 14 19.2092 14 17C14 14.7908 15.7908 13 18 13Z");
}

</style>
