<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hit3bi0-v.css';
import '../../css/y/ynmj3tykv.css';
import '../../css/q/qyeqm8boe.css';
import '../../css/v/vv2y0abry.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="hit3bi0-v"><path class="ynmj3tykv"/><path class="qyeqm8boe"/><path class="vv2y0abry"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:u-disk" /></template>
