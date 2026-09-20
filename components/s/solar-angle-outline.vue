<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hjkqadw8w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hjkqadw8w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:solar-angle-outline" /></template>
