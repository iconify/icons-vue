<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o8g6tm0he.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":27,"height":24};
const content = `<path class="o8g6tm0he"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:sentry" /></template>
