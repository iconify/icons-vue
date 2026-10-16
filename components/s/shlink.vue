<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n9ybb-cwt.css';
import '../../css/y/yfzrx8bbn.css';
import '../../css/h/h461_iiso.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<g class="n9ybb-cwt"><path class="yfzrx8bbn"/><path class="h461_iiso"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:shlink" /></template>
