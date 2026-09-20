<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vwr_azbnc.css';
import '../../css/h/hzhb0bcwn.css';
import '../../css/j/jhtplst3i.css';
import '../../css/t/tsuhnpbzy.css';
import '../../css/w/wdh_whbyu.css';
import '../../css/i/i04lqib5p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="vwr_azbnc"/><g class="hzhb0bcwn"><rect class="jhtplst3i"/><circle class="tsuhnpbzy"/><path class="wdh_whbyu"/><path class="i04lqib5p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:wireless" /></template>
