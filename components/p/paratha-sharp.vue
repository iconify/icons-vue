<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="g9e9mmxoe"/><path class="sx-4gqbte"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:paratha-sharp" /></template>
<style>
.g9e9mmxoe {
  d: path("m12 3.5l2.52-.92l1.73 2.06l2.64.47l.47 2.64l2.06 1.73L20.5 12l.92 2.52l-2.06 1.73l-.47 2.64l-2.64.47l-1.73 2.06L12 20.5l-2.52.92l-1.73-2.06l-2.64-.47l-.47-2.64l-2.06-1.73L3.5 12l-.92-2.52l2.06-1.73l.47-2.64l2.64-.47l1.73-2.06z");
}

.sx-4gqbte {
  d: path("M7.67 9.5a5 5 0 0 1 3.04-2.33");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
