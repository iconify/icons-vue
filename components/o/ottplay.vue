<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="fmn8yub-d"><path class="gx-7s_b5k"/><path class="vcl-xs47i"/><path class="ffcw0r53u"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:ottplay" /></template>
<style>
.ffcw0r53u {
  d: path("M6.344 22.502c9.885 5.103 28.106-1.96 36.208-5.332l-11.25 16.493c-6.725.633-18.171.325-22.878-3.484m16.836 3.469l2.166-11.027m-13.219 1.902l.45 8.166");
}

.fmn8yub-d {
  fill: none;
  stroke: currentColor;
  stroke-dashoffset: 3;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.gx-7s_b5k {
  d: path("M13.388 19.177c2.087 0 3.975-.408 5.342-1.066s2.213-1.568 2.213-2.572c0-2.009-3.382-3.638-7.555-3.638c-2.833 0-5.285.772-6.57 1.841c-4.346 3.617-1.097 7.604 6.57 7.343c10.959-.373 24.974-7.012 29.738-10.282");
}

.vcl-xs47i {
  d: path("m4.942 17.63l3.952 14.585c4.858 4.68 14.867 5.019 19.812 4.978");
}

</style>
