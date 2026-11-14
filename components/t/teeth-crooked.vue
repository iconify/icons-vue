<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zamrmbb4f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:teeth-crooked" /></template>
<style>
.zamrmbb4f {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m2.003 5.459l2.389.594l2.042-1.375l.782 4.431l-.204 4.606l-.738.13l-.927-2.375l-.058 2.548l-.739.131l-1.766-4.258Zm8.23 2.33l2.133 1.23l2.342-.759l-.47 4.475l-1.465 4.371l-.746-.078l-.236-2.539l-.759 2.434l-.746-.078l-.524-4.58Zm7.333-2.111l2.042 1.375l2.389-.594l-.781 4.432l-1.766 4.258l-.739-.131l-.058-2.548l-.927 2.375l-.738-.13l-.204-4.606Z");
}

</style>
