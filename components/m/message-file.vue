<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="st061pbve"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:message-file" /></template>
<style>
.st061pbve {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M17 15.746v.754q0 .123-.012.245t-.036.243t-.06.238t-.082.231q-.047.113-.105.221q-.058.109-.126.211q-.069.102-.146.197q-.078.095-.165.182t-.182.165t-.197.146t-.211.126t-.221.105q-.114.047-.231.082t-.238.06t-.243.036T14.5 19h-5L6 21.5V19H5q-.123 0-.245-.012t-.243-.036q-.12-.024-.238-.06t-.231-.082t-.221-.105t-.211-.126q-.102-.069-.197-.146q-.095-.078-.182-.165t-.165-.182q-.077-.095-.146-.197t-.126-.211t-.105-.221q-.047-.114-.082-.231t-.06-.238q-.024-.121-.036-.243T2.5 16.5v-6q0-.123.012-.245t.036-.243q.024-.12.06-.238t.082-.231q.047-.113.105-.221q.058-.109.126-.211q.069-.102.146-.197q.078-.095.165-.182t.182-.165t.197-.146t.211-.126t.221-.105q.114-.047.231-.082t.238-.06q.121-.024.243-.036T5 8h7.173M21 5.5V10a3 3 0 0 1-6 0V4.75a1.875 1.875 0 0 1 3.75 0V9.5");
}

</style>
