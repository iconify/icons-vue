<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/m/mab2rwb6t.css';
import '../../css/q/qv3mdbcpi.css';
import '../../css/q/q3s-uuc5p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="mab2rwb6t"/><path class="qv3mdbcpi"/><path clip-rule="evenodd" class="q3s-uuc5p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:suspension-x-duotone" /></template>
