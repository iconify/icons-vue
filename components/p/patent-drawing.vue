<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="c6ntlbb9i"/><path class="uaen0lila"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:patent-drawing" /></template>
<style>
.c6ntlbb9i {
  d: path("M12.112 21.5H7q-.123 0-.245-.012t-.243-.036q-.12-.024-.238-.06t-.231-.082t-.221-.105t-.211-.126q-.102-.069-.197-.146q-.095-.078-.182-.165t-.165-.182t-.146-.197t-.126-.211t-.105-.221q-.047-.114-.082-.231t-.06-.238t-.036-.243T4.5 19V5q0-.123.012-.245t.036-.243q.024-.12.06-.238t.082-.231t.105-.221q.058-.109.126-.211q.069-.102.146-.197q.078-.095.165-.182t.182-.165q.095-.077.197-.146t.211-.126q.108-.058.221-.105q.114-.047.231-.082t.238-.06q.121-.024.243-.036T7 2.5h6.5l6 6v3.315");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.uaen0lila {
  d: path("M13.5 2.5v4a2 2 0 0 0 2 2h4m-12.25 3a2.75 2.75 0 1 0 5.5 0a2.75 2.75 0 1 0-5.5 0m7.5 8.5l.171-1.026a1.5 1.5 0 0 1 .419-.814l3.099-3.099a1.5 1.5 0 0 1 2.122 0l.378.378a1.5 1.5 0 0 1 0 2.122L17.84 20.66a1.5 1.5 0 0 1-.814.419L16 21.25A1.086 1.086 0 0 1 14.75 20");
}

</style>
