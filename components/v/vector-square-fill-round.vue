<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eu--urbsm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eu--urbsm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:vector-square-fill-round" /></template>
