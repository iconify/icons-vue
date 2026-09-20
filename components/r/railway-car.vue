<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<defs><path id="SVG2Kv1vUZX" class="wtx3q2t9f"/></defs><use href="#SVG2Kv1vUZX" class="j71m3fb1u"/><clipPath id="SVGIw0oPcRS"><use href="#SVG2Kv1vUZX"/></clipPath><path clip-path="url(#SVGIw0oPcRS)" class="tmcs9v_3a"/><path class="rzdk3tbbm"/><path class="qh9c3kb4z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto-v1:railway-car" /></template>
<style>
.j71m3fb1u {
  fill: var(--svg-color--fcc21b, #fcc21b);
}

.qh9c3kb4z {
  fill: var(--svg-color--fff, #fff);
  d: path("M35.33 75.08c0 1.75-1.41 3.16-3.17 3.16h-10.3c-1.75 0-3.17-1.41-3.17-3.16V58.29c0-1.75 1.42-3.17 3.17-3.17h10.3c1.75 0 3.17 1.42 3.17 3.17zm28.45-16.79c0-1.75-1.42-3.17-3.18-3.17H50.3c-1.75 0-3.16 1.42-3.16 3.17v16.79c0 1.75 1.41 3.16 3.16 3.16h10.3c1.75 0 3.18-1.41 3.18-3.16zm23.05 0a3.18 3.18 0 0 0-3.18-3.17h-10.3c-1.75 0-3.17 1.42-3.17 3.17v16.79c0 1.75 1.42 3.16 3.17 3.16h10.31c1.75 0 3.18-1.41 3.18-3.16V58.29zm22.32 0c0-1.75-1.41-3.17-3.18-3.17h-10.3c-1.75 0-3.17 1.42-3.17 3.17v16.79c0 1.75 1.42 3.16 3.17 3.16h10.29c1.77 0 3.18-1.41 3.18-3.16V58.29z");
}

.rzdk3tbbm {
  fill: var(--svg-color--2f2f2f, #2f2f2f);
  d: path("M39 108.81c0 6.62-5.37 11.97-11.98 11.97c-6.62 0-11.99-5.36-11.99-11.97c0-6.63 5.37-11.97 11.99-11.97c6.61 0 11.98 5.35 11.98 11.97m71.21 0c0 6.62-5.37 11.97-11.98 11.97c-6.62 0-11.99-5.36-11.99-11.97c0-6.63 5.37-11.97 11.99-11.97s11.98 5.35 11.98 11.97");
}

.tmcs9v_3a {
  fill: var(--svg-color--f79329, #f79329);
  d: path("M-2.52 51.88h133.89v30.46H-2.52z");
}

.wtx3q2t9f {
  d: path("M127.38 51.82c0-7.55-4.09-14.64-22.55-14.64H23.27C4.8 37.18.71 44.27.71 51.82v15.57c0 .04.02.06.02.1c-.08 1.07-.11 2.15-.11 3.23v35.68c0 1.81 1.45 3.26 3.26 3.26h120.24c1.8 0 3.26-1.45 3.26-3.26V70.72c0-.96-.03-1.91-.09-2.86c.05-.15.09-.3.09-.48z");
}

</style>
