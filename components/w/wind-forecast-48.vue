<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lh-k8dbly.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="lh-k8dbly"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:wind-forecast-48" /></template>
