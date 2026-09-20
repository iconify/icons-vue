<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ny7g-0bqj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ny7g-0bqj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:zap" /></template>
