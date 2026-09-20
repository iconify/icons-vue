<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":416};
const content = `<defs><linearGradient id="SVGIoYDikML" x1="0%" x2="100%" y1="50%" y2="50%"><stop offset="0%" class="fcjg1en7j"/><stop offset="100%"/></linearGradient><linearGradient id="SVG8SIKbbQY" x1="0%" x2="100%" y1="50%" y2="50%"><stop offset="0%" class="eu6vb4bna"/><stop offset="100%" class="la1q1sbut"/></linearGradient></defs><path fill="url(#SVGIoYDikML)" transform="matrix(1 0 0 -1 0 544)" class="i45xlzbzp"/><path fill="url(#SVGIoYDikML)" transform="matrix(1 0 0 -1 0 288)" class="ba_67z7ue"/><path fill="url(#SVG8SIKbbQY)" transform="matrix(1 0 0 -1 0 416)" class="xg9bu-nvy"/><path fill="url(#SVG8SIKbbQY)" transform="matrix(1 0 0 -1 0 160)" class="i26728cyj"/><path fill="url(#SVG8SIKbbQY)" transform="matrix(1 0 0 -1 0 672)" class="voplncnxv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:scala" /></template>
<style>
.ba_67z7ue {
  d: path("M0 160v-32c0-5.394 116.377-14.428 192.2-32c36.628 8.49 63.8 18.969 63.8 32v32c0 13.024-27.172 23.51-63.8 32C116.376 174.425 0 165.39 0 160");
}

.eu6vb4bna {
  stop-color: var(--svg-color--c40000, #c40000);
}

.fcjg1en7j {
  stop-color: var(--svg-color--4f4f4f, #4f4f4f);
}

.i26728cyj {
  d: path("M0 96V0c0 8 256 24 256 64v96c0-40-256-56-256-64");
}

.i45xlzbzp {
  d: path("M0 288v-32c0-5.394 116.377-14.428 192.2-32c36.628 8.49 63.8 18.969 63.8 32v32c0 13.024-27.172 23.51-63.8 32C116.376 302.425 0 293.39 0 288");
}

.la1q1sbut {
  stop-color: var(--svg-color--red, red);
}

.voplncnxv {
  d: path("M0 352v-96c0 8 256 24 256 64v96c0-40-256-56-256-64");
}

.xg9bu-nvy {
  d: path("M0 224v-96c0 8 256 24 256 64v96c0-40-256-56-256-64");
}

</style>
