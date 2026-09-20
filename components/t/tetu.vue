<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="t2735x7by"/><path class="sen6f325c"/><path class="d_679hg-q"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:tetu" /></template>
<style>
.d_679hg-q {
  fill: var(--svg-color--04a8f0, #04a8f0);
  d: path("m13.012 20.206l2.7-3.791c.568-.788-.011-1.885-1.012-1.885H9.3c-1.002 0-1.581 1.092-1.013 1.885l2.7 3.79a1.254 1.254 0 0 0 2.025 0");
}

.ft5dv1b6b {
  fill: none;
}

.sen6f325c {
  fill: var(--svg-color--686df1, #686df1);
  d: path("M11.994 11.719A5.58 5.58 0 0 1 6.46 6.234C6.59 4.8 5.306 4.8 4.958 5.188l-.08.079A8.38 8.38 0 0 0 3 10.537c0 1.744 1.727 2.87 3.56 2.87h10.88c1.816 0 3.56-1.115 3.56-2.87a8.35 8.35 0 0 0-1.958-5.343c-.36-.394-1.642-.394-1.513 1.04c0 2.92-2.475 5.485-5.535 5.485");
}

.t2735x7by {
  fill: var(--svg-color--04a8f0, #04a8f0);
  d: path("M12 10.03a3.375 3.375 0 1 0 0-6.75a3.375 3.375 0 0 0 0 6.75");
}

</style>
