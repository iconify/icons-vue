<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f4nvl3pqt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f4nvl3pqt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:weather-night" /></template>
