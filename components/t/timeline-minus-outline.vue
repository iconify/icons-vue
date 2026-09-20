<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tye0q80jh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tye0q80jh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:timeline-minus-outline" /></template>
