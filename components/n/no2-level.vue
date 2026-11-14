<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="il5mtqyhr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:no2-level" /></template>
<style>
.il5mtqyhr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.5 6a3 3 0 1 0 6 0a3 3 0 1 0-6 0m-6.25 8a2.75 2.75 0 1 0 5.5 0a2.75 2.75 0 1 0-5.5 0m18.563-1.779q.164-.172.292-.373q.129-.2.217-.421t.133-.455t.045-.472q0-.123-.012-.245t-.036-.243q-.024-.12-.06-.238t-.082-.231t-.105-.221t-.126-.211q-.069-.102-.146-.197q-.078-.095-.165-.182t-.182-.165t-.197-.146t-.211-.126t-.221-.105q-.114-.047-.231-.082t-.238-.06q-.121-.024-.243-.036T19 8t-.245.012t-.243.036t-.238.06q-.117.035-.231.082q-.113.047-.221.105q-.109.058-.211.126q-.102.069-.197.146q-.095.078-.182.165t-.165.182t-.146.197t-.126.211t-.105.221q-.047.114-.082.231t-.06.238t-.036.243t-.012.245t.012.245t.036.243q.024.12.06.238t.082.231t.105.221t.126.211q.069.102.146.197q.078.095.165.182t.182.165t.197.146t.211.126t.221.105q.114.047.231.082t.238.06q.121.024.243.036T19 13q.177 0 .353-.025M9.5 8.5l-2.75 3.25M14 7.5l2.75 1.75m-1 12.25V19m2.75 2.5V17m2.75 4.5V15");
}

</style>
