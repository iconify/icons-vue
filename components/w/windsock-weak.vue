<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d5ktiob-i.css';
import '../../css/t/t3uqx1qva.css';
import '../../css/f/fp0sg7bcx.css';
import '../../css/b/bkv6t-b9r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="d5ktiob-i"/><path class="t3uqx1qva"><animateTransform additive="sum" attributeName="transform" calcMode="spline" dur="3s" keySplines=".42, 0, .58, 1; .42, 0, .58, 1" repeatCount="indefinite" type="rotate" values="0 204 183; -3 204 183; 0 204 183"/><animateTransform additive="sum" attributeName="transform" calcMode="spline" dur="3s" keySplines=".42, 0, .58, 1; .42, 0, .58, 1" repeatCount="indefinite" type="translate" values="0 0; 1 -2; 0 0"/></path><path class="fp0sg7bcx"><animateTransform additive="sum" attributeName="transform" calcMode="spline" dur="3s" keySplines=".42, 0, .58, 1; .42, 0, .58, 1" repeatCount="indefinite" type="rotate" values="0 249 222; -6 249 222; 0 249 222"/><animateTransform additive="sum" attributeName="transform" calcMode="spline" dur="3s" keySplines=".42, 0, .58, 1; .42, 0, .58, 1" repeatCount="indefinite" type="translate" values="0 0; 5 -7; 0 0"/></path><path class="bkv6t-b9r"><animateTransform additive="sum" attributeName="transform" calcMode="spline" dur="3s" keySplines=".42, 0, .58, 1; .42, 0, .58, 1" repeatCount="indefinite" type="rotate" values="0 279 269; -9 279 269; 0 279 269"/><animateTransform additive="sum" attributeName="transform" calcMode="spline" dur="3s" keySplines=".42, 0, .58, 1; .42, 0, .58, 1" repeatCount="indefinite" type="translate" values="0 0; 17 -12; 0 0"/></path>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="meteocons:windsock-weak" /></template>
