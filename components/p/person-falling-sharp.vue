<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><circle class="e51f8ryyj"/><path class="gitxsnbhq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:person-falling-sharp" /></template>
<style>
.e51f8ryyj {
  cx: 6.5px;
  cy: 8px;
  r: 2px;
}

.gitxsnbhq {
  d: path("M12.5 14L9 10.5m1 1l-3.25 3.75l-.75 3m4-6.75l4.25-2.75M12.5 14l4.5-1.5l1.75 2.75M12.5 14l2.5 3.75l3.75-.25M7.3 3.55l2.317.412L10.6 6.1M3 20.75h18");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
