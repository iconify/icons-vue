<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<ellipse class="sezeq_bmi"/><path class="bd5f5mbuy"/><path class="u29lv1b9x"/><path class="jvdxpactq"/><path class="i486hemdh"/><path class="a0oyqtbjx"/><path class="u4mpjbxph"/><path class="fzx2v2b7w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:mercado-libre" /></template>
<style>
.a0oyqtbjx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24.202 31.316a2.31 2.31 0 0 0 3.648-.186");
}

.bd5f5mbuy {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M9.704 15.53a20.8 20.8 0 0 0 6.386 1.866a23 23 0 0 0 4.546-.773");
}

.fzx2v2b7w {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M4.67 22.279a18.3 18.3 0 0 1 9.064 3.214");
}

.i486hemdh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M30.135 29.215c.988 1.037-.927 3.273-2.15 2.05s-2.025-1.962-2.025-1.962");
}

.jvdxpactq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M43.4 22.683a24 24 0 0 0-8.547 2.692m-2.273 2.081c.989 1.037-.926 3.273-2.149 2.05s-2.581-2.513-2.581-2.513");
}

.sezeq_bmi {
  cx: 24px;
  cy: 24px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 19.5px;
  ry: 12.978px;
}

.u29lv1b9x {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.882 15.614a8.6 8.6 0 0 1-5.165 1.485c-3.335 0-6.225-2.199-9.215-2.199c-2.668 0-7.189 4.373-7.189 5.164s1.31 1.26 2.372.74c.621-.303 3.31-2.914 5.484-2.914s9.219 7.136 9.857 7.806c.989 1.038-.926 3.274-2.149 2.05s-3.41-3.162-3.41-3.162");
}

.u4mpjbxph {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24.202 31.316c.53-.697.49-3.182-2.244-2.688c.642-1.219.066-3.146-2.388-2.01a1.69 1.69 0 0 0-3.146-.658a1.455 1.455 0 0 0-2.8-.28c-.544 1.104.296 3.096 2.092 1.976c-.182 1.944.84 2.537 2.684 1.78c.099 1.91 1.367 1.745 2.273 1.3a1.938 1.938 0 0 0 3.529.58");
}

</style>
