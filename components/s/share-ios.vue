<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/b/b5ghrabne.css';
import '../../css/t/tn7wo2bci.css';
import '../../css/u/ub6dgxt8m.css';
import '../../css/i/irtma8bnv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="b5ghrabne"/><path class="tn7wo2bci"/><path class="ub6dgxt8m"/><path class="irtma8bnv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-print:share-ios" /></template>
