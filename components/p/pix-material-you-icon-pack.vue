<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="u2jot77uo"/><circle class="a6q40plwf"/><rect class="i4jeoe_dp"/><path class="ebnwc1-ot"/><circle class="a7ur7-w2z"/><path class="chlf4-bae"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:pix-material-you-icon-pack" /></template>
<style>
.a6q40plwf {
  cx: 31.273px;
  cy: 18.88px;
  r: 5.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.a7ur7-w2z {
  cx: 23.689px;
  cy: 31.12px;
  r: 3.281px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.chlf4-bae {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M29.876 27.839v3.75a2.812 2.812 0 1 0 5.624 0v-3.75");
}

.ebnwc1-ot {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m18.124 27.839l-2.812 3.281l-2.812-3.281m2.812 6.562V31.12");
}

.i4jeoe_dp {
  width: 11px;
  height: 11px;
  x: 11.227px;
  y: 13.38px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 3px;
  ry: 3px;
}

.u2jot77uo {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M35.803 40.286c-4.226.37-4.192 5.863-9.725 3.72c-3.844-1.793-6.561 2.981-10.28-1.642c-2.434-3.474-7.174-.698-8.084-6.561c-.37-4.226-5.863-4.192-3.72-9.725c1.793-3.844-2.981-6.561 1.642-10.28c3.474-2.434.698-7.174 6.562-8.084c4.225-.37 4.191-5.863 9.724-3.72c3.844 1.793 6.561-2.981 10.28 1.642c2.434 3.474 7.174.698 8.084 6.562c.37 4.225 5.863 4.191 3.72 9.724c-1.793 3.844 2.981 6.561-1.642 10.28c-3.474 2.434-.698 7.174-6.561 8.084");
}

</style>
