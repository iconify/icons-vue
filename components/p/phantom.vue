<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<ellipse class="n5ci11b8z"/><path class="kh_vbl29w"/><ellipse class="gkki6gbga"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:phantom" /></template>
<style>
.gkki6gbga {
  cx: 29.72px;
  cy: 18.716px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 1.827px;
  ry: 2.61px;
}

.kh_vbl29w {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M19.85 32.819c-.948 9.482 7.654 4.308 10.862-.366c.663 8.898 8.475-.07 10.235-4.387c4.951-12.149-1.98-27.98-20.889-15.617c-23.454 15.336-14.826 39.875-.208 20.37");
}

.n5ci11b8z {
  cx: 35.862px;
  cy: 18.915px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 1.827px;
  ry: 2.61px;
}

</style>
