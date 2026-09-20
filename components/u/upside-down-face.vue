<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="fwvg7xghr"/><path class="afezg003f"/><ellipse class="j8c791bti"/><ellipse class="gvsg_lz-p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:upside-down-face" /></template>
<style>
.afezg003f {
  fill: var(--svg-color--664500, #664500);
  d: path("M8.665 12.871a.5.5 0 0 0 .635.029c.039-.029 3.922-2.9 8.7-2.9c4.766 0 8.662 2.871 8.7 2.9a.5.5 0 0 0 .729-.657C27.3 12.029 24.212 7 18 7s-9.301 5.028-9.429 5.243a.5.5 0 0 0 .094.628");
}

.fwvg7xghr {
  fill: var(--svg-color--ffcc4d, #ffcc4d);
  d: path("M0 18C0 8.059 8.059 0 18 0s18 8.059 18 18s-8.059 18-18 18S0 27.941 0 18");
}

.gvsg_lz-p {
  cx: 24.5px;
  cy: 21.5px;
  fill: var(--svg-color--664500, #664500);
  rx: 2.5px;
  ry: 3.5px;
}

.j8c791bti {
  cx: 11.5px;
  cy: 21.5px;
  fill: var(--svg-color--664500, #664500);
  rx: 2.5px;
  ry: 3.5px;
}

</style>
