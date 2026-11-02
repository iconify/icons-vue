<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lx9z-d2ap"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:star-fill" /></template>
<style>
.lx9z-d2ap {
  fill: currentColor;
  d: path("m15.66 8.084l6.481.926a1.001 1.001 0 0 1 .566 1.697l-4.636 4.636l.915 5.493a1 1 0 0 1-.392.968a1 1 0 0 1-1.041.09L12 19.118l-5.553 2.776a1 1 0 0 1-1.041-.09a1 1 0 0 1-.392-.968l.915-5.493l-4.636-4.636a1.001 1.001 0 0 1 .566-1.697l6.481-.926l2.766-5.531a.998.998 0 0 1 1.788 0Z");
}

</style>
