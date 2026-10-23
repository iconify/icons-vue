<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yalxtnbgg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yalxtnbgg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:train-track" /></template>
