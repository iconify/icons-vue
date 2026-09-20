<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/upm3vqb1d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="upm3vqb1d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:weather-cloud-sun-fine" /></template>
