<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g1b6-vbzs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g1b6-vbzs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:weather-sunset-down" /></template>
