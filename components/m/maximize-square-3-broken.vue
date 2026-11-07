<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/w/wn1mmp0fq.css';
import '../../css/h/hb6t3lb4p.css';
import '../../css/y/yqghi_b_r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="wn1mmp0fq"/><path class="hb6t3lb4p"/><path class="yqghi_b_r"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:maximize-square-3-broken" /></template>
