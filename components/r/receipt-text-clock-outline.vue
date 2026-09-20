<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fl11uwbud.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fl11uwbud"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:receipt-text-clock-outline" /></template>
