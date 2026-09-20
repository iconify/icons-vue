<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ykq2q8kya.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ykq2q8kya"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:world-arrow-left" /></template>
