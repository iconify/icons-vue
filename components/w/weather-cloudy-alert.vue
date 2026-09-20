<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l9qs8hiyn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l9qs8hiyn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:weather-cloudy-alert" /></template>
