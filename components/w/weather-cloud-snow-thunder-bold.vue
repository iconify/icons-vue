<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vft_ecclt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vft_ecclt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:weather-cloud-snow-thunder-bold" /></template>
