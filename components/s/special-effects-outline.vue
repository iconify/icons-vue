<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/l/l12u5k3ye.css';
import '../../css/i/ibs-b3bnk.css';
import '../../css/u/un073yd9d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="l12u5k3ye"/><path class="ibs-b3bnk"/><path clip-rule="evenodd" class="un073yd9d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:special-effects-outline" /></template>
