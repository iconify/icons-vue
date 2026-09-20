<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="iumt0lbxf"/><path class="ydffvacoz"/><path clip-rule="evenodd" class="ex17wkb-a"/><path class="droxnd8cg"/><path clip-rule="evenodd" class="k0y8y2pmd"/><path clip-rule="evenodd" class="zhnl7lbmw"/><path clip-rule="evenodd" class="kphejjb8s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pop:photo-circle" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.droxnd8cg {
  d: path("M13.494 12.123a1 1 0 0 1 1.512 0l3.007 3.472a1 1 0 0 1-.756 1.655h-6.014a1 1 0 0 1-.756-1.655z");
}

.ex17wkb-a {
  fill-rule: evenodd;
  d: path("m10.5 14.517l-.916 1.233h1.832zm.803-1.435a1 1 0 0 0-1.606 0l-1.91 2.572a1 1 0 0 0 .804 1.596h3.818a1 1 0 0 0 .803-1.596z");
}

.iumt0lbxf {
  fill-rule: evenodd;
  d: path("M11 12a2 2 0 1 0 0-4a2 2 0 0 0 0 4");
}

.k0y8y2pmd {
  fill-rule: evenodd;
  d: path("m14.25 13.541l-1.913 2.209h3.826zm.756-1.418a1 1 0 0 0-1.512 0l-3.007 3.472a1 1 0 0 0 .756 1.655h6.014a1 1 0 0 0 .756-1.655z");
}

.kphejjb8s {
  fill-rule: evenodd;
  d: path("M13 24c6.075 0 11-4.925 11-11S19.075 2 13 2S2 6.925 2 13s4.925 11 11 11m0 2c7.18 0 13-5.82 13-13S20.18 0 13 0S0 5.82 0 13s5.82 13 13 13");
}

.ydffvacoz {
  d: path("M9.697 13.082a1 1 0 0 1 1.606 0l1.91 2.572a1 1 0 0 1-.804 1.596H8.591a1 1 0 0 1-.803-1.596z");
}

.zhnl7lbmw {
  fill-rule: evenodd;
  d: path("M6.5 6.5v13h13v-13zm-.5-2A1.5 1.5 0 0 0 4.5 6v14A1.5 1.5 0 0 0 6 21.5h14a1.5 1.5 0 0 0 1.5-1.5V6A1.5 1.5 0 0 0 20 4.5z");
}

</style>
