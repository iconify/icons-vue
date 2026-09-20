<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ke4wifbjz.css';
import '../../css/q/qeliok-fz.css';
import '../../css/m/mb-jqwb9o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ke4wifbjz"/><path class="qeliok-fz"/><path class="mb-jqwb9o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:tune" /></template>
