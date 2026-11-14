<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="hnvnn0bgl"/><path class="jfndnkb6y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:shield-cog" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.hnvnn0bgl {
  d: path("m12 2.75l7.5 2.75v6c0 4.7-3.1 8-7.5 9.75c-4.4-1.75-7.5-5.05-7.5-9.75v-6Z");
}

.jfndnkb6y {
  d: path("m11.439 8.318l.009-.25A.55.55 0 0 1 12 7.536a.55.55 0 0 1 .552.532l.009.25a.77.77 0 0 0 .474.683a.77.77 0 0 0 .819-.148l.183-.17a.55.55 0 0 1 .766.014a.55.55 0 0 1 .014.766l-.17.183a.77.77 0 0 0-.148.819a.77.77 0 0 0 .683.474l.25.009a.55.55 0 0 1 .532.552a.55.55 0 0 1-.532.552l-.25.009a.77.77 0 0 0-.683.474a.77.77 0 0 0 .148.819l.17.183a.55.55 0 0 1-.014.766a.55.55 0 0 1-.766.014l-.183-.17a.77.77 0 0 0-.819-.148a.77.77 0 0 0-.474.683l-.009.25a.55.55 0 0 1-.552.532a.55.55 0 0 1-.552-.532l-.009-.25a.77.77 0 0 0-.474-.683a.77.77 0 0 0-.819.148l-.183.17a.55.55 0 0 1-.766-.014a.55.55 0 0 1-.014-.766l.17-.183a.77.77 0 0 0 .148-.819a.77.77 0 0 0-.683-.474l-.25-.009a.55.55 0 0 1-.532-.552a.55.55 0 0 1 .532-.552l.25-.009a.77.77 0 0 0 .683-.474a.77.77 0 0 0-.148-.819l-.17-.183a.55.55 0 0 1 .014-.766a.55.55 0 0 1 .766-.014l.183.17a.77.77 0 0 0 .819.148a.77.77 0 0 0 .474-.683");
}

</style>
