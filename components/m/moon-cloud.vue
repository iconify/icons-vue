<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mqze3xboy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:moon-cloud" /></template>
<style>
.mqze3xboy {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10.616 7.733q.007-.23.032-.459t.07-.455t.109-.447t.145-.437q.081-.215.181-.423t.215-.406q.117-.199.249-.387q.133-.188.281-.365q.148-.176.31-.34t.337-.313t.363-.284q.187-.134.384-.252q.198-.118.405-.219t.421-.185t.436-.149q.22-.065.446-.112q-.068.169-.123.343t-.098.351q-.042.177-.072.357t-.045.362t-.019.363q-.003.183.007.365t.034.362q.023.181.06.36q.037.178.086.354q.05.175.112.347t.136.337q.075.167.161.327q.087.161.185.315q.098.153.206.3q.109.146.228.284t.248.267t.267.248t.284.228t.3.206t.315.185q.16.086.327.161q.166.074.337.136t.347.112q.176.049.354.086q.179.037.36.06q.18.024.362.034t.365.007t.363-.019q.182-.016.362-.045q.18-.03.357-.072q.177-.043.351-.098T21.5 9q-.107.516-.309 1.002q-.203.486-.494.925t-.66.814t-.803.675M5.5 21a3.5 3.5 0 0 1 0-7a4.75 4.75 0 0 1 9-.5A3.75 3.75 0 0 1 15 21Z");
}

</style>
