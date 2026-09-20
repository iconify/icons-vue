<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/t/tmsthrbjy.css';
import '../../css/c/cns6ly1bg.css';
import '../../css/p/pqsrmgrdx.css';
import '../../css/h/hqsaabc6g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="tmsthrbjy"/><path class="cns6ly1bg"/><path class="pqsrmgrdx"/><path class="hqsaabc6g"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:pills-3-broken" /></template>
