<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/w/wi4bmnkdl.css';
import '../../css/p/pra_i-bub.css';
import '../../css/g/gh6r56btc.css';
import '../../css/m/mpqbsvblm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="cuyn6tgcc"><path class="wi4bmnkdl"/><path class="pra_i-bub"/><path class="gh6r56btc"/><path clip-rule="evenodd" class="mpqbsvblm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:miner-worker-alt" /></template>
