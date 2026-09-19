<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wtr2jecan.css';
import '../../css/h/hom3--61e.css';
import '../../css/y/yfls4paib.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":14};
const content = `<path class="wtr2jecan"/><path class="hom3--61e"/><path class="yfls4paib"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="formkit:uploadcloud" /></template>
