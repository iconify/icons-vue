<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wrm4pgbwi.css';
import '../../css/v/vs6my9btk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="wrm4pgbwi"/><path class="vs6my9btk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:send-horizontal-48" /></template>
