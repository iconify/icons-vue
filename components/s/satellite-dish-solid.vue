<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hdx6upobh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hdx6upobh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:satellite-dish-solid" /></template>
