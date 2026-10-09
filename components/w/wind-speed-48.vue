<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oepi3hb8j.css';
import '../../css/m/mvcr2gb0y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="oepi3hb8j"/><path class="mvcr2gb0y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:wind-speed-48" /></template>
