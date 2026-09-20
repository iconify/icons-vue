<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/j/j5n9j3vfq.css';
import '../../css/t/trdem2e-g.css';
import '../../css/z/zrf-ivbpw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="j5n9j3vfq"/><path class="trdem2e-g"/><path class="zrf-ivbpw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:square-arrows-down-duotone" /></template>
