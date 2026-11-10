<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b6wdtjb7e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:sneaker" /></template>
<style>
.b6wdtjb7e {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9.8578 5L12.3874 7.69M18.5628 12.41L15.1258 10.12L14.1007 9.44C13.9707 9.35 13.8505 9.25 13.7422 9.13L12.3874 7.69M12.3874 7.69L8.1592 10.19C7.9493 10.32 7.7048 10.36 7.4693 10.31L4.9392 9.77C3.7754 9.52 2.6621 10.39 2.531 11.64L2.2689 14.15M15.1258 10.12L12.8933 12.54M18.5628 12.41L19.4156 12.97C21.0234 14.04 22 15.92 22 17.94C22 18.52 21.5524 19 21.0002 19H6.8222M18.5628 12.41L16.9407 14.15M2.2689 14.15L2.0126 16.61C1.8794 17.88 2.8178 19 4.0239 19H6.8222M2.2689 14.15C3.7866 14.33 6.8222 15.55 6.8222 19");
}

</style>
