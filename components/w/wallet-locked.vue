<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="u87v8xayu"/><path class="hfuvsqbpg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:wallet-locked" /></template>
<style>
.hfuvsqbpg {
  d: path("M21 6h-3.75a1.75 1.75 0 0 0 0 3.5H21m-6 8h6v4h-6Zm1.5 0v-1a1.5 1.5 0 0 1 3 0v1");
}

.u87v8xayu {
  d: path("M12.154 19.5H5.5q-.123 0-.245-.012t-.243-.036q-.12-.024-.238-.06t-.231-.082t-.221-.105t-.211-.126q-.102-.069-.197-.146q-.095-.078-.182-.165t-.165-.182q-.077-.095-.146-.197t-.126-.211t-.105-.221q-.047-.114-.082-.231t-.06-.238q-.024-.121-.036-.243T3 17V6q0-.123.012-.245t.036-.243q.024-.12.06-.238t.082-.231q.047-.113.105-.221q.058-.109.126-.211q.069-.102.146-.197q.078-.095.165-.182t.182-.165t.197-.146t.211-.126q.108-.058.221-.105q.114-.047.231-.082t.238-.06q.121-.024.243-.036T5.5 3.5h13q.123 0 .245.012t.243.036t.238.06t.231.082q.113.047.221.105q.109.058.211.126q.102.069.197.146q.095.078.182.165t.165.182t.146.197t.126.211q.058.108.105.221q.047.114.082.231t.06.238t.036.243T21 6v7.473");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
