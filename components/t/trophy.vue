<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m7bbkk8yo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m7bbkk8yo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:trophy" /></template>
