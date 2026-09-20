<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/r/rz61hplvb.css';
import '../../css/b/bmknc5bwv.css';
import '../../css/m/mpuuhxylu.css';
import '../../css/h/h_tskvb-r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="rz61hplvb"/><path clip-rule="evenodd" class="bmknc5bwv"/><path class="mpuuhxylu"/><path class="h_tskvb-r"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:translation-2-bold" /></template>
