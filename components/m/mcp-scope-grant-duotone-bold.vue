<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="exn420ato"/><path class="pfsnloz0n"/><path class="ni20md-jo"/><path class="j6o0shbiv"/><path class="uesvxd39h"/><path class="icvc39peu"/><path class="nacdkmbhw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:mcp-scope-grant-duotone-bold" /></template>
<style>
.exn420ato {
  fill: currentColor;
  d: path("M13.5 3H17a3 3 0 0 1 3 3v12a3 3 0 0 1 -3 3H7a3 3 0 0 1 -3 -3V6l3 -3h3.5");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.icvc39peu {
  d: path("m9 7 3 3 3 -3");
}

.j6o0shbiv {
  d: path("M7 18h5");
}

.nacdkmbhw {
  d: path("m9.5 13 2 2 3.5 -3.5");
}

.ni20md-jo {
  d: path("M13.5 3H17a3 3 0 0 1 3 3v12a3 3 0 0 1 -3 3H7a3 3 0 0 1 -3 -3V6l3 -3h3.5");
}

.pfsnloz0n {
  fill: currentColor;
  d: path("M15 18a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.uesvxd39h {
  d: path("M15 18a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

</style>
