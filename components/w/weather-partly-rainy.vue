<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yz-9f0blo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yz-9f0blo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:weather-partly-rainy" /></template>
