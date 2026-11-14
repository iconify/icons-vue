<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="kuwx-2b8e"/><path class="ucpojdarb"/><path class="u5q3h-bce"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:sketch-journal" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.kuwx-2b8e {
  d: path("M19.5 10.873V21.5H7q-.123 0-.245-.012t-.243-.036q-.12-.024-.238-.06t-.231-.082t-.221-.105t-.211-.126q-.102-.069-.197-.146q-.095-.078-.182-.165t-.165-.182t-.146-.197t-.126-.211t-.105-.221q-.047-.114-.082-.231t-.06-.238t-.036-.243T4.5 19V5q0-.123.012-.245t.036-.243q.024-.12.06-.238t.082-.231t.105-.221q.058-.109.126-.211q.069-.102.146-.197q.078-.095.165-.182t.182-.165q.095-.077.197-.146t.211-.126q.108-.058.221-.105q.114-.047.231-.082t.238-.06q.121-.024.243-.036T7 2.5h12.5v3.373");
}

.u5q3h-bce {
  d: path("m9.659 14.023l.318.318a.794.794 0 0 1-.424 1.344a1.068 1.068 0 0 1-1.238-1.238a.794.794 0 0 1 1.344-.424");
}

.ucpojdarb {
  d: path("M4.5 19q0-.189.028-.376q.029-.186.085-.367q.056-.18.138-.35t.19-.325q.107-.156.236-.293q.13-.138.278-.255t.313-.209t.341-.161m7.764-.164H19.5m-2.788-9.566l.354.354a1.5 1.5 0 0 1 0 2.121l-4.95 4.95a1.5 1.5 0 0 1-2.121 0l-.354-.354a1.5 1.5 0 0 1 0-2.121l4.95-4.95a1.5 1.5 0 0 1 2.121 0");
}

</style>
