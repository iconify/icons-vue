<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yqiy8ef7n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:unlink-text" /></template>
<style>
.yqiy8ef7n {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m1.904 18.561l5.657-5.657l3.535 3.535l-5.657 5.657Zm11-11l5.657-5.657l3.535 3.535l-5.657 5.657ZM12 10v4");
}

</style>
