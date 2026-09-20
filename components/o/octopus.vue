<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="prw6fpt8j"/><path class="snrl9fbyj"/><path class="h1y_1b48g"/><path class="xbk2atxew"/><circle class="sy4x8qcum"/><circle class="g7jl_obiw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:octopus" /></template>
<style>
.g7jl_obiw {
  cx: 22px;
  cy: 21px;
  r: 2px;
  fill: var(--svg-color--292f33, #292f33);
}

.h1y_1b48g {
  fill: var(--svg-color--744eaa, #744eaa);
  d: path("M30.188 16c-3 5 0 10.692 3 9.692s4 2 1 3s-9.465-.465-13-4c-1-1-2-1-2-1zM5.812 16c3 5 0 10.692-3 9.692s-4 2-1 3s9.465-.465 13-4c1-1 2-1 2-1z");
}

.prw6fpt8j {
  fill: var(--svg-color--553788, #553788);
  d: path("M10 12c3 5 0 10.692-3 9.692s-4 2-1 3s9.465-.465 13-4c1-1 2-1 2-1z");
}

.snrl9fbyj {
  fill: var(--svg-color--553788, #553788);
  d: path("M26 12c-3 5 0 10.692 3 9.692s4 2 1 3s-9.465-.465-13-4c-1-1-2-1-2-1z");
}

.sy4x8qcum {
  cx: 14px;
  cy: 21px;
  r: 2px;
  fill: var(--svg-color--292f33, #292f33);
}

.xbk2atxew {
  fill: var(--svg-color--9266cc, #9266cc);
  d: path("M33.188 31.375c-2.729.91-6.425-5.626-4.812-10.578C30.022 17.554 31 13.94 31 11c0-7.18-5.82-11-13-11S5 3.82 5 11c0 2.94.978 6.554 2.624 9.797c1.613 4.952-2.083 11.488-4.812 10.578c-3-1-4 3-1 4s8.31-.627 12-4c2.189-2 4.189-2 4.189-2s2 0 4.188 2c3.69 3.373 9 5 12 4s1.999-5-1.001-4");
}

</style>
