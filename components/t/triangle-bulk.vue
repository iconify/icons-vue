<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b8-kz7bzg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:triangle-bulk" /></template>
<style>
.b8-kz7bzg {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("m14.591 4.488l7 12A2.999 2.999 0 0 1 19 21H5a2.999 2.999 0 0 1-2.591-4.512l7-12a3 3 0 0 1 5.182 0");
}

</style>
