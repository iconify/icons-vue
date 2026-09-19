<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qnr2jccom.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="qnr2jccom"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gis:story-map" /></template>
