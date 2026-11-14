<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="h0yojpbyp"/><path class="t88j269os"/><path class="ypn1qlbeb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:timer-reset" /></template>
<style>
.h0yojpbyp {
  d: path("M4 13a8 8 0 1 0 16 0a8 8 0 1 0-16 0ZM9.5 2.5h5");
}

.t88j269os {
  d: path("M12 9a4 4 0 1 1-4 4");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ypn1qlbeb {
  d: path("M6.75 14.25L8 13l1.25 1.25");
}

</style>
