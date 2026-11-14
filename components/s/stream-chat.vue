<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ou5k1uxvz"/><path class="aegoecbbh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:stream-chat" /></template>
<style>
.aegoecbbh {
  fill: currentColor;
  d: path("M16 5.25a2.75 2.75 0 1 0 5.5 0a2.75 2.75 0 1 0-5.5 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ou5k1uxvz {
  d: path("M20 10.646V14q0 .123-.012.245t-.036.243q-.024.12-.06.238t-.082.231t-.105.221t-.126.211q-.069.102-.146.197q-.078.095-.165.182t-.182.165t-.197.146t-.211.126t-.221.105q-.114.047-.231.082t-.238.06t-.243.036t-.245.012H11L7 20v-3.5h-.5q-.123 0-.245-.012t-.243-.036q-.12-.024-.238-.06t-.231-.082t-.221-.105t-.211-.126q-.102-.069-.197-.146q-.095-.078-.182-.165t-.165-.182t-.146-.197t-.126-.211t-.105-.221q-.047-.114-.082-.231t-.06-.238t-.036-.243T4 14V6q0-.123.012-.245t.036-.243q.024-.12.06-.238t.082-.231t.105-.221q.058-.109.126-.211q.069-.102.146-.197q.078-.095.165-.182t.182-.165t.197-.146t.211-.126q.108-.058.221-.105q.114-.047.231-.082t.238-.06q.121-.024.243-.036T6.5 3.5h6.973M8 9h6.7M8 12.5h4.5");
}

</style>
