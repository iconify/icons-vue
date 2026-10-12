<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jp_govsun"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:palm-tree-sharp" /></template>
<style>
.jp_govsun {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 7.5c-1.75-2.25-5.25-2.75-8.5-1m8.5 1c1.75-2.25 5.25-2.75 8.5-1m-8.5 1c-2.75 0-5.25 1.5-6.5 4.25M12 7.5c2.75 0 5.25 1.5 6.5 4.25M12 7.5c1 4.25 1.25 9 .75 13.75m-4.75 0h8.5");
}

</style>
