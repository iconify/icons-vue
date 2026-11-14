<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mvbyf4bwp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:xr-dev-mode" /></template>
<style>
.mvbyf4bwp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M15.554 14.5H13.25l-1.75-2.75h-2L7.75 14.5H4.5q-.123 0-.245-.012t-.243-.036q-.12-.024-.238-.06t-.231-.082q-.113-.047-.221-.105q-.109-.058-.211-.126q-.102-.069-.197-.146q-.095-.078-.182-.165t-.165-.182q-.077-.095-.146-.197t-.126-.211q-.058-.108-.105-.221q-.047-.114-.082-.231t-.06-.238q-.024-.121-.036-.243T2 12V6q0-.123.012-.245t.036-.243q.024-.12.06-.238t.082-.231q.047-.113.105-.221q.058-.109.126-.211q.069-.102.146-.197q.078-.095.165-.182t.182-.165t.197-.146t.211-.126t.221-.105q.114-.047.231-.082t.238-.06q.121-.024.243-.036T4.5 3.5h12q.123 0 .245.012t.243.036t.238.06t.231.082q.113.047.221.105q.109.058.211.126q.102.069.197.146q.095.078.182.165t.165.182t.146.197t.126.211q.058.108.105.221q.047.114.082.231t.06.238t.036.243T19 6v6q0 .147-.017.293t-.052.29q-.034.143-.085.281t-.118.269t-.148.254t-.177.234t-.203.212t-.227.187M17 17l-2.25 2.25L17 21.5m2.25-4.5l2.25 2.25l-2.25 2.25");
}

</style>
