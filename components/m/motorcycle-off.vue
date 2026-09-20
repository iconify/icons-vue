<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path class="nviw1iuac"/><path clip-rule="evenodd" class="hmrwnbc8w"/><path class="ksotgsblm"/><path clip-rule="evenodd" class="r12sxtbln"/><path class="atqdkebxx"/><path class="k7e70ibtc"/><path class="xedf9ccsf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pop:motorcycle-off" /></template>
<style>
.atqdkebxx {
  d: path("M15.5 4.5a1 1 0 1 1 0-2h2a1 1 0 1 1 0 2zm-13 0a1 1 0 0 1 0-2h2a1 1 0 0 1 0 2z");
}

.cuyn6tgcc {
  fill: currentColor;
}

.hmrwnbc8w {
  fill-rule: evenodd;
  d: path("M10 8a3.5 3.5 0 1 0 0-7a3.5 3.5 0 0 0 0 7m0-5a1.5 1.5 0 1 1 0 3a1.5 1.5 0 0 1 0-3");
}

.k7e70ibtc {
  d: path("m3.41 4.046l.476-1.455l4.524.863l-.477 1.456zm8.18-.592l.477 1.456l4.523-.864l-.476-1.455z");
}

.ksotgsblm {
  d: path("M10 14a2 2 0 0 1 2 2v1.5a2 2 0 1 1-4 0V16a2 2 0 0 1 2-2");
}

.nviw1iuac {
  d: path("M12.75 12.5a1 1 0 1 1-2 0a1 1 0 0 1 2 0m-3.5 0a1 1 0 1 1-2 0a1 1 0 0 1 2 0");
}

.r12sxtbln {
  fill-rule: evenodd;
  d: path("M15 11a5 5 0 0 0-10 0v2.5A2.5 2.5 0 0 0 7.5 16h5a2.5 2.5 0 0 0 2.5-2.5zm-8 0a3 3 0 0 1 6 0v2.5a.5.5 0 0 1-.5.5h-5a.5.5 0 0 1-.5-.5z");
}

.xedf9ccsf {
  d: path("M1.293 2.707a1 1 0 0 1 1.414-1.414l16 16a1 1 0 0 1-1.414 1.414z");
}

</style>
