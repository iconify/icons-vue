<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<g class="u8jb0tbox"><path class="l_pj_8bdk"/><path class="st3vtqbmt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-v1:prohibited-sign" /></template>
<style>
.l_pj_8bdk {
  d: path("M53.28 47.659Q34.795 29.177 16.306 10.687c-5.486-5.486-11.1.129-5.613 5.615l36.972 36.972c5.487 5.491 11.1-.128 5.615-5.615");
}

.st3vtqbmt {
  d: path("M31.983 0C14.349 0 0 14.349 0 31.983s14.349 31.983 31.983 31.983s31.983-14.349 31.983-31.983S49.618 0 31.983 0m0 56.04c-13.266 0-24.06-10.79-24.06-24.06S18.715 7.92 31.983 7.92s24.06 10.793 24.06 24.06s-10.79 24.05-24.06 24.05");
}

.u8jb0tbox {
  fill: var(--svg-color--be1e2d, #be1e2d);
}

</style>
