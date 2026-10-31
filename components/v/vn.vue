<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/m/mbit45gps.css';
import '../../css/b/bzb5x4zov.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":301,"height":201};
const content = `<g class="ft5dv1b6b"><path class="mbit45gps"/><path class="bzb5x4zov"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cif:vn" /></template>
