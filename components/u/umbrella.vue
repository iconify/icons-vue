<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z2shf1bna.css';
import '../../css/w/w0pnhi9xs.css';
import '../../css/k/kk5pombug.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="z2shf1bna"/><g><path class="w0pnhi9xs"/><path class="kk5pombug"/><animateTransform additive="sum" attributeName="transform" calcMode="spline" dur="6s" keySplines=".42, 0, .58, 1; .42, 0, .58, 1" repeatCount="indefinite" type="scale" values="1 1; .9 1.1; 1 1"/><animateTransform additive="sum" attributeName="transform" calcMode="spline" dur="6s" keySplines=".42, 0, .58, 1; .42, 0, .58, 1" repeatCount="indefinite" type="translate" values="0 0; 29 -14; 0 0"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="meteocons:umbrella" /></template>
