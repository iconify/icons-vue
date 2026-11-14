<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="m4vi3abby"/><path class="m5hes0bss"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:pin-care-home" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.m4vi3abby {
  d: path("M13.956 20H4.75q-.086 0-.172-.008t-.169-.026q-.085-.016-.167-.041t-.162-.058q-.079-.033-.155-.074t-.147-.088q-.072-.048-.138-.102q-.067-.055-.127-.116q-.061-.06-.116-.127q-.054-.066-.102-.138q-.048-.071-.088-.147q-.041-.076-.074-.155q-.033-.08-.058-.162t-.041-.167t-.026-.169Q3 18.336 3 18.25v-6.924q0-.194.042-.383t.126-.364q.082-.175.201-.328t.269-.276l6.75-5.559q.117-.096.248-.171q.131-.074.273-.125t.291-.077t.3-.026t.3.026t.291.077t.273.125q.131.075.248.171l6.75 5.559q.15.123.269.276t.201.328t.126.364t.042.383v.693M11.5 10.5v6m-3-3h6");
}

.m5hes0bss {
  d: path("m19 22l-2.25-2.75a2.75 2.75 0 1 1 4.5 0Z");
}

</style>
