<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kwyavvbfn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:telescope-search" /></template>
<style>
.kwyavvbfn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m4.947 6.507l7.704-3.592a1.75 1.75 0 0 1 2.326.846l.422.906a1.75 1.75 0 0 1-.846 2.326l-7.704 3.592a1.75 1.75 0 0 1-2.326-.846l-.422-.906a1.75 1.75 0 0 1 .846-2.326M9.75 9.25l-4 11.25m4-11.25L13 20.5m2.25-3a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0m4 1.75L21 21");
}

</style>
