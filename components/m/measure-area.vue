<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uzcxy2o3x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="uzcxy2o3x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gis:measure-area" /></template>
