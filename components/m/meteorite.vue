<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="czmqhmbah"/><path class="mue8y31lb"/><path class="b-kovd7qe"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:meteorite" /></template>
<style>
.b-kovd7qe {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M7.75 10.25h.01m.99 5h.01m8.49-1.75h.01");
}

.czmqhmbah {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m3.88 9.49l1.74-2.98Q6.5 5 8.15 4.42l1.7-.59q1.65-.58 3.29.02l2.22.8q1.64.6 2.58 2.07l2.12 3.31q.94 1.47.5 3.16l-.87 3.37q-.44 1.69-2.04 2.39L14.6 20.3q-1.6.7-3.3.28l-3.6-.91q-1.7-.42-2.3-2.06l-1.8-4.97Q3 11 3.88 9.49");
}

.mue8y31lb {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m11.75 4.5l2.75 7.25l-1.25 8.5");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
