<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/f/fc7gr3bdl.css';
import '../../css/p/pra_i-bub.css';
import '../../css/g/gh6r56btc.css';
import '../../css/q/qloxnbbrs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="fc7gr3bdl"/><path class="pra_i-bub"/><path class="gh6r56btc"/><path clip-rule="evenodd" class="qloxnbbrs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:miner-worker-alt-outline" /></template>
