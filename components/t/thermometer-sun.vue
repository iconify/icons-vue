<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rl4i8_zfy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rl4i8_zfy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:thermometer-sun" /></template>
