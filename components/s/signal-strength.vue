<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/j/jia142bum.css';
import '../../css/i/i_3be54om.css';
import '../../css/n/n8xhjmb-g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="ft5dv1b6b"><path class="jia142bum"/><path class="i_3be54om"/><path class="n8xhjmb-g"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:signal-strength" /></template>
