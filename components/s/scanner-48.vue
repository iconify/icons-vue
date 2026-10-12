<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m1mdf92vw.css';
import '../../css/d/dvo8x3sla.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="m1mdf92vw"/><path class="dvo8x3sla"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:scanner-48" /></template>
