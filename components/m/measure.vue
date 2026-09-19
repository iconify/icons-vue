<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ib604zbkn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="ib604zbkn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gis:measure" /></template>
