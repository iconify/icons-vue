<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d59gnbt4d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d59gnbt4d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:play-box" /></template>
