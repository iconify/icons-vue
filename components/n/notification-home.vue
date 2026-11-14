<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="jwe5z74vr"/><path class="q0vasms1a"/><path class="a0w33eb1f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:notification-home" /></template>
<style>
.a0w33eb1f {
  fill: currentColor;
  d: path("M15.25 18.5a3.25 3.25 0 1 0 6.5 0a3.25 3.25 0 1 0-6.5 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jwe5z74vr {
  d: path("M12.744 20.5H4.25q-.086 0-.172-.008t-.169-.026q-.085-.016-.167-.041t-.162-.058t-.155-.074q-.076-.04-.147-.088q-.072-.048-.138-.102q-.067-.055-.127-.116q-.061-.06-.116-.127q-.054-.066-.102-.138q-.048-.071-.088-.147q-.041-.076-.074-.155q-.033-.08-.058-.162t-.041-.167t-.026-.169q-.008-.086-.008-.172v-7.46q0-.186.039-.368t.116-.352t.187-.319t.25-.273l6.75-5.956q.059-.052.123-.099t.132-.088t.139-.075t.145-.063t.15-.049t.154-.035t.157-.022t.158-.007t.158.007t.157.022t.154.035t.15.049t.145.063t.139.075t.132.088t.123.099l6.75 5.956q.14.123.25.273q.111.15.187.319q.077.17.116.352t.039.368v1.241");
}

.q0vasms1a {
  d: path("M8.5 20.5v-5h4v2.9m0 .2v1.9");
}

</style>
