<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="rgr2-10cm"/><path class="giehpgcsc"/><path class="xoid_8bxw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:podcast-episode-plus" /></template>
<style>
.giehpgcsc {
  d: path("M6.25 13a5 5 0 1 1 8.5 0");
}

.rgr2-10cm {
  d: path("M8.5 10.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xoid_8bxw {
  d: path("M3 13.25q-.084-.226-.154-.456q-.07-.231-.126-.465t-.098-.471t-.069-.477t-.041-.48t-.012-.481t.017-.481t.047-.479q.03-.239.074-.476q.045-.237.104-.47q.059-.234.131-.463q.073-.23.159-.455t.187-.444q.099-.219.212-.432t.238-.418q.126-.206.263-.404q.138-.197.287-.386q.149-.19.309-.369q.161-.18.331-.35q.171-.17.352-.329t.371-.307t.388-.285t.405-.26q.206-.125.42-.236q.213-.112.433-.21q.22-.099.445-.184t.455-.156t.464-.129t.471-.101t.476-.072t.48-.043t.481-.015q.224 0 .448.013t.447.037t.444.063q.221.038.44.087q.218.05.434.112t.427.136t.419.16t.41.183t.398.206t.386.227q.19.12.373.249q.183.13.359.27q.175.14.342.289t.326.308t.309.325q.149.168.289.343t.27.358t.249.373q.12.189.229.386q.108.196.206.398t.183.409t.161.419q.074.211.136.427q.062.215.113.434q.05.218.088.44q.037.221.063.443q.025.223.038.447t.013.448t-.012.449t-.037.447t-.062.444t-.087.44M10.5 15.5v6M18 15v6m-3-3h6");
}

</style>
