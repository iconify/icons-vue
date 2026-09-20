<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="htbgz6bpb"/><path class="tnz7vnrlc"/><path class="k9__tqbja"/><circle class="y1ws6sb7x"/><circle transform="rotate(-29.991 107.237 39.032)" class="ctqjchbeg"/><circle transform="rotate(-60.012 88.973 20.758)" class="riga22bmh"/><circle transform="rotate(-29.991 39.032 20.755)" class="v3hx-6jha"/><circle transform="rotate(-60.007 20.758 39.032)" class="epcti1vdw"/><path class="x8utnrbjf"/><circle transform="rotate(-60.007 39.03 107.24)" class="q_e0pxbui"/><path class="mxef_ni0s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto-v1:two-oclock" /></template>
<style>
.ctqjchbeg {
  cx: 107.24px;
  cy: 39.04px;
  r: 3.68px;
  fill: var(--svg-color--2f2f2f, #2f2f2f);
}

.epcti1vdw {
  cx: 20.76px;
  cy: 39.03px;
  r: 3.68px;
  fill: var(--svg-color--2f2f2f, #2f2f2f);
}

.htbgz6bpb {
  fill: var(--svg-color--fff, #fff);
  d: path("M64 121.73c-31.84 0-57.73-25.9-57.73-57.73C6.27 32.16 32.16 6.27 64 6.27c31.83 0 57.73 25.9 57.73 57.74c0 31.83-25.89 57.72-57.73 57.72");
}

.k9__tqbja {
  fill: var(--svg-color--2f2f2f, #2f2f2f);
  d: path("M69.15 55.71c-.17-.11-.36-.2-.54-.3V11.33H59.4v44.09c-3.07 1.64-5.18 4.84-5.18 8.57c0 5.41 4.37 9.79 9.78 9.79c5.4 0 9.78-4.38 9.78-9.79c0-.1-.03-.2-.03-.31l21.38-12.34l-4.6-7.97zm-3.7 11.68c-.02.01-.04.01-.06.02a3.6 3.6 0 0 1-2.79 0c-.02-.01-.04-.01-.06-.02a3.6 3.6 0 0 1-.82-.5a3.66 3.66 0 0 1-1.36-2.37c-.03-.17-.05-.34-.05-.52c0-2.04 1.65-3.68 3.69-3.68s3.69 1.65 3.69 3.68c0 1.52-.92 2.82-2.24 3.39");
}

.mxef_ni0s {
  fill: var(--svg-color--2f2f2f, #2f2f2f);
  d: path("M63.99 110.25c-2.04 0-3.67 1.65-3.68 3.68c.01 2.03 1.65 3.68 3.68 3.68s3.69-1.65 3.68-3.68a3.67 3.67 0 0 0-3.68-3.68m23.13-6.19a3.66 3.66 0 0 0-1.34 5.03a3.68 3.68 0 0 0 5.03 1.35a3.68 3.68 0 0 0 1.35-5.03a3.685 3.685 0 0 0-5.04-1.35m21.96-18.28a3.68 3.68 0 0 0-5.03 1.35a3.67 3.67 0 0 0 1.35 5.03c1.76 1.01 4.01.41 5.03-1.35s.42-4.02-1.35-5.03");
}

.q_e0pxbui {
  cx: 39.03px;
  cy: 107.24px;
  r: 3.68px;
  fill: var(--svg-color--2f2f2f, #2f2f2f);
}

.riga22bmh {
  cx: 88.97px;
  cy: 20.76px;
  r: 3.68px;
  fill: var(--svg-color--2f2f2f, #2f2f2f);
}

.tnz7vnrlc {
  fill: var(--svg-color--40c0e7, #40c0e7);
  d: path("M64 .1C28.77.1.1 28.76.1 64c0 35.23 28.67 63.89 63.9 63.89S127.89 99.22 127.89 64C127.9 28.76 99.23.1 64 .1m0 121.63c-31.84 0-57.73-25.9-57.73-57.73C6.27 32.16 32.16 6.27 64 6.27c31.83 0 57.73 25.9 57.73 57.74c0 31.83-25.89 57.72-57.73 57.72");
}

.v3hx-6jha {
  cx: 39.03px;
  cy: 20.76px;
  r: 3.68px;
  fill: var(--svg-color--2f2f2f, #2f2f2f);
}

.x8utnrbjf {
  fill: var(--svg-color--2f2f2f, #2f2f2f);
  d: path("M14.06 60.31c-2.03 0-3.68 1.65-3.68 3.68c0 2.04 1.65 3.68 3.68 3.68a3.679 3.679 0 1 0 0-7.36m4.85 25.47a3.69 3.69 0 0 0-1.34 5.03a3.69 3.69 0 0 0 5.03 1.35a3.694 3.694 0 0 0 1.35-5.04a3.69 3.69 0 0 0-5.04-1.34");
}

.y1ws6sb7x {
  cx: 113.93px;
  cy: 64px;
  r: 3.69px;
  fill: var(--svg-color--2f2f2f, #2f2f2f);
}

</style>
