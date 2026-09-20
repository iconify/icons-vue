<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l98vq_bhi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l98vq_bhi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:weather-heavy-rain" /></template>
