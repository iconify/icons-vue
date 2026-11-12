<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="kzd06b-3d"/><path class="erq4sqghc"/><path class="onn90jb9j"/><path class="f2i7g9b1n"/><path class="s_gtqnwjr"/><path class="wujdauagd"/><path class="ono0e8bgt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:tornado-linear" /></template>
<style>
.erq4sqghc {
  d: path("M20 8C20 8 17.2089 9 11.7241 9C6.23938 9 4 8 4 8");
}

.f2i7g9b1n {
  d: path("M16 16.5C15.2525 16.7554 14.3516 17 13 17C11.6484 17 10.6575 16.8786 10 16.7554");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.kzd06b-3d {
  d: path("M12 3C7.02944 3 3 3.67157 3 4.5C3 5.32843 7.02944 6 12 6C16.9706 6 21 5.32843 21 4.5C21 3.97993 19.412 3.52168 17 3.25259");
}

.onn90jb9j {
  d: path("M16 14C16 14 14.7424 14.5 12 14.5C9.25762 14.5 8 14 8 14");
}

.ono0e8bgt {
  d: path("M13 22H13.5");
}

.s_gtqnwjr {
  d: path("M11.7188 19.4609C12.103 19.4853 12.5297 19.5 13.0002 19.5C13.5738 19.5 14.0662 19.456 14.5002 19.3857");
}

.wujdauagd {
  d: path("M18 11C18 11 17.4848 12 12 12M7.8918 11.721C6.21904 11.4251 6 11 6 11");
}

</style>
