<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v50fc2bsh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v50fc2bsh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:weather-moonset-down" /></template>
