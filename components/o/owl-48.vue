<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hnv8bn3zi.css';
import '../../css/x/xqa9wgbqx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="hnv8bn3zi"/><path class="xqa9wgbqx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:owl-48" /></template>
