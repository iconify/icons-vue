<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k-bb6ccxt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<rect transform="translate(55.328 -99820.702)scale(96.7529)" class="k-bb6ccxt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bpmn:task" /></template>
