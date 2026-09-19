<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sss_nfbgc.css';
import '../../css/b/bztkctbob.css';
import '../../css/m/m-wjl1bwa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<g class="sss_nfbgc"><path class="bztkctbob"/><path class="m-wjl1bwa"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gis:simplify" /></template>
