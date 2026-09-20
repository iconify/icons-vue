<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="hpqtfpzva"/><ellipse class="fix04rbfz"/><ellipse class="c757m7bdq"/><path clip-rule="evenodd" class="pzlr9db_n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pop:music-note-double" /></template>
<style>
.c757m7bdq {
  cx: 5.75px;
  cy: 16px;
  rx: 3px;
  ry: 2.5px;
}

.cuyn6tgcc {
  fill: currentColor;
}

.fix04rbfz {
  cx: 14.75px;
  cy: 15px;
  rx: 3px;
  ry: 2.5px;
}

.hpqtfpzva {
  fill-rule: evenodd;
  d: path("M6.75 3.81a1 1 0 0 1 .906-.996l9-.846a1 1 0 0 1 1.094.996v2.181a1 1 0 0 1-.901.995l-9 .893a1 1 0 0 1-1.099-.995z");
}

.pzlr9db_n {
  fill-rule: evenodd;
  d: path("M15.75 5h2v10h-2zm-9 1h2v10h-2z");
}

</style>
