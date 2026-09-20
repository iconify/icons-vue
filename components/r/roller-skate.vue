<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xxzkr4y1y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xxzkr4y1y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:roller-skate" /></template>
