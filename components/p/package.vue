<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="o-9qx3b2l"/><path class="prrhmi-3h"/><path class="n-wk_gluk"/><path class="dm938fbmx"/><path class="si6ah6g-a"/><path class="ryar1q58b"/><path class="a7f-s_bzg"/><path class="gmvj59h_f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:package" /></template>
<style>
.a7f-s_bzg {
  fill: var(--svg-color--fff, #fff);
  d: path("m62.5 22.1l-5.7 3.4v9.2l5.7-3.4zM41.6 43.5l-7.7 4.6v12.6l7.7-4.7z");
}

.dm938fbmx {
  fill: var(--svg-color--89664c, #89664c);
  d: path("M50.9 27L19 7.8l-6 3.6l32 19.2z");
}

.gmvj59h_f {
  fill: var(--svg-color--d3976e, #d3976e);
  d: path("m45.2 56.1l5.6-3.4v-9.2l-5.6 3.4z");
}

.n-wk_gluk {
  fill: var(--svg-color--d3976e, #d3976e);
  d: path("m0 19.2l32 19.2l32-19.2L32 0z");
}

.o-9qx3b2l {
  fill: var(--svg-color--89664c, #89664c);
  d: path("M32 64L0 44.8V19.2l32 19.2z");
}

.prrhmi-3h {
  fill: var(--svg-color--fed0ac, #fed0ac);
  d: path("M32 38.4V64l32-19.2V19.2z");
}

.ryar1q58b {
  fill: var(--svg-color--d3976e, #d3976e);
  d: path("m50.8 27.1l-5.6 3.4v9.2l5.6-3.4z");
}

.si6ah6g-a {
  fill: var(--svg-color--d0d0d0, #d0d0d0);
  d: path("m39.3 6.8l-7.1-4.4L26.3 6l7.1 4.3z");
}

</style>
