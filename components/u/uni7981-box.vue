<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ki3sfflmm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="ki3sfflmm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:uni7981-box" /></template>
