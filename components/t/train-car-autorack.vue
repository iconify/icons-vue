<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vdazkl9at.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vdazkl9at"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:train-car-autorack" /></template>
