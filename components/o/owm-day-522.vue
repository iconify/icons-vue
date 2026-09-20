<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mqur53baa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":30,"height":30};
const content = `<path class="mqur53baa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wi:owm-day-522" /></template>
