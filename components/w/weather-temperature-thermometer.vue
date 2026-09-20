<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/an8xsuxoe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="an8xsuxoe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:weather-temperature-thermometer" /></template>
