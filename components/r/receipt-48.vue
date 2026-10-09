<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oegrs6bql.css';
import '../../css/o/okiekq7yz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="oegrs6bql"/><path class="okiekq7yz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:receipt-48" /></template>
