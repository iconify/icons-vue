<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f-4ae2bhy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f-4ae2bhy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:train-car-hopper-covered" /></template>
