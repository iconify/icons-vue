<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/g/ggc5c-1wb.css';
import '../../css/b/bgrw82b0m.css';
import '../../css/w/waj9yrbya.css';
import '../../css/b/bgvt5lblx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="ft5dv1b6b"><path class="ggc5c-1wb"/><path class="bgrw82b0m"/><path class="waj9yrbya"/><path class="bgvt5lblx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:play-volleyball" /></template>
