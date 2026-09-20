<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="mumfproca"/><path class="rx5s3q8jg"/><path class="m7_8qkb4t"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:prism-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.m7_8qkb4t {
  fill: var(--svg-color--fff, #fff);
  d: path("M4.442 19.002a.45.45 0 0 1-.39-.66l.49-.84h5.743l.82 1.49c-.65.01-1.15.01-1.68.01zm15.523-.765s.22.765-.44.765h-.876l-2.906-4.937l.87-1.52zm-8.36-13.021a.446.446 0 0 1 .761-.01l.545.91L9.43 11.5H7.764z");
}

.mumfproca {
  fill: var(--svg-color--000, #000);
  d: path("M24 0H0v24h24z");
}

.rx5s3q8jg {
  fill: var(--svg-color--fff, #fff);
  d: path("M15.533 19.002s.15.2-2.822-5.003l2.422-4.137l.77 1.446l-1.55 2.707l2.88 4.987zm-1.986-11.8l.83 1.46l-3.252 5.337H6.593c.285-.5.586-1.02.85-1.5h2.727zM11.816 15l2.331 4.002h-1.68L10.954 16.5H5.123l.87-1.5z");
}

</style>
