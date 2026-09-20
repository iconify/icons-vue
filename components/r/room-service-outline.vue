<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ys-mqb6ws.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ys-mqb6ws"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:room-service-outline" /></template>
