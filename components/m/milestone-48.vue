<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/slkapwbis.css';
import '../../css/t/tb36haboa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="slkapwbis"/><path class="tb36haboa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:milestone-48" /></template>
