<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="ufndfebsz"/><path clip-rule="evenodd" class="k_3w14v_f"/><path clip-rule="evenodd" class="wiwdxuxuu"/><path clip-rule="evenodd" class="i4lr8n7ap"/><path clip-rule="evenodd" class="cozod1byu"/><path class="t_j776bmu"/><path clip-rule="evenodd" class="kphejjb8s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pop:watch-circle-off" /></template>
<style>
.cozod1byu {
  fill-rule: evenodd;
  d: path("M10.5 20.5a1 1 0 0 1 1-1h3a1 1 0 1 1 0 2h-3a1 1 0 0 1-1-1");
}

.cuyn6tgcc {
  fill: currentColor;
}

.i4lr8n7ap {
  fill-rule: evenodd;
  d: path("M11.775 4.538a1 1 0 0 1 .687 1.237l-1 3.5a1 1 0 1 1-1.924-.55l1-3.5a1 1 0 0 1 1.237-.687m0 16.924a1 1 0 0 0 .687-1.237l-1-3.5a1 1 0 1 0-1.924.55l1 3.5a1 1 0 0 0 1.237.687m2.45 0a1 1 0 0 1-.686-1.237l1-3.5a1 1 0 1 1 1.923.55l-1 3.5a1 1 0 0 1-1.237.687m0-16.924a1 1 0 0 0-.686 1.237l1 3.5a1 1 0 1 0 1.923-.55l-1-3.5a1 1 0 0 0-1.237-.687");
}

.k_3w14v_f {
  fill-rule: evenodd;
  d: path("M13 10.75a.75.75 0 0 1 .75.75V13a.75.75 0 0 1-1.5 0v-1.5a.75.75 0 0 1 .75-.75");
}

.kphejjb8s {
  fill-rule: evenodd;
  d: path("M13 24c6.075 0 11-4.925 11-11S19.075 2 13 2S2 6.925 2 13s4.925 11 11 11m0 2c7.18 0 13-5.82 13-13S20.18 0 13 0S0 5.82 0 13s5.82 13 13 13");
}

.t_j776bmu {
  d: path("M4.293 5.707a1 1 0 0 1 1.414-1.414l16 16a1 1 0 0 1-1.414 1.414z");
}

.ufndfebsz {
  fill-rule: evenodd;
  d: path("M13 9.5a3.5 3.5 0 1 0 0 7a3.5 3.5 0 0 0 0-7M7.5 13a5.5 5.5 0 1 1 11 0a5.5 5.5 0 0 1-11 0");
}

.wiwdxuxuu {
  fill-rule: evenodd;
  d: path("M15.25 13a.75.75 0 0 1-.75.75H13a.75.75 0 0 1 0-1.5h1.5a.75.75 0 0 1 .75.75M10.5 5.5a1 1 0 0 1 1-1h3a1 1 0 1 1 0 2h-3a1 1 0 0 1-1-1");
}

</style>
