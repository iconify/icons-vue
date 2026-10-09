<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g14_4pfmo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="g14_4pfmo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:wind-forecast-20" /></template>
