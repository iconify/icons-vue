<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n1lsf0bnc.css';
import '../../css/g/g1mq_3eus.css';
import '../../css/x/xln0-bxve.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="n1lsf0bnc"><path class="g1mq_3eus"/><path class="xln0-bxve"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency:pink" /></template>
