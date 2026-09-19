<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h01tyzbfu.css';
import '../../css/l/lofmxcb-i.css';
import '../../css/e/e-dxg-xyc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<g class="h01tyzbfu"><path class="lofmxcb-i"/><rect class="e-dxg-xyc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:thumbs-up-stroke-12" /></template>
