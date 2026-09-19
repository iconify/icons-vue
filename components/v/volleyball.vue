<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y3dpzbtra.css';
import '../../css/m/m9104igsh.css';
import '../../css/w/w455zy2rh.css';
import '../../css/h/h-qhc362c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="y3dpzbtra"><path class="m9104igsh"/><path class="w455zy2rh"/><path class="h-qhc362c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:volleyball" /></template>
