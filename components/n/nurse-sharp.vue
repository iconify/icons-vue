<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="rwf3zibmg"/><path class="zge6dn00z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:nurse-sharp" /></template>
<style>
.rwf3zibmg {
  d: path("m5 16.5l.5-8.75l.378-1.665L7.6 5.85C9 5.6 10.5 5.5 12 5.5s3 .1 4.4.35l1.722.235l.378 1.665l.5 8.75Z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.zge6dn00z {
  d: path("M11.5 8.5h1.4v1.6h1.6v1.8h-1.6v1.6h-1.8v-1.6H9.5v-1.8h1.6V8.5zm-7.75 8h16.5V20H3.75z");
}

</style>
