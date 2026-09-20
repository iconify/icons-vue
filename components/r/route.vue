<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path fill="url(#SVGqLZcVdGJ)" class="qp-2_okjt"/><path fill="url(#SVGsW3CXbUP)" class="s9qmrnb7p"/><defs><linearGradient id="SVGqLZcVdGJ" x1="15.961" x2="10.527" y1="10.284" y2="10.284" gradientUnits="userSpaceOnUse"><stop class="f-skp2ple"/><stop offset="1" class="lvsvg0b2y"/></linearGradient><linearGradient id="SVGsW3CXbUP" x1="13.625" x2="11.171" y1="9.89" y2="13.447" gradientUnits="userSpaceOnUse"><stop class="j02u2ibrh"/><stop offset=".51" class="gedwahbqy"/><stop offset="1" class="j02u2ibrh"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:route" /></template>
<style>
.f-skp2ple {
  stop-color: var(--svg-color--fe8664, #fe8664);
}

.ft5dv1b6b {
  fill: none;
}

.gedwahbqy {
  stop-color: var(--svg-color--bd4551, #bd4551);
}

.j02u2ibrh {
  stop-color: var(--svg-color--ab3e55, #ab3e55);
}

.lvsvg0b2y {
  stop-color: var(--svg-color--ff3b56, #ff3b56);
}

.qp-2_okjt {
  d: path("M8.528 4.3a.29.29 0 0 1-.01-.393a2.624 2.624 0 0 1 3.852-.127l1.99 1.975a4.164 4.164 0 0 1 .047 5.789l-2.539 2.638l2.643 2.733a2.91 2.91 0 0 1 .01 4.003a.26.26 0 0 1-.293.06a.3.3 0 0 1-.086-.06l-3.785-3.827a4.164 4.164 0 0 1 .01-5.808l2.52-2.534l-4.359-4.453z");
}

.s9qmrnb7p {
  d: path("m11.196 10.444l1.686-1.696a3.08 3.08 0 0 1 .422 3.941l-1.436 1.488c-.54-.545-1.535-1.848-.7-3.667z");
}

</style>
