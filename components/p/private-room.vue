<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="lsmbw6b7c"/><path class="ywhh0ybux"/><path class="wop1ovbfq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:private-room" /></template>
<style>
.lsmbw6b7c {
  d: path("M4 21.5v-17c0-1.1.9-2 2-2h10c1.1 0 2 .9 2 2v2.681M2.5 21.5h19");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.wop1ovbfq {
  d: path("M16 12a1 1 0 1 0 2 0a1 1 0 1 0-2 0Zm-.75 3.5h3.5");
}

.ywhh0ybux {
  d: path("M13.5 11v6.5c0 .55.45 1 1 1h5c.55 0 1-.45 1-1V11c0-.55-.45-1-1-1h-5c-.55 0-1 .45-1 1Z");
}

</style>
