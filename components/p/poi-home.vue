<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i8x4b0bmi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="i8x4b0bmi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gis:poi-home" /></template>
