<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bxfufab8j.css';
import '../../css/p/pjmwtvb9n.css';
import '../../css/x/xojozel9z.css';
import '../../css/c/c-vpkna0u.css';
import '../../css/e/exawh0bsk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="bxfufab8j"><animateTransform additive="sum" attributeName="transform" calcMode="spline" dur="3s" keySplines=".42, 0, .58, 1; .42, 0, .58, 1" repeatCount="indefinite" type="translate" values="-12 0; 12 0; -12 0"/></path><path class="pjmwtvb9n"><animateTransform additive="sum" attributeName="transform" calcMode="spline" dur="3s" keySplines=".42, 0, .58, 1; .42, 0, .58, 1" repeatCount="indefinite" type="translate" values="-24 0; 24 0; -24 0"/></path><path class="xojozel9z"><animateTransform additive="sum" attributeName="transform" calcMode="spline" dur="3s" keySplines=".42, 0, .58, 1; .42, 0, .58, 1" repeatCount="indefinite" type="translate" values="-36 0; 36 0; -36 0"/></path><path class="c-vpkna0u"><animateTransform additive="sum" attributeName="transform" calcMode="spline" dur="3s" keySplines=".42, 0, .58, 1; .42, 0, .58, 1" repeatCount="indefinite" type="translate" values="-48 0; 48 0; -48 0"/></path><path class="exawh0bsk"><animateTransform additive="sum" attributeName="transform" calcMode="spline" dur="3s" keySplines=".42, 0, .58, 1; .42, 0, .58, 1" repeatCount="indefinite" type="translate" values="-60 0; 60 0; -60 0"/></path>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="meteocons:tornado" /></template>
