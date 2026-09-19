<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vl4ivtbit.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="vl4ivtbit"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:weather-front-warm" /></template>
