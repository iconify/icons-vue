<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="kqskqje3y"/><path class="w6_4-b4ec"/><path class="gx2_em63e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:staging-home" /></template>
<style>
.gx2_em63e {
  d: path("M14 21v-3.5a1.25 1.25 0 0 1 2.5 0V19H19v-1.5a1.25 1.25 0 0 1 2.5 0V21Z");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.kqskqje3y {
  d: path("M11.156 19.5H4.25q-.086 0-.172-.008t-.169-.026q-.085-.016-.167-.041t-.162-.058t-.155-.074q-.076-.04-.147-.088q-.072-.048-.138-.102q-.067-.055-.127-.116q-.061-.06-.116-.127q-.054-.066-.102-.138q-.048-.071-.088-.147q-.041-.076-.074-.155q-.033-.08-.058-.162t-.041-.167t-.026-.169q-.008-.086-.008-.172v-6.924q0-.194.042-.383t.126-.364q.082-.175.201-.328t.269-.276l6.75-5.559q.117-.096.248-.171q.131-.074.273-.125t.291-.077t.3-.026t.3.026t.291.077t.273.125t.248.171l6.75 5.559q.15.123.269.276t.201.328t.126.364t.042.383v.893");
}

.w6_4-b4ec {
  d: path("M15.25 16.25V14.5h5v1.75");
}

</style>
