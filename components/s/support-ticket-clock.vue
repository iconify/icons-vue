<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="a-xv02bmv"/><path class="a6k62accz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:support-ticket-clock" /></template>
<style>
.a-xv02bmv {
  d: path("M11.954 17.5H2.5v-4q.123 0 .245-.012t.243-.036t.238-.06q.117-.035.231-.082q.113-.047.221-.105q.109-.058.211-.126q.102-.069.197-.146q.095-.078.182-.165t.165-.182t.146-.197t.126-.211t.105-.221q.047-.114.082-.231t.06-.238t.036-.243T5 11t-.012-.245t-.036-.243q-.024-.12-.06-.238t-.082-.231t-.105-.221t-.126-.211q-.069-.102-.146-.197q-.078-.095-.165-.182t-.182-.165t-.197-.146t-.211-.126t-.221-.105q-.114-.047-.231-.082t-.238-.06q-.121-.024-.243-.036T2.5 8.5v-4h18v4q-.123 0-.245.012t-.243.036t-.238.06q-.117.035-.231.082q-.113.047-.221.105q-.109.058-.211.126q-.102.069-.197.146q-.095.078-.182.165t-.165.182t-.146.197t-.126.211t-.105.221q-.047.114-.082.231t-.06.238t-.036.243T18 11q0 .486.182.936M8.5 8v6m6.25 4a3.25 3.25 0 1 0 6.5 0a3.25 3.25 0 1 0-6.5 0");
}

.a6k62accz {
  d: path("M18 16.5V18l1.25 1");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
