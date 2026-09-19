<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mx0j3m0za.css';
import '../../css/c/cpk8xwb9i.css';
import '../../css/x/xhdogwbyc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="mx0j3m0za"><path class="cpk8xwb9i"/><path class="xhdogwbyc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:screwdriver-bold" /></template>
