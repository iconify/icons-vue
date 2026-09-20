<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/u/u3vs50bgi.css';
import '../../css/k/kv8gt_bsu.css';
import '../../css/i/ib4otfp4a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="u3vs50bgi"/><path class="kv8gt_bsu"/><path clip-rule="evenodd" class="ib4otfp4a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:music-slider-duotone" /></template>
