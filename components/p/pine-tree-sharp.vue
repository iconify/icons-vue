<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ixwn7ab0f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:pine-tree-sharp" /></template>
<style>
.ixwn7ab0f {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m12.55 3.46l3.4 4.33l.55.71h-1.75l.54.72l2.67 3.56l.54.72h-2.25l.56.7l2.88 3.6l.56.7H3.75l.56-.7l2.88-3.6l.56-.7H5.5l.54-.72l2.67-3.56l.54-.72H7.5l.55-.71l3.4-4.33l.55-.71zM12 18.5v2.75");
}

</style>
