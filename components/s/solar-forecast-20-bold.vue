<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/ho_z9ty5t.css';
import '../../css/z/zvwpzebnm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ho_z9ty5t"/><path class="zvwpzebnm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:solar-forecast-20-bold" /></template>
