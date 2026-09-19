<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nz_20wbpz.css';
import '../../css/m/mnh5f9zfq.css';
import '../../css/o/ocruyxbsi.css';
import '../../css/h/hpyym12cz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="nz_20wbpz"><rect class="mnh5f9zfq"/><path class="ocruyxbsi"/><rect class="hpyym12cz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:spoon" /></template>
