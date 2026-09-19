<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/l/l6y8wvbql.css';
import '../../css/t/t1_lhjnns.css';
import '../../css/i/ifa6tqr9c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="l6y8wvbql"/><path class="t1_lhjnns"/><path class="ifa6tqr9c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:tree-05" /></template>
