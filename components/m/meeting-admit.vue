<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a231-mkxh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:meeting-admit" /></template>
<style>
.a231-mkxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.25 7.5a3.75 3.75 0 1 0 7.5 0a3.75 3.75 0 1 0-7.5 0Zm-1.75 14q0-.135.007-.27q.006-.135.019-.269q.014-.134.034-.268q.019-.134.046-.266q.026-.132.059-.263t.072-.261t.085-.256q.045-.127.097-.252q.051-.125.109-.247t.121-.241t.133-.235q.07-.115.145-.228q.075-.112.155-.22q.081-.109.166-.213q.086-.105.177-.205q.09-.1.186-.195q.095-.096.195-.186q.1-.091.205-.177t.213-.166t.22-.155q.113-.075.228-.145q.116-.069.235-.133q.119-.063.241-.121q.123-.058.247-.109q.125-.052.252-.097t.256-.085t.261-.072t.263-.059t.266-.046q.134-.02.268-.034q.134-.013.269-.019Q7.865 16 8 16q.302 0 .602.033q.301.033.596.099t.581.164t.559.226t.531.286q.258.157.497.342t.456.395t.41.443m1.224 2.815q.044.347.044.697M15 18h4.25m-2-2l2 2l-2 2m2.25-5.5H22v7h-2.5");
}

</style>
