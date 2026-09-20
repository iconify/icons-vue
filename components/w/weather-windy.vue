<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ap5g_-gyo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ap5g_-gyo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="typcn:weather-windy" /></template>
