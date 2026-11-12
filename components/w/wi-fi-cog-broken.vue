<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="nx9b_s0ui"/><path class="itvkagoch"/><path class="t4ug9nsrr"/><path class="afiszmbnt"/><path class="zj2p4py0y"/><path class="bahj11bjp"/><path class="kb42jzcum"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:wi-fi-cog-broken" /></template>
<style>
.afiszmbnt {
  d: path("M8.53613 4.68853C9.99986 4.2911 11.511 4.14983 13.0085 4.26472");
}

.bahj11bjp {
  d: path("M16 7.86488V8.13577C16 8.93671 16 9.33718 16.1856 9.66699C16.3713 9.9968 16.7094 10.197 17.3856 10.5975L17.6144 10.733C18.2906 11.1334 18.6287 11.3337 19 11.3337C19.3713 11.3337 19.7094 11.1334 20.3856 10.733L20.6144 10.5975C21.2906 10.197 21.6287 9.9968 21.8144 9.66699C22 9.33718 22 8.93671 22 8.13577V7.86488C22 7.06394 22 6.66347 21.8144 6.33366C21.6287 6.00385 21.2906 5.80361 20.6144 5.40314L20.3856 5.2677C19.7094 4.86723 19.3713 4.66699 19 4.66699C18.6287 4.66699 18.2906 4.86723 17.6144 5.2677L17.3856 5.40314C16.7094 5.80361 16.3713 6.00385 16.1856 6.33366C16 6.66347 16 7.06394 16 7.86488Z");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.itvkagoch {
  d: path("M5.33301 12.295C7.42965 10.032 10.2681 9.05764 13.0035 9.37195");
}

.kb42jzcum {
  stroke-linejoin: round;
  d: path("M19 8H19.0001");
}

.nx9b_s0ui {
  d: path("M8.66699 15.8931C10.5079 13.9061 13.4927 13.9061 15.3337 15.8931");
}

.t4ug9nsrr {
  d: path("M2 8.69693C2.78921 7.84509 3.64848 7.11498 4.5578 6.50659");
}

.zj2p4py0y {
  stroke-linejoin: round;
  d: path("M12.0176 19.4644H12.0177");
}

</style>
