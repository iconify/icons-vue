<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i6u7_8bet.css';
import '../../css/c/con_q4m6a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="i6u7_8bet"/><path class="con_q4m6a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:wind-speed-48-bold" /></template>
