<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ud7h_6y6z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ud7h_6y6z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:solar-forecast-48" /></template>
