<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o7f70rbdz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o7f70rbdz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:weather-partly-snowy" /></template>
