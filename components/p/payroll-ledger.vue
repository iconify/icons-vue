<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="r_x9t5c9g"/><path class="conkmvb8n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:payroll-ledger" /></template>
<style>
.conkmvb8n {
  d: path("M4.5 19q0-.123.012-.245t.036-.243t.06-.238t.082-.231q.047-.113.105-.221q.058-.109.126-.211q.069-.102.146-.197q.078-.095.165-.182t.182-.165t.197-.146t.211-.126q.108-.058.221-.105q.114-.047.231-.082t.238-.06t.243-.036T7 16.5h6.573m.927 4.75c0-1.5 1.5-2.5 3.5-2.5s3.5 1 3.5 2.5c0 .25-.25.5-.5.5h-6c-.25 0-.5-.25-.5-.5Zm1.75-6a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0Z");
}

.r_x9t5c9g {
  d: path("M11.727 21.5H7q-.123 0-.245-.012t-.243-.036q-.12-.024-.238-.06t-.231-.082t-.221-.105t-.211-.126q-.102-.069-.197-.146q-.095-.078-.182-.165t-.165-.182t-.146-.197t-.126-.211t-.105-.221q-.047-.114-.082-.231t-.06-.238t-.036-.243T4.5 19V5q0-.123.012-.245t.036-.243q.024-.12.06-.238t.082-.231t.105-.221q.058-.109.126-.211q.069-.102.146-.197q.078-.095.165-.182t.182-.165q.095-.077.197-.146t.211-.126q.108-.058.221-.105q.114-.047.231-.082t.238-.06q.121-.024.243-.036T7 2.5h12.5v8.473");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
