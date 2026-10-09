<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fj5h1jbsa.css';
import '../../css/i/ih47sreee.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="fj5h1jbsa"/><path class="ih47sreee"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:vertical-axis-turbine-48-bold" /></template>
