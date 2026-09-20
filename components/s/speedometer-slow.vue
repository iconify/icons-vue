<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/durkhjrcq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="durkhjrcq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:speedometer-slow" /></template>
