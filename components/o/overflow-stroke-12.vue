<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/s/sk2yvlahd.css';
import '../../css/y/y54gef5lv.css';
import '../../css/f/fw5rt46mg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<g class="cuyn6tgcc"><circle class="sk2yvlahd"/><circle class="y54gef5lv"/><circle class="fw5rt46mg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:overflow-stroke-12" /></template>
