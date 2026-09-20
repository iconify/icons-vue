<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a4y-9qb6u.css';
import '../../css/u/u1frltaje.css';
import '../../css/f/faskdnt1b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="a4y-9qb6u"><animateTransform additive="sum" attributeName="transform" dur="6s" repeatCount="indefinite" type="translate" values="-48 0; 48 0; -48 0"/></path><path class="u1frltaje"><animateTransform additive="sum" attributeName="transform" begin="-1.5s" dur="6s" repeatCount="indefinite" type="translate" values="-48 0; 48 0; -48 0"/></path><path class="faskdnt1b"><animateTransform additive="sum" attributeName="transform" dur="6s" repeatCount="indefinite" type="translate" values="48 0; -48 0; 48 0"/></path>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="meteocons:mist" /></template>
