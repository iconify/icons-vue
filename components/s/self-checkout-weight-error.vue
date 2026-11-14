<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="jm4__5bgs"/><path class="s25awubsb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:self-checkout-weight-error" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jm4__5bgs {
  d: path("M11.186 17.5H3.75q-.061 0-.123-.006q-.061-.006-.121-.018t-.119-.03t-.115-.041t-.111-.053t-.105-.063q-.052-.034-.099-.073t-.091-.082q-.043-.044-.082-.091t-.073-.099q-.034-.051-.063-.105t-.053-.111t-.041-.115t-.03-.119t-.018-.121q-.006-.062-.006-.123t.006-.123q.006-.061.018-.121t.03-.119t.041-.115q.024-.057.053-.111t.063-.105t.073-.099t.082-.091t.091-.082t.099-.073t.105-.063t.111-.053q.056-.023.115-.041t.119-.03t.121-.018T3.75 15h8.1");
}

.s25awubsb {
  d: path("M12.2 21.5H6.75q-.086 0-.172-.008t-.169-.026q-.085-.016-.167-.041t-.162-.058q-.079-.033-.155-.074t-.147-.088q-.072-.048-.138-.102q-.067-.055-.127-.116q-.061-.06-.116-.127q-.054-.066-.102-.138q-.048-.071-.088-.147q-.041-.076-.074-.155q-.033-.08-.058-.162t-.041-.167t-.026-.169Q5 19.836 5 19.75v-.5q0-.086.008-.172t.026-.169q.016-.085.041-.167t.058-.162t.074-.155t.088-.147t.102-.138t.116-.127t.127-.116q.066-.054.138-.102q.071-.048.147-.088q.076-.041.155-.074q.08-.033.162-.058t.167-.041q.084-.017.169-.026t.172-.008h4.5M5 15V8.5L6 5h2v3c1 1 3 1 4 0V5h2l1 3.5v3.348M14 18a4 4 0 1 0 8 0a4 4 0 1 0-8 0m4-2.25v2.75m0 2h.01");
}

</style>
