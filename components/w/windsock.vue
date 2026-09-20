<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d5ktiob-i.css';
import '../../css/z/z0yvkybcs.css';
import '../../css/x/x8u3oob-q.css';
import '../../css/r/rhtsmynlo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="d5ktiob-i"/><path class="z0yvkybcs"><animateTransform additive="sum" attributeName="transform" calcMode="spline" dur="3s" keySplines=".42, 0, .58, 1; .42, 0, .58, 1" repeatCount="indefinite" type="rotate" values="-6 99 184; 6 99 184; -6 99 184"/></path><path class="x8u3oob-q"><animateTransform additive="sum" attributeName="transform" calcMode="spline" dur="3s" keySplines=".42, 0, .58, 1; .42, 0, .58, 1" repeatCount="indefinite" type="rotate" values="-6 99 184; 6 99 184; -6 99 184"/><animateTransform additive="sum" attributeName="transform" calcMode="spline" dur="1.5s" keySplines=".42, 0, .58, 1; .42, 0, .58, 1" repeatCount="indefinite" type="translate" values="0 0; 5 0; 0 0"/></path><path class="rhtsmynlo"><animateTransform additive="sum" attributeName="transform" calcMode="spline" dur="3s" keySplines=".42, 0, .58, 1; .42, 0, .58, 1" repeatCount="indefinite" type="rotate" values="-6 99 184; 6 99 184; -6 99 184"/><animateTransform additive="sum" attributeName="transform" calcMode="spline" dur="1.5s" keySplines=".42, 0, .58, 1; .42, 0, .58, 1" repeatCount="indefinite" type="translate" values="0 0; 10 0; 0 0"/></path>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="meteocons:windsock" /></template>
