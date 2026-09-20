<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="gachxc6dt"/><path class="fx28_kbpk"/><circle class="j45flxzev"/><circle class="c-05qabni"/><circle class="d__kye1mx"/><circle class="voet0yb4z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:potato" /></template>
<style>
.c-05qabni {
  cx: 30.25px;
  cy: 26px;
  r: 1px;
  fill: var(--svg-color--c1694f, #c1694f);
}

.d__kye1mx {
  cx: 14.75px;
  cy: 25.5px;
  r: 1.5px;
  fill: var(--svg-color--c1694f, #c1694f);
}

.fx28_kbpk {
  fill: var(--svg-color--c1694f, #c1694f);
  d: path("M17.71 14.822c1.827-1.737 3.628-2.498 5.649-2.838l-.109.015c0-.858-.204-1.597-.534-2.28c-2.074.772-4.288 2.281-5.006 5.103");
}

.gachxc6dt {
  fill: var(--svg-color--d99e82, #d99e82);
  d: path("M.25 13c0-7.158 10-15 18-8c2.714 2.375 5 4 5 7c12-2 13.703 8.892 12 14c-1 3-5.868 11.059-24 3c-9-4-11-11.616-11-16");
}

.j45flxzev {
  cx: 10.25px;
  cy: 16px;
  r: 1px;
  fill: var(--svg-color--c1694f, #c1694f);
}

.voet0yb4z {
  cx: 5.75px;
  cy: 19.5px;
  r: 1.5px;
  fill: var(--svg-color--c1694f, #c1694f);
}

</style>
