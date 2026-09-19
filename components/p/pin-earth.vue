<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rvsudxb6g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="rvsudxb6g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gis:pin-earth" /></template>
