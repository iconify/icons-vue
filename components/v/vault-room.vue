<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="bchikbeba"/><path class="h8hbdqbky"/><path class="bj7c6pbaf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:vault-room" /></template>
<style>
.bchikbeba {
  d: path("M2.5 3h19v16h-19Zm0 18.5h19");
}

.bj7c6pbaf {
  d: path("M10.5 11a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0ZM12 9.5v-4m1.25 6.25l3.5 2m-6-2l-3.5 2");
}

.h8hbdqbky {
  d: path("M6.5 11a5.5 5.5 0 1 0 11 0a5.5 5.5 0 1 0-11 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
