<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kagb8yi_r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="colorfff kagb8yi_r svgShape"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="academicons:zenodo" /></template>
