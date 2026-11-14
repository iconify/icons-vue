<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="r76u_5jze"/><path class="qfz86qebg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:response-due" /></template>
<style>
.qfz86qebg {
  d: path("M15 15.5h6v5.75h-6Zm0 2.25h6m-4.25-3.25V16m2.5-1.5V16");
}

.r76u_5jze {
  d: path("M12.154 18H9.5l-4 3.5V18H5q-.123 0-.245-.012t-.243-.036q-.12-.024-.238-.06t-.231-.082t-.221-.105t-.211-.126q-.102-.069-.197-.146q-.095-.078-.182-.165t-.165-.182q-.077-.095-.146-.197t-.126-.211t-.105-.221q-.047-.114-.082-.231t-.06-.238q-.024-.121-.036-.243T2.5 15.5v-10q0-.123.012-.245t.036-.243q.024-.12.06-.238t.082-.231q.047-.113.105-.221q.058-.109.126-.211q.069-.102.146-.197q.078-.095.165-.182t.182-.165q.095-.077.197-.146t.211-.126t.221-.105q.114-.047.231-.082t.238-.06q.121-.024.243-.036T5 3h14q.123 0 .245.012t.243.036t.238.06t.231.082q.113.047.221.105q.109.058.211.126q.102.069.197.146q.095.078.182.165t.165.182t.146.197t.126.211q.058.108.105.221q.047.114.082.231t.06.238t.036.243t.012.245v6.173M8 10.5h.01m3.99 0h.01m3.99 0h.01");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
