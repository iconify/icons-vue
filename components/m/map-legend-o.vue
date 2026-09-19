<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y7h9c3bom.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="y7h9c3bom"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gis:map-legend-o" /></template>
