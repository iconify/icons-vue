<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tit30sb8b"/><path class="q6qb_qz6a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-king-bed" /></template>
<style>
.q6qb_qz6a {
  fill: currentColor;
  d: path("M20 10V7c0-1.1-.9-2-2-2H6c-1.1 0-2 .9-2 2v3c-1.1 0-2 .9-2 2v5h1.33L4 19h1l.67-2h12.67l.66 2h1l.67-2H22v-5c0-1.1-.9-2-2-2m-7-3h5v3h-5zM6 7h5v3H6zm14 8H4v-3h16z");
}

.tit30sb8b {
  fill: currentColor;
  d: path("M4 12h16v3H4z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

</style>
