<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/s/s9rkou0mf.css';
import '../../css/m/m_ogqzi-d.css';
import '../../css/v/vjc3f2jdt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="s9rkou0mf"/><path class="m_ogqzi-d"/><path clip-rule="evenodd" class="vjc3f2jdt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:spray-outline" /></template>
