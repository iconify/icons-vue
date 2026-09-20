<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="m-qzp1biu"/><path class="wm84inb4v"/><path class="o-lm50bcg"/><path class="lpaup3b6h"/><path class="al00ysbrd"/><path class="jdbh6ab2a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:woman-red-haired-medium-dark-skin-tone" /></template>
<style>
.al00ysbrd {
  fill: var(--svg-color--e95f28, #e95f28);
  d: path("M3.064 24c-.03-.325-.064-.647-.064-1c0-5 3 .562 3-3s2-4 4-6l3-3s5 3 9 3s8 2 8 6s3-2 3 3c0 .355-.033.673-.058 1h1.049C34 22.523 34 20.868 34 19C34 6 24 1 18 1S2 6 2 19c0 1.158-.028 2.986.012 5z");
}

.jdbh6ab2a {
  fill: var(--svg-color--662113, #662113);
  d: path("M13 22a1 1 0 0 1-1-1v-2a1 1 0 0 1 2 0v2a1 1 0 0 1-1 1m10 0a1 1 0 0 1-1-1v-2a1 1 0 1 1 2 0v2a1 1 0 0 1-1 1");
}

.lpaup3b6h {
  fill: var(--svg-color--915a34, #915a34);
  d: path("M19 25h-2a1 1 0 1 1 0-2h2a1 1 0 1 1 0 2");
}

.m-qzp1biu {
  fill: var(--svg-color--e95f28, #e95f28);
  d: path("M18 3c6 0 16 3 16 16s0 16-3 16s-7-3-13-3s-9.915 3-13 3c-3.343 0-3-12-3-16C2 6 12 3 18 3");
}

.o-lm50bcg {
  fill: var(--svg-color--df1f32, #df1f32);
  d: path("M18 30c-2.347 0-3.575-1.16-3.707-1.293a.999.999 0 0 1 1.404-1.424c.051.047.806.717 2.303.717c1.519 0 2.273-.69 2.305-.719a1.01 1.01 0 0 1 1.408.029a.994.994 0 0 1-.006 1.397C21.575 28.84 20.347 30 18 30");
}

.wm84inb4v {
  fill: var(--svg-color--ae7e57, #ae7e57);
  d: path("M6 18.562c0-8.526 5.373-15.438 12-15.438s12 6.912 12 15.438S24.627 34 18 34S6 27.088 6 18.562");
}

</style>
