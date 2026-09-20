<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ru8xkse7f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ru8xkse7f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi-light:presentation-play" /></template>
