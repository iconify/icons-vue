<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="du-5mnkon"/><path class="o17q8nbkk"/><path class="eawrvo-zk"/><path class="a9qq5obmi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:streets-map-point-line-duotone" /></template>
<style>
.a9qq5obmi {
  stroke-linejoin: round;
  d: path("M9 9H9.0001");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.du-5mnkon {
  d: path("M22 12C22 16.714 22 19.0711 20.5355 20.5355C19.0711 22 16.714 22 12 22C7.28595 22 4.92893 22 3.46447 20.5355C2 19.0711 2 16.714 2 12C2 7.28595 2 4.92893 3.46447 3.46447C4.92893 2 7.28595 2 12 2C16.714 2 19.0711 2 20.5355 3.46447C22 4.92893 22 7.28595 22 12Z");
}

.eawrvo-zk {
  d: path("M20.5004 20.4998L14.0004 13.9998M21.6072 6.39307L14.0004 13.9998L6.39453 21.6057");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.o17q8nbkk {
  d: path("M9.64003 13.3697C9.23374 13.5433 8.76626 13.5433 8.35997 13.3697C6.61708 12.6248 5.5 10.5421 5.5 8.7572C5.5 6.95823 7.067 5.49988 9 5.49988C10.933 5.49988 12.5 6.95823 12.5 8.7572C12.5 10.5421 11.3829 12.6248 9.64003 13.3697Z");
  opacity: var(--svg-opacity--0-5, 0.5);
}

</style>
