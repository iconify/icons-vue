<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fr1471duu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:sorting-guide" /></template>
<style>
.fr1471duu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 2.5v19m-9.5-6H9m-5.5 0l.75 6h3l.75-6m7 0h6.5m-5.5 0l.75 6h3l.75-6M12 4.5H4.5m2-2l-2 2l2 2M12 10h7.5m-2-2l2 2l-2 2");
}

</style>
