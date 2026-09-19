<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/r/ra5g_ob8l.css';
import '../../css/t/ti9ommb8x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="cuyn6tgcc"><path class="ra5g_ob8l"/><path clip-rule="evenodd" class="ti9ommb8x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:tongue" /></template>
