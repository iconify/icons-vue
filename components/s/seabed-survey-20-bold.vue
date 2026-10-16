<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i2cwbgbog.css';
import '../../css/m/mqzn7v0fm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="i2cwbgbog"/><path class="mqzn7v0fm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:seabed-survey-20-bold" /></template>
