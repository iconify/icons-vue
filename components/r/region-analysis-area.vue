<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fcnawdb5g.css';
import '../../css/t/tkku46-oc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<defs/><path class="fcnawdb5g"/><path class="tkku46-oc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:region-analysis-area" /></template>
