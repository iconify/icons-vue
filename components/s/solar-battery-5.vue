<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mqlq5clhz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mqlq5clhz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:solar-battery-5" /></template>
