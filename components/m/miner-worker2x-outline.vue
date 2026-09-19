<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/s/sywyxcrdp.css';
import '../../css/o/ozq7jpbkt.css';
import '../../css/e/ev8vc4b6a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="sywyxcrdp"/><path class="ozq7jpbkt"/><path clip-rule="evenodd" class="ev8vc4b6a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:miner-worker2x-outline" /></template>
