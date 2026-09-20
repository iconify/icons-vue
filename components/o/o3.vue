<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path fill="url(#SVGDaoc8dcm)" clip-rule="evenodd" class="ngdjmqq_v"/><defs><linearGradient id="SVGDaoc8dcm" x1="12" x2="10.665" y1="6" y2="17.514" gradientUnits="userSpaceOnUse"><stop class="trqrzyb4w"/><stop offset="1" class="g3kinpijf"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:o3" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.g3kinpijf {
  stop-color: var(--svg-color--06af8f, #06af8f);
}

.ngdjmqq_v {
  fill-rule: evenodd;
  d: path("M8.5 18H18a3 3 0 0 0 2.304-4.922a2.75 2.75 0 1 0-4.128-3.635l-.008.015c-.23.33-.4 1.005.051 1.407c.445.396 1.1.237 1.448-.087a.751.751 0 0 1 1.33.526a.75.75 0 0 1-.764.696l.002.004c-.57 0-1.238.392-1.238 1.246c0 .855.681 1.204 1.238 1.241v.002h.011a.754.754 0 0 1 0 1.507l-.252-.004V16H9.125l.001-.002a4 4 0 1 1 3.341-2c-.335.6-.314 1.014.104 1.35c.73.365 1.417-.029 1.571-.256A6 6 0 1 0 8.5 17.98z");
}

.trqrzyb4w {
  stop-color: var(--svg-color--42b06b, #42b06b);
}

</style>
