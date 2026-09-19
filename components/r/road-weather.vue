<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jq7dzc16m.css';
import '../../css/e/e_cwsjbhd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="jq7dzc16m"/><path class="e_cwsjbhd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:road-weather" /></template>
