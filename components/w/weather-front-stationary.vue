<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qauhaqiob.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="qauhaqiob"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:weather-front-stationary" /></template>
