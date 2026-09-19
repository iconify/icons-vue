<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/u/uzrocibyu.css';
import '../../css/f/fthxges_p.css';
import '../../css/c/c6am73bhf.css';
import '../../css/g/g42dkccnc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path class="uzrocibyu"/><path class="fthxges_p"/><path clip-rule="evenodd" class="c6am73bhf"/><path clip-rule="evenodd" class="g42dkccnc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons:pinpoint-off-print" /></template>
