<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="va_pdjepp"/><path class="nk893wbhl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:mortgage-conveyancing" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.nk893wbhl {
  d: path("M18.22 12.598za.5.5 0 0 1 0 .707l-1.415 1.415a.5.5 0 0 1-.707 0a.5.5 0 0 1 0-.707l1.415-1.415a.5.5 0 0 1 .707 0m3.182 3.182za.5.5 0 0 1 0 .707l-1.415 1.415a.5.5 0 0 1-.707 0a.5.5 0 0 1 0-.707l1.415-1.415a.5.5 0 0 1 .707 0M18 16l-3.25 3.25m2 2.25h5");
}

.va_pdjepp {
  d: path("M12.241 20.5H5.75q-.086 0-.172-.008t-.169-.026q-.085-.016-.167-.041t-.162-.058q-.079-.033-.155-.074t-.147-.088q-.072-.048-.138-.102q-.067-.055-.127-.116q-.061-.06-.116-.127q-.054-.066-.102-.138q-.048-.071-.088-.147q-.041-.076-.074-.155q-.033-.08-.058-.162t-.041-.167t-.026-.169Q4 18.836 4 18.75v-7.456q0-.187.04-.37q.039-.183.117-.353q.077-.171.189-.321q.111-.15.252-.273l6.25-5.469q.059-.052.123-.098q.063-.046.131-.087q.067-.04.138-.074t.145-.062t.149-.049q.076-.02.153-.034q.078-.015.156-.022T12 4.075t.157.007t.156.022q.077.014.153.034t.149.049q.074.028.145.062t.138.074t.131.087t.123.098l6.25 5.469q.071.062.135.131M16 7V4h2v4.75m.927 5.263l1.06 1.06a1 1 0 0 1 0 1.414a1 1 0 0 1-1.414 0l-1.06-1.06a1 1 0 0 1 0-1.414a1 1 0 0 1 1.414 0");
}

</style>
