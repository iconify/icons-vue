<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y0d4p95pm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1411,"height":1557};
const content = `<path class="y0d4p95pm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:ubs-etracs" /></template>
