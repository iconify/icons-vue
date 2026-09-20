<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vs38770rt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vs38770rt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:weather-sunny" /></template>
