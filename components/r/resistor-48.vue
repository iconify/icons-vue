<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/irlkbhb-y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="irlkbhb-y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:resistor-48" /></template>
