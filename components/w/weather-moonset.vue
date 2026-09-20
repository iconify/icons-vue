<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kaydvykfe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kaydvykfe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:weather-moonset" /></template>
