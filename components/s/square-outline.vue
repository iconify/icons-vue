<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/su8_q7bcb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="su8_q7bcb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:square-outline" /></template>
