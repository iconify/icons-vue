<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/h/hqpl1bcby.css';
import '../../css/y/yc8xgkbyw.css';
import '../../css/e/ed-q8abvo.css';
import '../../css/h/hqsaabc6g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="hqpl1bcby"/><path class="yc8xgkbyw"/><path class="ed-q8abvo"/><path class="hqsaabc6g"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:pills-3-linear" /></template>
