<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qm-zvw_lm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="qm-zvw_lm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:puzzle-48" /></template>
