<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/y/yrn3nmbns.css';
import '../../css/l/l1p3q2bay.css';
import '../../css/l/l-fwh23rz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="yrn3nmbns"/><path class="l1p3q2bay"/><path class="l-fwh23rz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:playing-card-duotone" /></template>
