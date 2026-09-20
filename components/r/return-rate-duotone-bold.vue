<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="h1p6rhblx"/><path class="rbb8skbyt"/><path class="lxtdjq46a"/><path class="af7iv3n-p"/><path class="iiquwwbvb"/><path class="jnf_2db5t"/><path class="wfnf9nbje"/><path class="jx_6sacnm"/><path class="p4nfdfole"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:return-rate-duotone-bold" /></template>
<style>
.af7iv3n-p {
  d: path("M12 2v2.5");
}

.h1p6rhblx {
  fill: currentColor;
  d: path("M5 6.5a2 2 0 0 1 2 -2h10a2 2 0 0 1 2 2V16a2 2 0 0 1 -2 2H7a2 2 0 0 1 -2 -2Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.iiquwwbvb {
  d: path("M5 6.5a2 2 0 0 1 2 -2h10a2 2 0 0 1 2 2V16a2 2 0 0 1 -2 2H7a2 2 0 0 1 -2 -2Z");
}

.jnf_2db5t {
  d: path("M12 18v3");
}

.jx_6sacnm {
  d: path("m9 14 6 -6");
}

.lxtdjq46a {
  fill: currentColor;
  d: path("M13.5 13.5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.p4nfdfole {
  d: path("M13.5 13.5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.rbb8skbyt {
  fill: currentColor;
  d: path("M8.5 8.5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.wfnf9nbje {
  d: path("M8.5 8.5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

</style>
