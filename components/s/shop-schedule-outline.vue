<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aux66vpig.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aux66vpig"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:shop-schedule-outline" /></template>
