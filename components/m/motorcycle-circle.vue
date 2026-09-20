<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<g class="cuyn6tgcc"><path class="a-l37qlir"/><path clip-rule="evenodd" class="tm3007bhz"/><path class="n9mys9bqg"/><path clip-rule="evenodd" class="gxq-ctbxd"/><path class="r2i5iwbba"/><path class="c74qz6uav"/><path clip-rule="evenodd" class="kphejjb8s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pop:motorcycle-circle" /></template>
<style>
.a-l37qlir {
  d: path("M15.75 15.5a1 1 0 1 1-2 0a1 1 0 0 1 2 0m-3.5 0a1 1 0 1 1-2 0a1 1 0 0 1 2 0");
}

.c74qz6uav {
  d: path("m6.41 7.046l.476-1.455l4.524.863l-.477 1.456zm8.18-.592l.477 1.456l4.523-.864l-.476-1.455z");
}

.cuyn6tgcc {
  fill: currentColor;
}

.gxq-ctbxd {
  fill-rule: evenodd;
  d: path("M18 14a5 5 0 0 0-10 0v2.5a2.5 2.5 0 0 0 2.5 2.5h5a2.5 2.5 0 0 0 2.5-2.5zm-8 0a3 3 0 0 1 6 0v2.5a.5.5 0 0 1-.5.5h-5a.5.5 0 0 1-.5-.5z");
}

.kphejjb8s {
  fill-rule: evenodd;
  d: path("M13 24c6.075 0 11-4.925 11-11S19.075 2 13 2S2 6.925 2 13s4.925 11 11 11m0 2c7.18 0 13-5.82 13-13S20.18 0 13 0S0 5.82 0 13s5.82 13 13 13");
}

.n9mys9bqg {
  d: path("M13 17a2 2 0 0 1 2 2v1.5a2 2 0 1 1-4 0V19a2 2 0 0 1 2-2");
}

.r2i5iwbba {
  d: path("M18.5 7.5a1 1 0 1 1 0-2h2a1 1 0 1 1 0 2zm-13 0a1 1 0 0 1 0-2h2a1 1 0 0 1 0 2z");
}

.tm3007bhz {
  fill-rule: evenodd;
  d: path("M13 11a3.5 3.5 0 1 0 0-7a3.5 3.5 0 0 0 0 7m0-5a1.5 1.5 0 1 1 0 3a1.5 1.5 0 0 1 0-3");
}

</style>
