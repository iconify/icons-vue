<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="xi87dbc9s"/><path class="bwq243_7l"/><path clip-rule="evenodd" class="qljt8cc5j"/><path class="x23izhi9a"/><path clip-rule="evenodd" class="nv7ka1dmw"/><path clip-rule="evenodd" class="sf3n60bru"/><path class="xedf9ccsf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pop:photo-off" /></template>
<style>
.bwq243_7l {
  d: path("M6.697 10.082a1 1 0 0 1 1.606 0l1.91 2.572a1 1 0 0 1-.804 1.596H5.591a1 1 0 0 1-.803-1.596z");
}

.cuyn6tgcc {
  fill: currentColor;
}

.nv7ka1dmw {
  fill-rule: evenodd;
  d: path("M11.25 10.541L9.337 12.75h3.826zm.756-1.418a1 1 0 0 0-1.512 0l-3.007 3.472a1 1 0 0 0 .756 1.655h6.014a1 1 0 0 0 .756-1.655z");
}

.qljt8cc5j {
  fill-rule: evenodd;
  d: path("m7.5 11.517l-.916 1.233h1.832zm.803-1.435a1 1 0 0 0-1.606 0l-1.91 2.572a1 1 0 0 0 .804 1.596h3.818a1 1 0 0 0 .803-1.596z");
}

.sf3n60bru {
  fill-rule: evenodd;
  d: path("M3.5 3.5v13h13v-13zm-.5-2A1.5 1.5 0 0 0 1.5 3v14A1.5 1.5 0 0 0 3 18.5h14a1.5 1.5 0 0 0 1.5-1.5V3A1.5 1.5 0 0 0 17 1.5z");
}

.x23izhi9a {
  d: path("M10.494 9.123a1 1 0 0 1 1.512 0l3.007 3.472a1 1 0 0 1-.756 1.655H8.243a1 1 0 0 1-.756-1.655z");
}

.xedf9ccsf {
  d: path("M1.293 2.707a1 1 0 0 1 1.414-1.414l16 16a1 1 0 0 1-1.414 1.414z");
}

.xi87dbc9s {
  fill-rule: evenodd;
  d: path("M8 9a2 2 0 1 0 0-4a2 2 0 0 0 0 4");
}

</style>
