<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="t8drw368i"/><path class="nogghxbkw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:peace-two-tone" /></template>
<style>
.nogghxbkw {
  d: path("M12 2C17.5228 2 22 6.4772 22 12C22 14.7614 20.8807 17.2614 19.0711 19.0711M12 2C6.4772 2 2 6.4772 2 12C2 14.7614 3.1193 17.2614 4.92895 19.0711M12 2V12M19.0711 19.0711C17.2614 20.8807 14.7614 22 12 22M19.0711 19.0711L12 12M19.0711 19.0711M12 22C9.2386 22 6.7386 20.8807 4.92895 19.0711M12 22V12M4.92895 19.0711L12 12M4.92895 19.0711");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.t8drw368i {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M23 12C23 18.0751 18.0751 23 12 23C5.9249 23 1 18.0751 1 12C1 5.9249 5.9249 1 12 1C18.0751 1 23 5.9249 23 12Z");
  stroke: none;
}

</style>
