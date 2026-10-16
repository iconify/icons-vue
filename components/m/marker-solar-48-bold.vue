<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/etlms99xu.css';
import '../../css/z/zlhvgcb_b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="etlms99xu"/><path class="zlhvgcb_b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:marker-solar-48-bold" /></template>
