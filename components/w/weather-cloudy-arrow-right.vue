<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bsrfxxbcd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bsrfxxbcd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:weather-cloudy-arrow-right" /></template>
