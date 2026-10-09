<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yox-1ubct.css';
import '../../css/w/wqshwfdjv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="yox-1ubct"/><path class="wqshwfdjv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:tidal-barrage-20-bold" /></template>
