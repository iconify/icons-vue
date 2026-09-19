<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i5eoifbgr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="i5eoifbgr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:weather-front-cold" /></template>
