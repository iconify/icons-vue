<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path fill="url(#SVGCbPKldja)" class="g3wsf9b1q"/><path fill="url(#SVGCbPKldja)" class="e-qiyy4xu"/><defs><linearGradient id="SVGCbPKldja" x1="-.462" x2="77.832" y1="1.062" y2="17.697" gradientUnits="userSpaceOnUse"><stop class="yqbov8bgh"/><stop offset=".13" class="nsxy5j6ft"/><stop offset=".275" class="jvfbfhz3y"/><stop offset=".395" class="j2oooab-l"/><stop offset=".52" class="bsutt-qml"/><stop offset=".66" class="srjb01h8m"/><stop offset=".8" class="l-s1yjbah"/><stop offset="1" class="rxnkilbzg"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:nibiru" /></template>
<style>
.bsutt-qml {
  stop-color: var(--svg-color--82d1d9, #82d1d9);
}

.e-qiyy4xu {
  d: path("M6.15 8.281v8.767L11.92 21l5.88-4.25zm1.146 8.167v-5.952l8.597 6.252l-3.97 2.87z");
}

.ft5dv1b6b {
  fill: none;
}

.g3wsf9b1q {
  d: path("M12.225 3L6.19 7.244l11.66 8.475V6.957zm4.52 10.504L8.156 7.26l4.09-2.878l4.5 3.165z");
}

.j2oooab-l {
  stop-color: var(--svg-color--cdc6d7, #cdc6d7);
}

.jvfbfhz3y {
  stop-color: var(--svg-color--f2bad5, #f2bad5);
}

.l-s1yjbah {
  stop-color: var(--svg-color--11bbca, #11bbca);
}

.nsxy5j6ft {
  stop-color: var(--svg-color--f2a9cb, #f2a9cb);
}

.rxnkilbzg {
  stop-color: var(--svg-color--17a0bf, #17a0bf);
}

.srjb01h8m {
  stop-color: var(--svg-color--09d4d7, #09d4d7);
}

.yqbov8bgh {
  stop-color: var(--svg-color--f29ac4, #f29ac4);
}

</style>
