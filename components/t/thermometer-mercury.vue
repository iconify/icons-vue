<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h01-jxany.css';
import '../../css/e/e7304gbzl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<defs><symbol id="SVGFjSUBeLT" viewBox="0 0 72 168"><circle class="h01-jxany"/><path class="e7304gbzl"/></symbol></defs><use width="72" height="168" href="#SVGFjSUBeLT" transform="translate(220 205)"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="meteocons:thermometer-mercury" /></template>
