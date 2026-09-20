<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e8g17ccmo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e8g17ccmo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:slope-downhill" /></template>
