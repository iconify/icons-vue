<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="fcw7y0bgt"/><path class="u7dp50bbg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:metadata-nft" /></template>
<style>
.fcw7y0bgt {
  d: path("M11.584 19.5H6q-.123 0-.245-.012t-.243-.036q-.12-.024-.238-.06t-.231-.082t-.221-.105t-.211-.126q-.102-.069-.197-.146q-.095-.078-.182-.165t-.165-.182t-.146-.197t-.126-.211t-.105-.221q-.047-.114-.082-.231t-.06-.238q-.024-.121-.036-.243T3.5 17V5q0-.123.012-.245t.036-.243q.024-.12.06-.238t.082-.231q.047-.113.105-.221q.058-.109.126-.211q.069-.102.146-.197q.078-.095.165-.182t.182-.165q.095-.077.197-.146t.211-.126q.108-.058.221-.105q.114-.047.231-.082t.238-.06q.121-.024.243-.036T6 2.5h6.5l4 4v4.543");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.u7dp50bbg {
  d: path("M12.5 2.5v4h4m-10 3h5m-5 4H10m5.541.404l1.671-.105a1.75 1.75 0 0 1 1.346.509l1.705 1.705a1.75 1.75 0 0 1 0 2.474l-1.776 1.776a1.75 1.75 0 0 1-2.474 0l-1.705-1.705a1.75 1.75 0 0 1-.509-1.346l.105-1.671a1.75 1.75 0 0 1 1.637-1.637m1.709 3.346h.01");
}

</style>
