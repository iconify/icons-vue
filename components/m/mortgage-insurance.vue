<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wxq231b7d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:mortgage-insurance" /></template>
<style>
.wxq231b7d {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m3.506 9.936l8-7q.051-.045.109-.08q.058-.034.121-.058t.13-.036T12 2.75t.134.012t.13.036t.121.058q.058.035.109.08l8 7q.122.106.189.254t.067.31v3.229l-1.981-.825q-.183-.076-.377-.115T18 12.75t-.392.039t-.377.115l-3 1.25q-.136.056-.262.132q-.127.076-.24.17q-.114.094-.213.203t-.18.232t-.145.255t-.105.274q-.043.141-.064.287T13 16v2.25q0 1.382.645 2.5H6q-2.75 0-2.75-2.75v-7.5q0-.162.067-.31t.189-.254m14.782 4.122l3 1.25q.103.042.189.113q.085.071.147.163t.094.199t.032.217v2.25q0 2.709-3.455 4.189q-.141.061-.295.061t-.295-.061q-3.455-1.48-3.455-4.189V16q0-.111.032-.217q.032-.107.094-.199t.147-.163t.189-.113l3-1.25Q17.85 14 18 14t.288.058M15.75 16.5v1.75q0 1.617 2.25 2.678q2.25-1.061 2.25-2.678V16.5L18 15.563zm2.25.417l-1 .416v.917q0 .67 1 1.267q1-.597 1-1.267v-.917z");
}

</style>
