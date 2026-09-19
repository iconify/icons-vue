<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/je4k0vbju.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="je4k0vbju"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:traffic-weather-incident" /></template>
