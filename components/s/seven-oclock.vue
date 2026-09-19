<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<g transform="scale(.99881 .99878)"><circle class="d91wy0buk"/><path class="yx4y6mbrc"/><path class="j3-nmx9dt"/><path class="si-b2p5ra"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-v1:seven-oclock" /></template>
<style>
.d91wy0buk {
  cx: 32.04px;
  cy: 32.04px;
  r: 29.681px;
  fill: var(--svg-color--e0e7ec, #e0e7ec);
}

.j3-nmx9dt {
  fill: var(--svg-color--85939c, #85939c);
  d: path("M30.16 11.05c0-1.438.849-2.604 1.895-2.604c1.042 0 1.891 1.167 1.891 2.604v21.11c0 1.441-.849 2.609-1.891 2.609c-1.046 0-1.895-1.168-1.895-2.609z");
}

.si-b2p5ra {
  fill: var(--svg-color--788288, #788288);
  d: path("M26.805 47.923c-.64 1.29-1.92 1.96-2.854 1.497c-.936-.464-1.177-1.888-.539-3.179l6.78-13.69c.638-1.289 1.918-1.959 2.854-1.496c.935.463 1.179 1.886.544 3.177z");
}

.yx4y6mbrc {
  fill: var(--svg-color--98a9b4, #98a9b4);
  d: path("M32.04 0C14.374 0 0 14.372 0 32.04c0 17.666 14.374 32.04 32.04 32.04s32.04-14.372 32.04-32.04S49.71 0 32.04 0m0 57.841c-14.228 0-25.805-11.575-25.805-25.801c0-14.229 11.577-25.805 25.805-25.805c14.226 0 25.797 11.575 25.797 25.805c0 14.226-11.571 25.801-25.797 25.801");
}

</style>
