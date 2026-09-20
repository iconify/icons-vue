<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<defs><clipPath id="SVGFF1bhDAE"><path class="m2o3sh-9c"/></clipPath></defs><g clip-path="url(#SVGFF1bhDAE)"><path class="bm39iabka"/></g><path class="o5ltyubpr"/><path class="cxiygibjh"/><circle class="oottdobkk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:wireless" /></template>
<style>
.bm39iabka {
  fill: var(--svg-color--2b87c7, #2b87c7);
  d: path("M36 32c0 4-4 4-4 4H4c-4 0-4-4-4-4V4c0-4 4-4 4-4h28s4 0 4 4z");
}

.cxiygibjh {
  fill: var(--svg-color--fff, #fff);
  d: path("m9.43 17.9l1.45 1.64c.15.16.39.2.58.08c1.8-1.2 4.06-1.92 6.51-1.92s4.74.73 6.54 1.95c.18.12.42.1.57-.07l1.47-1.64c.18-.2.14-.5-.08-.65c-2.34-1.66-5.29-2.65-8.5-2.65s-6.12.98-8.45 2.61a.43.43 0 0 0-.08.65Zm4.22 4.77l1.46 1.64c.14.16.39.19.57.07c.63-.41 1.42-.65 2.28-.65s1.67.25 2.3.66c.18.12.42.09.57-.07l1.46-1.64a.44.44 0 0 0-.06-.64c-1.17-.86-2.65-1.37-4.27-1.37s-3.08.51-4.24 1.35c-.21.15-.24.45-.07.64Z");
}

.m2o3sh-9c {
  fill: none;
  d: path("M0 0h36v36H0z");
}

.o5ltyubpr {
  fill: var(--svg-color--fff, #fff);
  d: path("m5.1 13.01l1.46 1.65c.15.16.39.19.57.07c3.01-1.98 6.77-3.17 10.83-3.17s7.88 1.2 10.9 3.21c.18.12.42.09.57-.07l1.47-1.64c.17-.2.14-.5-.07-.65c-3.56-2.45-8.02-3.91-12.87-3.91S8.72 9.94 5.17 12.36c-.22.15-.25.45-.08.65Z");
}

.oottdobkk {
  cx: 17.91px;
  cy: 27.64px;
  r: 1.86px;
  fill: var(--svg-color--fff, #fff);
}

</style>
