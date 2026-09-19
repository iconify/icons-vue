<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/f/fbehgn6qb.css';
import '../../css/g/gt4fqkosk.css';
import '../../css/e/eiaq64bmn.css';
import '../../css/f/fajoa5bmp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="fbehgn6qb"/><path class="gt4fqkosk"/><path clip-rule="evenodd" class="eiaq64bmn"/><path class="fajoa5bmp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:military-worker" /></template>
