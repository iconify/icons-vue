<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="srzgk7jml"/><path class="zohykibek"/><path class="m6nkjhiin"/><path class="jkuojibnm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:vpn-outline-regular" /></template>
<style>
.jkuojibnm {
  d: path("M3 20h18");
}

.m6nkjhiin {
  d: path("M12 13v3");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.srzgk7jml {
  d: path("M3 17a9 9 0 0 1 18 0");
}

.zohykibek {
  d: path("M10 11a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

</style>
