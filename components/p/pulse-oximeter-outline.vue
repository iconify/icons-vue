<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/c/cwxjm2ojj.css';
import '../../css/n/nh70ojbcn.css';
import '../../css/j/jkczbp70i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="cwxjm2ojj"/><path class="nh70ojbcn"/><path clip-rule="evenodd" class="jkczbp70i"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:pulse-oximeter-outline" /></template>
