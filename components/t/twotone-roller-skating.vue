<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n6r9f_brt"/><path class="ckjr-u-zl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-roller-skating" /></template>
<style>
.ckjr-u-zl {
  fill: currentColor;
  d: path("M20 12a3.96 3.96 0 0 0-2.91-3.82l-2.62-.74C13.62 7.19 13 6.39 13 5.5V1H4v15h16zm-2 2H6V3h5v1H9.5c-.28 0-.5.22-.5.5s.22.5.5.5H11l.1 1H9.5c-.28 0-.5.22-.5.5s.22.5.5.5h1.81c.45 1.12 1.4 2.01 2.6 2.36l2.62.73C17.4 10.33 18 11.1 18 12zM5 17c-1.66 0-3 1.34-3 3s1.34 3 3 3s3-1.34 3-3s-1.34-3-3-3m0 4c-.55 0-1-.45-1-1s.45-1 1-1s1 .45 1 1s-.45 1-1 1m14-4c-1.66 0-3 1.34-3 3s1.34 3 3 3s3-1.34 3-3s-1.34-3-3-3m0 4c-.55 0-1-.45-1-1s.45-1 1-1s1 .45 1 1s-.45 1-1 1m-7-4c-1.66 0-3 1.34-3 3s1.34 3 3 3s3-1.34 3-3s-1.34-3-3-3m0 4c-.55 0-1-.45-1-1s.45-1 1-1s1 .45 1 1s-.45 1-1 1");
}

.n6r9f_brt {
  fill: currentColor;
  d: path("M18 14H6V3h5v1H9.5c-.28 0-.5.22-.5.5s.22.5.5.5H11l.1 1H9.5c-.28 0-.5.22-.5.5s.22.5.5.5h1.81c.45 1.12 1.4 2.01 2.6 2.36l2.62.73C17.4 10.33 18 11.1 18 12zM5 21c-.55 0-1-.45-1-1s.45-1 1-1s1 .45 1 1s-.45 1-1 1m14 0c-.55 0-1-.45-1-1s.45-1 1-1s1 .45 1 1s-.45 1-1 1m-7 0c-.55 0-1-.45-1-1s.45-1 1-1s1 .45 1 1s-.45 1-1 1");
  opacity: var(--svg-opacity--0-3, 0.3);
}

</style>
