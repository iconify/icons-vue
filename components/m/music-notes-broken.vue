<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="mw8ccub0a"/><path class="jzhpb3bqb"/><path class="q5ty2f3-s"/><path class="ux-601-mt"/><path class="e_o28f1-b"/><circle class="st1arvbax"/><path class="dgtms6b-f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:music-notes-broken" /></template>
<style>
.dgtms6b-f {
  d: path("M10 5C8.75736 5 7 4.07107 7 2");
}

.e_o28f1-b {
  d: path("M7 11V6.5V2");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jzhpb3bqb {
  d: path("M22 17.5C22 18.8807 20.8807 20 19.5 20C18.1193 20 17 18.8807 17 17.5C17 16.1193 18.1193 15 19.5 15C20.8807 15 22 16.1193 22 17.5Z");
}

.mw8ccub0a {
  d: path("M12 19.5C12 20.8807 10.8807 22 9.5 22C8.11929 22 7 20.8807 7 19.5C7 18.1193 8.11929 17 9.5 17C10.8807 17 12 18.1193 12 19.5Z");
}

.q5ty2f3-s {
  d: path("M22 8L12 12");
}

.st1arvbax {
  cx: 4.5px;
  cy: 10.5px;
  r: 2.5px;
}

.ux-601-mt {
  d: path("M12 19V8.8475C12 7.55704 12 6.9118 12.335 6.40841C12.67 5.90502 13.2652 5.6559 14.4556 5.15766L16.4556 4.32057C18.9626 3.27128 20.2161 2.74663 21.1081 3.34022C22 3.93381 22 5.29268 22 8.01042V12");
}

</style>
