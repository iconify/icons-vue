<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="pokwh3bed"/><path class="giehpgcsc"/><path class="cnmwxjbwd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:podcast-episode-share" /></template>
<style>
.cnmwxjbwd {
  d: path("M3 13.25q-.084-.226-.154-.456q-.07-.231-.126-.465t-.098-.471t-.069-.477t-.041-.48t-.012-.481t.017-.481t.047-.479q.03-.239.074-.476q.045-.237.104-.47q.059-.234.131-.463q.073-.23.159-.455t.187-.444q.099-.219.212-.432t.238-.418q.126-.206.263-.404q.138-.197.287-.386q.149-.19.309-.369q.161-.18.331-.35q.171-.17.352-.329t.371-.307t.388-.285t.405-.26q.206-.125.42-.236q.213-.112.433-.21q.22-.099.445-.184t.455-.156t.464-.129t.471-.101t.476-.072t.48-.043t.481-.015q.232 0 .463.014q.232.013.462.04t.459.067t.453.093q.226.053.448.119q.222.067.44.146t.431.17t.421.195t.408.219t.395.243t.38.265q.187.137.365.286t.347.307t.329.327q.159.168.309.345q.149.177.289.362q.139.186.267.379t.245.393t.222.407t.197.419q.093.213.174.43q.08.218.148.439q.067.222.122.447q.055.226.096.454q.042.228.07.458t.043.461t.017.463t-.011.464q-.012.231-.037.462q-.025.23-.064.459q-.038.228-.09.454t-.117.449M10.5 15.5v6M15 21l5.25-5.25m-4-.25h4.25v4.25");
}

.giehpgcsc {
  d: path("M6.25 13a5 5 0 1 1 8.5 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.pokwh3bed {
  d: path("M8.5 10.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0");
}

</style>
