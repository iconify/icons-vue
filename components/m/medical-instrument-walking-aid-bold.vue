<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fy6kykofr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fy6kykofr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:medical-instrument-walking-aid-bold" /></template>
