<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><circle class="jbq3dzslw"/><path class="accup4bru"/><circle class="bar3ntbmm"/><path class="fglvb20wz"/><circle class="wijmr5spd"/><path class="ua_p3lzyk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:standup-sharp" /></template>
<style>
.accup4bru {
  d: path("M3.5 21.25h6.75v-.75c0-1.9-1.65-3-3.75-3s-3.75 1.1-3.75 3v.75z");
}

.bar3ntbmm {
  cx: 17.5px;
  cy: 13px;
  r: 2.25px;
}

.fglvb20wz {
  d: path("M14.5 21.25h6.75v-.75c0-1.9-1.65-3-3.75-3s-3.75 1.1-3.75 3v.75z");
}

.jbq3dzslw {
  cx: 6.5px;
  cy: 13px;
  r: 2.25px;
}

.ua_p3lzyk {
  d: path("M12 4.25v1.5l1.25 1");
}

.wijmr5spd {
  cx: 12px;
  cy: 5.75px;
  r: 3px;
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
