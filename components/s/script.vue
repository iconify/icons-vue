<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uhxs1y3oh.css';
import '../../css/h/hvw76hbuq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="uhxs1y3oh"/><path class="hvw76hbuq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:script" /></template>
