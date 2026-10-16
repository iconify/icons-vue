<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/savufeexy.css';
import '../../css/m/m7b13zbzp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="savufeexy"/><path class="m7b13zbzp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:seabed-survey-48" /></template>
