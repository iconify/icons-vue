<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ayrrf_kwh.css';
import '../../css/n/nnu64c95v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ayrrf_kwh"/><path class="nnu64c95v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:pizza-slice-48-bold" /></template>
