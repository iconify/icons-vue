<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="u2j-9r34n"/><path class="p21ljo36x"/><path class="udrot0b5i"/><path class="i44sm08zt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:transmission-square-linear" /></template>
<style>
.i44sm08zt {
  d: path("M12 22V22C16.714 22 19.0711 22 20.5355 20.5355C22 19.0711 22 16.714 22 12V12C22 7.28595 22 4.92893 20.5355 3.46447C19.0711 2 16.714 2 12 2V2C7.28595 2 4.92893 2 3.46447 3.46447C2 4.92893 2 7.28595 2 12V12C2 16.714 2 19.0711 3.46447 20.5355C4.92893 22 7.28595 22 12 22Z");
}

.jx0p4fbya {
  fill: none;
  stroke: currentColor;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.p21ljo36x {
  stroke-linecap: round;
  d: path("M12 9V15");
}

.u2j-9r34n {
  stroke-linecap: round;
  d: path("M8 9V15");
}

.udrot0b5i {
  stroke-linecap: round;
  d: path("M8 12H13C13.9319 12 14.3978 12 14.7654 11.8478C15.2554 11.6448 15.6448 11.2554 15.8478 10.7654C16 10.3978 16 9.93188 16 9");
}

</style>
