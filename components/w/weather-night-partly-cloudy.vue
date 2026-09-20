<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n_l0clr8b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n_l0clr8b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:weather-night-partly-cloudy" /></template>
