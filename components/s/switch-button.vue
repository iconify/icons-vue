<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ufeehvblu.css';
import '../../css/f/fb3tv3bfw.css';
import '../../css/o/o3gfejbmt.css';
import '../../css/m/ma9v-ebqy.css';
import '../../css/t/tpuugf0vy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="ufeehvblu"><path class="fb3tv3bfw"/><path class="o3gfejbmt"/><path class="ma9v-ebqy"/><path class="tpuugf0vy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:switch-button" /></template>
