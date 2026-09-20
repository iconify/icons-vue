<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ew4z5r.css';
import '../../css/d/d-z279dq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ew4z5r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="line-md:weather-cloudy-loop" /></template>
