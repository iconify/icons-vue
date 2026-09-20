<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="vyo0tv_6k"/><path class="gnqu005-c"/><path class="uzxi23bjw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto:stop-sign" /></template>
<style>
.gnqu005-c {
  fill: var(--svg-color--c33, #c33);
  d: path("M120 87.2L87.2 120H42l-2.85 4h49.7L124 88.85v-49.7L120 42z");
}

.uzxi23bjw {
  fill: var(--svg-color--ff8a80, #ff8a80);
  d: path("M42.88 13H78c4.68 0 7.03-1.71 8.18-3.13c.6-.75.08-1.87-.89-1.87H40.8L9.46 39.35c-.49.49-.09 1.32.59 1.25l1.66-.17c2.77-.28 5.36-1.51 7.32-3.48z");
  opacity: var(--svg-opacity--0-9, 0.9);
}

.vyo0tv_6k {
  fill: var(--svg-color--f44336, #f44336);
  d: path("M88.85 4h-49.7L4 39.15v49.7L39.15 124h49.7L124 88.85v-49.7z");
}

</style>
