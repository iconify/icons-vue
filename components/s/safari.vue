<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jx0p4fbya.css';
import '../../css/q/qbqs7jbro.css';
import '../../css/w/websu8mzr.css';
import '../../css/g/gxt617bhz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="qbqs7jbro"/><path class="websu8mzr"/><path class="gxt617bhz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:safari" /></template>
