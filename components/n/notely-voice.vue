<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="y9tr6bcfx"><path class="zyxuxxbwx"/><path class="xppwnackm"/><path class="n0lw5hf9f"/><path class="x34mdz1qr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:notely-voice" /></template>
<style>
.n0lw5hf9f {
  d: path("M26.527 21.822v1.664c0 1.662-1.338 3-3 3H2.832");
}

.x34mdz1qr {
  d: path("M11.391 26.487V24.23c0-7.202 5.798-13 13-13h16.91m-4.692 10.28v2.26c0 7.201-5.798 13-13 13H6.699");
}

.xppwnackm {
  d: path("M21.45 26.149v-1.664c0-1.662 1.338-3 3-3h20.694");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.zyxuxxbwx {
  d: path("M45.5 24c0 11.874-9.626 21.5-21.5 21.5S2.5 35.874 2.5 24S12.126 2.5 24 2.5S45.5 12.126 45.5 24");
}

</style>
