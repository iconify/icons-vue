<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oes8zp1_h.css';
import '../../css/z/zw46xpt_r.css';
import '../../css/h/h2pk78obw.css';
import '../../css/z/z1xnbn1qu.css';
import '../../css/m/miwmk1bpe.css';
import '../../css/a/a23qqrb9t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<defs><symbol id="SVGktimpeOD" viewBox="0 0 138 96"><path class="oes8zp1_h"><animate attributeName="stroke-dashoffset" dur="6s" repeatCount="indefinite" values="0; 1274"/></path><path class="zw46xpt_r"><animate attributeName="stroke-dashoffset" dur="6s" repeatCount="indefinite" values="0; 857"/></path></symbol></defs><path class="h2pk78obw"/><g transform="rotate(45 256 256)"><g class="z1xnbn1qu"><path class="miwmk1bpe"/><path class="a23qqrb9t"/></g><animateTransform additive="sum" attributeName="transform" calcMode="spline" dur="6s" keySplines=".42, 0, .58, 1; .42, 0, .58, 1" repeatCount="indefinite" type="scale" values="1 1; .9 1.1; 1 1"/><animateTransform additive="sum" attributeName="transform" calcMode="spline" dur="6s" keySplines=".42, 0, .58, 1; .42, 0, .58, 1" repeatCount="indefinite" type="translate" values="0 0; 29 -14; 0 0"/></g><use width="138" height="96" href="#SVGktimpeOD" transform="translate(62.5 201)"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="meteocons:umbrella-wind" /></template>
