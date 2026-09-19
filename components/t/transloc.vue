<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="woqifgt3u"/><circle class="np2k-7kxt"/><path class="n87mi4b-r"/><path class="whvv-dbdk"/><rect class="qnlhwbc1n"/><rect class="mmij8g5no"/><rect class="j_e7spkok"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:transloc" /></template>
<style>
.j_e7spkok {
  width: 16.378px;
  height: 20.479px;
  x: 5.55px;
  y: 5.569px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 2.104px;
  ry: 2.104px;
}

.mmij8g5no {
  width: 16.4px;
  height: 13.334px;
  x: 26.009px;
  y: 5.535px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 1.933px;
  ry: 1.933px;
}

.n87mi4b-r {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M28.64 26.528h11.319v5.084H28.64z");
}

.np2k-7kxt {
  cx: 30.2px;
  cy: 35.839px;
  r: 1.376px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.qnlhwbc1n {
  width: 16.36px;
  height: 12.298px;
  x: 5.5px;
  y: 30.167px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 1.875px;
  ry: 1.875px;
}

.whvv-dbdk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M30.17 39.89v1.175c0 .451-.438.816-.774.816h-1.498c-.536 0-.808-.332-.808-.678v-2.044c-.53-.543-.99-1.042-.99-1.93V26.141c.009.015-.74-3.59 6.882-3.59h3.938c5.508.075 5.58 3.59 5.58 3.59v11.086c0 .988-.844 1.616-1.14 1.93v2.045c-.02.554-.39.678-.699.678h-1.399c-.636 0-.88-.389-.88-.816V39.89z");
}

.woqifgt3u {
  cx: 38.46px;
  cy: 35.839px;
  r: 1.376px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
