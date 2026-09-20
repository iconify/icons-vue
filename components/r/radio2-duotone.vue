<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/k/kdpl1_b6g.css';
import '../../css/n/nxl56yepe.css';
import '../../css/h/h5aa40bhg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="kdpl1_b6g"/><path clip-rule="evenodd" class="nxl56yepe"/><path class="h5aa40bhg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:radio2-duotone" /></template>
