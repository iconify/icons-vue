<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="xl5o0fsjj"/><path class="e7fje5jwr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:notification-dot" /></template>
<style>
.e7fje5jwr {
  fill: currentColor;
  d: path("M16.25 4.75a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xl5o0fsjj {
  d: path("M16.995 9.764Q17 9.882 17 10v4.5l1.5 2.5h-14L6 14.5V10q0-.135.007-.27q.006-.135.019-.269q.014-.134.034-.268q.019-.134.046-.266q.026-.132.059-.263t.072-.261t.085-.256q.045-.127.097-.252q.051-.124.109-.247q.058-.122.121-.241q.064-.119.133-.235q.07-.115.145-.228q.075-.112.155-.22q.081-.109.166-.213q.086-.105.177-.205q.09-.1.186-.195q.095-.096.195-.186q.1-.091.205-.177t.213-.166t.22-.155t.228-.145q.116-.069.235-.133q.119-.063.241-.121q.123-.058.247-.109q.125-.052.252-.097t.256-.085q.13-.039.261-.072t.263-.059q.132-.027.266-.046q.134-.02.268-.034q.134-.013.269-.019q.135-.007.27-.007q1.028 0 1.987.371M9.5 20.5h4");
}

</style>
