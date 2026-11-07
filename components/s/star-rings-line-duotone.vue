<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/k/k1cjlz8kf.css';
import '../../css/e/ea230sxql.css';
import '../../css/n/njjolibwa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="k1cjlz8kf"/><path class="ea230sxql"/><path class="njjolibwa"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:star-rings-line-duotone" /></template>
