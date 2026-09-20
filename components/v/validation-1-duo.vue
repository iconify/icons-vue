<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dk1zpm-hn.css';
import '../../css/j/j0d7q5h2p.css';
import '../../css/m/m6e2ex0xx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":40,"height":40};
const content = `<g class="dk1zpm-hn"><path class="j0d7q5h2p"/><path class="m6e2ex0xx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-stickies-color:validation-1-duo" /></template>
