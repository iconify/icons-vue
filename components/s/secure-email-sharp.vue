<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="h1rt1dbdw"/><path class="y7wi85k7o"/><path class="o40ix-bpd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:secure-email-sharp" /></template>
<style>
.h1rt1dbdw {
  d: path("M2.75 4.75h13.5v12H2.75z");
}

.o40ix-bpd {
  d: path("M16 16.75L17.25 18l2-2.25");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.y7wi85k7o {
  d: path("m2.75 6.5l6.75 5l6.75-5m1.67 6.38l2.41.99l.92.38v3.06l-.73.68l-2.79 2.58l-.73.68l-.73-.68l-2.79-2.58l-.73-.68v-3.06l.92-.38l2.41-.99l.92-.38z");
}

</style>
