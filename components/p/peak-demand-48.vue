<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qb5gahbns.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="qb5gahbns"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:peak-demand-48" /></template>
