<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yb-7heutx.css';
import '../../css/b/bgfe5mgwh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="yb-7heutx"/><path class="bgfe5mgwh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:thermistor-48-bold" /></template>
