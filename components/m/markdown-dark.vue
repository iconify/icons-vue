<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ff__zcblq.css';
import '../../css/q/qsplvob1b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":208,"height":128};
const content = `<path class="ff__zcblq"/><path class="qsplvob1b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:markdown-dark" /></template>
