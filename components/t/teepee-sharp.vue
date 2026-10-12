<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="jvwgfiiro"/><path class="lvan4njfs"/><path class="jxm6vhbos"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:teepee-sharp" /></template>
<style>
.jvwgfiiro {
  d: path("M9.75 2.75L12 6.25l2.25-3.5");
}

.jxm6vhbos {
  d: path("m12.2 13.46l3.1 7.33l.2.46h-7l.2-.46l3.1-7.33l.2-.46z");
}

.lvan4njfs {
  d: path("m12.36 6.16l7.78 14.43l.36.66h-17l.36-.66l7.78-14.43l.36-.66zM7.25 16.25h2.5m4.5 0h2.5");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
