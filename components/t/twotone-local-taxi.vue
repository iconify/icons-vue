<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ogu4_qy2n"/><path class="kgpji5bal"/><circle class="i41e6pm1x"/><circle class="icc3mmbjf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-local-taxi" /></template>
<style>
.i41e6pm1x {
  cx: 7.5px;
  cy: 14.5px;
  r: 1.5px;
  fill: currentColor;
}

.icc3mmbjf {
  cx: 16.5px;
  cy: 14.5px;
  r: 1.5px;
  fill: currentColor;
}

.kgpji5bal {
  fill: currentColor;
  d: path("M17.5 5H15V3H9v2H6.5c-.66 0-1.21.42-1.42 1.01L3 12v8c0 .55.45 1 1 1h1c.55 0 1-.45 1-1v-1h12v1c0 .55.45 1 1 1h1c.55 0 1-.45 1-1v-8l-2.08-5.99C18.72 5.42 18.16 5 17.5 5M6.85 7h10.29l1.04 3H5.81zM19 17H5v-4.66l.12-.34h13.77l.11.34z");
}

.ogu4_qy2n {
  fill: currentColor;
  d: path("m5.12 12l-.12.34V17h14v-4.66l-.12-.34zm2.38 4c-.83 0-1.5-.67-1.5-1.5S6.67 13 7.5 13s1.5.67 1.5 1.5S8.33 16 7.5 16m9 0c-.83 0-1.5-.67-1.5-1.5s.67-1.5 1.5-1.5s1.5.67 1.5 1.5s-.67 1.5-1.5 1.5");
  opacity: var(--svg-opacity--0-3, 0.3);
}

</style>
