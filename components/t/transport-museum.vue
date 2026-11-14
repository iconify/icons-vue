<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="n7a62ll0d"/><path class="x3-sikbdc"/><path class="q1054bc0o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:transport-museum" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.n7a62ll0d {
  d: path("M11.541 20.5H5.75q-.086 0-.172-.008t-.169-.026q-.085-.016-.167-.041t-.162-.058q-.079-.033-.155-.074t-.147-.088q-.072-.048-.138-.102q-.067-.055-.127-.116q-.061-.06-.116-.127q-.054-.066-.102-.138q-.048-.071-.088-.147q-.041-.076-.074-.155q-.033-.08-.058-.162t-.041-.167t-.026-.169Q4 18.836 4 18.75v-7.456q0-.187.04-.37q.039-.183.117-.353q.077-.171.189-.321q.111-.15.252-.273l6.25-5.469q.059-.052.123-.098q.063-.046.131-.087q.067-.04.138-.074t.145-.062t.149-.049q.076-.02.153-.034q.078-.015.156-.022T12 4.075t.157.007t.156.022q.077.014.153.034t.149.049q.074.028.145.062t.138.074t.131.087t.123.098l6.25 5.469q.173.152.302.343q.128.191.202.409M16 7V4h2v4.75");
}

.q1054bc0o {
  d: path("M14.5 19.75a1.25 1.25 0 1 0 2.5 0a1.25 1.25 0 1 0-2.5 0m4 0a1.25 1.25 0 1 0 2.5 0a1.25 1.25 0 1 0-2.5 0");
}

.x3-sikbdc {
  d: path("M13.5 18.5v-2a1 1 0 0 1 1-1l1.5-2h3.5l1.5 2a1 1 0 0 1 1 1v2Z");
}

</style>
