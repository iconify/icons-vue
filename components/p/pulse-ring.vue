<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lm2moacxj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path transform="matrix(0 0 0 0 12 12)" class="lm2moacxj"><animateTransform attributeName="transform" calcMode="spline" dur="1.2s" keySplines=".52,.6,.25,.99" repeatCount="indefinite" type="translate" values="12 12;0 0"/><animateTransform additive="sum" attributeName="transform" calcMode="spline" dur="1.2s" keySplines=".52,.6,.25,.99" repeatCount="indefinite" type="scale" values="0;1"/><animate attributeName="opacity" calcMode="spline" dur="1.2s" keySplines=".52,.6,.25,.99" repeatCount="indefinite" values="1;0"/></path>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="svg-spinners:pulse-ring" /></template>
