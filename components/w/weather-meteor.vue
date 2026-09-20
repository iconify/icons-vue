<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/amosus9kb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="amosus9kb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:weather-meteor" /></template>
