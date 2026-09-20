<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ktku_nbzg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ktku_nbzg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:weather-time" /></template>
