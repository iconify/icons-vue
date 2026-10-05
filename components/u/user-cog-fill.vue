<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="zwpv-tb0j"/><path class="p949j8b3e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:user-cog-fill" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.p949j8b3e {
  d: path("M20.6667 17C20.6667 18.4728 19.4728 19.6667 18 19.6667C16.5272 19.6667 15.3333 18.4728 15.3333 17C15.3333 15.5272 16.5272 14.3333 18 14.3333C19.4728 14.3333 20.6667 15.5272 20.6667 17ZM21.5417 17L22 17M20.5043 19.5043L20.8284 19.8284M18 20.5417L18 21M15.4957 19.5043L15.1716 19.8284M14.4583 17L14 17M15.4957 14.4957L15.1716 14.1716M18 13.4583L18 13M20.5043 14.4957L20.8284 14.1716");
}

.zwpv-tb0j {
  fill: currentColor;
  d: path("M10 13C10.5523 13 11 13.4477 11 14V21C11 21.5523 10.5523 22 10 22H3C1.89542 22 1 21.1046 1 20C1 16.134 4.13402 13 8 13H10ZM9 3C11.2092 3 13 4.79082 13 7C13 9.20918 11.2092 11 9 11C6.79094 11 5 9.20921 5 7C5 4.79079 6.79094 3 9 3Z");
  stroke: none;
}

</style>
