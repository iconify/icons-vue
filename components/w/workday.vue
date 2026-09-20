<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/f/fz4g6ybxa.css';
import '../../css/g/gvilvubwg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<g class="ft5dv1b6b"><path class="fz4g6ybxa"/><path class="gvilvubwg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:workday" /></template>
