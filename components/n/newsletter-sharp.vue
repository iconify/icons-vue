<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="kjkgwjbtg"/><path class="jbd_wdkfq"/><path class="uf6fyl81q"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:newsletter-sharp" /></template>
<style>
.jbd_wdkfq {
  d: path("M2.75 9.25h18.5v11H2.75z");
}

.kjkgwjbtg {
  d: path("M5.75 10.5V2.75h12.5v7.75M9 6.25h6M9 9h4");
}

.uf6fyl81q {
  d: path("m6.5 12.75l4.1 2.9l1.4.988l1.4-.988l4.1-2.9");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
