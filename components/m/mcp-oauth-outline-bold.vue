<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="ni20md-jo"/><path class="j6o0shbiv"/><path class="uesvxd39h"/><path class="fgsu10bod"/><path class="mzw38bcyd"/><path class="h9dt6-bol"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:mcp-oauth-outline-bold" /></template>
<style>
.fgsu10bod {
  d: path("M7 10a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.h9dt6-bol {
  d: path("M15 10v2.5");
}

.j6o0shbiv {
  d: path("M7 18h5");
}

.mzw38bcyd {
  d: path("M11 10h5.5");
}

.ni20md-jo {
  d: path("M13.5 3H17a3 3 0 0 1 3 3v12a3 3 0 0 1 -3 3H7a3 3 0 0 1 -3 -3V6l3 -3h3.5");
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
