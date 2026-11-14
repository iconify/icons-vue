<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="umhv6bb6v"/><path class="ucxuw5bbe"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:new-listing-badge" /></template>
<style>
.ucxuw5bbe {
  d: path("m9 16l-1.5 5.5l2.25-1M15 16l1.5 5.5l-2.25-1M9 10l3-3l3 3v2.5H9Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.umhv6bb6v {
  d: path("m12 2l1.219 1.37l1.651-.799l.602 1.732l1.831-.106l-.106 1.831l1.732.602l-.799 1.651L19.5 9.5l-1.37 1.219l.799 1.651l-1.732.602l.106 1.831l-1.831-.106l-.602 1.732l-1.651-.799L12 17l-1.219-1.37l-1.651.799l-.602-1.732l-1.831.106l.106-1.831l-1.732-.602l.799-1.651L4.5 9.5l1.37-1.219l-.799-1.651l1.732-.602l-.106-1.831l1.831.106l.602-1.732l1.651.799Z");
}

</style>
