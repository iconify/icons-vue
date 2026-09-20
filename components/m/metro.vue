<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="jke97c8rf"/><path class="x6tutwbxi"/><defs><path id="SVGZFKtvbkp" class="wp3mpkqcp"/></defs><use href="#SVGZFKtvbkp" class="i2v6ey-hu"/><path class="d7c0je4wf"/><path class="v301zlb4n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto-v1:metro" /></template>
<style>
.d7c0je4wf {
  fill: var(--svg-color--40c0e7, #40c0e7);
  d: path("M93.08 47.76c0 4.87-3.94 8.83-8.83 8.83H44.02c-4.87 0-8.82-3.95-8.82-8.83V36.61c0-4.87 3.95-8.83 8.82-8.83h40.24c4.88 0 8.83 3.95 8.83 8.83v11.15z");
}

.i2v6ey-hu {
  fill: var(--svg-color--ed6c30, #ed6c30);
}

.jke97c8rf {
  fill: var(--svg-color--006ca2, #006ca2);
  d: path("M127.64 64c0 35.15-28.49 63.64-63.65 63.64C28.86 127.64.36 99.15.36 64S28.86.36 63.99.36c35.16 0 63.65 28.49 63.65 63.64");
}

.v301zlb4n {
  fill: var(--svg-color--fff, #fff);
  d: path("M47.24 83.78c0 3.27-2.67 5.93-5.94 5.93c-3.29 0-5.94-2.66-5.94-5.93c0-3.28 2.65-5.94 5.94-5.94c3.27 0 5.94 2.66 5.94 5.94m33.8 0c0 3.27 2.66 5.93 5.94 5.93s5.94-2.66 5.94-5.93a5.94 5.94 0 0 0-5.94-5.94c-3.27 0-5.94 2.66-5.94 5.94");
}

.wp3mpkqcp {
  d: path("M100.3 83.77c0 9.04-7.32 16.36-16.37 16.36H44.34c-9.04 0-16.37-7.33-16.37-16.36V38.69c0-9.03 7.33-16.36 16.37-16.36h39.59c9.05 0 16.37 7.33 16.37 16.36z");
}

.x6tutwbxi {
  fill: var(--svg-color--fff, #fff);
  d: path("M49.72 106.98c0 1.97-1.6 3.57-3.57 3.57s-3.56-1.6-3.56-3.57v-13.7c0-1.97 1.6-3.56 3.56-3.56c1.97 0 3.57 1.6 3.57 3.56zm28.85 0c0 1.97 1.59 3.57 3.56 3.57s3.56-1.6 3.56-3.57v-13.7c0-1.97-1.6-3.56-3.56-3.56c-1.97 0-3.56 1.6-3.56 3.56z");
}

</style>
