<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tkfw2ofxh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="tkfw2ofxh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency:wbtc" /></template>
