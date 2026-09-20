<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="nwvok0bfn"/><path class="z2jpptbqq"/><circle class="nerhv1bov"/><circle class="c-cmpybqj"/><circle class="uarur_8fx"/><path class="slh48d__b"/><path class="k69yx_bph"/><circle class="zt5t2kj3m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:movie-camera" /></template>
<style>
.c-cmpybqj {
  cx: 27.999px;
  cy: 14px;
  r: 4px;
  fill: var(--svg-color--66757f, #66757f);
}

.k69yx_bph {
  fill: var(--svg-color--31373d, #31373d);
  d: path("M19 22h6v6h-6z");
}

.nerhv1bov {
  cx: 17px;
  cy: 11px;
  r: 2px;
  fill: var(--svg-color--ccd6dd, #ccd6dd);
}

.nwvok0bfn {
  fill: var(--svg-color--31373d, #31373d);
  d: path("M32 21v1h-2v-1c0-.446-.09-.867-.225-1.268a6 6 0 0 0-1.776-11.733a5.97 5.97 0 0 0-4.131 1.656A7 7 0 0 0 10 11a6.99 6.99 0 0 0 3.409 6H13a4 4 0 0 0-4 4H8l-6-4H1v14h1l6-4h1v2a4 4 0 0 0 4 4h13a4 4 0 0 0 4-4v-3h2v1h3v-6z");
}

.slh48d__b {
  fill: var(--svg-color--8899a6, #8899a6);
  d: path("M17 20h10v10H17z");
}

.uarur_8fx {
  cx: 27.999px;
  cy: 14px;
  r: 2px;
  fill: var(--svg-color--ccd6dd, #ccd6dd);
}

.z2jpptbqq {
  fill: var(--svg-color--66757f, #66757f);
  d: path("M22 11a5 5 0 1 1-10.001-.001A5 5 0 0 1 22 11");
}

.zt5t2kj3m {
  cx: 12.999px;
  cy: 28px;
  r: 2px;
  fill: var(--svg-color--8899a6, #8899a6);
}

</style>
