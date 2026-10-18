<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g99zjzb_y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="g99zjzb_y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:peak-shaving-48-bold" /></template>
