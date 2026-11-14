<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sedpdob5f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:meeting-check" /></template>
<style>
.sedpdob5f {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.25 10.5a4.25 4.25 0 1 0 8.5 0a4.25 4.25 0 1 0-8.5 0m-2.645 2.24a7.25 7.25 0 0 1 0-4.48m13.898.364a7.25 7.25 0 0 1 0 3.752m-5.542 5.225q-.46.095-.928.129q-.467.035-.936.009q-.468-.027-.93-.113q-.461-.086-.907-.231m.364-13.898a7.25 7.25 0 0 1 3.752 0M14.75 18l2 2L21 15.75");
}

</style>
